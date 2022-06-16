---
layout: style-guide
title: Довідник по стилю Scala
language: uk
partof: style
overview-name: "&nbsp;"
---

Цей документ має на меті окреслити деякі основні стилістичні вказівки Scala, яких слід дотримуватися з більшою чи меншою ретельністю.
Усюди, де це можливо, цей посібник намагається докладно розповісти, чому заохочується певний стиль і як він співвідноситься з іншими альтернативами.
Як і з усіма посібниками зі стилю, сприймайте цей документ як список правил, які слід порушувати.
Звичайно, бувають випадки, коли альтернативним стилям слід надавати перевагу над наведеними тут.


- [Відступи](indentation.html)
  - [Line Wrapping](indentation.html#line-wrapping)
  - [Методи з багатьма аргументами](indentation.html#methods-with-numerous-arguments)
- [Правила іменування](naming-conventions.html)
  - [Класи/Трейти](naming-conventions.html#classestraits)
  - [Об'єкти](naming-conventions.html#objects)
  - [Пакети](naming-conventions.html#packages)
    - [root](naming-conventions.html#root)
  - [Методи](naming-conventions.html#methods)
    - [Акцесори/Мутатори](naming-conventions.html#accessorsmutators)
    - [Круглі дужки](naming-conventions.html#parentheses)
    - [Символічні імена методів](naming-conventions.html#symbolic-method-names)
  - [Константи, значення та змінні](naming-conventions.html#constants-values-and-variables)
  - [Параметри типу (generics)](naming-conventions.html#type-parameters-generics)
    - [Higher-Kinds and Parameterized Type parameters](naming-conventions.html#higher-kinds-and-parameterized-type-parameters)
  - [Анотації](naming-conventions.html#annotations)
  - [Особлива примітка щодо скорочень](naming-conventions.html#special-note-on-brevity)
- [Типи](types.html)
  - [Inference](types.html#inference)
    - [Function Values](types.html#function-values)
  - [Анотації](types.html#annotations)
  - [Ascription](types.html#ascription)
  - [Функції](types.html#functions)
    - [Arity-1](types.html#arity-1)
  - [Structural Types](types.html#structural-types)
- [Вкладені блоки](nested-blocks.html)
  - [Фігурні дужки](nested-blocks.html#curly-braces)
  - [Parentheses](nested-blocks.html#parentheses)
- [Declarations](declarations.html)
  - [Classes](declarations.html#classes)
    - [Ordering Of Class Elements](declarations.html#ordering-of-class-elements)
    - [Methods](declarations.html#methods)
      - [Procedure Syntax](declarations.html#procedure-syntax)
      - [Modifiers](declarations.html#modifiers)
      - [Body](declarations.html#body)
      - [Multiple Parameter Lists](declarations.html#multiple-parameter-lists)
      - [Higher-Order Functions](declarations.html#higher-order-functions)
    - [Fields](declarations.html#fields)
  - [Function Values](declarations.html#function-values)
    - [Spacing](declarations.html#spacing)
    - [Multi-Expression Functions](declarations.html#multi-expression-functions)
- [Control Structures](control-structures.html)
  - [Фігурні дужки](control-structures.html#curly-braces)
  - [Comprehensions](control-structures.html#comprehensions)
  - [Trivial Conditionals](control-structures.html#trivial-conditionals)
- [Method Invocation](method-invocation.html)
  - [Arity-0](method-invocation.html#arity-0)
  - [Arity-1 (Infix Notation)](method-invocation.html#arity-1-infix-notation)
    - [Symbolic Methods/Operators](method-invocation.html#symbolic-methodsoperators)
    - [Функції вищого порядку](method-invocation.html#higher-order-functions)
- [Файли](files.html)
  - [Multi-Unit Files](files.html#multi-unit-files)
- [Scaladoc](scaladoc.html)
  - [Загальний стиль](scaladoc.html#general-style)
  - [Пакети](scaladoc.html#packages)
  - [Класи, Об'єкти та Трейти](scaladoc.html#classes-objects-and-traits)
    - [Класи](scaladoc.html#classes)
    - [Об'єкти](scaladoc.html#objects)
    - [Трейти](scaladoc.html#traits)
  - [Methods and Other Members](scaladoc.html#methods-and-other-members)

### Подяка ###

[Daniel Spiewak](https://www.codecommit.com/) і [David Copeland](https://www.naildrivin5.com/) за те, що зібрали цей довідник по стилю докупи, а також Simon Ochsenreither за конвертацію в Markdown.
