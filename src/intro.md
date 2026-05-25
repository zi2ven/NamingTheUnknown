# 前言

现在的语言非常多，有 C/C++, C#, Java, Kotlin, Haskell, OCaml 等等，但是你在使用这些语言的时候总是希望有某些功能来方便你的开发以及更好接入新的技术栈。

大部分语言都是开源的，你可以随便修改他们来符合你自己的要求，但通常很多语言的前后端都已经深入绑定使你难以修改大部分底层特性，而且这些工程可能会非常大。

**那么，为什么不自己写一个语言并且把它推广开来呢？**

这便是本书出现的原因。目前网上都没有特别好的书来教你实现各种类似的编程语言，即使有通常也过于深奥或过于浅显。我们希望无论知识的深浅，只要各位读者有一定的编程基础知识，都能够创造带有自己风格的语言。

我们将从基础开始，编写一个足以和主流语言媲美的高级语言。罗马不是一日建成的，所以我们会分不同阶段来讲解不同类型的语言要如何实现。我们将使用 Rust 来完成所有部分，如果你没有任何 Rust 经验，就去看看[Rust 圣经](https://theajack.github.io/rust)吧。

如果看到这里，这本书的介绍没有吸引到你，不要放弃，强烈建议读一下下列书，他们都是经过大量读者认证的好书，可能会帮助你更加快速进入 PL 世界

- [Crafting Interpreters](https://craftinginterpreters.com/)
    - [中文版](https://craftinginterpreters.fullstack.org.cn/)
- [Writing An Interpreter In Go](https://interpreterbook.com/)
- [Writing A Compiler In Go](https://compilerbook.com/)