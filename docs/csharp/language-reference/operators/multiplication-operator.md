---
title: "* operator - C# Reference"
ms.custom: seodec18
ms.date: 04/04/2018
f1_keywords: 
  - "*_CSharpKeyword"
helpviewer_keywords: 
  - "multiplication operator (*) [C#]"
  - "* operator [C#]"
ms.assetid: abd9a5f0-9b24-431e-971a-09ee1c45c50e
---
# * operator (C# Reference)

The multiplication operator (`*`) computes the product of its operands. All numeric types have predefined multiplication operators.

`*` also serves as the dereference operator, which allows reading and writing to a pointer.

## Remarks

The `*` operator is also used to declare pointer types and to dereference pointers. This operator can only be used in unsafe contexts, denoted by the use of the [unsafe](../keywords/unsafe.md) keyword, and requiring the [/unsafe](../compiler-options/unsafe-compiler-option.md) compiler option.  The dereference operator is also known as the indirection operator.

User-defined types can overload the binary `*` operator (see [operator](../keywords/operator.md)). When a binary operator is overloaded, the corresponding assignment operator, if any, is also implicitly overloaded.

## Example

[!code-csharp-interactive[csRefOperators#50](~/samples/snippets/csharp/VS_Snippets_VBCSharp/csrefOperators/CS/csrefOperators.cs#50)]

## Example

[!code-csharp[csRefOperators#51](~/samples/snippets/csharp/VS_Snippets_VBCSharp/csrefOperators/CS/csrefOperators.cs#51)]

## See also

- [C# Reference](../index.md)
- [C# Programming Guide](../../programming-guide/index.md)
- [Unsafe Code and Pointers](../../programming-guide/unsafe-code-pointers/index.md)
- [C# Operators](index.md)