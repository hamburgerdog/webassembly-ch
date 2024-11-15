# **Webassembly 学习手册（全）**

> 原文：annas-archive.org/md5/d5832e9a9d99a1607969f42f55873dd5
> 
> 
> 译者：[飞龙](https://github.com/wizardforcel)
> 
> PDF 整理：[hamburgerdog](https://github.com/hamburgerdog)
> 
> 协议：[CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/)

# **本书涵盖内容**

第一章，*什么是 WebAssembly？*，描述了 WebAssembly 的起源，并提供了对该技术的高级概述。它涵盖了 WebAssembly 的用途，支持哪些编程语言以及当前的限制。

第二章，*WebAssembly 的元素- Wat、Wasm 和 JavaScript API*，概述了构成 WebAssembly 的元素。它详细解释了文本和二进制格式，以及相应的 JavaScript 和 Web API。

第三章，*设置开发环境*，介绍了用于开发 WebAssembly 的工具。它提供了每个平台的安装说明，并提供了改进开发体验的建议。

第四章，*安装所需的依赖项*，提供了每个平台安装工具链要求的说明。通过本章结束时，您将能够将 C 和 C++编译为 WebAssembly 模块。

第五章，*创建和加载 WebAssembly 模块*，解释了如何使用 Emscripten 生成 WebAssembly 模块，以及传递给编译器的标志如何影响生成的输出。它描述了在浏览器中加载 WebAssembly 模块的技术。

第六章，*与 JavaScript 交互和调试*，详细介绍了 Emscripten 的 Module 对象和浏览器的全局 WebAssembly 对象之间的区别。本章描述了 Emscripten 提供的功能，以及生成源映射的说明。

第七章，*从头开始创建应用程序*，介绍了创建一个与 WebAssembly 模块交互的 JavaScript 会计应用程序的过程。我们将编写 C 代码来计算会计交易的值，并在 JavaScript 和编译后的 WebAssembly 模块之间传递数据。

第八章，*使用 Emscripten 移植游戏*，采用逐步方法将现有的 C++游戏移植到 WebAssembly 上，使用 Emscripten。在审查现有的 C++代码库之后，对适当的文件进行更改，以使游戏能够在浏览器中运行。

第九章，*与 Node.js 集成*，演示了如何在服务器端和客户端使用 Node.js 和 npm 与 WebAssembly。本章涵盖了在 Express 应用程序中使用 WebAssembly，将 WebAssembly 与 webpack 集成以及使用 Jest 测试 WebAssembly 模块。

第十章，*高级工具和即将推出的功能*，涵盖了正在标准化过程中的高级工具，用例和新的 WebAssembly 功能。本章描述了 WABT，Binaryen 和在线可用的工具。在本章中，您将学习如何使用 LLVM 编译 WebAssembly 模块，以及如何将 WebAssembly 模块与 Web Workers 一起使用。本章最后描述了标准化过程，并审查了一些正在添加到规范中的令人兴奋的功能。
