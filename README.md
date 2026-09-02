# awesome-cpp

A curated list of awesome C++ frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Build Systems](#build-systems)
	* [Linters and Formatters](#linters-and-formatters)
	* [Debugging and Profiling](#debugging-and-profiling)
	* [Editor and IDE Support](#editor-and-ide-support)
* Web
	* [Web Frameworks](#web-frameworks)
	* [HTTP and Networking Clients](#http-and-networking-clients)
	* [Web Servers and Proxies](#web-servers-and-proxies)
* Data and Storage
	* [Databases](#databases)
	* [Database Clients and ORMs](#database-clients-and-orms)
	* [Serialization and Formats](#serialization-and-formats)
* Machine Learning and AI
	* [LLM and Inference](#llm-and-inference)
	* [Machine Learning Frameworks](#machine-learning-frameworks)
	* [Computer Vision](#computer-vision)
	* [Natural Language Processing](#natural-language-processing)
	* [Data Science and Analytics](#data-science-and-analytics)
* Networking and Distributed
	* [Networking](#networking)
	* [RPC and Messaging](#rpc-and-messaging)
	* [Distributed Systems](#distributed-systems)
* User Interface
	* [GUI Toolkits](#gui-toolkits)
	* [Terminal and Console UI](#terminal-and-console-ui)
	* [Mobile](#mobile)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Graphics and Rendering](#graphics-and-rendering)
	* [Game Development](#game-development)
	* [Audio](#audio)
	* [Image and Video](#image-and-video)
* Security
	* [Cryptography](#cryptography)
	* [Security Tools](#security-tools)
	* [Reverse Engineering](#reverse-engineering)
* Concurrency and Performance
	* [Concurrency and Parallelism](#concurrency-and-parallelism)
	* [Performance and Optimization](#performance-and-optimization)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Command Line Tools](#command-line-tools)
	* [Logging and Configuration](#logging-and-configuration)
	* [Text Processing](#text-processing)
	* [Files and Operating System](#files-and-operating-system)
	* [Automation and Scripting](#automation-and-scripting)
	* [General Purpose Libraries](#general-purpose-libraries)
* Systems and Hardware
	* [Embedded and Firmware](#embedded-and-firmware)
* Science and Math
	* [Mathematics](#mathematics)
	* [Scientific Computing](#scientific-computing)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [Light-City/CPlusPlusThings](https://github.com/Light-City/CPlusPlusThings) - C++那些事
* [changkun/modern-cpp-tutorial](https://github.com/changkun/modern-cpp-tutorial) - 📚 Modern C++ Tutorial: C++11 to C++26 On the Fly | https://changkun.de/modern-cpp/
* [USTC-Resource/USTC-Course](https://github.com/USTC-Resource/USTC-Course) - :heart:中国科学技术大学课程资源
* [cp-algorithms/cp-algorithms](https://github.com/cp-algorithms/cp-algorithms) - Algorithm and data structure articles for https://cp-algorithms.com (based on http://e-maxx.ru)
* [wuye9036/CppTemplateTutorial](https://github.com/wuye9036/CppTemplateTutorial) - 中文的C++ Template的教学指南。与知名书籍C++ Templates不同，该系列教程将C++ Templates作为一门图灵完备的语言来讲授，以求帮助读者对Meta-Programming融会贯通。(正在施工中)
* [yuesong-feng/30dayMakeCppServer](https://github.com/yuesong-feng/30dayMakeCppServer) - 30天自制C++服务器，包含教程和源代码
* [0voice/cpp_new_features](https://github.com/0voice/cpp_new_features) - 2021年最新整理， C++ 学习资料，含C++ 11 / 14 / 17 / 20 / 23 新特性、入门教程、推荐书籍、优质文章、学习笔记、教学视频等
* [CodePanda66/CSPostgraduate-408](https://github.com/CodePanda66/CSPostgraduate-408) - 💯 CSPostgraduate 计算机考研 408 专业课资料及真题资源 *(archived)*
* [forhappy/Cplusplus-Concurrency-In-Practice](https://github.com/forhappy/Cplusplus-Concurrency-In-Practice) - A Detailed Cplusplus Concurrency Tutorial 《C++ 并发编程指南》
* [gibsjose/cpp-cheat-sheet](https://github.com/gibsjose/cpp-cheat-sheet) - C++ Syntax, Data Structures, and Algorithms Cheat Sheet
* [parallel101/course](https://github.com/parallel101/course) - 高性能并行编程与优化 - 课件
* [ZachL1/Bilibili-plus](https://github.com/ZachL1/Bilibili-plus) - 课程视频、PPT和源代码：侯捷C++系列；台大郭彦甫MATLAB
* [ThisisGame/cpp-game-engine-book](https://github.com/ThisisGame/cpp-game-engine-book) - 从零编写游戏引擎教程 Writing a game engine tutorial from scratch
* [mortennobel/cpp-cheatsheet](https://github.com/mortennobel/cpp-cheatsheet) - Modern C++ Cheatsheet
* [AnkerLeng/Cpp-0-1-Resource](https://github.com/AnkerLeng/Cpp-0-1-Resource) - C++ 匠心之作 从0到1入门资料
* [Salensoft/thu-cst-cracker](https://github.com/Salensoft/thu-cst-cracker) - 清华大学计算机系课程攻略
* [dev-cafe/cmake-cookbook](https://github.com/dev-cafe/cmake-cookbook) - CMake Cookbook recipes.
* [ShiqiYu/CPP](https://github.com/ShiqiYu/CPP) - Lecture notes, projects and other materials for Course 'CS219 Advanced Programming' at Southern University of Science and Technology.
* [cheatsheet1999/CloudCollection](https://github.com/cheatsheet1999/CloudCollection) - Notes for Software Engineers on infrastructure and distributed systems. Covers common data structure and algorithms, web concepts, and more!
* [harleyszhang/cv_note](https://github.com/harleyszhang/cv_note) - 记录cv算法工程师的成长之路，分享计算机视觉和模型压缩部署技术栈笔记。https://harleyszhang.github.io/cv_note/
* [liu-jianhao/Cpp-Design-Patterns](https://github.com/liu-jianhao/Cpp-Design-Patterns) - C++设计模式
* [Walton1128/CPP-Templates-2nd--](https://github.com/Walton1128/CPP-Templates-2nd--) - 《C++ Templates 第二版》中文翻译，和原书排版一致，第一部分（1至11章）以及第18，19，20，21、22、23、24、25章已完成，其余内容逐步更新中。 个人爱好，发现错误请指正
* [SFUMECJF/cmake-examples-Chinese](https://github.com/SFUMECJF/cmake-examples-Chinese) - 快速入门CMake,通过例程学习语法。在线阅读地址：https://sfumecjf.github.io/cmake-examples-Chinese/
* [szza/LearningNote](https://github.com/szza/LearningNote) - C++和Linux学习笔记
* [CppCon/CppCon2014](https://github.com/CppCon/CppCon2014) - Speaker materials from CppCon 2014
* [jainaman224/Algo_Ds_Notes](https://github.com/jainaman224/Algo_Ds_Notes) - A comprehensive resource for learning and implementing algorithms and data structures. This repository includes detailed notes, complexity analysis, and code examples in C++, Java, Python, and more. Ideal for students, professionals, and those preparing for coding interviews.
* [rutura/The-C-20-Masterclass-Source-Code](https://github.com/rutura/The-C-20-Masterclass-Source-Code) - Source code for the C++ 20 Masterclass on udemy
* [selfboot/CS_Offer](https://github.com/selfboot/CS_Offer) - 计算机学科基础知识和主流编程语言相关内容的总结
* [downdemo/Cpp-Concurrency-in-Action-2ed](https://github.com/downdemo/Cpp-Concurrency-in-Action-2ed) - C++11/14/17/20 Concurrency Demystified: From Core Principles to Thread-Safe Code
* [prabhuomkar/pytorch-cpp](https://github.com/prabhuomkar/pytorch-cpp) - C++ Implementation of PyTorch Tutorials for Everyone
* [ssloy/tinyraycaster](https://github.com/ssloy/tinyraycaster) - 486 lines of C++: old-school FPS in a weekend
* [hengqiali/AwesomeCpp](https://github.com/hengqiali/AwesomeCpp) - ---AWESOME--- C++学习笔记和常见面试知识点，C++11特性，包括智能指针、四种强制转换、function和bind、移动语义、完美转发、tuple、多态原理、虚表、友元函数、符号重载、函数指针、深浅拷贝、struct内存对齐、volatile以及union\static等各种关键字的用法等等
* [ashvardanian/less_slow.cpp](https://github.com/ashvardanian/less_slow.cpp) - Playing around "Less Slow" coding practices in C++ 20, C, CUDA, PTX, & Assembly, from numerics & SIMD to coroutines, ranges, exception handling, networking and user-space IO
* [tkchu/Game-Programming-Patterns-CN](https://github.com/tkchu/Game-Programming-Patterns-CN) - 《游戏编程模式》中文版 *(archived)*
* [CppCon/CppCon2016](https://github.com/CppCon/CppCon2016) - Slides and other materials from CppCon 2016
* [CppCon/CppCon2015](https://github.com/CppCon/CppCon2015) - Presentation Materials from CppCon 2015
* [mcpp-community/d2mcpp](https://github.com/mcpp-community/d2mcpp) - D2X | Modern C++ Core Language Features - "A C++ tutorial project focused on practical"
* [electech6/ORB_SLAM2_detailed_comments](https://github.com/electech6/ORB_SLAM2_detailed_comments) - Detailed comments for ORB-SLAM2 with trouble-shooting, key formula derivation, and diagrammatic drawing
* [mostafa-saad/ArabicCompetitiveProgramming](https://github.com/mostafa-saad/ArabicCompetitiveProgramming) - The repository contains the ENGLISH description files attached to the video series in my ARABIC algorithms channel.
* [MKXJun/DirectX11-With-Windows-SDK](https://github.com/MKXJun/DirectX11-With-Windows-SDK) - 现代DX11系列教程：使用Windows SDK(C++)开发Direct3D 11.x
* [downdemo/Cpp-Templates-2ed](https://github.com/downdemo/Cpp-Templates-2ed) - Master Modern C++(11/14/17/20) Templates: TMP, SFINAE, Concepts, CRTP, Variadic Magic, and Compile-Time Sorcery
* [CppCon/CppCon2020](https://github.com/CppCon/CppCon2020) - Slides and other materials from CppCon 2020
* [0xJs/RedTeaming_CheatSheet](https://github.com/0xJs/RedTeaming_CheatSheet) - Pentesting cheatsheet with all the commands I learned during my learning journey. Will try to to keep it up-to-date.
* [Blitzer207/C-Resource](https://github.com/Blitzer207/C-Resource) - 黑马程序员匠心之作|C++教程从0到1入门编程
* [BrightXiaoHan/CMakeTutorial](https://github.com/BrightXiaoHan/CMakeTutorial) - CMake中文实战教程
* [Bhupesh-V/30-seconds-of-cpp](https://github.com/Bhupesh-V/30-seconds-of-cpp) - 30 Seconds of C++ (STL in C++). Read More about 30C++ here 👉 *(archived)*
* [electech6/ORB_SLAM3_detailed_comments](https://github.com/electech6/ORB_SLAM3_detailed_comments) - Detailed comments for ORB-SLAM3
* [harvestlamb/Cpp_houjie](https://github.com/harvestlamb/Cpp_houjie) - 侯捷C++课程PPT及代码,动手学起来
* [sftrabbit/CppPatterns-Patterns](https://github.com/sftrabbit/CppPatterns-Patterns) - A repository of modern C++ patterns curated by the community.
* [CppCon/CppCon2018](https://github.com/CppCon/CppCon2018) - Slides and other materials from CppCon 2018
* [facontidavide/CPP_Optimizations_Diary](https://github.com/facontidavide/CPP_Optimizations_Diary) - Tips and tricks to optimize your C++ code
* [3dgen/cppwasm-book](https://github.com/3dgen/cppwasm-book) - :books: WebAssembly friendly programming with C/C++ -- Emscripten practice
* [Dor1s/libfuzzer-workshop](https://github.com/Dor1s/libfuzzer-workshop) - Repository for materials of "Modern fuzzing of C/C++ Projects" workshop.
* [rongweihe/CPPNotes](https://github.com/rongweihe/CPPNotes) - 【C++ 面试 + C++ 学习指南】 一份涵盖大部分 C++ 程序员所需要掌握的核心知识。
* [Captain1986/CaptainBlackboard](https://github.com/Captain1986/CaptainBlackboard) - 船长关于机器学习、计算机视觉和工程技术的总结和分享
* [vector-of-bool/pitchfork](https://github.com/vector-of-bool/pitchfork) - Pitchfork is a Set of C++ Project Conventions
* [luguanxing/Cheating-Plugin-Program](https://github.com/luguanxing/Cheating-Plugin-Program) - 从零开始研究外挂设计原理 Study the principles of cheat design from scratch
* [green7ea/blog](https://github.com/green7ea/blog) - A short description of the C++ build process
* [jeaye/stdman](https://github.com/jeaye/stdman) - Formatted C++20 stdlib man pages (cppreference)
* [the-hyp0cr1t3/CC](https://github.com/the-hyp0cr1t3/CC) - Everything competitive programming related - introductory guide, topics/concepts, practice problems, snippets & templates, tips & tricks and more.
* [HeYijia/VINS-Course](https://github.com/HeYijia/VINS-Course) - VINS-Mono code without Ceres or ROS
* [chronolaw/cpp_study](https://github.com/chronolaw/cpp_study) - follow me to study modern c++
* [qixianyu-buaa/EigenChineseDocument](https://github.com/qixianyu-buaa/EigenChineseDocument) - This is my translation of Chinese document of Eigen
* [xiaojiaqi/C1000kPracticeGuide](https://github.com/xiaojiaqi/C1000kPracticeGuide) - A C1000k demo with detailed description
* [nvpro-samples/vk_mini_path_tracer](https://github.com/nvpro-samples/vk_mini_path_tracer) - A beginner-friendly Vulkan path tracing tutorial in under 300 lines of C++.

### Examples and Exercises

* [huihut/interview](https://github.com/huihut/interview) - 📚 C/C++ 技术面试基础知识总结，包括语言、程序库、数据结构、算法、系统、网络、链接装载库等知识及面试经验、招聘、内推等信息。This repository is a summary of the basic knowledge of recruiting job seekers and beginners in the direction of C/C++ technology, including language, program library, data structure, algorithm, system, network, link loading library, interview experience, recruitment, recommendation, etc.
* [TheAlgorithms/C-Plus-Plus](https://github.com/TheAlgorithms/C-Plus-Plus) - Collection of various algorithms in mathematics, machine learning, computer science and physics implemented in C++ for educational purposes.
* [OpenGenus/cosmos](https://github.com/OpenGenus/cosmos) - World's largest Contributor driven code dataset | Used in Quark Search Engine, @OpenGenus IQ, OpenGenus Visual Project
* [Alinshans/MyTinySTL](https://github.com/Alinshans/MyTinySTL) - Achieve a tiny STL in C++11
* [gzc/CLRS](https://github.com/gzc/CLRS) - :notebook:Solutions to Introduction to Algorithms
* [NVIDIA/cuda-samples](https://github.com/NVIDIA/cuda-samples) - Samples for CUDA Developers which demonstrates features in CUDA Toolkit
* [applenob/Cpp_Primer_Practice](https://github.com/applenob/Cpp_Primer_Practice) - 搞定C++:punch:。C++ Primer 中文版第5版学习仓库，包括笔记和课后练习答案。
* [Mooophy/Cpp-Primer](https://github.com/Mooophy/Cpp-Primer) - C++ Primer 5 answers
* [wisdompeak/LeetCode](https://github.com/wisdompeak/LeetCode) - This repository contains the solutions and explanations to the algorithm problems on LeetCode. Only medium or above are included. All are written in C++/Python and implemented by myself. The problems attempted multiple times are labelled with hyperlinks.
* [mandliya/algorithms_and_data_structures](https://github.com/mandliya/algorithms_and_data_structures) - 180+ Algorithm & Data Structure Problems using C++
* [kamyu104/LeetCode-Solutions](https://github.com/kamyu104/LeetCode-Solutions) - 🏋️ Python / Modern C++ Solutions of All 4033 LeetCode Problems (Weekly Update)
* [xtaci/algorithms](https://github.com/xtaci/algorithms) - Algorithms & Data structures in C++.
* [zhedahht/CodingInterviewChinese2](https://github.com/zhedahht/CodingInterviewChinese2) - 《剑指Offer：名企面试官精讲典型编程面试题》第二版源代码
* [gatieme/CodingInterviews](https://github.com/gatieme/CodingInterviews) - 剑指Offer——名企面试官精讲典型编程题
* [tomlooman/ActionRoguelike](https://github.com/tomlooman/ActionRoguelike) - Co-op Action Roguelike in Unreal Engine C++
* [JakubVojvoda/design-patterns-cpp](https://github.com/JakubVojvoda/design-patterns-cpp) - C++ Design Patterns
* [huaxz1986/cplusplus-_Implementation_Of_Introduction_to_Algorithms](https://github.com/huaxz1986/cplusplus-_Implementation_Of_Introduction_to_Algorithms) - 《算法导论》第三版中算法的C++实现
* [loveBabbar/CodeHelp-DSA-Busted-Series](https://github.com/loveBabbar/CodeHelp-DSA-Busted-Series) - This repo is creating providing students easy access to all the programs taught under Codehelp's DSA Busted Series.
* [ShahjalalShohag/code-library](https://github.com/ShahjalalShohag/code-library) - Templates, algorithms and data structures implemented and collected for programming contests.
* [pezy/LeetCode](https://github.com/pezy/LeetCode) - :pencil2: LeetCode solutions in C++ 11 and Python3
* [liuchuo/PAT](https://github.com/liuchuo/PAT) - 🍭 浙江大学PAT题解(C/C++/Java/Python) - 努力成为萌萌的程序媛～
* [pezy/CppPrimer](https://github.com/pezy/CppPrimer) - :books: Solutions for C++ Primer 5th exercises.
* [ShujiaHuang/Cpp-Primer-Plus-6th](https://github.com/ShujiaHuang/Cpp-Primer-Plus-6th) - 《C++ Primer Plus 第6版（中文版）》原书代码、习题答案和个人笔记，仅供学习和交流。
* [huangmingchuan/Cpp_Primer_Answers](https://github.com/huangmingchuan/Cpp_Primer_Answers) - 《C++ Primer》第五版中文版习题答案
* [ndrplz/self-driving-car](https://github.com/ndrplz/self-driving-car) - Udacity Self-Driving Car Engineer Nanodegree projects.
* [bqi343/cp-notebook](https://github.com/bqi343/cp-notebook) - General Resources for Competitive Programming
* [MasteringOpenCV/code](https://github.com/MasteringOpenCV/code) - Code for the book "Mastering OpenCV with Practical Computer Vision Projects" by Packt Publishing 2012.
* [liuyubobobo/Play-Leetcode](https://github.com/liuyubobobo/Play-Leetcode) - My Solutions to Leetcode problems. All solutions support C++ language, some support Java and Python. Multiple solutions will be given by most problems. Enjoy:) 我的Leetcode解答。所有的问题都支持C++语言，一部分问题支持Java语言。近乎所有问题都会提供多个算法解决。大家加油！：）
* [Jack-Cherish/LeetCode](https://github.com/Jack-Cherish/LeetCode) - :monkey:LeetCode、剑指Offer刷题笔记（C/C++、Python3实现）
* [nodejs/node-addon-examples](https://github.com/nodejs/node-addon-examples) - Node.js C++ addon examples from http://nodejs.org/docs/latest/api/addons.html
* [anthropics/claude-desktop-buddy](https://github.com/anthropics/claude-desktop-buddy) - Reference and an example for the Bluetooth API for makers in Claude Cowork & Claude Code Desktop
* [flutter/codelabs](https://github.com/flutter/codelabs) - Flutter codelab examples
* [QianMo/OpenCV3-Intro-Book-Src](https://github.com/QianMo/OpenCV3-Intro-Book-Src) - :blue_book:《OpenCV3编程入门》书本配套源码 |《Introduction to OpenCV3 Programming》Book Source Code
* [yogykwan/acm-challenge-workbook](https://github.com/yogykwan/acm-challenge-workbook) - 《挑战程序设计竞赛》习题册攻略
* [manishbisht/Competitive-Programming](https://github.com/manishbisht/Competitive-Programming) - :pushpin: :books: Solution of competitive programming problems, code templates, Data Structures and Algorithms, hackathons, interviews and much more.
* [MikeMirzayanov/testlib](https://github.com/MikeMirzayanov/testlib) - C++ library to develop competitive programming problems
* [lzl124631x/LeetCode](https://github.com/lzl124631x/LeetCode) - My C++ Code for LeetCode OJ
* [luliyucoordinate/Leetcode](https://github.com/luliyucoordinate/Leetcode) - Play Leetcode with different programming language
* [Hawstein/cracking-the-coding-interview](https://github.com/Hawstein/cracking-the-coding-interview) - Solutions for the book: Cracking the coding interview V4. Written in C++.
* [walbourn/directx-sdk-samples-reworked](https://github.com/walbourn/directx-sdk-samples-reworked) - This repo contains Direct3D 11, XInput, and XAudio2 samples C++ samples from the legacy DirectX SDK updated to build using the Windows 10 SDK *(archived)*
* [zhedahht/ChineseCodingInterviewAppendix](https://github.com/zhedahht/ChineseCodingInterviewAppendix) - The source code for the appendix part of the Chinese version of the book Coding Interviews
* [careercup/CtCI-6th-Edition-cpp](https://github.com/careercup/CtCI-6th-Edition-cpp) - Cracking the Coding Interview 6th Ed. C++ Solutions
* [walkccc/LeetCode](https://github.com/walkccc/LeetCode) - 💡 LeetCode in C++23/Java/Python/MySQL/TypeScript (respect coding conventions)
* [gameprogcpp/code](https://github.com/gameprogcpp/code) - Game Programming in C++ Code
* [Harrison1/unrealcpp](https://github.com/Harrison1/unrealcpp) - Unreal Engine 4 C++ examples
* [smv1999/CompetitiveProgrammingQuestionBank](https://github.com/smv1999/CompetitiveProgrammingQuestionBank) - This repository contains all the popular Competitive Programming and DSA questions with solutions for your Coding Interview Preparation.
* [eliben/llvm-clang-samples](https://github.com/eliben/llvm-clang-samples) - UNMAINTAINED: Examples of using the LLVM and Clang compilation libraries and tools *(archived)*
* [Miller-Xie/Code](https://github.com/Miller-Xie/Code) - 面试高频算法题总结，个人博客
* [QianMo/GPU-Gems-Book-Source-Code](https://github.com/QianMo/GPU-Gems-Book-Source-Code) - :cd: CD Content ( Source Code ) Collection of Book <GPU Gems > 1~ 3 | 《GPU精粹》 1~ 3 随书CD（源代码）珍藏
* [CodeTest-StudyGroup/Code-Test-Study](https://github.com/CodeTest-StudyGroup/Code-Test-Study) - 코딩 테스트 관련 기출문항을 풀어보고 소스코드 및 설명을 업로드합니다.
* [gzwl/leetcode](https://github.com/gzwl/leetcode) - The optimum C++ solutions for the leetcode

## Language and Tooling

### Compilers and Interpreters

* [carbon-language/carbon-lang](https://github.com/carbon-language/carbon-lang) - Carbon Language's main repository: documents, design, implementation, and related tools. (NOTE: Carbon Language is experimental; see README)
* [exaloop/codon](https://github.com/exaloop/codon) - A high-performance, zero-overhead, extensible Python compiler with built-in NumPy support
* [focus-creative-games/hybridclr](https://github.com/focus-creative-games/hybridclr) - HybridCLR是一个特性完整、零成本、高性能、低内存的Unity全平台原生c#热更新解决方案。 HybridCLR is a fully featured, zero-cost, high-performance, low-memory solution for Unity's all-platform native c# hotupdate.
* [hsutter/cppfront](https://github.com/hsutter/cppfront) - A personal experimental C++ Syntax 2 -> Syntax 1 compiler
* [skeeto/w64devkit](https://github.com/skeeto/w64devkit) - Portable C and C++ Development Kit for x64 (and x86) Windows
* [asmjit/asmjit](https://github.com/asmjit/asmjit) - Low-latency machine code generation
* [sass/libsass](https://github.com/sass/libsass) - A C/C++ implementation of a Sass compiler *(archived)*
* [root-project/cling](https://github.com/root-project/cling) - The cling C++ interpreter
* [jank-lang/jank](https://github.com/jank-lang/jank) - jank is the native Clojure dialect with seamless C++ interop.
* [grame-cncm/faust](https://github.com/grame-cncm/faust) - Functional programming language for signal processing and sound synthesis
* [ChaiScript/ChaiScript](https://github.com/ChaiScript/ChaiScript) - Embedded Scripting Language Designed for C++
* [llvm-mirror/clang](https://github.com/llvm-mirror/clang) - Mirror kept for legacy. Moved to https://github.com/llvm/llvm-project *(archived)*
* [seanbaxter/circle](https://github.com/seanbaxter/circle) - The compiler is available for download. Get it!
* [RuntimeCompiledCPlusPlus/RuntimeCompiledCPlusPlus](https://github.com/RuntimeCompiledCPlusPlus/RuntimeCompiledCPlusPlus) - Change C++ code at runtime
* [herumi/xbyak](https://github.com/herumi/xbyak) - A JIT assembler for x86/x64 architectures supporting the latest instruction set extensions such as AVX10.2 and ACE
* [llvm/circt](https://github.com/llvm/circt) - Circuit IR Compilers and Tools
* [AdaptiveCpp/AdaptiveCpp](https://github.com/AdaptiveCpp/AdaptiveCpp) - Compiler for multiple programming models (SYCL, C++ standard parallelism, HIP/CUDA) for CPUs and GPUs from all vendors: The independent, community-driven compiler for C++-based heterogeneous programming models. Lets applications adapt themselves to all the hardware in the system - even at runtime!
* [fusionlanguage/fut](https://github.com/fusionlanguage/fut) - Fusion programming language. Transpiling to C, C++, C#, D, Java, JavaScript, Python, Swift, TypeScript and OpenCL C.
* [vgvassilev/cling](https://github.com/vgvassilev/cling) - The interactive C++ interpreter Cling
* [standardese/cppast](https://github.com/standardese/cppast) - Library to parse and work with the C++ AST
* [yrnkrn/zapcc](https://github.com/yrnkrn/zapcc) - zapcc is a caching C++ compiler based on clang, designed to perform faster compilations
* [BitFunnel/NativeJIT](https://github.com/BitFunnel/NativeJIT) - A C++ expression -> x64 JIT
* [curv3d/curv](https://github.com/curv3d/curv) - a language for making art using mathematics *(archived)*
* [tomhrr/dale](https://github.com/tomhrr/dale) - Lisp-flavoured C
* [LiquidPlayer/LiquidCore](https://github.com/LiquidPlayer/LiquidCore) - Node.js virtual machine for Android and iOS
* [lsegal/my_toy_compiler](https://github.com/lsegal/my_toy_compiler) - My Toy Compiler. Read about how I did it at the homepage URL

### Build Systems

* [tsoding/nob.h](https://github.com/tsoding/nob.h) - Header only library for writing build recipes in C.
* [ccache/ccache](https://github.com/ccache/ccache) - ccache – a fast compiler cache
* [fungos/cr](https://github.com/fungos/cr) - cr.h: A Simple C Hot Reload Header-only Library
* [runestubbe/Crinkler](https://github.com/runestubbe/Crinkler) - Crinkler is an executable file compressor (or rather, a compressing linker) for compressing small 32-bit Windows demoscene executables. As of 2026, it is the most widely used tool for compressing 1k/4k/8k intros.
* [aras-p/ClangBuildAnalyzer](https://github.com/aras-p/ClangBuildAnalyzer) - Clang build analysis tool using -ftime-trace
* [Chuyu-Team/VC-LTL](https://github.com/Chuyu-Team/VC-LTL) - Shared to msvcrt.dll and optimize the C/C++ application file size. *(archived)*

### Linters and Formatters

* [cppcheck-opensource/cppcheck](https://github.com/cppcheck-opensource/cppcheck) - static analysis of C/C++ code
* [include-what-you-use/include-what-you-use](https://github.com/include-what-you-use/include-what-you-use) - A tool for use with clang to analyze #includes in C and C++ source files
* [andreasfertig/cppinsights](https://github.com/andreasfertig/cppinsights) - C++ Insights - See your source code with the eyes of a compiler
* [oclint/oclint](https://github.com/oclint/oclint) - A static source code analysis tool to improve quality and reduce defects for C, C++ and Objective-C
* [NASA-SW-VnV/ikos](https://github.com/NASA-SW-VnV/ikos) - Static analyzer for C/C++ based on the theory of Abstract Interpretation.
* [Tencent/TscanCode](https://github.com/Tencent/TscanCode) - A static code analyzer for C++, C#, Lua

### Debugging and Profiling

* [wolfpld/tracy](https://github.com/wolfpld/tracy) - Frame profiler
* [google/orbit](https://github.com/google/orbit) - C/C++ Performance Profiler *(archived)*
* [bombela/backward-cpp](https://github.com/bombela/backward-cpp) - A beautiful stack trace pretty printer for C++
* [sharkdp/dbg-macro](https://github.com/sharkdp/dbg-macro) - A dbg(…) macro for C++
* [RudjiGames/MTuner](https://github.com/RudjiGames/MTuner) - MTuner is a C/C++ memory profiler and memory leak finder for Windows and other platforms *(archived)*
* [yse/easy_profiler](https://github.com/yse/easy_profiler) - Lightweight profiler library for c++
* [dfeneyrou/palanteer](https://github.com/dfeneyrou/palanteer) - Visual Python and C++ nanosecond profiler, logger, tests enabler
* [jeremy-rifkin/cpptrace](https://github.com/jeremy-rifkin/cpptrace) - Simple, portable, and self-contained stacktrace library for C++11 and newer
* [crosire/blink](https://github.com/crosire/blink) - A tool which allows you to edit source code of any MSVC C++ project live at runtime
* [GPUOpen-Archive/CodeXL](https://github.com/GPUOpen-Archive/CodeXL) - CodeXL is a comprehensive tool suite that enables developers to harness the benefits of CPUs, GPUs and APUs. *(archived)*
* [inspector-repl/inspector](https://github.com/inspector-repl/inspector) - A drop-anywhere C++ REPL

### Editor and IDE Support

* [sbarex/SourceCodeSyntaxHighlight](https://github.com/sbarex/SourceCodeSyntaxHighlight) - Quick Look extension for highlight source code files on macOS 10.15 and later.
* [MaskRay/ccls](https://github.com/MaskRay/ccls) - C/C++/ObjC language server supporting cross references, hierarchies, completion and semantic highlighting
* [qt-creator/qt-creator](https://github.com/qt-creator/qt-creator) - A cross-platform Qt IDE
* [eranif/codelite](https://github.com/eranif/codelite) - A multi purpose IDE specialized in C/C++/Rust/Python/PHP and Node.js. Written in C++
* [jacobdufault/cquery](https://github.com/jacobdufault/cquery) - C/C++ language server supporting multi-million line code base, powered by libclang. Emacs, Vim, VSCode, and others with language server protocol support. Cross references, completion, diagnostics, semantic highlighting and more *(archived)*
* [cpeditor/cpeditor](https://github.com/cpeditor/cpeditor) - The IDE for competitive programming :tada: | Fetch, Code, Compile, Run, Check, Submit :rocket:
* [Andersbakken/rtags](https://github.com/Andersbakken/rtags) - A client/server indexer for c/c++/objc[++] with integration for Emacs based on clang.
* [royqh1979/RedPanda-CPP](https://github.com/royqh1979/RedPanda-CPP) - A light-weight C/C++ IDE based on Qt
* [pnedev/comparePlus](https://github.com/pnedev/comparePlus) - Compare plugin for Notepad++
* [KDAB/codebrowser](https://github.com/KDAB/codebrowser) - Woboq CodeBrowser
* [cppit/jucipp](https://github.com/cppit/jucipp) - A lightweight & cross-platform IDE supporting the most recent C++ standards. This project has moved to https://gitlab.com/cppit/jucipp. *(archived)*

## Web

### Web Frameworks

* [drogonframework/drogon](https://github.com/drogonframework/drogon) - Drogon: A C++14/17/20 based HTTP web application framework running on Linux/macOS/Unix/Windows
* [oatpp/oatpp](https://github.com/oatpp/oatpp) - 🌱Light and powerful C++ web framework for highly scalable and resource-efficient web application. It's zero-dependency and easy-portable.
* [ipkn/crow](https://github.com/ipkn/crow) - Crow is very fast and easy to use C++ micro web framework (inspired by Python Flask)
* [CrowCpp/Crow](https://github.com/CrowCpp/Crow) - A Fast and Easy to use microframework for the web.
* [pistacheio/pistache](https://github.com/pistacheio/pistache) - A high-performance REST toolkit written in C++
* [userver-framework/userver](https://github.com/userver-framework/userver) - Production-ready C++ Asynchronous Framework with rich functionality
* [qicosmos/cinatra](https://github.com/qicosmos/cinatra) - C++20 实现的跨平台、header only，易用的高性能http库; modern c++(c++20), cross-platform, header-only, easy to use http framework
* [Corvusoft/restbed](https://github.com/Corvusoft/restbed) - Corvusoft's Restbed framework brings asynchronous RESTful functionality to C++ applications.
* [matt-42/silicon](https://github.com/matt-42/silicon) - A high performance, middleware oriented C++14 http web framework please use matt-42/lithium instead
* [matt-42/lithium](https://github.com/matt-42/lithium) - Easy to use C++17 HTTP Server with no compromise on performances. https://matt-42.github.io/lithium
* [treefrogframework/treefrog-framework](https://github.com/treefrogframework/treefrog-framework) - TreeFrog Framework : High-speed C++ MVC Framework for Web Application
* [stefanocasazza/ULib](https://github.com/stefanocasazza/ULib) - C++ application development framework, to help developers create and deploy applications quickly and simply

### HTTP and Networking Clients

* [yhirose/cpp-httplib](https://github.com/yhirose/cpp-httplib) - A C++ header-only HTTP/HTTPS server and client library
* [microsoft/cpprestsdk](https://github.com/microsoft/cpprestsdk) - The C++ REST SDK is a Microsoft project for cloud-based client-server communication in native code using a modern asynchronous C++ API design. This project aims to help C++ developers connect to and interact with services. *(archived)*
* [libcpr/cpr](https://github.com/libcpr/cpr) - C++ Requests: Curl for People, a spiritual port of Python Requests.
* [boostorg/beast](https://github.com/boostorg/beast) - HTTP and WebSocket built on Boost.Asio in C++11
* [jpbarrette/curlpp](https://github.com/jpbarrette/curlpp) - C++ wrapper around libcURL
* [mrtazz/restclient-cpp](https://github.com/mrtazz/restclient-cpp) - C++ client for making HTTP/REST requests
* [BitMEX/api-connectors](https://github.com/BitMEX/api-connectors) - Libraries for connecting to the BitMEX API.

### Web Servers and Proxies

* [qinguoyi/TinyWebServer](https://github.com/qinguoyi/TinyWebServer) - :fire: Linux下C++轻量级WebServer服务器
* [facebook/proxygen](https://github.com/facebook/proxygen) - A collection of C++ HTTP libraries including an easy to use HTTP server.
* [linyacool/WebServer](https://github.com/linyacool/WebServer) - A C++ High Performance Web Server
* [markparticle/WebServer](https://github.com/markparticle/WebServer) - C++ Linux WebServer服务器
* [eidheim/Simple-Web-Server](https://github.com/eidheim/Simple-Web-Server) - A very simple, fast, multithreaded, platform independent HTTP and HTTPS server and client library implemented using C++11 and Boost.Asio. Created to be an easy way to make REST resources available from C++ applications. *(archived)*
* [ideawu/icomet](https://github.com/ideawu/icomet) - A C1000K comet/push server built with C++, for web and mobile app
* [Stiffstream/restinio](https://github.com/Stiffstream/restinio) - Cross-platform, efficient, customizable, and robust asynchronous HTTP(S)/WebSocket server C++ library with the right balance between performance and ease of use
* [d5/node.native](https://github.com/d5/node.native) - C++11 port for the Node: native performance and modern simplicity.
* [etr/libhttpserver](https://github.com/etr/libhttpserver) - C++ library for creating an embedded Rest HTTP server (and more)

## Data and Storage

### Databases

* [ClickHouse/ClickHouse](https://github.com/ClickHouse/ClickHouse) - ClickHouse® is a real-time analytics database management system
* [memgraph/memgraph](https://github.com/memgraph/memgraph) - High-performance open-source in-memory graph database for GraphRAG, AI memory, agentic AI, and real-time graph analytics. Cypher-compatible, built in C++.
* [facebookincubator/velox](https://github.com/facebookincubator/velox) - A composable and fully extensible C++ execution engine library for data management systems.
* [chdb-io/chdb](https://github.com/chdb-io/chdb) - chDB is an in-process OLAP SQL Engine 🚀 powered by ClickHouse
* [youngyangyang04/Skiplist-CPP](https://github.com/youngyangyang04/Skiplist-CPP) - A tiny KV storage based on skiplist written in C++ language| 使用C++开发，基于跳表实现的轻量级键值数据库🔥🔥 🚀
* [timeplus-io/proton](https://github.com/timeplus-io/proton) - The Fastest Unified Streaming SQL Engine in a Single C++ Binary. ⚡ Millisecond latency. 100+ GB/s throughput. Continuously compute real-time context from streams, logs, metrics, events, and CDC.
* [ByConity/ByConity](https://github.com/ByConity/ByConity) - ByConity is an open source cloud data warehouse *(archived)*
* [realm/realm-core](https://github.com/realm/realm-core) - Core database component for the Realm Mobile Database SDKs

### Database Clients and ORMs

* [fnc12/sqlite_orm](https://github.com/fnc12/sqlite_orm) - ❤️ SQLite ORM light header only library for modern C++
* [rbock/sqlpp11](https://github.com/rbock/sqlpp11) - A type safe SQL template library for C++
* [sewenew/redis-plus-plus](https://github.com/sewenew/redis-plus-plus) - Redis client written in C++
* [SOCI/soci](https://github.com/SOCI/soci) - Official repository of the SOCI - The C++ Database Access Library
* [qicosmos/ormpp](https://github.com/qicosmos/ormpp) - modern C++ ORM, C++17, support mysql, postgresql,sqlite
* [jtv/libpqxx](https://github.com/jtv/libpqxx) - The official C++ client API for PostgreSQL.
* [Cylix/cpp_redis](https://github.com/Cylix/cpp_redis) - C++11 Lightweight Redis client: async, thread-safe, no dependency, pipelining, multi-platform - NO LONGER MAINTAINED - Please check https://github.com/cpp-redis/cpp_redis *(archived)*
* [mongodb/mongo-cxx-driver](https://github.com/mongodb/mongo-cxx-driver) - C++ Driver for MongoDB

### Serialization and Formats

* [nlohmann/json](https://github.com/nlohmann/json) - JSON for Modern C++
* [google/flatbuffers](https://github.com/google/flatbuffers) - FlatBuffers: Memory Efficient Serialization Library
* [Tencent/rapidjson](https://github.com/Tencent/rapidjson) - A fast JSON parser/generator for C++ with both SAX/DOM style API
* [capnproto/capnproto](https://github.com/capnproto/capnproto) - Cap'n Proto serialization/RPC system - core tools and C++ library
* [open-source-parsers/jsoncpp](https://github.com/open-source-parsers/jsoncpp) - A C++ library for interacting with JSON.
* [bblanchon/ArduinoJson](https://github.com/bblanchon/ArduinoJson) - 📟 JSON library for Arduino and embedded C++. Simple and efficient.
* [jbeder/yaml-cpp](https://github.com/jbeder/yaml-cpp) - A YAML parser and emitter in C++
* [leethomason/tinyxml2](https://github.com/leethomason/tinyxml2) - TinyXML2 is a simple, small, efficient, C++ XML parser that can be easily integrated into other programs.
* [USCiLab/cereal](https://github.com/USCiLab/cereal) - A C++11 library for serialization
* [zeux/pugixml](https://github.com/zeux/pugixml) - Light-weight, simple and fast XML parser for C++ with XPath support
* [ultrajson/ultrajson](https://github.com/ultrajson/ultrajson) - Ultra fast JSON decoder and encoder written in C with Python bindings
* [protobuf-c/protobuf-c](https://github.com/protobuf-c/protobuf-c) - Protocol Buffers implementation in C
* [stephenberry/glaze](https://github.com/stephenberry/glaze) - Extremely fast, in memory, serialization, reflection, and RPC library for C++. JSON, BEVE, BSON, CBOR, CSV, JSONB, MessagePack, TOML, YAML, EETF
* [dropbox/json11](https://github.com/dropbox/json11) - A tiny JSON library for C++11. *(archived)*
* [syoyo/tinygltf](https://github.com/syoyo/tinygltf) - Header only C11 tiny glTF 2.0 library
* [ben-strasser/fast-cpp-csv-parser](https://github.com/ben-strasser/fast-cpp-csv-parser) - fast-cpp-csv-parser
* [felixguendling/cista](https://github.com/felixguendling/cista) - Cista is a simple, high-performance, zero-copy C++ serialization & reflection library.
* [marzer/tomlplusplus](https://github.com/marzer/tomlplusplus) - Header-only TOML config file parser and serializer for C++17.
* [getml/reflect-cpp](https://github.com/getml/reflect-cpp) - A C++20 library for fast serialization, deserialization and validation using reflection. Supports JSON, Avro, Boost Serialization, BSON, Cap'n Proto, CBOR, Cereal, Command line interfaces, CSV, Environment variables, flexbuffers, msgpack, parquet, TOML, UBJSON, XML, YAML, yas / msgpack.org[C++20]
* [troldal/OpenXLSX](https://github.com/troldal/OpenXLSX) - A C++ library for reading, writing, creating and modifying Microsoft Excel® (.xlsx) files.
* [tfussell/xlnt](https://github.com/tfussell/xlnt) - :bar_chart: Cross-platform user-friendly xlsx library for C++11+
* [QtExcel/QXlsx](https://github.com/QtExcel/QXlsx) - Excel file(*.xlsx) reader/writer library using Qt. Descendant of QtXlsxWriter.
* [rogersce/cnpy](https://github.com/rogersce/cnpy) - library to read/write .npy and .npz files in C/C++
* [ToruNiina/toml11](https://github.com/ToruNiina/toml11) - TOML for Modern C++
* [alembic/alembic](https://github.com/alembic/alembic) - Alembic is an open framework for storing and sharing scene data that includes a C++ library, a file format, and client plugins and applications.
* [kazuho/picojson](https://github.com/kazuho/picojson) - a header-file-only, JSON parser serializer in C++

## Machine Learning and AI

### LLM and Inference

* [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) - LLM inference in C/C++
* [rocketride-org/rocketride-server](https://github.com/rocketride-org/rocketride-server) - High-performance AI pipeline engine with a C++ core and 50+ Python-extensible nodes. Build, debug, and scale LLM workflows with 13+ model providers, 8+ vector databases, and agent orchestration, all from your IDE. Includes VS Code extension, TypeScript/Python SDKs, and Docker deployment.
* [google/gemma.cpp](https://github.com/google/gemma.cpp) - lightweight, standalone C++ inference engine for Google's Gemma models.
* [leejet/stable-diffusion.cpp](https://github.com/leejet/stable-diffusion.cpp) - Diffusion model(SD,Flux,Wan,Qwen Image,Z-Image,...) inference in pure C/C++
* [cactus-compute/cactus](https://github.com/cactus-compute/cactus) - Quantization, kernels, runtime and inference engine for mobiles, wearables, smart home and robots.
* [ztxz16/fastllm](https://github.com/ztxz16/fastllm) - fastllm是后端无依赖的高性能大模型推理库。同时支持张量并行推理稠密模型和混合模式推理MOE模型，任意10G以上显卡即可推理满血DeepSeek。双路9004/9005服务器+单显卡部署DeepSeek满血满精度原版模型，单并发20tps；INT4量化模型单并发30tps，多并发可达60+。
* [ikawrakow/ik_llama.cpp](https://github.com/ikawrakow/ik_llama.cpp) - llama.cpp fork with additional SOTA quants and improved performance
* [li-plus/chatglm.cpp](https://github.com/li-plus/chatglm.cpp) - C++ implementation of ChatGLM-6B & ChatGLM2-6B & ChatGLM3 & GLM4(V)
* [janhq/cortex.cpp](https://github.com/janhq/cortex.cpp) - Local AI API Platform *(archived)*
* [vitoplantamura/OnnxStream](https://github.com/vitoplantamura/OnnxStream) - Lightweight inference library for ONNX files, written in C++. It can run Stable Diffusion XL 1.0 on a RPI Zero 2 (or in 298MB of RAM) but also Mistral 7B on desktops and servers. ARM, x86, WASM, RISC-V supported. Accelerated by XNNPACK. Python, C# and JS(WASM) bindings available.
* [RWKV/rwkv.cpp](https://github.com/RWKV/rwkv.cpp) - INT4/INT5/INT8 and FP16 inference on CPU for RWKV language model
* [nomic-ai/gpt4all-chat](https://github.com/nomic-ai/gpt4all-chat) - gpt4all-j chat *(archived)*
* [NVIDIA/TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) - TensorRT LLM provides users with an easy-to-use Python API to define Large Language Models (LLMs) and supports state-of-the-art optimizations to perform inference efficiently on NVIDIA GPUs. TensorRT LLM also contains components to create Python and C++ runtimes that orchestrate the inference execution in a performant way.

### Machine Learning Frameworks

* [BVLC/caffe](https://github.com/BVLC/caffe) - Caffe: a fast open framework for deep learning.
* [dmlc/xgboost](https://github.com/dmlc/xgboost) - Scalable, Portable and Distributed Gradient Boosting (GBDT, GBRT or GBM) Library, for Python, R, Java, Scala, C and more. Runs on single machine, Hadoop, Spark, Dask, Flink and DataFlow
* [microsoft/CNTK](https://github.com/microsoft/CNTK) - Microsoft Cognitive Toolkit (CNTK), an open source deep-learning toolkit *(archived)*
* [davisking/dlib](https://github.com/davisking/dlib) - A toolkit for making real world machine learning and data analysis applications in C++
* [NVIDIA/TensorRT](https://github.com/NVIDIA/TensorRT) - NVIDIA® TensorRT™ is an SDK for high-performance deep learning inference on NVIDIA GPUs. This repository contains the open source components of TensorRT.
* [catboost/catboost](https://github.com/catboost/catboost) - A fast, scalable, high performance Gradient Boosting on Decision Trees library, used for ranking, classification, regression and other machine learning tasks for Python, R, Java, C++. Supports computation on CPU and GPU.
* [tiny-dnn/tiny-dnn](https://github.com/tiny-dnn/tiny-dnn) - header only, dependency-free deep learning framework in C++14
* [mlpack/mlpack](https://github.com/mlpack/mlpack) - mlpack: a fast, header-only C++ machine learning library
* [flashlight/flashlight](https://github.com/flashlight/flashlight) - A C++ standalone library for machine learning
* [NVlabs/tiny-cuda-nn](https://github.com/NVlabs/tiny-cuda-nn) - Lightning fast C++/CUDA neural network framework
* [jolibrain/deepdetect](https://github.com/jolibrain/deepdetect) - Deep Learning Server and CLI for Torch and TensorRT
* [facebookresearch/SparseConvNet](https://github.com/facebookresearch/SparseConvNet) - Submanifold sparse convolutional networks *(archived)*
* [facebookresearch/TensorComprehensions](https://github.com/facebookresearch/TensorComprehensions) - A domain specific language to express machine learning workloads. *(archived)*
* [libfann/fann](https://github.com/libfann/fann) - Official github repository for Fast Artificial Neural Network Library (FANN)
* [sail-sg/envpool](https://github.com/sail-sg/envpool) - C++-based high-performance parallel environment execution engine (vectorized env) for general RL environments.
* [ucbrise/clipper](https://github.com/ucbrise/clipper) - A low-latency prediction-serving system
* [TorchCraft/TorchCraft](https://github.com/TorchCraft/TorchCraft) - Connecting Torch to StarCraft *(archived)*
* [happynear/caffe-windows](https://github.com/happynear/caffe-windows) - Configure Caffe in one hour for Windows users.
* [Tencent/FeatherCNN](https://github.com/Tencent/FeatherCNN) - FeatherCNN is a high performance inference engine for convolutional neural networks.
* [Dobiasd/frugally-deep](https://github.com/Dobiasd/frugally-deep) - A lightweight header-only library for using Keras (TensorFlow) models in C++.
* [dmlc/mshadow](https://github.com/dmlc/mshadow) - Matrix Shadow:Lightweight CPU/GPU Matrix and Tensor Template Library in C++/CUDA for (Deep) Machine Learning *(archived)*
* [novak-99/MLPP](https://github.com/novak-99/MLPP) - A library created to revitalize C++ as a machine learning front end. Per aspera ad astra.
* [dmlc/cxxnet](https://github.com/dmlc/cxxnet) - move forward to https://github.com/dmlc/mxnet *(archived)*
* [hughperkins/DeepCL](https://github.com/hughperkins/DeepCL) - OpenCL library to train deep convolutional neural networks
* [dmlc/dmlc-core](https://github.com/dmlc/dmlc-core) - A common bricks library for building scalable and portable distributed machine learning.
* [intel/caffe](https://github.com/intel/caffe) - This fork of BVLC/Caffe is dedicated to improving performance of this deep learning framework when running on CPU, in particular Intel® Xeon processors. *(archived)*
* [DefTruth/lite.ai.toolkit](https://github.com/DefTruth/lite.ai.toolkit) - 🛠 A lite C++ toolkit: contains 100+ Awesome AI models, support MNN, NCNN, TNN, ONNXRuntime and TensorRT. 🎉🎉
* [rapidsai/cuml](https://github.com/rapidsai/cuml) - cuML - RAPIDS Machine Learning Library

### Computer Vision

* [colmap/colmap](https://github.com/colmap/colmap) - COLMAP - Structure-from-Motion and Multi-View Stereo
* [DayBreak-u/chineseocr_lite](https://github.com/DayBreak-u/chineseocr_lite) - 超轻量级中文ocr，支持竖排文字识别, 支持ncnn、mnn、tnn推理 ( dbnet(1.8M) + crnn(2.5M) + anglenet(378KB)) 总模型仅4.7M
* [opencv/opencv_contrib](https://github.com/opencv/opencv_contrib) - Repository for OpenCV's extra modules
* [liuliu/ccv](https://github.com/liuliu/ccv) - C-based/Cached/Core Computer Vision Library, A Modern Computer Vision Library
* [xlite-dev/lite.ai.toolkit](https://github.com/xlite-dev/lite.ai.toolkit) - A lite C++ AI toolkit: 100+ models with MNN, ORT and TRT, including Det, Seg, Stable-Diffusion, Face-Fusion.
* [shouxieai/tensorRT_Pro](https://github.com/shouxieai/tensorRT_Pro) - C++ library based on tensorrt integration
* [andrewssobral/bgslibrary](https://github.com/andrewssobral/bgslibrary) - A C++ Background Subtraction Library with wrappers for Python, MATLAB, Java and GUI on QT
* [patrikhuber/eos](https://github.com/patrikhuber/eos) - A lightweight 3D Morphable Face Model library in modern C++
* [hiroi-sora/PaddleOCR-json](https://github.com/hiroi-sora/PaddleOCR-json) - OCR离线图片文字识别命令行windows程序，以JSON字符串形式输出结果，方便别的程序调用。提供各种语言API。由 PaddleOCR C++ 编译。
* [Star-Clouds/CenterFace](https://github.com/Star-Clouds/CenterFace) - face detection
* [senlinuc/caffe_ocr](https://github.com/senlinuc/caffe_ocr) - 主流ocr算法研究实验性的项目，目前实现了CNN+BLSTM+CTC架构
* [hengli/camodocal](https://github.com/hengli/camodocal) - CamOdoCal: Automatic Intrinsic and Extrinsic Calibration of a Rig with Multiple Generic Cameras and Odometry
* [alexgkendall/caffe-segnet](https://github.com/alexgkendall/caffe-segnet) - Implementation of SegNet: A Deep Convolutional Encoder-Decoder Architecture for Semantic Pixel-Wise Labelling
* [zhaoweicai/cascade-rcnn](https://github.com/zhaoweicai/cascade-rcnn) - Caffe implementation of multiple popular object detection frameworks
* [devilsen/CZXing](https://github.com/devilsen/CZXing) - Make you have the QRCode Scan ability like WeChat!
* [kylemcdonald/FaceTracker](https://github.com/kylemcdonald/FaceTracker) - Real time deformable face tracking in C++ with OpenCV 3. *(archived)*
* [pmoulon/CMVS-PMVS](https://github.com/pmoulon/CMVS-PMVS) - This software (CMVS) takes the output of a structure-from-motion (SfM) software as input, then decomposes the input images into a set of image clusters of managable size. An MVS software can be used to process each cluster independently and in parallel, where the union of reconstructions from all the clusters should not miss any details that can be otherwise obtained from the whole image set. CMVS should be used in conjunction with an SfM software Bundler and an MVS software PMVS2 (PMVS version 2).
* [joaofaro/KCFcpp](https://github.com/joaofaro/KCFcpp) - C++ Implementation of KCF Tracker
* [anhttran/3dmm_cnn](https://github.com/anhttran/3dmm_cnn) - Regressing Robust and Discriminative 3D Morphable Models with a very Deep Neural Network
* [CVCUDA/CV-CUDA](https://github.com/CVCUDA/CV-CUDA) - CV-CUDA™ is an open-source, GPU accelerated library for cloud-scale image processing and computer vision.

### Natural Language Processing

* [ggml-org/whisper.cpp](https://github.com/ggml-org/whisper.cpp) - Port of OpenAI's Whisper model in C/C++
* [k2-fsa/sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) - Speech-to-text, text-to-speech, speaker diarization, speech enhancement, source separation, and VAD using next-gen Kaldi with onnxruntime without Internet connection. Support embedded systems, Android, iOS, HarmonyOS, Raspberry Pi, RISC-V, RK NPU, Axera NPU, Ascend NPU, x86_64 servers, websocket server/client, support 12 programming languages
* [OpenNMT/CTranslate2](https://github.com/OpenNMT/CTranslate2) - Fast inference engine for Transformer models
* [yanyiwu/cppjieba](https://github.com/yanyiwu/cppjieba) - "结巴"中文分词的C++版本
* [0xShug0/audio.cpp](https://github.com/0xShug0/audio.cpp) - An all-in-one, pure C++ inference engine for audio models, powered by ggml. Supports TTS, STT, VAD, voice conversion, music generation, and more, with highly optimized performance. No Python dependency.
* [handy-computer/transcribe.cpp](https://github.com/handy-computer/transcribe.cpp) - ggml speech-to-text inference for 16+ model families
* [k2-fsa/sherpa-ncnn](https://github.com/k2-fsa/sherpa-ncnn) - Real-time speech recognition and voice activity detection (VAD) using next-gen Kaldi with ncnn without Internet connection. Support iOS, Android, Linux, macOS, Windows, Raspberry Pi, VisionFive2, LicheePi4A etc.
* [marian-nmt/marian](https://github.com/marian-nmt/marian) - Fast Neural Machine Translation in C++

### Data Science and Analytics

* [NVIDIA/cudf](https://github.com/NVIDIA/cudf) - cuDF - GPU DataFrame Library
* [asmuth/clip](https://github.com/asmuth/clip) - Create charts from the command line
* [alandefreitas/matplotplusplus](https://github.com/alandefreitas/matplotplusplus) - Matplot++: A C++ Graphics Library for Data Visualization 📊🗾
* [lava/matplotlib-cpp](https://github.com/lava/matplotlib-cpp) - Extremely simple yet powerful header-only C++ plotting library built on the popular matplotlib
* [jupyter-xeus/xeus-cling](https://github.com/jupyter-xeus/xeus-cling) - Jupyter kernel for the C++ programming language
* [hosseinmoein/DataFrame](https://github.com/hosseinmoein/DataFrame) - C++ DataFrame for statistical, financial, and ML analysis in modern C++
* [ChenglongChen/kaggle-CrowdFlower](https://github.com/ChenglongChen/kaggle-CrowdFlower) - 1st Place Solution for CrowdFlower Product Search Results Relevance Competition on Kaggle.
* [rapidsai/cudf](https://github.com/rapidsai/cudf) - cuDF - GPU DataFrame Library

## Networking and Distributed

### Networking

* [chenshuo/muduo](https://github.com/chenshuo/muduo) - Event-driven network library for multi-threaded Linux server in C++11
* [sogou/workflow](https://github.com/sogou/workflow) - C++ Parallel Computing and Asynchronous Networking Framework
* [project-chip/connectedhomeip](https://github.com/project-chip/connectedhomeip) - Matter (formerly Project CHIP) creates more connections between more objects, simplifying development for manufacturers and increasing compatibility for consumers, guided by the Connectivity Standards Alliance.
* [zaphoyd/websocketpp](https://github.com/zaphoyd/websocketpp) - C++ websocket client/server library
* [chriskohlhoff/asio](https://github.com/chriskohlhoff/asio) - Asio C++ Library
* [arvidn/libtorrent](https://github.com/arvidn/libtorrent) - an efficient feature complete C++ bittorrent implementation
* [nghttp2/nghttp2](https://github.com/nghttp2/nghttp2) - nghttp2 - HTTP/2 C Library and tools
* [sylar-yin/sylar](https://github.com/sylar-yin/sylar) - C++高性能分布式服务器框架,webserver,websocket server,自定义tcp_server（包含日志模块，配置模块，线程模块，协程模块，协程调度模块，io协程调度模块，hook模块，socket模块，bytearray序列化，http模块，TcpServer模块，Websocket模块，Https模块等, Smtp邮件模块, MySQL, SQLite3, ORM,Redis,Zookeeper)
* [yedf2/handy](https://github.com/yedf2/handy) - 🔥简洁易用的C++11网络库 / 支持单机千万并发连接 / a simple C++11 network server framework
* [Qihoo360/evpp](https://github.com/Qihoo360/evpp) - A modern C++ network library for developing high performance network services in TCP/UDP/HTTP protocols.
* [seladb/PcapPlusPlus](https://github.com/seladb/PcapPlusPlus) - PcapPlusPlus is a multiplatform C++ library for capturing, parsing and crafting of network packets. It is designed to be efficient, powerful and easy to use. It provides C++ wrappers for the most popular packet processing engines such as libpcap, Npcap, WinPcap, DPDK, AF_XDP and PF_RING.
* [mas-bandwidth/yojimbo](https://github.com/mas-bandwidth/yojimbo) - A network library for client/server games written in C++
* [paullouisageneau/libdatachannel](https://github.com/paullouisageneau/libdatachannel) - C/C++ WebRTC network library featuring Data Channels, Media Transport, and WebSockets
* [socketio/socket.io-client-cpp](https://github.com/socketio/socket.io-client-cpp) - C++11 implementation of Socket.IO client
* [ZLMediaKit/ZLToolKit](https://github.com/ZLMediaKit/ZLToolKit) - 一个基于C++11的轻量级网络框架，基于线程池技术可以实现大并发网络IO
* [c-ares/c-ares](https://github.com/c-ares/c-ares) - A C library for asynchronous DNS requests
* [mfontanini/libtins](https://github.com/mfontanini/libtins) - High-level, multiplatform C++ network packet sniffing and crafting library.
* [quickfix/quickfix](https://github.com/quickfix/quickfix) - QuickFIX C++ Fix Engine Library
* [magma/magma](https://github.com/magma/magma) - Platform for building access networks and modular network services
* [chronoxor/CppServer](https://github.com/chronoxor/CppServer) - Ultra fast and low latency asynchronous socket server & client C++ library with support TCP, SSL, UDP, HTTP, HTTPS, WebSocket protocols and 10K connections problem solution
* [shadowsocks/libQtShadowsocks](https://github.com/shadowsocks/libQtShadowsocks) - A lightweight and ultra-fast shadowsocks library written in C++14 with Qt framework *(archived)*
* [nilstate/icey](https://github.com/nilstate/icey) - Real-time media stack and lightweight libwebrtc alternative, built in C++20
* [inspircd/inspircd](https://github.com/inspircd/inspircd) - A high-performance Internet Relay Chat (IRCv3) server for UNIX-like and Windows systems
* [OpenVPN/openvpn3](https://github.com/OpenVPN/openvpn3) - OpenVPN 3 is a C++ class library that implements the functionality of an OpenVPN client, and is protocol-compatible with the OpenVPN 2.x branch.
* [caozhiyi/CppNet](https://github.com/caozhiyi/CppNet) - Cross platform network library with C++11
* [njh/EtherCard](https://github.com/njh/EtherCard) - EtherCard is an IPv4 driver for the ENC28J60 chip, compatible with Arduino IDE
* [OpenZWave/open-zwave](https://github.com/OpenZWave/open-zwave) - a C++ library to control Z-Wave Networks via a USB Z-Wave Controller.
* [Hieromon/AutoConnect](https://github.com/Hieromon/AutoConnect) - An Arduino library for ESP8266/ESP32 WLAN configuration at runtime with the Web interface

### RPC and Messaging

* [grpc/grpc](https://github.com/grpc/grpc) - C++ based gRPC (C++, Python, Ruby, Objective-C, PHP, C#)
* [apache/brpc](https://github.com/apache/brpc) - brpc is an Industrial-grade RPC framework using C++ Language, which is often used in high performance system such as Search, Storage, Machine learning, Advertisement, Recommendation etc. "brpc" means "better RPC".
* [zeromq/libzmq](https://github.com/zeromq/libzmq) - ZeroMQ core engine in C++, implements ZMTP/3.1
* [apache/thrift](https://github.com/apache/thrift) - Apache Thrift
* [facebook/fbthrift](https://github.com/facebook/fbthrift) - Facebook's branch of Apache Thrift, including a new C++ server.
* [zeromq/cppzmq](https://github.com/zeromq/cppzmq) - Header-only C++ binding for libzmq
* [mutouyun/cpp-ipc](https://github.com/mutouyun/cpp-ipc) - C++ IPC Library: A high-performance inter-process communication using shared memory on Linux/Windows.
* [zeroc-ice/ice](https://github.com/zeroc-ice/ice) - All-in-one solution for creating networked applications with RPC, pub/sub, server deployment, and more.
* [sogou/srpc](https://github.com/sogou/srpc) - RPC framework based on C++ Workflow. Supports SRPC, Baidu bRPC, Tencent tRPC, thrift protocols.
* [Tencent/phxrpc](https://github.com/Tencent/phxrpc) - A simple C++ based RPC framework.
* [qicosmos/rest_rpc](https://github.com/qicosmos/rest_rpc) - modern C++(C++20), simple, easy to use rpc framework
* [rpclib/rpclib](https://github.com/rpclib/rpclib) - rpclib is a modern C++ msgpack-RPC server and client library
* [Gooddbird/tinyrpc](https://github.com/Gooddbird/tinyrpc) - c++ async rpc framework. 14w+qps.
* [OpenDDS/OpenDDS](https://github.com/OpenDDS/OpenDDS) - OpenDDS is an open source C++ implementation of the Object Management Group (OMG) Data Distribution Service (DDS). OpenDDS also supports Java bindings through JNI.
* [Tencent/flare](https://github.com/Tencent/flare) - Flare是广泛投产于腾讯广告后台的现代化C++开发框架，包含了基础库、RPC、各种客户端等。主要特点为易用性强、长尾延迟低。
* [cinemast/libjson-rpc-cpp](https://github.com/cinemast/libjson-rpc-cpp) - C++ framework for json-rpc (json remote procedure call)

### Distributed Systems

* [ceph/ceph](https://github.com/ceph/ceph) - Ceph is a distributed object, block, and file storage platform
* [cubefs/cubefs](https://github.com/cubefs/cubefs) - cloud-native distributed storage
* [XRPLF/rippled](https://github.com/XRPLF/rippled) - Decentralized cryptocurrency blockchain daemon implementing the XRP Ledger protocol in C++
* [baidu/braft](https://github.com/baidu/braft) - An industrial-grade C++ implementation of RAFT consensus algorithm based on brpc, widely used inside Baidu to build highly-available distributed systems.
* [ethereum/aleth](https://github.com/ethereum/aleth) - Aleth – Ethereum C++ client, tools and libraries *(archived)*
* [trustwallet/wallet-core](https://github.com/trustwallet/wallet-core) - Cross-platform, cross-blockchain wallet library.
* [Tencent/phxpaxos](https://github.com/Tencent/phxpaxos) - The Paxos library implemented in C++ that has been used in the WeChat production environment.
* [stellar/stellar-core](https://github.com/stellar/stellar-core) - Reference implementation for the peer-to-peer agent that manages the Stellar network.
* [opencurve/curve](https://github.com/opencurve/curve) - Curve is a sandbox project hosted by the CNCF Foundation. It's cloud-native, high-performance, and easy to operate. Curve is an open-source distributed storage system for block and shared file storage.
* [miguelfreitas/twister-core](https://github.com/miguelfreitas/twister-core) - twister core / daemon
* [libbitcoin/libbitcoin-system](https://github.com/libbitcoin/libbitcoin-system) - Bitcoin Cross-Platform C++ Development Toolkit
* [Cocos-BCX/cocos-mainnet](https://github.com/Cocos-BCX/cocos-mainnet) - Cocos-BCX: The platform for the next generation of digital game economy
* [eBay/NuRaft](https://github.com/eBay/NuRaft) - C++ implementation of Raft core logic as a replication library
* [bitshares/bitshares-core](https://github.com/bitshares/bitshares-core) - BitShares Blockchain node and command-line wallet
* [savoirfairelinux/opendht](https://github.com/savoirfairelinux/opendht) - OpenDHT: a C++17 Distributed Hash Table implementation
* [fireice-uk/xmr-stak-cpu](https://github.com/fireice-uk/xmr-stak-cpu) - Monero CPU miner
* [WaykiChain/WaykiChain](https://github.com/WaykiChain/WaykiChain) - Public Blockchain as a Decentralized Finance Infrastructure Service Platform

## User Interface

### GUI Toolkits

* [ocornut/imgui](https://github.com/ocornut/imgui) - Dear ImGui: Bloat-free Graphical User interface for C++ with minimal dependencies
* [webview/webview](https://github.com/webview/webview) - Tiny cross-platform webview library for C/C++. Uses WebKit (GTK/Cocoa) and Edge WebView2 (Windows).
* [idea4good/GuiLite](https://github.com/idea4good/GuiLite) - ✔️The smallest header-only GUI library(4 KLOC) for all platforms
* [wxWidgets/wxWidgets](https://github.com/wxWidgets/wxWidgets) - Cross-Platform C++ GUI Library
* [chromiumembedded/cef](https://github.com/chromiumembedded/cef) - Chromium Embedded Framework (CEF). A simple framework for embedding Chromium-based browsers in other applications.
* [cycfi/elements](https://github.com/cycfi/elements) - Elements C++ GUI library
* [cztomczak/cefpython](https://github.com/cztomczak/cefpython) - Python bindings for the Chromium Embedded Framework (CEF)
* [vczh-libraries/GacUI](https://github.com/vczh-libraries/GacUI) - Native C++ UI library, cross-platform, MVVM and data binding, XML description, multi-language, core/renderer cross-process separation, etc
* [cnjinhao/nana](https://github.com/cnjinhao/nana) - a modern C++ GUI library
* [sudoevolve/EUI-NEO](https://github.com/sudoevolve/EUI-NEO) - EUI-NEO is a cross-platform, high-performance, low-overhead C++17 GPUI framework
* [mitsuba-renderer/nanogui](https://github.com/mitsuba-renderer/nanogui) - Minimalistic C++/Python GUI library for OpenGL, GLES2/3, Metal, and WebAssembly/WebGL
* [BalazsJako/ImGuiColorTextEdit](https://github.com/BalazsJako/ImGuiColorTextEdit) - Colorizing text editor for ImGui
* [uwerat/qskinny](https://github.com/uwerat/qskinny) - A lightweight framework on top of the Qt scene graph and only few classes from Qt/Quick. It is usable from C++ and/or QML.
* [arturadib/node-qt](https://github.com/arturadib/node-qt) - C++ Qt bindings for Node.js
* [cneben/QuickQanava](https://github.com/cneben/QuickQanava) - :link: C++17 network / graph visualization library - Qt6 / QML node editor.
* [copperspice/copperspice](https://github.com/copperspice/copperspice) - Set of cross platform C++ libraries (Core, Gui, Network, Multimedia, SQL, Vulkan, etc)
* [samhocevar/portable-file-dialogs](https://github.com/samhocevar/portable-file-dialogs) - 💬 Portable GUI dialogs library, C++11, single-header

### Terminal and Console UI

* [ArthurSonzogni/FTXUI](https://github.com/ArthurSonzogni/FTXUI) - :computer: C++ Functional Terminal User Interface. :heart:
* [ggerganov/imtui](https://github.com/ggerganov/imtui) - ImTui: Immediate Mode Text-based User Interface C++ Library
* [p-ranav/indicators](https://github.com/p-ranav/indicators) - Activity Indicators for Modern C++
* [p-ranav/tabulate](https://github.com/p-ranav/tabulate) - Table Maker for Modern C++
* [agauniyal/rang](https://github.com/agauniyal/rang) - A Minimal, Header only Modern c++ library for terminal goodies 💄✨
* [jstkdng/ueberzugpp](https://github.com/jstkdng/ueberzugpp) - Drop in replacement for ueberzug written in C++

### Mobile

* [crosswalk-project/crosswalk](https://github.com/crosswalk-project/crosswalk) - A web runtime built on Chrome. This project is currently unmaintained. *(archived)*
* [HuTianQi/SmartOpenCV](https://github.com/HuTianQi/SmartOpenCV) - :fire: :fire: :fire: SmartOpenCV是一个OpenCV在Android端的增强库，解决了OpenCV Android SDK在图像预览方面存在的诸多问题，且无需修改OpenCV SDK源码，与OpenCV的SDK解耦
* [margelo/nitro](https://github.com/margelo/nitro) - 🔥 Insanely fast native C++, Swift or Kotlin modules with a statically compiled binding layer to JSI
* [ammarahm-ed/react-native-mmkv-storage](https://github.com/ammarahm-ed/react-native-mmkv-storage) - An ultra fast (0.0002s read/write), small & encrypted mobile key-value storage framework for React Native written in C++ using JSI
* [AshampooSystems/boden](https://github.com/AshampooSystems/boden) - Purely native C++ cross-platform GUI framework for Android and iOS development. https://www.boden.io
* [9miao/CrossApp](https://github.com/9miao/CrossApp) - Cross-Platform Mobile APP Development Engine

### Applications and End User Tools

* [FreeCAD/FreeCAD](https://github.com/FreeCAD/FreeCAD) - Official source code of FreeCAD, a free and opensource multiplatform 3D parametric modeler.
* [microsoft/calculator](https://github.com/microsoft/calculator) - Windows Calculator: A simple yet powerful calculator that ships with Windows
* [cmderdev/cmder](https://github.com/cmderdev/cmder) - Lovely console emulator package for Windows
* [chromium/chromium](https://github.com/chromium/chromium) - The official GitHub mirror of the Chromium source
* [Qv2ray/Qv2ray](https://github.com/Qv2ray/Qv2ray) - :star: Linux / Windows / macOS 跨平台 V2Ray 客户端 | 支持 VMess / VLESS / SSR / Trojan / Trojan-Go / NaiveProxy / HTTP / HTTPS / SOCKS5 | 使用 C++ / Qt 开发 | 可拓展插件式设计 :star:
* [CoatiSoftware/Sourcetrail](https://github.com/CoatiSoftware/Sourcetrail) - Sourcetrail - free and open-source interactive source explorer *(archived)*
* [xournalpp/xournalpp](https://github.com/xournalpp/xournalpp) - Xournal++ is a handwriting notetaking software with PDF annotation support. Written in C++ with GTK3, supporting Linux (e.g. Ubuntu, Debian, Arch, SUSE), macOS and Windows 10. Supports pen input from devices such as Wacom Tablets.
* [amnezia-vpn/amnezia-client](https://github.com/amnezia-vpn/amnezia-client) - Amnezia VPN Client (Desktop+Mobile)
* [dyang886/Game-Cheats-Manager](https://github.com/dyang886/Game-Cheats-Manager) - Easily download and manage single-player game cheats for your convenience
* [vnotex/vnote](https://github.com/vnotex/vnote) - A pleasant note-taking platform in native C++.
* [hluk/CopyQ](https://github.com/hluk/CopyQ) - Clipboard manager with advanced features
* [filecxx/FileCentipede](https://github.com/filecxx/FileCentipede) - Cross-platform internet upload/download manager for HTTP(S), FTP(S), SSH, magnet-link, BitTorrent, m3u8, ed2k, and online videos. WebDAV client, FTP client, SSH client.
* [Stellarium/stellarium](https://github.com/Stellarium/stellarium) - Stellarium is a free GPL software which renders realistic skies in real time with OpenGL. It is available for Linux/Unix, Windows, macOS and Haiku. With Stellarium, you really see what you can see with your eyes, binoculars or a small telescope.
* [ConEmu/ConEmu](https://github.com/ConEmu/ConEmu) - ConEmu: Customizable Windows terminal with tabs, splits, quake-style, hotkeys and more
* [brndnmtthws/conky](https://github.com/brndnmtthws/conky) - Light-weight system monitor for X, Wayland, and other things, too
* [std-microblock/chromatic](https://github.com/std-microblock/chromatic) - Universal modifier for Chromium/V8 | 广谱注入 Chromium/V8 的通用修改器
* [LibreCAD/LibreCAD](https://github.com/LibreCAD/LibreCAD) - LibreCAD is a cross-platform 2D CAD program. It can read DXF/DWG, and write DXF/DWG/PDF/SVG files. It supports point/line/circle/ellipse/parabola/hyperbola/spline primitives. The GUI is highly customizable, and has dozens of translations.
* [Lymphatus/caesium-image-compressor](https://github.com/Lymphatus/caesium-image-compressor) - Caesium is an image compression software that helps you store, send and share digital pictures, supporting JPG, PNG, WebP and TIFF formats. You can quickly reduce the file size (and resolution, if you want) by preserving the overall quality of the image.
* [mhogomchungu/media-downloader](https://github.com/mhogomchungu/media-downloader) - Media Downloader is a Qt/C++ front end to yt-dlp, youtube-dl, gallery-dl, lux, you-get, svtplay-dl, aria2c, wget and safari books..
* [clangen/musikcube](https://github.com/clangen/musikcube) - a cross-platform, terminal-based music player, audio engine, metadata indexer, and server in c++
* [CloudCompare/CloudCompare](https://github.com/CloudCompare/CloudCompare) - CloudCompare main repository
* [anhkgg/SuperWeChatPC](https://github.com/anhkgg/SuperWeChatPC) - 超级微信电脑客户端，支持多开、防消息撤销、语音消息备份...开放WeChatSDK
* [LibreOffice/core](https://github.com/LibreOffice/core) - Read-only LibreOffice core repo - no pull request (use gerrit instead https://gerrit.libreoffice.org/) - don't download zip, use https://dev-www.libreoffice.org/bundles/ instead
* [kunkundi/crossdesk](https://github.com/kunkundi/crossdesk) - A lightweight, cross-platform remote desktop software with support for Web Client access | 一款支持 Web 客户端访问的轻量级跨平台远程桌面软件。
* [nuttyartist/notes](https://github.com/nuttyartist/notes) - Fast and beautiful note-taking app written in C++. Write down your thoughts.
* [clementine-player/Clementine](https://github.com/clementine-player/Clementine) - :tangerine: Clementine Music Player
* [giuspen/cherrytree](https://github.com/giuspen/cherrytree) - cherrytree
* [ctubio/Krypto-trading-bot](https://github.com/ctubio/Krypto-trading-bot) - Self-hosted crypto trading bot (automated high frequency market making) written in C++
* [ckb-next/ckb-next](https://github.com/ckb-next/ckb-next) - RGB Driver for Linux
* [brave/brave-core](https://github.com/brave/brave-core) - Core engine for the Brave browser for mobile and desktop. For issues https://github.com/brave/brave-browser/issues
* [ndeadly/MissionControl](https://github.com/ndeadly/MissionControl) - Use controllers from other consoles natively on your Nintendo Switch via Bluetooth. No dongles or other external hardware neccessary.
* [hiyohiyo/CrystalDiskInfo](https://github.com/hiyohiyo/CrystalDiskInfo) - CrystalDiskInfo
* [BernardoGiordano/Checkpoint](https://github.com/BernardoGiordano/Checkpoint) - Fast and simple homebrew save management framework for 3DS and Switch.
* [contour-terminal/contour](https://github.com/contour-terminal/contour) - Modern C++ Terminal Emulator
* [sanni/cartreader](https://github.com/sanni/cartreader) - A shield for the Arduino Mega that can back up video game cartridges. *(archived)*
* [Chatterino/chatterino2](https://github.com/Chatterino/chatterino2) - Chat client for https://twitch.tv
* [OpenStickCommunity/GP2040-CE](https://github.com/OpenStickCommunity/GP2040-CE) - Multi-Platform Gamepad Firmware for Raspberry Pi Pico and other RP2040 boards
* [Nheko-Reborn/nheko](https://github.com/Nheko-Reborn/nheko) - Desktop client for Matrix using Qt and C++20.
* [CelestiaProject/Celestia](https://github.com/CelestiaProject/Celestia) - Real-time 3D visualization of space.
* [webyog/sqlyog-community](https://github.com/webyog/sqlyog-community) - Webyog provides monitoring and management tools for open source relational databases. We develop easy-to-use MySQL client tools for performance tuning and database management. Webyog's solutions include SQL Diagnostic Manager for MySQL performance optimization and SQLyog for MySQL administration. More than 35,000 companies (including Amazon, IBM, Salesforce, AT&T, eBay, and GE) and 2.5 million users rely on Webyog's solutions to provide valuable insights into their databases. Webyog is an Idera, Inc. company.
* [cjcliffe/CubicSDR](https://github.com/cjcliffe/CubicSDR) - Cross-Platform Software-Defined Radio Application
* [FarGroup/FarManager](https://github.com/FarGroup/FarManager) - File and Archive Manager
* [uowuo/abaddon](https://github.com/uowuo/abaddon) - An alternative Discord client with voice support made with C++ and GTK 3
* [storax/kubedoom](https://github.com/storax/kubedoom) - Kill Kubernetes pods by playing Id's DOOM!
* [Bush2021/chrome_plus](https://github.com/Bush2021/chrome_plus) - A DLL hijack implements Chrome full portability as well as tab enhancements.
* [pgkt04/defender-control](https://github.com/pgkt04/defender-control) - An open-source windows defender manager. Now you can disable windows defender permanently.
* [crow-translate/crow-translate](https://github.com/crow-translate/crow-translate) - A simple and lightweight translator that allows you to translate and speak text using Google, Yandex Bing, LibreTranslate and Lingva. *(archived)*
* [Sapd/HeadsetControl](https://github.com/Sapd/HeadsetControl) - Sidetone and Battery status for Logitech G930, G533, G633, G933 SteelSeries Arctis 7/PRO 2019 and Corsair VOID (Pro) in Linux and MacOSX
* [serge-rgb/milton](https://github.com/serge-rgb/milton) - An infinite-canvas paint program
* [188080501/JQTools](https://github.com/188080501/JQTools) - JQTools 是一个基于 Qt/QML/C++ 的开源开发工具箱，集成文本处理、加密计算、图片优化、二维码与 Qt 辅助等常用功能。
* [collin80/SavvyCAN](https://github.com/collin80/SavvyCAN) - QT based cross platform canbus tool
* [sainnhe/caj2pdf-qt](https://github.com/sainnhe/caj2pdf-qt) - CAJ 转 PDF 转换器（GUI 版本）
* [pixop/video-compare](https://github.com/pixop/video-compare) - Split-screen video comparison tool using FFmpeg and SDL2
* [s60sc/ESP32-CAM_MJPEG2SD](https://github.com/s60sc/ESP32-CAM_MJPEG2SD) - ESP32 Camera motion capture application to record JPEGs to SD card as AVI files and stream to browser as MJPEG. If a microphone is installed then a WAV file is also created. Files can be uploaded via FTP or downloaded to browser.
* [Cubitect/cubiomes-viewer](https://github.com/Cubitect/cubiomes-viewer) - An efficient graphical Minecraft seed finder and map viewer.
* [Denvi/Candle](https://github.com/Denvi/Candle) - GRBL controller application with G-Code visualizer written in Qt.
* [benkuper/Chataigne](https://github.com/benkuper/Chataigne) - Artist-friendly Modular Machine for Art and Technology
* [cool2528/baiduCDP](https://github.com/cool2528/baiduCDP) - 百度网盘下载神器 *(archived)*
* [ChrisAnd1998/TaskbarXI](https://github.com/ChrisAnd1998/TaskbarXI) - An application written in C++ to modify the Windows 11 Taskbar. *(archived)*
* [cloose/CuteMarkEd](https://github.com/cloose/CuteMarkEd) - Qt Markdown Editor
* [calamares/calamares](https://github.com/calamares/calamares) - Distribution-independent installer framework *(archived)*
* [owncloud/client](https://github.com/owncloud/client) - 🖥️ Desktop Syncing Client for ownCloud
* [anael-seghezzi/CToy](https://github.com/anael-seghezzi/CToy) - Interactive C live coding environment
* [Voine/ChatWaifu_Mobile](https://github.com/Voine/ChatWaifu_Mobile) - 移动版二次元 AI 老婆聊天器
* [brookhong/KeyCastOW](https://github.com/brookhong/KeyCastOW) - keystroke visualizer for Windows, lets you easily display your keystrokes while recording screencasts.
* [Plutoberth/SonyHeadphonesClient](https://github.com/Plutoberth/SonyHeadphonesClient) - A {Windows, macOS, Linux} client recreating the functionality of the Sony Headphones app *(archived)*
* [ccMSC/ckb](https://github.com/ccMSC/ckb) - RGB Driver for Linux and OS X
* [ratwithacompiler/OBS-captions-plugin](https://github.com/ratwithacompiler/OBS-captions-plugin) - Closed Captioning OBS plugin using Google Speech Recognition
* [hyprwm/Hypr](https://github.com/hyprwm/Hypr) - Hypr is a tiling window manager written in modern C++.
* [thewtex/tmux-mem-cpu-load](https://github.com/thewtex/tmux-mem-cpu-load) - CPU, RAM, and load monitor for use with tmux
* [fossephate/JoyCon-Driver](https://github.com/fossephate/JoyCon-Driver) - A vJoy feeder for the Nintendo Switch JoyCons and Pro Controller
* [CDrummond/cantata](https://github.com/CDrummond/cantata) - Qt5 Graphical MPD Client *(archived)*
* [symless/synergy](https://github.com/symless/synergy) - Use the keyboard, mouse, or trackpad of one computer to control nearby computers, and work seamlessly between them.

## Graphics and Media

### Graphics and Rendering

* [openframeworks/openFrameworks](https://github.com/openframeworks/openFrameworks) - openFrameworks is a community-developed cross platform toolkit for creative coding in C++.
* [cinder/Cinder](https://github.com/cinder/Cinder) - Cinder is a community-developed, free and open source library for professional-quality creative coding in C++.
* [patriciogonzalezvivo/glslViewer](https://github.com/patriciogonzalezvivo/glslViewer) - Console-based GLSL Sandbox for 2D/3D shaders
* [mosra/magnum](https://github.com/mosra/magnum) - Lightweight and modular C++11 graphics middleware for games and data visualization
* [OGRECave/ogre](https://github.com/OGRECave/ogre) - high-performance rendering backend (C++, Python, C#, Java)
* [KhronosGroup/Vulkan-Hpp](https://github.com/KhronosGroup/Vulkan-Hpp) - Open-Source Vulkan C++ API
* [MrNeRF/LichtFeld-Studio](https://github.com/MrNeRF/LichtFeld-Studio) - Train, inspect, edit, automate, and export 3D Gaussian Splatting scenes from a single native application.
* [microsoft/DirectXShaderCompiler](https://github.com/microsoft/DirectXShaderCompiler) - This repo hosts the source for the DirectX Shader Compiler which is based on LLVM/Clang.
* [xelatihy/yocto-gl](https://github.com/xelatihy/yocto-gl) - Yocto/GL: Tiny C++ Libraries for Data-Driven Physically-based Graphics
* [microsoft/DirectXTK](https://github.com/microsoft/DirectXTK) - The DirectX Tool Kit (aka DirectXTK) is a collection of helper classes for writing DirectX 11.x code in C++
* [tsoding/olive.c](https://github.com/tsoding/olive.c) - Simple 2D Graphics Library for C
* [nmwsharp/polyscope](https://github.com/nmwsharp/polyscope) - A C++ & Python viewer for 3D data like meshes and point clouds
* [floooh/oryol](https://github.com/floooh/oryol) - A small, portable and extensible C++ 3D coding framework
* [knightcrawler25/GLSL-PathTracer](https://github.com/knightcrawler25/GLSL-PathTracer) - A toy physically based GPU path tracer (C++/OpenGL/GLSL)
* [microsoft/Win2D](https://github.com/microsoft/Win2D) - Win2D is an easy-to-use Windows Runtime API for immediate mode 2D graphics rendering with GPU acceleration. It is available to C#, C++ and VB developers writing apps for the Windows Universal Platform (UWP). It utilizes the power of Direct2D, and integrates seamlessly with XAML and CoreWindow.
* [microsoft/ShaderConductor](https://github.com/microsoft/ShaderConductor) - ShaderConductor is a tool designed for cross-compiling HLSL to other shading languages *(archived)*
* [tunabrain/tungsten](https://github.com/tunabrain/tungsten) - High performance physically based renderer in C++11
* [vsg-dev/VulkanSceneGraph](https://github.com/vsg-dev/VulkanSceneGraph) - Vulkan & C++17 based Scene Graph Project
* [thorvg/thorvg](https://github.com/thorvg/thorvg) - A production-ready C++ vector graphics engine supporting SVG and Lottie formats, featuring advanced rendering backends such as WebGPU for high-performance graphics.
* [pelicanmapping/osgearth](https://github.com/pelicanmapping/osgearth) - 3D Maps & Terrain SDK (C++)
* [microsoft/DirectXTK12](https://github.com/microsoft/DirectXTK12) - The DirectX Tool Kit (aka DirectXTK12) is a collection of helper classes for writing DirectX 12 code in C++
* [LiangliangNan/Easy3D](https://github.com/LiangliangNan/Easy3D) - A lightweight, easy-to-use, and efficient library for processing and rendering 3D data (C++ & Python)
* [googlevr/cardboard](https://github.com/googlevr/cardboard) - Open source Cardboard SDK and samples
* [Auburn/FastNoise2](https://github.com/Auburn/FastNoise2) - Modular node graph based noise generation library using SIMD, C++17 and templates
* [narzoul/DDrawCompat](https://github.com/narzoul/DDrawCompat) - DirectDraw and Direct3D 1-7 compatibility, performance and visual enhancements for Windows Vista, 7, 8, 10 and 11
* [OGRECave/ogre-next](https://github.com/OGRECave/ogre-next) - scene-oriented, flexible 3D C++ engine
* [LuxCoreRender/LuxCore](https://github.com/LuxCoreRender/LuxCore) - LuxCore source repository
* [tgfrerer/island](https://github.com/tgfrerer/island) - 🌋🐎 Project Island is an experimental, hot-reloading Vulkan Renderer for Linux and Windows, written in C/C++.
* [google/lullaby](https://github.com/google/lullaby) - A collection of C++ libraries designed to help teams develop virtual and augmented reality experiences *(archived)*
* [ibaaj/dijkstra-cartography](https://github.com/ibaaj/dijkstra-cartography) - Using Dijkstra's algorithm ("finding the shortest paths between nodes in a graph") to draw maps :earth_africa:. *(archived)*
* [madmann91/bvh](https://github.com/madmann91/bvh) - A modern C++ BVH construction and traversal library
* [keith2018/SoftGLRender](https://github.com/keith2018/SoftGLRender) - Tiny C++ Software Renderer / Rasterizer, and implements OpenGL and Vulkan renderers for comparison
* [aras-p/ToyPathTracer](https://github.com/aras-p/ToyPathTracer) - Toy path tracer for my own learning purposes (CPU/GPU, C++/C#, Win/Mac/Wasm, DX11/Metal, also Unity)
* [JoeyDeVries/Cell](https://github.com/JoeyDeVries/Cell) - OpenGL C++ Graphics Engine

### Game Development

* [shadps4-emu/shadPS4](https://github.com/shadps4-emu/shadPS4) - PlayStation 4 emulator for Windows, Linux, macOS and FreeBSD written in C++
* [electronicarts/CnC_Remastered_Collection](https://github.com/electronicarts/CnC_Remastered_Collection) - Command & Conquer: Remastered Collection *(archived)*
* [RPCS3/rpcs3](https://github.com/RPCS3/rpcs3) - PlayStation 3 emulator and debugger
* [cocos2d/cocos2d-x](https://github.com/cocos2d/cocos2d-x) - Cocos2d-x is a suite of open-source, cross-platform, game-development tools utilized by millions of developers across the globe. Its core has evolved to serve as the foundation for Cocos Creator 1.x & 2.x.
* [OpenRCT2/OpenRCT2](https://github.com/OpenRCT2/OpenRCT2) - An open source re-implementation of RollerCoaster Tycoon 2 🎢
* [hrydgard/ppsspp](https://github.com/hrydgard/ppsspp) - A PSP emulator for Android, Windows, Mac, Linux and iOS, written in C++. Want to contribute? Join us on Discord at https://discord.gg/5NJB6dD or just send pull requests / issues.
* [skypjack/entt](https://github.com/skypjack/entt) - Gaming meets modern C++ - a fast and reliable entity component system (ECS) and much more
* [CleverRaven/Cataclysm-DDA](https://github.com/CleverRaven/Cataclysm-DDA) - Cataclysm - Dark Days Ahead. A turn-based survival game set in a post-apocalyptic world.
* [jrouwe/JoltPhysics](https://github.com/jrouwe/JoltPhysics) - A multi core friendly rigid body physics and collision detection library. Written in C++. Suitable for games and VR applications. Used by Horizon Forbidden West and Death Stranding 2.
* [TrinityCore/TrinityCore](https://github.com/TrinityCore/TrinityCore) - TrinityCore Open Source MMO Framework (master = 12.1.0.69497, 3.3.5 = 3.3.5a.12340, cata classic = 4.4.2.60895)
* [cocos/cocos-engine](https://github.com/cocos/cocos-engine) - Cocos simplifies game creation and distribution with Cocos Creator, a free, open-source, cross-platform game engine. Empowering millions of developers to create high-performance, engaging 2D/3D games and instant web entertainment.
* [cemu-project/Cemu](https://github.com/cemu-project/Cemu) - Cemu - Wii U emulator
* [electronicarts/CnC_Red_Alert](https://github.com/electronicarts/CnC_Red_Alert) - Command and Conquer: Red Alert *(archived)*
* [cuberite/cuberite](https://github.com/cuberite/cuberite) - A lightweight, fast and extensible game server for Minecraft
* [supertuxkart/stk-code](https://github.com/supertuxkart/stk-code) - The code base of SuperTuxKart
* [The-Powder-Toy/The-Powder-Toy](https://github.com/The-Powder-Toy/The-Powder-Toy) - Written in C++ and using SDL, The Powder Toy is a desktop version of the classic 'falling sand' physics sandbox, it simulates air pressure and velocity as well as heat.
* [panda3d/panda3d](https://github.com/panda3d/panda3d) - Powerful, mature open-source cross-platform game engine for Python and C++, developed by Disney and CMU
* [amhndu/SimpleNES](https://github.com/amhndu/SimpleNES) - An NES emulator in C++
* [gameplay3d/gameplay](https://github.com/gameplay3d/gameplay) - Open-source, cross-platform, C++ game engine for creating 2D/3D games.
* [maximegmd/CyberEngineTweaks](https://github.com/maximegmd/CyberEngineTweaks) - Cyberpunk 2077 tweaks, hacks and scripting framework
* [electronicarts/CnC_Generals_Zero_Hour](https://github.com/electronicarts/CnC_Generals_Zero_Hour) - Command and Conquer: Generals - Zero Hour *(archived)*
* [k4zmu2a/SpaceCadetPinball](https://github.com/k4zmu2a/SpaceCadetPinball) - Decompilation of 3D Pinball for Windows – Space Cadet
* [ketoo/NoahGameFrame](https://github.com/ketoo/NoahGameFrame) - A fast, scalable, distributed game server engine/framework for C++, include the actor library, network library, can be used as a real time multiplayer game engine ( MMO RPG/MOBA ), which support C#/Lua script/ Unity3d, Cocos2dx and plan to support Unreal.
* [nem0/LumixEngine](https://github.com/nem0/LumixEngine) - 3D C++ Game Engine - yet another open source game engine
* [amzeratul/halley](https://github.com/amzeratul/halley) - A lightweight game engine written in modern C++
* [AtomicGameEngine/AtomicGameEngine](https://github.com/AtomicGameEngine/AtomicGameEngine) - The Atomic Game Engine is a multi-platform 2D and 3D engine with a consistent API in C++, C#, JavaScript, and TypeScript *(archived)*
* [crawl/crawl](https://github.com/crawl/crawl) - Dungeon Crawl: Stone Soup official repository
* [scarsty/kys-cpp](https://github.com/scarsty/kys-cpp) - 《金庸群侠传》c++复刻版，已完工
* [guillaumeblanc/ozz-animation](https://github.com/guillaumeblanc/ozz-animation) - Open source c++ skeletal animation library and toolset
* [alexbatalov/fallout1-ce](https://github.com/alexbatalov/fallout1-ce) - Fallout for modern operating systems
* [coronalabs/corona](https://github.com/coronalabs/corona) - Solar2D Game Engine main repository (ex Corona SDK)
* [Hopson97/MineCraft-One-Week-Challenge](https://github.com/Hopson97/MineCraft-One-Week-Challenge) - I challenged myself to see if I could create a voxel game (Minecraft-like) in just one week using C++ and OpenGL, and here is the result
* [yimengfan/BDFramework.Core](https://github.com/yimengfan/BDFramework.Core) - Simple and powerful Unity3d game workflow! 简单、高效、高度工业化的商业级unity3d 工作流。
* [PanicPetal/ALS-Community](https://github.com/PanicPetal/ALS-Community) - Replicated and optimized community version of Advanced Locomotion System V4 for Unreal Engine 5.4 with additional features & bug fixes
* [godotengine/godot-cpp](https://github.com/godotengine/godot-cpp) - C++ bindings for the Godot script API
* [teeworlds/teeworlds](https://github.com/teeworlds/teeworlds) - A retro multiplayer shooter
* [crownengine/crown](https://github.com/crownengine/crown) - A complete and cross-platform game engine designed for flexibility, performance and fast iteration.
* [alexbatalov/fallout2-ce](https://github.com/alexbatalov/fallout2-ce) - Fallout 2 for modern operating systems
* [Cxbx-Reloaded/Cxbx-Reloaded-legacy](https://github.com/Cxbx-Reloaded/Cxbx-Reloaded-legacy) - Xbox (Original) Emulator
* [alecthomas/entityx](https://github.com/alecthomas/entityx) - EntityX - A fast, type-safe C++ Entity-Component system
* [tuyoogame/huatuo](https://github.com/tuyoogame/huatuo) - huatuo是一个特性完整、零成本、高性能、低内存的近乎完美的Unity全平台原生c#热更方案。 Huatuo is a fully featured, zero-cost, high-performance, low-memory solution for Unity's all-platform native c# hotfix
* [JACoders/OpenJK](https://github.com/JACoders/OpenJK) - Community effort to maintain and improve Jedi Academy (SP & MP) + Jedi Outcast (SP only) released by Raven Software
* [plibither8/2048.cpp](https://github.com/plibither8/2048.cpp) - 🎮 Fully featured terminal version of the game "2048" written in C++
* [CytopiaTeam/Cytopia](https://github.com/CytopiaTeam/Cytopia) - :deciduous_tree::house_with_garden::office::evergreen_tree: A city building simulation game
* [gosu/gosu](https://github.com/gosu/gosu) - 2D game development library for Ruby and C++
* [EQMG/Acid](https://github.com/EQMG/Acid) - A high speed C++17 Vulkan game engine
* [ErLinErYi/PlantsVsZombies](https://github.com/ErLinErYi/PlantsVsZombies) - PlantsVsZombies game made by cocos2dx 3.16 (c++)
* [ezEngine/ezEngine](https://github.com/ezEngine/ezEngine) - An open source C++ game engine.
* [GameFoundry/B3DFramework](https://github.com/GameFoundry/B3DFramework) - Modern C++ library for the development of real-time graphical applications
* [cocos2d/cocos2d-js](https://github.com/cocos2d/cocos2d-js) - cocos2d-x for JS
* [otland/forgottenserver](https://github.com/otland/forgottenserver) - A free and open-source MMORPG server emulator written in C++
* [Cockatrice/Cockatrice](https://github.com/Cockatrice/Cockatrice) - A cross-platform virtual tabletop for multiplayer card games
* [electronicarts/CnC_Tiberian_Dawn](https://github.com/electronicarts/CnC_Tiberian_Dawn) - Command and Conquer Tiberian Dawn *(archived)*
* [dosbox-staging/dosbox-staging](https://github.com/dosbox-staging/dosbox-staging) - DOSBox Staging is a modern continuation of DOSBox with advanced features and current development practices.
* [DanielChappuis/reactphysics3d](https://github.com/DanielChappuis/reactphysics3d) - Open source C++ physics engine library in 3D
* [GValiente/butano](https://github.com/GValiente/butano) - Modern C++ high level GBA engine
* [TriAxis-Games/RealtimeMeshComponent](https://github.com/TriAxis-Games/RealtimeMeshComponent) - Unreal Engine 5 plugin component for rendering runtime generated content.
* [hugoam/two](https://github.com/hugoam/two) - c++ toolkit for rapid development of live graphical apps and games
* [Blizzard/s2client-api](https://github.com/Blizzard/s2client-api) - StarCraft II Client - C++ library supported on Windows, Linux and Mac designed for building scripted bots and research using the SC2API.
* [perilouswithadollarsign/cstrike15_src](https://github.com/perilouswithadollarsign/cstrike15_src) - Leak of CS:GO Source code, provided by yours truly so go rep me
* [electronicarts/CnC_Renegade](https://github.com/electronicarts/CnC_Renegade) - Command and Conquer: Renegade *(archived)*
* [TeamHypersomnia/Hypersomnia](https://github.com/TeamHypersomnia/Hypersomnia) - Multiplayer top-down shooter made from scratch in C++. Web version: https://play.hypersomnia.io Made in 🇵🇱
* [jmorton06/Lumos](https://github.com/jmorton06/Lumos) - Cross-Platform C++ 2D/3D game engine
* [hugoam/toy](https://github.com/hugoam/toy) - the thin c++ game engine
* [ProjectBorealis/PBCharacterMovement](https://github.com/ProjectBorealis/PBCharacterMovement) - HL2-style, classic FPS movement for Unreal Engine implemented in C++
* [chukong/quick-cocos2d-x](https://github.com/chukong/quick-cocos2d-x) - quick-cocos2d-x is a quick framework, based on cocos2d-x. Make mobile games in Lua.
* [Sixze/ALS-Refactored](https://github.com/Sixze/ALS-Refactored) - Completely reworked and improved C++ version of Advanced Locomotion System V4.
* [kripken/BananaBread](https://github.com/kripken/BananaBread) - BananaBread is a C++ 3D game engine that runs on the web using JavaScript+WebGL+HTML
* [MihailRis/voxelcore](https://github.com/MihailRis/voxelcore) - VoxelCore – voxel game engine in C++
* [mayerui/sudoku](https://github.com/mayerui/sudoku) - C++实现的跨平台数独游戏，命令行操作易上手，可以在开发间隙用来放松身心。数百行代码，初学者也可以轻松掌握。
* [binji/pokegb](https://github.com/binji/pokegb) - A gameboy emulator that only plays Pokemon Blue, in ~50 lines of c++.
* [SourMesen/Mesen](https://github.com/SourMesen/Mesen) - Mesen is a cross-platform (Windows & Linux) NES/Famicom emulator built in C++ and C# *(archived)*
* [nCine/nCine](https://github.com/nCine/nCine) - A cross-platform 2D game engine
* [silence1772/GreedySnake](https://github.com/silence1772/GreedySnake) - c++经典项目贪吃蛇游戏控制台版，详细注释
* [CE-Programming/CEmu](https://github.com/CE-Programming/CEmu) - Third-party TI-84 Plus CE / TI-83 Premium CE emulator, focused on developer features
* [colobot/colobot](https://github.com/colobot/colobot) - Source code of open-source Colobot: Gold Edition project developed by Epsitec and TerranovaTeam
* [asc-community/MxEngine](https://github.com/asc-community/MxEngine) - C++ open source 3D game engine
* [Siv3D/OpenSiv3D](https://github.com/Siv3D/OpenSiv3D) - C++20 framework for creative coding 🎮🎨🎹 / Cross-platform support (Windows, macOS, Linux, and the Web)
* [gscept/nebula](https://github.com/gscept/nebula) - Nebula is an open-source and free-to-use modern C++ game engine.
* [cmangos/mangos-classic](https://github.com/cmangos/mangos-classic) - C(ontinued)-MaNGOS (Classic fork) is about: -- Doing WoW-Emulation Right!
* [elnormous/ouzel](https://github.com/elnormous/ouzel) - C++ game engine for Windows, macOS, Linux, iOS, tvOS, Android, and web browsers
* [Cxbx-Reloaded/Cxbx-Reloaded](https://github.com/Cxbx-Reloaded/Cxbx-Reloaded) - Xbox (Original) Emulator

### Audio

* [juce-framework/JUCE](https://github.com/juce-framework/JUCE) - JUCE is an open-source cross-platform C++ application framework for desktop and mobile applications, including VST, VST3, AU, AUv3, LV2 and AAX audio plug-ins.
* [google/oboe](https://github.com/google/oboe) - Oboe is a C++ library that makes it easy to build high-performance audio apps on Android.
* [bozbez/win-capture-audio](https://github.com/bozbez/win-capture-audio) - An OBS plugin that allows capture of independant application audio streams on Windows, in a similar fashion to OBS's game capture and Discord's application streaming.
* [MTG/essentia](https://github.com/MTG/essentia) - C++ library for audio and music analysis, description and synthesis, including Python bindings
* [DISTRHO/Cardinal](https://github.com/DISTRHO/Cardinal) - Virtual modular synthesizer plugin
* [zrythm/zrythm](https://github.com/zrythm/zrythm) - a highly automated and intuitive digital audio workstation - official mirror
* [falkTX/Carla](https://github.com/falkTX/Carla) - Audio plugin host
* [bbc/audiowaveform](https://github.com/bbc/audiowaveform) - C++ program to generate waveform data and render waveform images from audio files
* [vinniefalco/DSPFilters](https://github.com/vinniefalco/DSPFilters) - A Collection of Useful C++ Classes for Digital Signal Processing
* [kfrlib/kfr](https://github.com/kfrlib/kfr) - Fast, modern C++ DSP framework, FFT, Sample Rate Conversion, FIR/IIR/Biquad Filters (SSE, AVX, AVX-512, ARM NEON, RISC-V RVV)
* [thestk/rtaudio](https://github.com/thestk/rtaudio) - A set of C++ classes that provide a common API for realtime audio input/output across Linux (native ALSA, JACK, PulseAudio and OSS), Macintosh OS X (CoreAudio and JACK), and Windows (DirectSound, ASIO, and WASAPI) operating systems.
* [micknoise/Maximilian](https://github.com/micknoise/Maximilian) - C++ Audio and Music DSP Library
* [tttapa/Control-Surface](https://github.com/tttapa/Control-Surface) - Arduino library for creating MIDI controllers and other MIDI devices.
* [cycfi/q](https://github.com/cycfi/q) - C++ Library for Audio Digital Signal Processing
* [acoustid/chromaprint](https://github.com/acoustid/chromaprint) - C library for generating audio fingerprints used by AcoustID
* [thestk/stk](https://github.com/thestk/stk) - The Synthesis ToolKit in C++ (STK) is a set of open source audio signal processing and algorithmic synthesis classes written in the C++ programming language.
* [thestk/rtmidi](https://github.com/thestk/rtmidi) - A set of C++ classes that provide a common API for realtime MIDI input/output across Linux (ALSA & JACK), Macintosh OS X (CoreMIDI) and Windows (Multimedia)
* [pierreguillot/Camomile](https://github.com/pierreguillot/Camomile) - An audio plugin with Pure Data embedded that allows to load and to control patches
* [spotify/echoprint-codegen](https://github.com/spotify/echoprint-codegen) - Codegen for Echoprint *(archived)*

### Image and Video

* [ossrs/srs](https://github.com/ossrs/srs) - SRS is a simple, high-performance, AI-driven real-time media server supporting RTMP, WebRTC, HLS, HTTP-FLV, HTTP-TS, SRT, MPEG-DASH, and GB28181, with codec support for H.264, H.265, AV1, VP9, AAC, Opus, and G.711.
* [ZLMediaKit/ZLMediaKit](https://github.com/ZLMediaKit/ZLMediaKit) - WebRTC/RTSP/RTMP/HTTP/HLS/HTTP-FLV/WebSocket-FLV/HTTP-TS/HTTP-fMP4/WebSocket-TS/WebSocket-fMP4/GB28181/SRT/STUN/TURN server and client framework based on C++11
* [lltcggie/waifu2x-caffe](https://github.com/lltcggie/waifu2x-caffe) - waifu2xのCaffe版
* [MayaPosch/NymphCast](https://github.com/MayaPosch/NymphCast) - Audio and video casting system with support for custom applications.
* [lvandeve/lodepng](https://github.com/lvandeve/lodepng) - PNG encoder and decoder in C and C++.
* [rdp/screen-capture-recorder-to-video-windows-free](https://github.com/rdp/screen-capture-recorder-to-video-windows-free) - a free open source windows "screen capture" device and recorder (also allows VLC/ffmpeg and others to capture/stream desktop/audio)
* [ermig1979/Simd](https://github.com/ermig1979/Simd) - C++ image processing and machine learning library with using of SIMD: SSE, AVX, AVX-512, AMX for x86/x64, NEON, SVE for ARM, HVX for Hexagon
* [material-foundation/material-color-utilities](https://github.com/material-foundation/material-color-utilities) - Color libraries for Material You
* [AcademySoftwareFoundation/OpenColorIO](https://github.com/AcademySoftwareFoundation/OpenColorIO) - A color management framework for visual effects and animation.
* [zxing-cpp/zxing-cpp](https://github.com/zxing-cpp/zxing-cpp) - C++ port of ZXing
* [CatxFish/obs-virtual-cam](https://github.com/CatxFish/obs-virtual-cam) - obs-studio plugin to simulate a directshow webcam *(archived)*
* [GreycLab/CImg](https://github.com/GreycLab/CImg) - The CImg Library is a small and open-source C++ toolkit for image processing
* [OpenShot/libopenshot](https://github.com/OpenShot/libopenshot) - OpenShot Video Library (libopenshot) is a free, open-source project dedicated to delivering high quality video editing, animation, and playback solutions to the world. API currently supports C++, Python, and Ruby.
* [jgh-/VideoCore-Inactive](https://github.com/jgh-/VideoCore-Inactive) - *No longer in development* Please see https://github.com/unpause-live/SwiftVideo *(archived)*
* [GPUOpen-Tools/compressonator](https://github.com/GPUOpen-Tools/compressonator) - Tool suite for Texture and 3D Model Compression, Optimization and Analysis using CPUs, GPUs and APUs
* [unity3d-jp/FrameCapturer](https://github.com/unity3d-jp/FrameCapturer) - export framebuffer, GBuffer or any RenderTextures from Unity to file. supported format: png, exr, gif, webm, mp4
* [BinomialLLC/crunch](https://github.com/BinomialLLC/crunch) - Advanced DXTc texture compression and transcoding library *(archived)*
* [NVIDIA/VideoProcessingFramework](https://github.com/NVIDIA/VideoProcessingFramework) - Set of Python bindings to C++ libraries which provides full HW acceleration for video decoding, encoding and GPU-accelerated color space and pixel format conversions

## Security

### Cryptography

* [AGWA/git-crypt](https://github.com/AGWA/git-crypt) - Transparent file encryption in git
* [weidai11/cryptopp](https://github.com/weidai11/cryptopp) - free C++ class library of cryptographic schemes
* [spaceandtimefdn/blitzar](https://github.com/spaceandtimefdn/blitzar) - Zero-knowledge proof acceleration with GPUs for C++ and Rust
* [google/fully-homomorphic-encryption](https://github.com/google/fully-homomorphic-encryption) - Homomorphic Encryption demos
* [facebookarchive/conceal](https://github.com/facebookarchive/conceal) - Conceal provides easy Android APIs for performing fast encryption and authentication of data. *(archived)*
* [cryfs/cryfs](https://github.com/cryfs/cryfs) - Cryptographic filesystem for the cloud
* [scipr-lab/libsnark](https://github.com/scipr-lab/libsnark) - C++ library for zkSNARKs
* [zama-ai/concrete](https://github.com/zama-ai/concrete) - Concrete: TFHE Compiler that converts python programs into FHE equivalent
* [facebookincubator/fizz](https://github.com/facebookincubator/fizz) - C++14 implementation of the TLS-1.3 standard
* [google/certificate-transparency](https://github.com/google/certificate-transparency) - Auditing for TLS certificates. *(archived)*

### Security Tools

* [Adaptix-Framework/AdaptixC2](https://github.com/Adaptix-Framework/AdaptixC2) - AdaptixC2 is a highly modular advanced redteam toolkit
* [eliboa/TegraRcmGUI](https://github.com/eliboa/TegraRcmGUI) - C++ GUI for TegraRcmSmash (Fusée Gelée exploit for Nintendo Switch)
* [0vercl0k/rp](https://github.com/0vercl0k/rp) - rp++ is a fast C++ ROP gadget finder for PE/ELF/Mach-O x86/x64/ARM/ARM64 binaries.
* [cifertech/RF-Clown](https://github.com/cifertech/RF-Clown) - BLE and Bluetooth Jammer with nRF24L01 and ESP32
* [HoShiMin/Kernel-Bridge](https://github.com/HoShiMin/Kernel-Bridge) - Windows kernel hacking framework, driver template, hypervisor and API written on C++
* [ReversecLabs/C3](https://github.com/ReversecLabs/C3) - Custom Command and Control (C3). A framework for rapid prototyping of custom C2 channels, while still providing integration with existing offensive toolkits.
* [andrivet/ADVobfuscator](https://github.com/andrivet/ADVobfuscator) - Obfuscation library based on C++20 and metaprogramming
* [google/sandboxed-api](https://github.com/google/sandboxed-api) - Generate sandboxes for C/C++ libraries automatically
* [Meckazin/ChromeKatz](https://github.com/Meckazin/ChromeKatz) - Dump cookies and credentials directly from Chrome/Edge process memory
* [roadwy/RIP](https://github.com/roadwy/RIP) - Free,Open-Source,Cross-platform agent and Post-exploiton tool written in Golang and C++. *(archived)*
* [JustasMasiulis/xorstr](https://github.com/JustasMasiulis/xorstr) - heavily vectorized c++17 compile time string encryption.
* [adamyaxley/Obfuscate](https://github.com/adamyaxley/Obfuscate) - Guaranteed compile-time string literal obfuscation header-only library for C++14
* [open-license-manager/licensecc](https://github.com/open-license-manager/licensecc) - Software licensing, copy protection in C++. It has few dependencies and it's cross-platform.
* [NytroRST/ShellcodeCompiler](https://github.com/NytroRST/ShellcodeCompiler) - Shellcode Compiler
* [d35ha/CallObfuscator](https://github.com/d35ha/CallObfuscator) - Obfuscate specific windows apis with different apis
* [breenmachine/RottenPotatoNG](https://github.com/breenmachine/RottenPotatoNG) - New version of RottenPotato as a C++ DLL and standalone C++ binary - no need for meterpreter or other tools.

### Reverse Engineering

* [rizinorg/cutter](https://github.com/rizinorg/cutter) - Free and Open Source Reverse Engineering Platform powered by rizin
* [lief-project/LIEF](https://github.com/lief-project/LIEF) - LIEF - Library to Instrument Executable Formats (C++, Python, Rust)
* [zrax/pycdc](https://github.com/zrax/pycdc) - C++ python bytecode disassembler and decompiler
* [danielkrupinski/Osiris](https://github.com/danielkrupinski/Osiris) - Cross-platform game hack for Counter-Strike 2 with Panorama-based GUI.
* [REhints/HexRaysCodeXplorer](https://github.com/REhints/HexRaysCodeXplorer) - Hex-Rays Decompiler plugin for better code navigation
* [stevemk14ebr/PolyHook_2_0](https://github.com/stevemk14ebr/PolyHook_2_0) - C++20, x86/x64 Hooking Libary v2.0
* [KEV0143/Direct-memory-access-CS2-DMA](https://github.com/KEV0143/Direct-memory-access-CS2-DMA) - Low-level Direct Memory Access (DMA) framework for CS2, designed for memory acquisition, entity-state parsing, synchronization, and PCIe/reverse-engineering research.
* [vtil-project/VTIL-Core](https://github.com/vtil-project/VTIL-Core) - Virtual-machine Translation Intermediate Language
* [wbenny/hvpp](https://github.com/wbenny/hvpp) - hvpp is a lightweight Intel x64/VT-x hypervisor written in C++ focused primarily on virtualization of already running operating system

## Concurrency and Performance

### Concurrency and Parallelism

* [cameron314/concurrentqueue](https://github.com/cameron314/concurrentqueue) - A fast multi-producer, multi-consumer lock-free concurrent queue for C++11
* [taskflow/taskflow](https://github.com/taskflow/taskflow) - A General-purpose Task-parallel Programming System in C++
* [progschj/ThreadPool](https://github.com/progschj/ThreadPool) - A simple C++11 Thread Pool implementation
* [cameron314/readerwriterqueue](https://github.com/cameron314/readerwriterqueue) - A fast single-producer, single-consumer lock-free queue for C++
* [lewissbaker/cppcoro](https://github.com/lewissbaker/cppcoro) - A library of C++ coroutine abstractions for the coroutines TS
* [actor-framework/actor-framework](https://github.com/actor-framework/actor-framework) - An Open Source Implementation of the Actor Model in C++
* [yyzybb537/libgo](https://github.com/yyzybb537/libgo) - Go-style concurrency in C++11
* [ReactiveX/RxCpp](https://github.com/ReactiveX/RxCpp) - Reactive Extensions for C++
* [bshoshany/thread-pool](https://github.com/bshoshany/thread-pool) - BS::thread_pool: a fast, lightweight, modern, and easy-to-use C++17 / C++20 / C++23 thread pool library
* [TheHPXProject/hpx](https://github.com/TheHPXProject/hpx) - The C++ Standard Library for Parallelism and Concurrency
* [David-Haim/concurrencpp](https://github.com/David-Haim/concurrencpp) - Modern concurrency for C++. Tasks, executors, timers and C++20 coroutines to rule them all
* [khizmax/libcds](https://github.com/khizmax/libcds) - A C++ library of Concurrent Data Structures
* [kokkos/kokkos](https://github.com/kokkos/kokkos) - Kokkos C++ Performance Portability Programming Ecosystem: The Programming Model - Parallel Execution and Memory Abstraction
* [ChunelFeng/CGraph](https://github.com/ChunelFeng/CGraph) - 【A common used C++ & Python DAG framework】 一个通用的、无三方依赖的、跨平台的、收录于awesome-cpp的、基于流图的并行计算框架。欢迎star & fork & 交流
* [skypjack/uvw](https://github.com/skypjack/uvw) - Header-only, event based, tiny and easy to use libuv wrapper in modern C++ - now available as also shared/static library!
* [vit-vit/CTPL](https://github.com/vit-vit/CTPL) - Modern and efficient C++ Thread Pool Library
* [dougbinks/enkiTS](https://github.com/dougbinks/enkiTS) - A permissively licensed C and C++ Task Scheduler for creating parallel programs. Requires C++11 support.
* [google/marl](https://github.com/google/marl) - A hybrid thread / fiber task scheduler written in C++ 11 *(archived)*
* [max0x7ba/atomic_queue](https://github.com/max0x7ba/atomic_queue) - C++14 concurrent lock-free low-latency queue.
* [rigtorp/MPMCQueue](https://github.com/rigtorp/MPMCQueue) - A bounded multi-producer multi-consumer concurrent queue written in C++11
* [preshing/junction](https://github.com/preshing/junction) - Concurrent data structures in C++
* [Amanieu/asyncplusplus](https://github.com/Amanieu/asyncplusplus) - Async++ concurrency framework for C++11
* [VoidStar2077/workspace](https://github.com/VoidStar2077/workspace) - workspace是基于C++11的轻量级异步执行框架，支持：通用任务异步并发执行、优先级任务调度、自适应动态线程池、高效静态线程池、异常处理机制等。
* [mtrebi/thread-pool](https://github.com/mtrebi/thread-pool) - Thread pool implementation using c++11 threads
* [snakster/cpp.react](https://github.com/snakster/cpp.react) - C++React: A reactive programming library for C++11.
* [RaftLib/RaftLib](https://github.com/RaftLib/RaftLib) - The RaftLib C++ library, streaming/dataflow concurrency via C++ iostream-like operators
* [NVIDIA/stdexec](https://github.com/NVIDIA/stdexec) - `std::execution`, the standard C++ framework for asynchronous and parallel programming.

### Performance and Optimization

* [NVIDIA/cutlass](https://github.com/NVIDIA/cutlass) - CUDA Templates and Python DSLs for High-Performance Linear Algebra
* [NVIDIA/thrust](https://github.com/NVIDIA/thrust) - [ARCHIVED] The C++ parallel algorithms library. See https://github.com/NVIDIA/cccl *(archived)*
* [arrayfire/arrayfire](https://github.com/arrayfire/arrayfire) - ArrayFire: a general purpose GPU library.
* [ROCm/hip](https://github.com/ROCm/hip) - HIP: C++ Heterogeneous-Compute Interface for Portability
* [AnswerDotAI/gpu.cpp](https://github.com/AnswerDotAI/gpu.cpp) - A lightweight library for portable low-level GPU computation using WebGPU.
* [google/zopfli](https://github.com/google/zopfli) - Zopfli Compression Algorithm is a compression library programmed in C to perform very good, but slow, deflate or zlib compression. *(archived)*
* [ARM-software/ComputeLibrary](https://github.com/ARM-software/ComputeLibrary) - The Compute Library is a set of computer vision and machine learning functions optimised for both Arm CPUs and GPUs using SIMD technologies.
* [richgel999/miniz](https://github.com/richgel999/miniz) - miniz: Single C source file zlib-replacement library, originally from code.google.com/p/miniz
* [xtensor-stack/xsimd](https://github.com/xtensor-stack/xsimd) - C++ wrappers for SIMD intrinsics and parallelized, optimized mathematical functions (SSE, AVX, AVX512, NEON, SVE, WebAssembly, VSX, RISC-V))
* [rurban/smhasher](https://github.com/rurban/smhasher) - Hash function quality and speed tests
* [mtrebi/memory-allocators](https://github.com/mtrebi/memory-allocators) - Custom memory allocators in C++ to improve the performance of dynamic memory allocation
* [plasma-umass/Mesh](https://github.com/plasma-umass/Mesh) - A memory allocator that automatically reduces the memory footprint of C/C++ applications.
* [martinus/nanobench](https://github.com/martinus/nanobench) - Simple, fast, accurate single-header microbenchmarking functionality for C++11/14/17/20
* [boostorg/compute](https://github.com/boostorg/compute) - A C++ GPU Computing Library for OpenCL
* [foonathan/memory](https://github.com/foonathan/memory) - STL compatible C++ memory allocator library using a new RawAllocator concept that is similar to an Allocator but easier to use and write.
* [VcDevel/Vc](https://github.com/VcDevel/Vc) - SIMD Vector Classes for C++
* [cacay/MemoryPool](https://github.com/cacay/MemoryPool) - An easy to use and efficient memory pool allocator written in C++.
* [intel/compute-runtime](https://github.com/intel/compute-runtime) - Intel® Graphics Compute Runtime for oneAPI Level Zero and OpenCL™ Driver
* [jfalcou/eve](https://github.com/jfalcou/eve) - Expressive Vector Engine - SIMD in C++ Goes Brrrr
* [p12tic/libsimdpp](https://github.com/p12tic/libsimdpp) - Portable header-only C++ low level SIMD library
* [NVIDIA/cccl](https://github.com/NVIDIA/cccl) - CUDA Core Compute Libraries
* [NVIDIA/libcudacxx](https://github.com/NVIDIA/libcudacxx) - [ARCHIVED] The C++ Standard Library for your entire system. See https://github.com/NVIDIA/cccl

## Testing and Quality

### Testing

* [catchorg/Catch2](https://github.com/catchorg/Catch2) - A modern, C++-native, test framework for unit-tests, TDD and BDD - using C++14, C++17 and later (C++11 support is in v2.x branch, and C++03 on the Catch1.x branch)
* [doctest/doctest](https://github.com/doctest/doctest) - The fastest feature-rich C++11/14/17/20/23 single-header testing framework
* [csmith-project/creduce](https://github.com/csmith-project/creduce) - C-Reduce, a C and C++ program reducer
* [cpputest/cpputest](https://github.com/cpputest/cpputest) - CppUTest unit testing and mocking framework for C/C++
* [boost-ext/ut](https://github.com/boost-ext/ut) - C++20 μ(micro)/Unit Testing framework
* [eranpeer/FakeIt](https://github.com/eranpeer/FakeIt) - C++ mocking made easy. A simple yet very expressive, headers only library for c++ mocking.
* [csmith-project/csmith](https://github.com/csmith-project/csmith) - Csmith, a random generator of C programs
* [emil-e/rapidcheck](https://github.com/emil-e/rapidcheck) - QuickCheck clone for C++ with the goal of being simple to use with as little boilerplate as possible.
* [OpenCppCoverage/OpenCppCoverage](https://github.com/OpenCppCoverage/OpenCppCoverage) - OpenCppCoverage is an open source code coverage tool for C++ under Windows. *(archived)*

## Utilities

### Command Line Tools

* [Slackadays/Clipboard](https://github.com/Slackadays/Clipboard) - 😎🏖️🐬 Your new, 𝙧𝙞𝙙𝙤𝙣𝙠𝙪𝙡𝙞𝙘𝙞𝙤𝙪𝙨𝙡𝙮 smart clipboard manager
* [chrisant996/clink](https://github.com/chrisant996/clink) - Bash's powerful command line editing in cmd.exe
* [jarro2783/cxxopts](https://github.com/jarro2783/cxxopts) - Lightweight C++ command line option parser
* [CLIUtils/CLI11](https://github.com/CLIUtils/CLI11) - CLI11 is a command line parser for C++11 and beyond that provides a rich feature set with a simple and intuitive interface.
* [p-ranav/argparse](https://github.com/p-ranav/argparse) - Argument Parser for Modern C++
* [gflags/gflags](https://github.com/gflags/gflags) - The gflags package contains a C++ library that implements commandline flags processing. It includes built-in support for standard types such as string and the ability to define flags in the source file in which they are used. Online documentation available at:
* [stefanhaustein/TerminalImageViewer](https://github.com/stefanhaustein/TerminalImageViewer) - Small C++ program to display images in a (modern) terminal using RGB ANSI codes and unicode block graphics characters
* [Taywee/args](https://github.com/Taywee/args) - A header-only C++ argument parser library. Supposed to be flexible and powerful, and attempts to be compatible with the functionality of the Python standard argparse library (though not necessarily the API).
* [daniele77/cli](https://github.com/daniele77/cli) - A library for interactive command line interfaces in modern C++
* [muellan/clipp](https://github.com/muellan/clipp) - easy to use, powerful & expressive command line argument parsing for modern C++ / single header / usage & doc generation
* [docopt/docopt.cpp](https://github.com/docopt/docopt.cpp) - C++11 port of docopt
* [naelstrof/slop](https://github.com/naelstrof/slop) - slop (Select Operation) is an application that queries for a selection from the user and prints the region to stdout.

### Logging and Configuration

* [gabime/spdlog](https://github.com/gabime/spdlog) - Fast C++ logging library.
* [google/glog](https://github.com/google/glog) - C++ implementation of the Google logging module *(archived)*
* [abumq/easyloggingpp](https://github.com/abumq/easyloggingpp) - C++ logging library. It is powerful, supports asynchronous low latency, extendable, light-weight, fast performing, thread and type safe and consists of many built-in features. It provides ability to write logs in your own customized format. It also provide support for logging your classes, third-party libraries, STL and third-party containers etc. *(archived)*
* [PlatformLab/NanoLog](https://github.com/PlatformLab/NanoLog) - Nanolog is an extremely performant nanosecond scale logging system for C++ that exposes a simple printf-like API.
* [benhoyt/inih](https://github.com/benhoyt/inih) - Simple .INI file parser in C, good for embedded systems
* [odygrd/quill](https://github.com/odygrd/quill) - Ultra-low-latency asynchronous C++17 logging and metrics library for performance-critical applications
* [SergiusTheBest/plog](https://github.com/SergiusTheBest/plog) - Portable, simple and extensible C++ logging library
* [emilk/loguru](https://github.com/emilk/loguru) - A lightweight C++ logging library
* [log4cplus/log4cplus](https://github.com/log4cplus/log4cplus) - log4cplus is a simple to use C++ logging API providing thread-safe, flexible, and arbitrarily granular control over log management and configuration. It is modelled after the Java log4j API.
* [brofield/simpleini](https://github.com/brofield/simpleini) - Cross-platform C++ library providing a simple API to read and write INI-style configuration files

### Text Processing

* [google/libphonenumber](https://github.com/google/libphonenumber) - Google's common Java, C++ and JavaScript library for parsing, formatting, and validating international phone numbers.
* [BYVoid/OpenCC](https://github.com/BYVoid/OpenCC) - Library for conversion between Traditional and Simplified Chinese
* [google/re2](https://github.com/google/re2) - RE2 is a fast, safe, thread-friendly alternative to backtracking regular expression engines like those used in PCRE, Perl, and Python. It is a C++ library.
* [harfbuzz/harfbuzz](https://github.com/harfbuzz/harfbuzz) - HarfBuzz text shaping engine
* [hanickadot/compile-time-regular-expressions](https://github.com/hanickadot/compile-time-regular-expressions) - Compile Time Regular Expression in C++
* [ashvardanian/StringZilla](https://github.com/ashvardanian/StringZilla) - Up to 100x faster strings for C, C++, CUDA, Python, Rust, Swift, JS, & Go, leveraging NEON, AVX2, AVX-512, SVE, GPGPU, & SWAR to accelerate search, hashing, sorting, edit distances, sketches, and memory ops 🦖
* [fastfloat/fast_float](https://github.com/fastfloat/fast_float) - Fast and exact implementation of the C++ from_chars functions for number types: 4x to 10x faster than strtod, part of GCC 12, MySQL, DuckDB, Chromium, Redis and WebKit/Safari
* [sisong/HDiffPatch](https://github.com/sisong/HDiffPatch) - a C\C++ library and command-line tools for Diff & Patch between binary files or directories(folder); cross-platform; runs fast; create small delta/differential; support large files and limit memory requires when diff & patch.
* [nemtrif/utfcpp](https://github.com/nemtrif/utfcpp) - UTF-8 with C++ in a Portable Way
* [sheredom/utf8.h](https://github.com/sheredom/utf8.h) - 📚 single header utf8 string functions for C and C++
* [pantor/inja](https://github.com/pantor/inja) - A Template Engine for Modern C++
* [ada-url/ada](https://github.com/ada-url/ada) - WHATWG-compliant and fast URL parser written in modern C++, part of Internet Archive, Node.js, Clickhouse, Redpanda, Kong, Telegram, Adguard, Datadog and Cloudflare Workers.
* [eliaskosunen/scnlib](https://github.com/eliaskosunen/scnlib) - scanf for modern C++
* [foonathan/lexy](https://github.com/foonathan/lexy) - C++ parsing DSL
* [google/double-conversion](https://github.com/google/double-conversion) - Efficient binary-decimal and decimal-binary conversion routines for IEEE doubles.
* [imageworks/pystring](https://github.com/imageworks/pystring) - C++ functions matching the interface and behavior of python string methods with std::string
* [yhirose/cpp-peglib](https://github.com/yhirose/cpp-peglib) - A single file C++ header-only PEG (Parsing Expression Grammars) library
* [ReneNyffenegger/cpp-base64](https://github.com/ReneNyffenegger/cpp-base64) - base64 encoding and decoding with c++

### Files and Operating System

* [emcrisostomo/fswatch](https://github.com/emcrisostomo/fswatch) - A cross-platform file change monitor with multiple backends: Apple macOS File System Events, *BSD kqueue, Solaris/Illumos File Events Notification, Linux inotify and fanotify, Microsoft Windows and a stat()-based backend.
* [inotify-tools/inotify-tools](https://github.com/inotify-tools/inotify-tools) - inotify-tools is a library and a set of command-line programs providing a simple interface to inotify.
* [google/cdc-file-transfer](https://github.com/google/cdc-file-transfer) - Tools for synching and streaming files from Windows to Linux *(archived)*
* [google/cpu_features](https://github.com/google/cpu_features) - A cross platform C99 library to get cpu features at runtime.
* [wjwwood/serial](https://github.com/wjwwood/serial) - Cross-platform, Serial Port library written in C++
* [vimpunk/mio](https://github.com/vimpunk/mio) - Cross-platform C++11 header-only library for memory mapped file IO
* [microsoft/cppwinrt](https://github.com/microsoft/cppwinrt) - C++/WinRT
* [gulrak/filesystem](https://github.com/gulrak/filesystem) - An implementation of C++17 std::filesystem for C++11 /C++14/C++17/C++20 on Windows, macOS, Linux and FreeBSD.

### Automation and Scripting

* [TonyChen56/WeChatRobot](https://github.com/TonyChen56/WeChatRobot) - 微信HOOK、微信机器人 wxhook，数据库解密 微信公众号采集 微信公众号爬虫，企业微信HOOK
* [lich0821/WeChatFerry](https://github.com/lich0821/WeChatFerry) - 微信机器人，可接入DeepSeek、Gemini、ChatGPT、ChatGLM、讯飞星火、Tigerbot等大模型。微信 hook WeChat Robot Hook. *(archived)*
* [aixed/WeChat-Hook](https://github.com/aixed/WeChat-Hook) - 微信 收发消息功能/ PC微信3.9.10.16 & 4.1.10.27接口 微信Hook 微信机器人 微信Hook源码 PC微信协议 PC微信协议算法
* [kyubotics/coolq-http-api](https://github.com/kyubotics/coolq-http-api) - 为 酷Q 提供通过 HTTP 或 WebSocket 接收事件和调用 API 的能力 *(archived)*
* [ljc545w/ComWeChatRobot](https://github.com/ljc545w/ComWeChatRobot) - PC微信机器人，实现获取通讯录，发送文本、图片、文件等消息，封装COM接口供Python、C#调用 *(archived)*
* [brainboxdotcc/DPP](https://github.com/brainboxdotcc/DPP) - C++ Discord API Bot Library - D++ is Lightweight and scalable for small and huge bots!
* [urob/zmk-config](https://github.com/urob/zmk-config) - Personal ZMK firmware configuration for various boards (34-keys, Glove80, Planck)
* [reo7sp/tgbot-cpp](https://github.com/reo7sp/tgbot-cpp) - C++ library for Telegram bot API

### General Purpose Libraries

* [facebook/folly](https://github.com/facebook/folly) - An open-source C++ library developed and used at Facebook.
* [abseil/abseil-cpp](https://github.com/abseil/abseil-cpp) - Abseil Common Libraries (C++)
* [microsoft/STL](https://github.com/microsoft/STL) - MSVC's implementation of the C++ Standard Library.
* [pocoproject/poco](https://github.com/pocoproject/poco) - The POCO C++ Libraries are powerful cross-platform C++ libraries for building network- and internet-based applications that run on desktop, server, mobile, IoT, and embedded systems.
* [Neargye/magic_enum](https://github.com/Neargye/magic_enum) - Static reflection for enums (to string, from string, iteration) for modern C++, work with any enum type without any macro or boilerplate code
* [ericniebler/range-v3](https://github.com/ericniebler/range-v3) - Range library for C++14/17/20, basis for C++20's std::ranges
* [idealvin/coost](https://github.com/idealvin/coost) - A tiny boost library in C++11.
* [rttrorg/rttr](https://github.com/rttrorg/rttr) - C++ Reflection Library
* [microsoft/proxy](https://github.com/microsoft/proxy) - Proxy: Next Generation Polymorphism in C++ *(archived)*
* [arximboldi/immer](https://github.com/arximboldi/immer) - Postmodern immutable and persistent data structures for C++ — value semantics at scale
* [Neargye/nameof](https://github.com/Neargye/nameof) - Nameof operator for modern C++, simply obtain the name of a variable, type, function, macro, and enum
* [Dobiasd/FunctionalPlus](https://github.com/Dobiasd/FunctionalPlus) - Functional Programming Library for C++. Write concise and readable C++ code.
* [alibaba/yalantinglibs](https://github.com/alibaba/yalantinglibs) - A collection of modern C++ libraries, include coro_http, coro_rpc, compile-time reflection, struct_pack, struct_json, struct_xml, struct_pb, easylog, async_simple etc.
* [google/fruit](https://github.com/google/fruit) - Fruit, a dependency injection framework for C++
* [TartanLlama/expected](https://github.com/TartanLlama/expected) - C++11/14/17 std::expected with functional-style extensions
* [bloomberg/bde](https://github.com/bloomberg/bde) - Basic Development Environment - a set of foundational C++ libraries used at Bloomberg.
* [aantron/better-enums](https://github.com/aantron/better-enums) - C++ compile-time enum to string, iteration, in a single header file
* [wqking/eventpp](https://github.com/wqking/eventpp) - Event Dispatcher and callback list for C++
* [martinus/robin-hood-hashing](https://github.com/martinus/robin-hood-hashing) - Fast & memory efficient hashtable based on robin hood hashing for C++11/14/17/20 *(archived)*
* [sparsehash/sparsehash](https://github.com/sparsehash/sparsehash) - C++ associative containers
* [serge-sans-paille/frozen](https://github.com/serge-sans-paille/frozen) - a header-only, constexpr alternative to gperf for C++14 users
* [Tessil/robin-map](https://github.com/Tessil/robin-map) - C++ implementation of a fast hash map and hash set using robin hood hashing
* [ryanhaining/cppitertools](https://github.com/ryanhaining/cppitertools) - Implementation of python itertools and builtin iteration functions for C++17
* [boost-ext/sml](https://github.com/boost-ext/sml) - C++14 State Machine library
* [solodon4/Mach7](https://github.com/solodon4/Mach7) - Functional programming style pattern-matching library for C++
* [greg7mdp/sparsepp](https://github.com/greg7mdp/sparsepp) - A fast, memory efficient hash map for C++
* [boost-ext/di](https://github.com/boost-ext/di) - C++14 Dependency Injection library
* [veselink1/refl-cpp](https://github.com/veselink1/refl-cpp) - Static reflection for C++17 (compile-time enumeration, attributes, proxies, overloads, template functions, metaprogramming).
* [digint/tinyfsm](https://github.com/digint/tinyfsm) - A simple C++ finite state machine library
* [qicosmos/cosmos](https://github.com/qicosmos/cosmos) - c++11基础库
* [facebook/fatal](https://github.com/facebook/fatal) - Fatal is a library for fast prototyping software in modern C++. It provides facilities to enhance the expressive power of C++. The library is heavily based on template meta-programming, while keeping the complexity under-the-hood.
* [beark/ftl](https://github.com/beark/ftl) - C++ template library for fans of functional programming
* [bolero-MURAKAMI/Sprout](https://github.com/bolero-MURAKAMI/Sprout) - C++11/14 constexpr based Containers, Algorithms, Random numbers, Parsing, Ray tracing, Synthesizer, and others.

## Systems and Hardware

### Embedded and Firmware

* [360Controller/360Controller](https://github.com/360Controller/360Controller) - TattieBogle Xbox 360 Driver (with improvements)
* [jrowberg/i2cdevlib](https://github.com/jrowberg/i2cdevlib) - I2C device library collection for AVR/Arduino or other C++-based MCUs
* [openhwgroup/cva6](https://github.com/openhwgroup/cva6) - The CORE-V CVA6 is a highly configurable, 6-stage RISC-V core for both application and embedded applications. Application class configurations are capable of booting Linux.
* [SmingHub/Sming](https://github.com/SmingHub/Sming) - Sming - powerful open source framework simplifying the creation of embedded C++ applications.
* [losehu/uv-k5-firmware-custom](https://github.com/losehu/uv-k5-firmware-custom) - 全功能泉盛UV-K5/K6固件 Quansheng UV-K5/K6 Firmware
* [itsharryle/LED_CUBE](https://github.com/itsharryle/LED_CUBE) - 8x8x8 LED cube powered by an arduino
* [particle-iot/device-os](https://github.com/particle-iot/device-os) - Device OS (Firmware) for Particle Devices

## Science and Math

### Mathematics

* [cvxpy/cvxpy](https://github.com/cvxpy/cvxpy) - A Python-embedded modeling language for convex optimization problems.
* [CGAL/cgal](https://github.com/CGAL/cgal) - The public CGAL repository, see the README below
* [libigl/libigl](https://github.com/libigl/libigl) - Simple MPL-2.0-licensed C++ geometry processing library.
* [ceres-solver/ceres-solver](https://github.com/ceres-solver/ceres-solver) - A large scale non-linear optimization library
* [dpilger26/NumCpp](https://github.com/dpilger26/NumCpp) - C++ implementation of the Python Numpy library
* [xtensor-stack/xtensor](https://github.com/xtensor-stack/xtensor) - C++ tensors with broadcasting and lazy computing
* [AngusJohnson/Clipper2](https://github.com/AngusJohnson/Clipper2) - Polygon Clipping, Offsetting & Triangulation in C++, C# and Delphi
* [strasdat/Sophus](https://github.com/strasdat/Sophus) - C++ implementation of Lie Groups using Eigen.
* [casadi/casadi](https://github.com/casadi/casadi) - CasADi is a symbolic framework for numeric optimization implementing automatic differentiation in forward and reverse modes on sparse matrix-valued computational graphs. It supports self-contained C-code generation and interfaces state-of-the-art codes such as SUNDIALS, IPOPT etc. It can be used from C++, Python, Matlab/Octave, Julia or Javascript
* [autodiff/autodiff](https://github.com/autodiff/autodiff) - automatic differentiation made easier for C++
* [artivis/manif](https://github.com/artivis/manif) - A small C++11 header-only library for Lie theory.
* [microsoft/DirectXMath](https://github.com/microsoft/DirectXMath) - DirectXMath is an all inline SIMD C++ linear algebra library for use in games and graphics apps
* [mapbox/polylabel](https://github.com/mapbox/polylabel) - A fast algorithm for finding the pole of inaccessibility of a polygon (in JavaScript and C++)
* [fwilliams/point-cloud-utils](https://github.com/fwilliams/point-cloud-utils) - An easy-to-use Python library for processing and manipulating 3D point clouds and meshes.
* [mherb/kalman](https://github.com/mherb/kalman) - Header-only C++11 Kalman Filtering Library (EKF, UKF) based on Eigen3
* [libgeos/geos](https://github.com/libgeos/geos) - Geometry Engine, Open Source
* [mpusz/mp-units](https://github.com/mpusz/mp-units) - The Domain-Correct Quantities and Units Library for C++ — full quantity kind safety, ISO 80000 compliant, C++29 standardization candidate.
* [artem-ogre/CDT](https://github.com/artem-ogre/CDT) - Constrained Delaunay Triangulation (C++)
* [symengine/symengine](https://github.com/symengine/symengine) - SymEngine is a fast symbolic manipulation library, written in C++
* [google/mathfu](https://github.com/google/mathfu) - C++ math library developed primarily for games focused on simplicity and efficiency. *(archived)*
* [nmwsharp/geometry-central](https://github.com/nmwsharp/geometry-central) - Applied 3D geometry in C++, with a focus on surface meshes.
* [cnr-isti-vclab/vcglib](https://github.com/cnr-isti-vclab/vcglib) - The VCGlib is a C++, templated, no dependency, library for manipulation, processing and cleaning of triangle meshes
* [CNugteren/CLBlast](https://github.com/CNugteren/CLBlast) - Tuned OpenCL BLAS
* [EricLengyel/Terathon-Math-Library](https://github.com/EricLengyel/Terathon-Math-Library) - C++ math library for 2D/3D/4D vector, matrix, quaternion, and geometric algebra.
* [NVIDIA/MatX](https://github.com/NVIDIA/MatX) - An efficient C++17 GPU numerical computing library with Python-like syntax

### Scientific Computing

* [carla-simulator/carla](https://github.com/carla-simulator/carla) - Open-source simulator for autonomous driving research.
* [cartographer-project/cartographer](https://github.com/cartographer-project/cartographer) - Cartographer is a system that provides real-time simultaneous localization and mapping (SLAM) in 2D and 3D across multiple platforms and sensor configurations.
* [lballabio/QuantLib](https://github.com/lballabio/QuantLib) - The QuantLib C++ library
* [PetoiCamp/OpenCat-Quadruped-Robot](https://github.com/PetoiCamp/OpenCat-Quadruped-Robot) - An open source quadruped robot pet framework for developing Boston Dynamics-style four-legged robots that are perfect for STEM, coding & robotics education, IoT robotics applications, AI-enhanced robotics application services, research, and DIY robotics kit development.
* [BehaviorTree/BehaviorTree.CPP](https://github.com/BehaviorTree/BehaviorTree.CPP) - Behavior Trees Library in C++. Batteries included.
* [borglab/gtsam](https://github.com/borglab/gtsam) - GTSAM is a library of C++ classes that implement smoothing and mapping (SAM) in robotics and vision, using factor graphs and Bayes networks as the underlying computing paradigm rather than sparse matrices.
* [fasiondog/hikyuu](https://github.com/fasiondog/hikyuu) - Hikyuu Quant Framework 基于C++/Python的超高速开源量化交易研究框架，同时可基于策略部件进行资产重用，快速累积策略资产。
* [PJLab-ADG/SensorsCalibration](https://github.com/PJLab-ADG/SensorsCalibration) - OpenCalib: A Multi-sensor Calibration Toolbox for Autonomous Driving
* [projectchrono/chrono](https://github.com/projectchrono/chrono) - High-performance C++ library for multiphysics and multibody dynamics simulations
* [simbody/simbody](https://github.com/simbody/simbody) - High-performance C++ multibody dynamics/physics library for simulating articulated biomechanical and mechanical systems like vehicles, robots, and the human skeleton.
* [chvmp/champ](https://github.com/chvmp/champ) - MIT Cheetah I Implementation
* [mfem/mfem](https://github.com/mfem/mfem) - Lightweight, general, scalable C++ library for finite element methods
* [onlytailei/CppRobotics](https://github.com/onlytailei/CppRobotics) - cpp implementation of robotics algorithms including localization, mapping, SLAM, path planning and control
* [deepmodeling/deepmd-kit](https://github.com/deepmodeling/deepmd-kit) - A deep learning package for many-body potential energy representation and molecular dynamics
* [cartographer-project/cartographer_ros](https://github.com/cartographer-project/cartographer_ros) - Provides ROS integration for Cartographer.
* [Ultimaker/CuraEngine](https://github.com/Ultimaker/CuraEngine) - Powerful, fast and robust engine for converting 3D models into g-code instructions for 3D printers. It is part of the larger open source project Cura.
* [qiayuanl/legged_control](https://github.com/qiayuanl/legged_control) - NMPC, WBC, state estimation, and sim2real framework for legged robots based on OCS2 and ros-controls
* [ankitdhall/lidar_camera_calibration](https://github.com/ankitdhall/lidar_camera_calibration) - ROS package to find a rigid-body transformation between a LiDAR and a camera for "LiDAR-Camera Calibration using 3D-3D Point correspondences"
* [ethz-adrl/control-toolbox](https://github.com/ethz-adrl/control-toolbox) - The Control Toolbox - An Open-Source C++ Library for Robotics, Optimal and Model Predictive Control
* [koide3/direct_visual_lidar_calibration](https://github.com/koide3/direct_visual_lidar_calibration) - A toolbox for target-less LiDAR-camera calibration [ROS1/ROS2]
* [ToanTech/Deng-s-foc-controller](https://github.com/ToanTech/Deng-s-foc-controller) - 灯哥开源 FOC 双路迷你无刷电机驱动
* [Smoothieware/Smoothieware](https://github.com/Smoothieware/Smoothieware) - Modular, opensource, high performance G-code interpreter and CNC controller written in Object-Oriented C++
* [johnBuffer/NoCol](https://github.com/johnBuffer/NoCol) - Trajectories finder
* [erwincoumans/tiny-differentiable-simulator](https://github.com/erwincoumans/tiny-differentiable-simulator) - Tiny Differentiable Simulator is a header-only C++ and CUDA physics library for reinforcement learning and robotics with zero dependencies.
* [PetoiCamp/OpenCat-Old](https://github.com/PetoiCamp/OpenCat-Old) - A programmable and highly maneuverable robotic cat for STEM education and AI-enhanced services.
* [KratosMultiphysics/Kratos](https://github.com/KratosMultiphysics/Kratos) - Kratos Multiphysics (A.K.A Kratos) is a framework for building parallel multi-disciplinary simulation software. Modularity, extensibility and HPC are the main objectives. Kratos has BSD license and is written in C++ with extensive Python interface.
* [gazebosim/gazebo-classic](https://github.com/gazebosim/gazebo-classic) - Gazebo classic. For the latest version, see https://github.com/gazebosim/gz-sim *(archived)*
* [cms-sw/cmssw](https://github.com/cms-sw/cmssw) - CMS Offline Software
* [PRBonn/depth_clustering](https://github.com/PRBonn/depth_clustering) - :taxi: Fast and robust clustering of point clouds generated with a Velodyne sensor.
* [hku-mars/livox_camera_calib](https://github.com/hku-mars/livox_camera_calib) - This repository is used for automatic calibration between high resolution LiDAR and camera in targetless scenes.
* [mrc-ide/covid-sim](https://github.com/mrc-ide/covid-sim) - This is the COVID-19 CovidSim microsimulation model developed by the MRC Centre for Global Infectious Disease Analysis hosted at Imperial College, London.
* [roboticslibrary/rl](https://github.com/roboticslibrary/rl) - The Robotics Library (RL) is a self-contained C++ library for rigid body kinematics and dynamics, motion planning, and control.
* [nvidia-isaac/cuVSLAM](https://github.com/nvidia-isaac/cuVSLAM) - cuVSLAM: CUDA-Accelerated Visual Odometry and Mapping

## Other

* [tensorflow/tensorflow](https://github.com/tensorflow/tensorflow) - An Open Source Machine Learning Framework for Everyone
* [react/react-native](https://github.com/react/react-native) - A framework for building native applications using React
* [electron/electron](https://github.com/electron/electron) - :electron: Build cross-platform desktop apps with JavaScript, HTML, and CSS
* [godotengine/godot](https://github.com/godotengine/godot) - Godot Engine – Multi-platform 2D and 3D game engine
* [microsoft/terminal](https://github.com/microsoft/terminal) - The new Windows Terminal and the original Windows console host, all in the same place!
* [opencv/opencv](https://github.com/opencv/opencv) - Open Source Computer Vision Library
* [bitcoin/bitcoin](https://github.com/bitcoin/bitcoin) - Bitcoin Core integration/staging tree
* [nomic-ai/gpt4all](https://github.com/nomic-ai/gpt4all) - GPT4All: Run Local LLMs on Any Device. Open-source and available for commercial use.
* [tesseract-ocr/tesseract](https://github.com/tesseract-ocr/tesseract) - Tesseract Open Source OCR Engine (main repository)
* [protocolbuffers/protobuf](https://github.com/protocolbuffers/protobuf) - Protocol Buffers - Google's data interchange format
* [LadybirdBrowser/ladybird](https://github.com/LadybirdBrowser/ladybird) - Truly independent web browser
* [WerWolv/ImHex](https://github.com/WerWolv/ImHex) - 🔍 A Hex Editor for Reverse Engineers, Programmers and people who value their retinas when working at 3 AM.
* [x64dbg/x64dbg](https://github.com/x64dbg/x64dbg) - An open-source user mode debugger for Windows. Optimized for reverse engineering and malware analysis.
* [zhongyang219/TrafficMonitor](https://github.com/zhongyang219/TrafficMonitor) - 这是一个用于显示当前网速、CPU及内存利用率的桌面悬浮窗软件，并支持任务栏显示，支持更换皮肤。
* [zen-browser/desktop](https://github.com/zen-browser/desktop) - Welcome to a calmer internet
* [aria2/aria2](https://github.com/aria2/aria2) - aria2 is a lightweight multi-protocol & multi-source, cross platform download utility operated in command-line. It supports HTTP/HTTPS, FTP, SFTP, BitTorrent and Metalink.
* [duckdb/duckdb](https://github.com/duckdb/duckdb) - DuckDB is an analytical in-process SQL database management system
* [facebookresearch/faiss](https://github.com/facebookresearch/faiss) - A library for efficient similarity search and clustering of dense vectors.
* [LizardByte/Sunshine](https://github.com/LizardByte/Sunshine) - Self-hosted game stream host for Moonlight.
* [microsoft/BitNet](https://github.com/microsoft/BitNet) - Official inference framework for 1-bit LLMs
* [qbittorrent/qBittorrent](https://github.com/qbittorrent/qBittorrent) - qBittorrent BitTorrent client
* [google/googletest](https://github.com/google/googletest) - GoogleTest - Google Testing and Mocking Framework
* [google/leveldb](https://github.com/google/leveldb) - LevelDB is a fast key-value storage library written at Google that provides an ordered mapping from string keys to string values.
* [aseprite/aseprite](https://github.com/aseprite/aseprite) - Animated sprite editor & pixel art tool (Windows, macOS, Linux)
* [hyprwm/Hyprland](https://github.com/hyprwm/Hyprland) - Hyprland is an independent, highly customizable, dynamic tiling Wayland compositor that doesn't sacrifice on its looks.
* [google-ai-edge/mediapipe](https://github.com/google-ai-edge/mediapipe) - Cross-platform, customizable ML solutions for live and streaming media.
* [CMU-Perceptual-Computing-Lab/openpose](https://github.com/CMU-Perceptual-Computing-Lab/openpose) - OpenPose: Real-time multi-person keypoint detection library for body, face, hands, and foot estimation
* [aristocratos/btop](https://github.com/aristocratos/btop) - A monitor of resources
* [SerenityOS/serenity](https://github.com/SerenityOS/serenity) - The Serenity Operating System 🐞
* [microsoft/WSL](https://github.com/microsoft/WSL) - Windows Subsystem for Linux
* [telegramdesktop/tdesktop](https://github.com/telegramdesktop/tdesktop) - Telegram Desktop messaging app
* [ValveSoftware/Proton](https://github.com/ValveSoftware/Proton) - Compatibility tool for Steam Play based on Wine and additional components
* [facebook/rocksdb](https://github.com/facebook/rocksdb) - A library that provides an embeddable, persistent key-value store for fast storage.
* [barry-ran/QtScrcpy](https://github.com/barry-ran/QtScrcpy) - Android real-time display control software
* [dragonflydb/dragonfly](https://github.com/dragonflydb/dragonfly) - A modern replacement for Redis and Memcached
* [Fincept-Corporation/FinceptTerminal](https://github.com/Fincept-Corporation/FinceptTerminal) - FinceptTerminal is a modern finance application offering advanced market analytics, investment research, and economic data tools, designed for interactive exploration and data-driven decision-making in a user-friendly environment.
* [flameshot-org/flameshot](https://github.com/flameshot-org/flameshot) - Powerful yet simple to use screenshot software :desktop_computer: :camera_flash:
* [78/xiaozhi-esp32](https://github.com/78/xiaozhi-esp32) - An MCP-based chatbot | 一个基于MCP的聊天机器人
* [ariya/phantomjs](https://github.com/ariya/phantomjs) - Scriptable Headless Browser *(archived)*
* [notepad-plus-plus/notepad-plus-plus](https://github.com/notepad-plus-plus/notepad-plus-plus) - Notepad++ official repository
* [envoyproxy/envoy](https://github.com/envoyproxy/envoy) - Cloud-native high-performance edge/middle/service proxy
* [keepassxreboot/keepassxc](https://github.com/keepassxreboot/keepassxc) - KeePassXC is a cross-platform community-driven port of the Windows application “KeePass Password Safe”.
* [mongodb/mongo](https://github.com/mongodb/mongo) - The MongoDB Database
* [deskflow/deskflow](https://github.com/deskflow/deskflow) - Share a single keyboard and mouse between multiple computers.
* [taichi-dev/taichi](https://github.com/taichi-dev/taichi) - Productive, portable, and performant GPU programming in Python.
* [ml-explore/mlx](https://github.com/ml-explore/mlx) - MLX: An array framework for Apple silicon
* [emscripten-core/emscripten](https://github.com/emscripten-core/emscripten) - Emscripten: An LLVM-to-WebAssembly Compiler
* [rethinkdb/rethinkdb](https://github.com/rethinkdb/rethinkdb) - The open-source database for the realtime web.
* [ApolloAuto/apollo](https://github.com/ApolloAuto/apollo) - An open autonomous driving platform
* [mozilla/DeepSpeech](https://github.com/mozilla/DeepSpeech) - DeepSpeech is an open source embedded (offline, on-device) speech-to-text engine which can run in real time on devices ranging from a Raspberry Pi 4 to high power GPU servers. *(archived)*
* [typesense/typesense](https://github.com/typesense/typesense) - Open Source alternative to Algolia + Pinecone and an Easier-to-Use alternative to ElasticSearch ⚡ 🔍 ✨ Fast, typo tolerant, in-memory fuzzy Search Engine for building delightful search experiences
* [microsoft/winget-cli](https://github.com/microsoft/winget-cli) - WinGet is the Windows Package Manager. This project includes a CLI (Command Line Interface), PowerShell modules, and a COM (Component Object Model) API (Application Programming Interface).
* [mozilla-ai/llamafile](https://github.com/mozilla-ai/llamafile) - Distribute and run LLMs with a single file.
* [argotorg/solidity](https://github.com/argotorg/solidity) - Solidity, the Smart Contract Programming Language
* [v8/v8](https://github.com/v8/v8) - The official mirror of the V8 Git repository
* [sqlitebrowser/sqlitebrowser](https://github.com/sqlitebrowser/sqlitebrowser) - Official home of the DB Browser for SQLite (DB4S) project. Previously known as "SQLite Database Browser" and "Database Browser for SQLite". Website at:
* [simdjson/simdjson](https://github.com/simdjson/simdjson) - Parsing gigabytes of JSON per second : used by Facebook/Meta Velox, the Node.js runtime, ClickHouse, WatermelonDB, Apache Doris, Milvus, StarRocks
* [ssloy/tinyrenderer](https://github.com/ssloy/tinyrenderer) - A brief computer graphics / rendering course
* [PaddlePaddle/Paddle](https://github.com/PaddlePaddle/Paddle) - PArallel Distributed Deep LEarning: Machine Learning Framework from Industrial Practice （『飞桨』核心框架，深度学习&机器学习高性能单机、分布式训练和跨平台部署）
* [fmtlib/fmt](https://github.com/fmtlib/fmt) - A modern formatting library
* [Tencent/ncnn](https://github.com/Tencent/ncnn) - ncnn is a high-performance neural network inference framework optimized for the mobile platform
* [osquery/osquery](https://github.com/osquery/osquery) - SQL powered operating system instrumentation, monitoring, and analytics.
* [redis/RedisDesktopManager](https://github.com/redis/RedisDesktopManager)
* [MaaAssistantArknights/MaaAssistantArknights](https://github.com/MaaAssistantArknights/MaaAssistantArknights) - 《明日方舟》小助手，全日常一键长草！| A one-click tool for the daily tasks of Arknights, supporting all clients.
* [pqrs-org/Karabiner-Elements](https://github.com/pqrs-org/Karabiner-Elements) - Karabiner-Elements is a powerful tool for customizing keyboards on macOS
* [scottbez1/smartknob](https://github.com/scottbez1/smartknob) - Haptic input knob with software-defined endstops and virtual detents
* [microsoft/onnxruntime](https://github.com/microsoft/onnxruntime) - ONNX Runtime: cross-platform, high performance ML inferencing and training accelerator
* [k4yt3x/video2x](https://github.com/k4yt3x/video2x) - A machine learning-based video super resolution and frame interpolation framework. Est. Hack the Valley II, 2018.
* [xbmc/xbmc](https://github.com/xbmc/xbmc) - Kodi is an award-winning free and open source home theater/media center software and entertainment hub for digital media. With its beautiful interface and powerful skinning engine, it's available for Android, BSD, Linux, macOS, iOS, tvOS and Windows.
* [apache/mxnet](https://github.com/apache/mxnet) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Scala, Go, Javascript and more *(archived)*
* [google/filament](https://github.com/google/filament) - Filament is a real-time physically based rendering engine for Android, iOS, Windows, Linux, macOS, and WebGL2
* [TranslucentTB/TranslucentTB](https://github.com/TranslucentTB/TranslucentTB) - A lightweight utility that makes the Windows taskbar translucent/transparent.
* [imputnet/helium](https://github.com/imputnet/helium) - Private, fast, and honest web browser
* [blender/blender](https://github.com/blender/blender) - Official mirror of Blender
* [lettier/3d-game-shaders-for-beginners](https://github.com/lettier/3d-game-shaders-for-beginners) - 🎮 A step-by-step guide to implementing SSAO, depth of field, lighting, normal mapping, and more for your 3D game.
* [trojan-gfw/trojan](https://github.com/trojan-gfw/trojan) - An unidentifiable mechanism that helps you bypass GFW.
* [id-Software/DOOM](https://github.com/id-Software/DOOM) - DOOM Open Source Release
* [Atmosphere-NX/Atmosphere](https://github.com/Atmosphere-NX/Atmosphere) - Atmosphère is a work-in-progress customized firmware for the Nintendo Switch.
* [kyleneideck/BackgroundMusic](https://github.com/kyleneideck/BackgroundMusic) - Background Music, a macOS audio utility: automatically pause your music, set individual apps' volumes and record system audio.
* [uNetworking/uWebSockets](https://github.com/uNetworking/uWebSockets) - Simple, secure & standards compliant web server for the most demanding of applications
* [swoole/swoole-src](https://github.com/swoole/swoole-src) - 🚀 Coroutine-based concurrency library for PHP
* [react/yoga](https://github.com/react/yoga) - Yoga is an embeddable layout engine targeting web standards.
* [lightgbm-org/LightGBM](https://github.com/lightgbm-org/LightGBM) - A fast, distributed, high performance gradient boosting (GBT, GBDT, GBRT, GBM or MART) framework based on decision tree algorithms, used for ranking, classification and many other machine learning tasks.
* [Tencent/MMKV](https://github.com/Tencent/MMKV) - An efficient, small mobile key-value storage framework developed by WeChat. Works on Android, iOS, macOS, Windows, POSIX, and OHOS.
* [facebook/hhvm](https://github.com/facebook/hhvm) - A virtual machine for executing programs written in Hack.
* [wled/WLED](https://github.com/wled/WLED) - Control WS2812B and many more types of digital RGB LEDs with an ESP32 over WiFi!
* [alibaba/weex](https://github.com/alibaba/weex) - A framework for building Mobile cross-platform UI
* [moonlight-stream/moonlight-qt](https://github.com/moonlight-stream/moonlight-qt) - GameStream client for PCs (Windows, Mac, Linux, and Steam Link)
* [microsoft/AirSim](https://github.com/microsoft/AirSim) - Open source simulator for autonomous vehicles built on Unreal Engine / Unity, from Microsoft AI & Research
* [haoel/leetcode](https://github.com/haoel/leetcode) - LeetCode Problems' Solutions
* [pybind/pybind11](https://github.com/pybind/pybind11) - Seamless operability between C++11 and Python
* [doitsujin/dxvk](https://github.com/doitsujin/dxvk) - Vulkan-based implementation of D3D8, 9, 10 and 11 for Linux / Wine
* [upx/upx](https://github.com/upx/upx) - UPX - the Ultimate Packer for eXecutables
* [audacity/audacity](https://github.com/audacity/audacity) - Audio Editor
* [Tencent/mars](https://github.com/Tencent/mars) - Mars is a cross-platform network component developed by WeChat.
* [NixOS/nix](https://github.com/NixOS/nix) - Nix, the purely functional package manager
* [MarlinFirmware/Marlin](https://github.com/MarlinFirmware/Marlin) - Marlin is a firmware for RepRap 3D printers optimized for both 8 and 32 bit microcontrollers. Marlin supports all common platforms. Many commercial 3D printers come with Marlin installed. Check with your vendor if you need source code for your specific machine.
* [bkaradzic/bgfx](https://github.com/bkaradzic/bgfx) - Cross-platform, graphics API agnostic, "Bring Your Own Engine/Framework" style rendering library.
* [microsoft/react-native-windows](https://github.com/microsoft/react-native-windows) - A framework for building native Windows apps with React.
* [espressif/arduino-esp32](https://github.com/espressif/arduino-esp32) - Arduino core for the ESP32 family of SoCs
* [apache/arrow](https://github.com/apache/arrow) - Apache Arrow is the universal columnar format and multi-language toolbox for fast data interchange and in-memory analytics
* [zerotier/ZeroTierOne](https://github.com/zerotier/ZeroTierOne) - A Smart Ethernet Switch for Earth
* [tindy2013/subconverter](https://github.com/tindy2013/subconverter) - Utility to convert between various subscription format
* [AaronFeng753/Waifu2x-Extension-GUI](https://github.com/AaronFeng753/Waifu2x-Extension-GUI) - Video, Image and GIF upscale/enlarge(Super-Resolution) and Video frame interpolation. Achieved with Waifu2x, Real-ESRGAN, Real-CUGAN, RTX Video Super Resolution VSR, SRMD, RealSR, Anime4K, RIFE, IFRNet, CAIN, DAIN, and ACNet.
* [rui314/mold](https://github.com/rui314/mold) - mold: A Modern Linker 🦠
* [wazuh/wazuh](https://github.com/wazuh/wazuh) - Wazuh - The Open Source Security Platform. Unified XDR and SIEM protection for endpoints and cloud workloads.
* [esp8266/Arduino](https://github.com/esp8266/Arduino) - ESP8266 core for Arduino
* [apple/foundationdb](https://github.com/apple/foundationdb) - FoundationDB - the open source, distributed, transactional key-value store
* [official-stockfish/Stockfish](https://github.com/official-stockfish/Stockfish) - A free and strong UCI chess engine
* [Snapchat/Valdi](https://github.com/Snapchat/Valdi) - Valdi is a cross-platform UI framework that delivers native performance without sacrificing developer velocity.
* [alibaba/MNN](https://github.com/alibaba/MNN) - MNN: A blazing-fast, lightweight inference engine battle-tested by Alibaba, powering high-performance on-device LLMs and Edge AI.
* [apache/doris](https://github.com/apache/doris) - Apache Doris is a real-time analytics and hybrid search database for AI agents.
* [ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot) - ArduPlane, ArduCopter, ArduRover, ArduSub source
* [scylladb/scylladb](https://github.com/scylladb/scylladb) - NoSQL data store using the Seastar framework, compatible with Apache Cassandra and Amazon DynamoDB
* [alibaba/zvec](https://github.com/alibaba/zvec) - A lightweight, lightning-fast, in-process vector database
* [hoffstadt/DearPyGui](https://github.com/hoffstadt/DearPyGui) - Dear PyGui: A fast and powerful Graphical User Interface Toolkit for Python with minimal dependencies
* [OrcaSlicer/OrcaSlicer](https://github.com/OrcaSlicer/OrcaSlicer) - G-code generator for 3D printers (Bambu, Prusa, Voron, VzBot, RatRig, Creality, etc.)
* [dolphin-emu/dolphin](https://github.com/dolphin-emu/dolphin) - Dolphin is a GameCube / Wii emulator, allowing you to play games for these two platforms on PC with improvements.
* [PCSX2/pcsx2](https://github.com/PCSX2/pcsx2) - PCSX2 - The Playstation 2 Emulator
* [M2Team/NanaZip](https://github.com/M2Team/NanaZip) - The 7-Zip derivative intended for the modern Windows experience
* [MatsuriDayo/nekoray](https://github.com/MatsuriDayo/nekoray) - 不再维护，自寻替代品。 Qt based cross-platform GUI proxy configuration manager (backend: sing-box) *(archived)*
* [polybar/polybar](https://github.com/polybar/polybar) - A fast and easy-to-use status bar
* [organicmaps/organicmaps](https://github.com/organicmaps/organicmaps) - 🍃 Organic Maps is a free Android & iOS offline maps app for more than 6M travelers, tourists, hikers, and cyclists. It uses crowd-sourced OpenStreetMap data and is developed with love by the community. No ads, no tracking, no data collection, no crapware. Please donate to support the development!
* [ggml-org/ggml](https://github.com/ggml-org/ggml) - Tensor library for machine learning
* [dogecoin/dogecoin](https://github.com/dogecoin/dogecoin) - very currency
* [transmission/transmission](https://github.com/transmission/transmission) - Official Transmission BitTorrent client repository
* [lynx-family/lynx](https://github.com/lynx-family/lynx) - Empower the Web community and invite more to build across platforms.
* [mltframework/shotcut](https://github.com/mltframework/shotcut) - cross-platform (Qt), open-source (GPLv3) video editor
* [musescore/MuseScore](https://github.com/musescore/MuseScore) - MuseScore is an open source and free music notation software. For support, contribution, bug reports, visit MuseScore.org. Fork and make pull requests!
* [google-deepmind/mujoco](https://github.com/google-deepmind/mujoco) - Multi-Joint dynamics with Contact. A general purpose physics simulator.
* [bulletphysics/bullet3](https://github.com/bulletphysics/bullet3) - Bullet Physics SDK: real-time collision detection and multi-physics simulation for VR, games, visual effects, robotics, machine learning etc.
* [wkhtmltopdf/wkhtmltopdf](https://github.com/wkhtmltopdf/wkhtmltopdf) - Convert HTML to PDF using Webkit (QtWebKit) *(archived)*
* [dail8859/NotepadNext](https://github.com/dail8859/NotepadNext) - A cross-platform, reimplementation of Notepad++
* [mobile-shell/mosh](https://github.com/mobile-shell/mosh) - Mobile Shell
* [qgis/QGIS](https://github.com/qgis/QGIS) - QGIS is a free, open source, cross platform (lin/win/mac) geographical information system (GIS)
* [spotify/annoy](https://github.com/spotify/annoy) - Approximate Nearest Neighbors in C++/Python optimized for memory usage and loading/saving to disk
* [arangodb/arangodb](https://github.com/arangodb/arangodb) - 🥑 ArangoDB is a native multi-model database with flexible data models for documents, graphs, and key-values. Build high performance applications using a convenient SQL-like query language or JavaScript extensions.
* [google/or-tools](https://github.com/google/or-tools) - Google's Operations Research tools:
* [isl-org/Open3D](https://github.com/isl-org/Open3D) - Open3D: A Modern Library for 3D Data Processing
* [facebook/watchman](https://github.com/facebook/watchman) - Watches files and records, or triggers actions, when they change.
* [apache/incubator-weex](https://github.com/apache/incubator-weex) - Apache Weex (Incubating) *(archived)*
* [luanti-org/luanti](https://github.com/luanti-org/luanti) - Luanti (formerly Minetest) is an open source voxel game-creation platform with easy modding and game creation
* [ninja-build/ninja](https://github.com/ninja-build/ninja) - a small build system with a focus on speed
* [assimp/assimp](https://github.com/assimp/assimp) - The official Open-Asset-Importer-Library Repository. Loads 40+ 3D-file-formats into one unified and clean data structure.
* [acaudwell/Gource](https://github.com/acaudwell/Gource) - software version control visualization
* [TheCherno/Hazel](https://github.com/TheCherno/Hazel) - Hazel Engine
* [AutoHotkey/AutoHotkey](https://github.com/AutoHotkey/AutoHotkey) - AutoHotkey - macro-creation and automation-oriented scripting utility for Windows.
* [HIllya51/LunaTranslator](https://github.com/HIllya51/LunaTranslator) - 视觉小说翻译器 / Visual Novel Translator
* [google/guetzli](https://github.com/google/guetzli) - Perceptual JPEG encoder *(archived)*
* [deepseek-ai/FlashMLA](https://github.com/deepseek-ai/FlashMLA) - FlashMLA: Efficient Multi-head Latent Attention Kernels
* [mapeditor/tiled](https://github.com/mapeditor/tiled) - Flexible level editor
* [ShiqiYu/libfacedetection](https://github.com/ShiqiYu/libfacedetection) - An open source library for face detection in images. The face detection speed can reach 1000FPS.
* [zealdocs/zeal](https://github.com/zealdocs/zeal) - Offline documentation browser. Your personal reference library, searchable in an instant.
* [Z3Prover/z3](https://github.com/Z3Prover/z3) - The Z3 Theorem Prover
* [JoeyDeVries/LearnOpenGL](https://github.com/JoeyDeVries/LearnOpenGL) - Code repository of all OpenGL chapters from the book and its accompanying website https://learnopengl.com
* [PX4/PX4-Autopilot](https://github.com/PX4/PX4-Autopilot) - PX4 Autopilot Software
* [Snapchat/KeyDB](https://github.com/Snapchat/KeyDB) - A Multithreaded Fork of Redis
* [redpanda-data/redpanda](https://github.com/redpanda-data/redpanda) - Redpanda is a streaming data platform for developers. Kafka API compatible. 10x faster. No ZooKeeper. No JVM!
* [mysql/mysql-server](https://github.com/mysql/mysql-server) - MySQL Server, the world's most popular open source database, and MySQL Cluster, a real-time, open source transactional database.
* [vesoft-inc/nebula](https://github.com/vesoft-inc/nebula) - A distributed, fast open-source graph database featuring horizontal scalability and high availability
* [justcallmekoko/ESP32Marauder](https://github.com/justcallmekoko/ESP32Marauder) - A suite of WiFi/Bluetooth offensive and defensive tools for the ESP32
* [sonic-pi-net/sonic-pi](https://github.com/sonic-pi-net/sonic-pi) - Code. Music. Live.
* [google/sentencepiece](https://github.com/google/sentencepiece) - Unsupervised text tokenizer for Neural Network-based text generation.
* [SFML/SFML](https://github.com/SFML/SFML) - Simple and Fast Multimedia Library
* [manticoresoftware/manticoresearch](https://github.com/manticoresoftware/manticoresearch) - Open-source search database for full-text, vector, and hybrid search with real-time indexing and SQL.
* [snowie2000/mactype](https://github.com/snowie2000/mactype) - Better font rendering for Windows.
* [microsoft/wslg](https://github.com/microsoft/wslg) - Enabling the Windows Subsystem for Linux to include support for Wayland and X server related scenarios
* [Alexays/Waybar](https://github.com/Alexays/Waybar) - Highly customizable Wayland bar for Sway and Wlroots based compositors. :v: :tada:
* [nasa/fprime](https://github.com/nasa/fprime) - F´ - A flight software and embedded systems framework
* [esphome/esphome](https://github.com/esphome/esphome) - ESPHome is a system to control your ESP32, ESP8266, BK72xx, RP2040 by simple yet powerful configuration files and control them remotely through Home Automation systems.
* [daijro/camoufox](https://github.com/daijro/camoufox) - 🦊 Anti-detect browser
* [openalpr/openalpr](https://github.com/openalpr/openalpr) - Automatic License Plate Recognition library
* [rhasspy/piper](https://github.com/rhasspy/piper) - A fast, local neural text to speech system *(archived)*
* [QuipNetwork/cpp-sdk](https://github.com/QuipNetwork/cpp-sdk)
* [gcc-mirror/gcc](https://github.com/gcc-mirror/gcc)
* [EOSIO/eos](https://github.com/EOSIO/eos) - An open source smart contract platform *(archived)*
* [apple/turicreate](https://github.com/apple/turicreate) - Turi Create simplifies the development of custom machine learning models. *(archived)*
* [PointCloudLibrary/pcl](https://github.com/PointCloudLibrary/pcl) - Point Cloud Library (PCL)
* [baldurk/renderdoc](https://github.com/baldurk/renderdoc) - RenderDoc is a stand-alone graphics debugging tool.
* [mawww/kakoune](https://github.com/mawww/kakoune) - mawww's experiment for a better code editor
* [moonshine-ai/moonshine](https://github.com/moonshine-ai/moonshine) - Very low latency speech to text, intent recognition, and text to speech, for building voice agents and interfaces
* [google/skia](https://github.com/google/skia) - Skia is a complete 2D graphic library for drawing Text, Geometries, and Images. See documentation for contribution instructions.
* [monero-project/monero](https://github.com/monero-project/monero) - Monero: the secure, private, untraceable cryptocurrency
* [WasmEdge/WasmEdge](https://github.com/WasmEdge/WasmEdge) - WasmEdge is a lightweight, high-performance, and extensible WebAssembly runtime for cloud native, edge, and decentralized applications. It powers serverless apps, embedded functions, microservices, smart contracts, and IoT devices.
* [openvinotoolkit/openvino](https://github.com/openvinotoolkit/openvino) - OpenVINO™ is an open source toolkit for optimizing and deploying AI inference
* [ClassicOldSong/Apollo](https://github.com/ClassicOldSong/Apollo) - Sunshine fork - The easiest way to stream with the native resolution of your client device
* [Const-me/Whisper](https://github.com/Const-me/Whisper) - High-performance GPGPU inference of OpenAI's Whisper automatic speech recognition (ASR) model
* [rr-debugger/rr](https://github.com/rr-debugger/rr) - Record and Replay Framework
* [tstack/lnav](https://github.com/tstack/lnav) - Log file navigator
* [stenzek/duckstation](https://github.com/stenzek/duckstation) - Fast PlayStation 1 emulator for x86-64/AArch32/AArch64/RV64
* [android/ndk-samples](https://github.com/android/ndk-samples) - Android NDK samples with Android Studio
* [mamedev/mame](https://github.com/mamedev/mame) - MAME
* [google/benchmark](https://github.com/google/benchmark) - A microbenchmark support library
* [LMMS/lmms](https://github.com/LMMS/lmms) - Cross-platform music production software
* [bpftrace/bpftrace](https://github.com/bpftrace/bpftrace) - High-level tracing language for Linux
* [KDE/krita](https://github.com/KDE/krita) - Krita is a free and open source cross-platform application that offers an end-to-end solution for creating digital art files from scratch built on the KDE and Qt frameworks.
* [PrismLauncher/PrismLauncher](https://github.com/PrismLauncher/PrismLauncher) - A custom launcher for Minecraft that allows you to easily manage multiple installations of Minecraft at once (Fork of MultiMC)
* [RunanywhereAI/runanywhere-sdks](https://github.com/RunanywhereAI/runanywhere-sdks) - Production ready toolkit to run AI locally
* [oceanbase/oceanbase](https://github.com/oceanbase/oceanbase) - OceanBase is the unified distributed database for the AI era — open-source, multi-model, one engine for your most demanding workloads.
* [raulmur/ORB_SLAM2](https://github.com/raulmur/ORB_SLAM2) - Real-Time SLAM for Monocular, Stereo and RGB-D Cameras, with Loop Detection and Relocalization Capabilities
* [optiscaler/OptiScaler](https://github.com/optiscaler/OptiScaler) - OptiScaler bridges upscaling/frame gen across GPUs. Supports DLSS2+/XeSS/FSR2+ inputs, replaces native upscalers, enables FSR-FG/XeFG on non-FG titles. Supports Nukem mod for DLSSG-to-FSR3 FG.
* [cxasm/notepad--](https://github.com/cxasm/notepad--) - 一个支持windows/linux/mac的文本编辑器，目标是做中国人自己的编辑器，来自中国。
* [deepseek-ai/3FS](https://github.com/deepseek-ai/3FS) - A high-performance distributed file system designed to address the challenges of AI training and inference workloads.
* [noctalia-dev/noctalia](https://github.com/noctalia-dev/noctalia) - A sleek, customizable desktop shell crafted for Wayland.
* [openscad/openscad](https://github.com/openscad/openscad) - OpenSCAD - The Programmers Solid 3D CAD Modeller
* [TarsCloud/Tars](https://github.com/TarsCloud/Tars) - Tars is a high-performance RPC framework based on name service and Tars protocol, also integrated administration platform, and implemented hosting-service via flexible schedule.
* [s3fs-fuse/s3fs-fuse](https://github.com/s3fs-fuse/s3fs-fuse) - FUSE-based file system backed by Amazon S3
* [ValveSoftware/source-sdk-2013](https://github.com/ValveSoftware/source-sdk-2013) - The 2013 edition of the Source SDK
* [ValveSoftware/GameNetworkingSockets](https://github.com/ValveSoftware/GameNetworkingSockets) - Reliable & unreliable messages over UDP. Robust message fragmentation & reassembly. P2P networking / NAT traversal. Encryption.
* [Tiiny-AI/PowerInfer](https://github.com/Tiiny-AI/PowerInfer) - High-speed Large Language Model Serving for Local Deployment
* [owasp-modsecurity/ModSecurity](https://github.com/owasp-modsecurity/ModSecurity) - ModSecurity is an open source, cross platform web application firewall (WAF) engine for Apache, IIS and Nginx. It has a robust event-based programming language which provides protection from a range of attacks against web applications and allows for HTTP traffic monitoring, logging and real-time analysis.
* [diasurgical/DevilutionX](https://github.com/diasurgical/DevilutionX) - Diablo build for modern operating systems
* [xenia-project/xenia](https://github.com/xenia-project/xenia) - Xbox 360 Emulator Research Project
* [o3de/o3de](https://github.com/o3de/o3de) - Open 3D Engine (O3DE) is an Apache 2.0-licensed multi-platform 3D engine that enables developers and content creators to build AAA games, cinema-quality 3D worlds, and high-fidelity simulations without any fees or commercial obligations.
* [ange-yaghi/engine-sim](https://github.com/ange-yaghi/engine-sim) - Combustion engine simulator that generates realistic audio.
* [Oneflow-Inc/oneflow](https://github.com/Oneflow-Inc/oneflow) - OneFlow is a deep learning framework designed to be user-friendly, scalable and efficient.
* [klzgrad/naiveproxy](https://github.com/klzgrad/naiveproxy) - Make a fortune quietly
* [Studio3T/robomongo](https://github.com/Studio3T/robomongo) - Native cross-platform MongoDB management tool
* [electronicarts/EASTL](https://github.com/electronicarts/EASTL) - EASTL stands for Electronic Arts Standard Template Library. It is an extensive and robust implementation that has an emphasis on high performance.
* [scylladb/seastar](https://github.com/scylladb/seastar) - High performance server-side application framework
* [falcosecurity/falco](https://github.com/falcosecurity/falco) - Cloud Native Runtime Security
* [oguzhaninan/Stacer](https://github.com/oguzhaninan/Stacer) - Linux System Optimizer and Monitoring - https://oguzhaninan.github.io/Stacer-Web
* [vicinaehq/vicinae](https://github.com/vicinaehq/vicinae) - A focused launcher for your desktop - native, fast, extensible
* [prusa3d/PrusaSlicer](https://github.com/prusa3d/PrusaSlicer) - G-code generator for 3D printers (RepRap, Makerbot, Ultimaker etc.)
* [activeloopai/deeplake](https://github.com/activeloopai/deeplake) - Deeplake is AI Data Runtime for Agents. It provides serverless postgres with a multimodal datalake, enabling scalable retrieval and training.
* [canonical/multipass](https://github.com/canonical/multipass) - Multipass orchestrates virtual Ubuntu instances
* [nodegui/nodegui](https://github.com/nodegui/nodegui) - A library for building cross-platform native desktop applications with Node.js and CSS 🚀. React NodeGui : https://react.nodegui.org and Vue NodeGui: https://vue.nodegui.org
* [yangyangwithgnu/hardseed](https://github.com/yangyangwithgnu/hardseed) - SEX IS ZERO (0), so, who wanna be the ONE (1), aha?
* [WinMerge/winmerge](https://github.com/WinMerge/winmerge) - WinMerge is an Open Source differencing and merging tool for Windows. WinMerge can compare both folders and files, presenting differences in a visual text format that is easy to understand and handle.
* [microsoft/napajs](https://github.com/microsoft/napajs) - Napa.js: a multi-threaded JavaScript runtime *(archived)*
* [uNetworking/uWebSockets.js](https://github.com/uNetworking/uWebSockets.js) - μWebSockets for Node.js back-ends :metal:
* [async-profiler/async-profiler](https://github.com/async-profiler/async-profiler) - Sampling CPU and HEAP profiler for Java featuring AsyncGetCallTrace + perf_events
* [olive-editor/olive](https://github.com/olive-editor/olive) - Free open-source non-linear video editor
* [Nevcairiel/LAVFilters](https://github.com/Nevcairiel/LAVFilters) - LAV Filters - Open-Source DirectShow Media Splitter and Decoders
* [tdlib/td](https://github.com/tdlib/td) - Cross-platform library for building Telegram clients
* [anbox/anbox](https://github.com/anbox/anbox) - Anbox is a container-based approach to boot a full Android system on a regular GNU/Linux system *(archived)*
* [ggerganov/kbd-audio](https://github.com/ggerganov/kbd-audio) - 🎤⌨️ Acoustic keyboard eavesdropping
* [UZ-SLAMLab/ORB_SLAM3](https://github.com/UZ-SLAMLab/ORB_SLAM3) - ORB-SLAM3: An Accurate Open-Source Library for Visual, Visual-Inertial and Multi-Map SLAM
* [diasurgical/devilution](https://github.com/diasurgical/devilution) - Diablo devolved - magic behind the 1996 computer game
* [realsenseai/librealsense](https://github.com/realsenseai/librealsense) - RealSense SDK
* [dusty-nv/jetson-inference](https://github.com/dusty-nv/jetson-inference) - Hello AI World guide to deploying deep-learning inference networks and deep vision primitives with TensorRT and NVIDIA Jetson.
* [gperftools/gperftools](https://github.com/gperftools/gperftools) - Main gperftools repository
* [azerothcore/azerothcore-wotlk](https://github.com/azerothcore/azerothcore-wotlk) - Complete Open Source and Modular solution for MMO
* [sebastianstarke/AI4Animation](https://github.com/sebastianstarke/AI4Animation) - Bringing Characters to Life with Computer Brains in Unity
* [VowpalWabbit/vowpal_wabbit](https://github.com/VowpalWabbit/vowpal_wabbit) - Vowpal Wabbit is a machine learning system which pushes the frontier of machine learning with techniques such as online, hashing, allreduce, reductions, learning2search, active, and interactive learning.
* [Ewenwan/MVision](https://github.com/Ewenwan/MVision) - 机器人视觉 移动机器人 VS-SLAM ORB-SLAM2 深度学习目标检测 yolov3 行为检测 opencv PCL 机器学习 无人驾驶
* [Tencent/libco](https://github.com/Tencent/libco) - libco is a coroutine library which is widely used in wechat back-end service. It has been running on tens of thousands of machines since 2013.
* [cloudflare/workerd](https://github.com/cloudflare/workerd) - The JavaScript / Wasm runtime that powers Cloudflare Workers
* [love2d/love](https://github.com/love2d/love) - LÖVE is an awesome 2D game framework for Lua.
* [jomjol/AI-on-the-edge-device](https://github.com/jomjol/AI-on-the-edge-device) - Easy to use device for connecting "old" measuring units (water, power, gas, ...) to the digital world
* [avast/retdec](https://github.com/avast/retdec) - RetDec is a retargetable machine-code decompiler based on LLVM.
* [Tencent/Hippy](https://github.com/Tencent/Hippy) - Hippy is designed to easily build cross-platform dynamic apps. 👏
* [wangyu-/udp2raw](https://github.com/wangyu-/udp2raw) - A Tunnel which Turns UDP Traffic into Encrypted UDP/FakeTCP/ICMP Traffic by using Raw Socket,helps you Bypass UDP FireWalls(or Unstable UDP Environment)
* [sass/node-sass](https://github.com/sass/node-sass) - :rainbow: Node.js bindings to libsass *(archived)*
* [BlueMatthew/WechatExporter](https://github.com/BlueMatthew/WechatExporter) - Wechat Chat History Exporter 微信聊天记录导出备份程序
* [input-leap/input-leap](https://github.com/input-leap/input-leap) - Open-source KVM software *(archived)*
* [LibreSprite/LibreSprite](https://github.com/LibreSprite/LibreSprite) - Animated sprite editor & pixel art tool -- Fork of the last GPLv2 commit of Aseprite
* [ideawu/ssdb](https://github.com/ideawu/ssdb) - SSDB - A fast NoSQL database, an alternative to Redis
* [zeux/meshoptimizer](https://github.com/zeux/meshoptimizer) - Mesh optimization library that makes meshes smaller and faster to render
* [microsoft/microsoft-ui-xaml](https://github.com/microsoft/microsoft-ui-xaml) - WinUI: a modern UI framework with a rich set of controls and styles to build dynamic and high-performing Windows applications.
* [draios/sysdig](https://github.com/draios/sysdig) - Linux system exploration and troubleshooting tool with first class support for containers
* [TheAssassin/AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher) - Helper application for Linux distributions serving as a kind of "entry point" for running and integrating AppImages
* [meshtastic/firmware](https://github.com/meshtastic/firmware) - The official firmware for Meshtastic, an open-source, off-grid mesh communication system.
* [0voice/introduce_c-cpp_manual](https://github.com/0voice/introduce_c-cpp_manual) - 一个收集C/C++新手学习的入门项目，整理收纳开发者开源的小项目、工具、框架、游戏等，视频，书籍，面试题/算法题，技术文章。
* [mumble-voip/mumble](https://github.com/mumble-voip/mumble) - Mumble is an open-source, low-latency, high quality voice chat software.
* [OpenTTD/OpenTTD](https://github.com/OpenTTD/OpenTTD) - OpenTTD is an open source simulation game based upon Transport Tycoon Deluxe
* [duixcom/Duix-Mobile](https://github.com/duixcom/Duix-Mobile) - 🚀 The best real-time interactive AI avatar(digital human) with on-premise deployment and <1.5 s latency.
* [MariaDB/server](https://github.com/MariaDB/server) - MariaDB server is a community developed fork of MySQL server. Started by core members of the original MySQL team, MariaDB actively works with outside developers to deliver the most featureful, stable, and sanely licensed open SQL server in the industry.
* [WebAssembly/wabt](https://github.com/WebAssembly/wabt) - The WebAssembly Binary Toolkit
* [N64Recomp/N64Recomp](https://github.com/N64Recomp/N64Recomp) - Tool to statically recompile N64 games into native executables
* [TechEmpower/FrameworkBenchmarks](https://github.com/TechEmpower/FrameworkBenchmarks) - Source for the TechEmpower Framework Benchmarks project *(archived)*
* [mamba-org/mamba](https://github.com/mamba-org/mamba) - The Fast Cross-Platform Package Manager
* [Project-OSRM/osrm-backend](https://github.com/Project-OSRM/osrm-backend) - Open Source Routing Machine - C++ backend
* [azahar-emu/azahar](https://github.com/azahar-emu/azahar) - An open-source 3DS emulator project based on Citra.
* [albertlauncher/albert](https://github.com/albertlauncher/albert) - A fast and flexible keyboard launcher
* [Squirrel/Squirrel.Windows](https://github.com/Squirrel/Squirrel.Windows) - An installation and update framework for Windows desktop apps
* [zeek/zeek](https://github.com/zeek/zeek) - Zeek is a powerful network analysis framework that is much different from the typical IDS you may know.
* [shadowsocks/shadowsocks-qt5](https://github.com/shadowsocks/shadowsocks-qt5) - A cross-platform shadowsocks GUI client *(archived)*
* [rime/weasel](https://github.com/rime/weasel) - 【小狼毫】Rime for Windows
* [FEX-Emu/FEX](https://github.com/FEX-Emu/FEX) - A fast usermode x86 and x86-64 emulator for Arm64 Linux
* [recastnavigation/recastnavigation](https://github.com/recastnavigation/recastnavigation) - Industry-standard navigation-mesh toolset for games
* [snapcast/snapcast](https://github.com/snapcast/snapcast) - Synchronous multiroom audio player
* [ggerganov/ggwave](https://github.com/ggerganov/ggwave) - Tiny data-over-sound library
* [wang-xinyu/tensorrtx](https://github.com/wang-xinyu/tensorrtx) - Implementation of popular deep learning networks with TensorRT network definition API
* [weolar/miniblink49](https://github.com/weolar/miniblink49) - a lighter, faster browser kernel of blink to integrate HTML UI in your app. 一个小巧、轻量的浏览器内核，用来取代wke和libcef
* [kelektiv/node.bcrypt.js](https://github.com/kelektiv/node.bcrypt.js) - bcrypt for NodeJs
* [visualfc/liteide](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.
* [rovo89/Xposed](https://github.com/rovo89/Xposed) - The native part of the Xposed framework (mainly the modified app_process binary). *(archived)*
* [opentoonz/opentoonz](https://github.com/opentoonz/opentoonz) - OpenToonz - An open-source full-featured 2D animation creation software
* [kroma-network/tachyon](https://github.com/kroma-network/tachyon) - Modular ZK(Zero Knowledge) backend accelerated by GPU
* [flutter-team-archive/engine](https://github.com/flutter-team-archive/engine) - The Flutter engine *(archived)*
* [endless-sky/endless-sky](https://github.com/endless-sky/endless-sky) - Space exploration, trading, and combat game.
* [Alex313031/thorium](https://github.com/Alex313031/thorium) - Chromium fork named after radioactive element No. 90. Source code and Linux releases. Windows/MacOS/ARM builds served in different repos, links are towards the top of the README.md.
* [FastLED/FastLED](https://github.com/FastLED/FastLED) - The FastLED library for colored LED animation on Arduino. Please direct questions/requests for help to the FastLED Reddit community: http://fastled.io/r We'd like to use github "issues" just for tracking library bugs / enhancements.
* [gaoxiang12/slambook](https://github.com/gaoxiang12/slambook)
* [google/draco](https://github.com/google/draco) - Draco is a library for compressing and decompressing 3D geometric meshes and point clouds. It is intended to improve the storage and transmission of 3D graphics.
* [PixarAnimationStudios/OpenUSD](https://github.com/PixarAnimationStudios/OpenUSD) - Universal Scene Description
* [TigerVNC/tigervnc](https://github.com/TigerVNC/tigervnc) - High performance, multi-platform VNC client and server
* [versatica/mediasoup](https://github.com/versatica/mediasoup) - Cutting Edge WebRTC Video Conferencing
* [PaddlePaddle/Paddle-Lite](https://github.com/PaddlePaddle/Paddle-Lite) - PaddlePaddle High Performance Deep Learning Inference Engine for Mobile and Edge (飞桨高性能深度学习端侧推理引擎）
* [tzapu/WiFiManager](https://github.com/tzapu/WiFiManager) - ESP8266 WiFi Connection manager with web captive portal
* [relativty/Relativty](https://github.com/relativty/Relativty) - An open source VR headset with SteamVR supports for $200
* [turanszkij/WickedEngine](https://github.com/turanszkij/WickedEngine) - 3D engine with modern graphics
* [FULU-Foundation/OrcaSlicer-bambulab](https://github.com/FULU-Foundation/OrcaSlicer-bambulab)
* [me115/design_patterns](https://github.com/me115/design_patterns) - 图说设计模式
* [mixxxdj/mixxx](https://github.com/mixxxdj/mixxx) - Mixxx is Free DJ software that gives you everything you need to perform live mixes.
* [ayoubfaouzi/al-khaser](https://github.com/ayoubfaouzi/al-khaser) - Public malware techniques used in the wild: Virtual Machine, Emulation, Debuggers, Sandbox detection.
* [google/flutter-desktop-embedding](https://github.com/google/flutter-desktop-embedding) - Experimental plugins for Flutter for Desktop *(archived)*
* [throneproj/Throne](https://github.com/throneproj/Throne) - Cross-platform GUI proxy utility (Empowered by sing-box)
* [FlaxEngine/FlaxEngine](https://github.com/FlaxEngine/FlaxEngine) - Flax Engine – multi-platform 3D game engine
* [alibaba/AndFix](https://github.com/alibaba/AndFix) - AndFix is a library that offer hot-fix for Android App.
* [Sigil-Ebook/Sigil](https://github.com/Sigil-Ebook/Sigil) - Sigil is a multi-platform EPUB ebook editor
* [interpretml/interpret](https://github.com/interpretml/interpret) - Fit interpretable models. Explain blackbox machine learning.
* [feiyangqingyun/QWidgetDemo](https://github.com/feiyangqingyun/QWidgetDemo) - Qt编写的一些开源的demo，预计会有100多个，一直持续更新完善，代码简洁易懂注释详细，每个都是独立项目，非常适合初学者，代码随意传播使用，拒绝打赏和捐赠，欢迎留言评论！公众号：Qt实战/Qt入门和进阶/Qt教程
* [sysown/proxysql](https://github.com/sysown/proxysql) - High-performance proxy for MySQL and PostgreSQL
* [wesnoth/wesnoth](https://github.com/wesnoth/wesnoth) - An open source, turn-based strategy game with a high fantasy theme.
* [microsoft/DirectX-Graphics-Samples](https://github.com/microsoft/DirectX-Graphics-Samples) - This repo contains the DirectX Graphics samples that demonstrate how to build graphics intensive applications on Windows.
* [werman/noise-suppression-for-voice](https://github.com/werman/noise-suppression-for-voice) - Noise suppression plugin based on Xiph's RNNoise
* [moudey/Shell](https://github.com/moudey/Shell) - Powerful context menu manager for Windows File Explorer
* [uxlfoundation/oneTBB](https://github.com/uxlfoundation/oneTBB) - oneAPI Threading Building Blocks (oneTBB)
* [microsoft/GSL](https://github.com/microsoft/GSL) - Guidelines Support Library
* [supercollider/supercollider](https://github.com/supercollider/supercollider) - An audio server, programming language, and IDE for sound synthesis and algorithmic composition.
* [BoomingTech/Piccolo](https://github.com/BoomingTech/Piccolo) - Piccolo (formerly Pilot) – mini game engine for games104
* [AlkaidLab/foundation-sunshine](https://github.com/AlkaidLab/foundation-sunshine) - Sunshine fork: an enhanced sunshine, a self-hosted game streaming host for Moonlight with HDR10/HDR Vivid, virtual displays, advanced audio, optimized encoders, and a modern control panel.
* [gaoxiang12/slambook2](https://github.com/gaoxiang12/slambook2) - edition 2 of the slambook
* [firebase/firebase-ios-sdk](https://github.com/firebase/firebase-ios-sdk) - Firebase SDK for Apple App Development
* [goldendict/goldendict](https://github.com/goldendict/goldendict) - A feature-rich dictionary lookup program, supporting multiple dictionary formats (StarDict/Babylon/Lingvo/Dictd) and online dictionaries, featuring perfect article rendering with the complete markup, illustrations and other content retained, and allowing you to type in words without any accents or correct case.
* [Tatsu-syo/noMeiryoUI](https://github.com/Tatsu-syo/noMeiryoUI) - No!! MeiryoUI is Windows system font setting tool on Windows 8.1/10/11.
* [ValveSoftware/openvr](https://github.com/ValveSoftware/openvr) - OpenVR SDK
* [zhongyang219/MusicPlayer2](https://github.com/zhongyang219/MusicPlayer2) - MusicPlayer2是一款功能强大的本地音乐播放软件，旨在为用户提供最佳的本地音乐播放体验。它支持歌词显示、歌词卡拉OK样式显示、歌词在线下载、歌词编辑、歌曲标签识别、专辑封面显示、专辑封面在线下载、频谱分析、音效设置、任务栏缩略图按钮、主题颜色、格式转换等功能，支持高度自定义的界面布局，支持多种播放内核（BASS和FFMpeg）。播放器支持大部分常见的音频格式。
* [BruceDevices/firmware](https://github.com/BruceDevices/firmware) - Predatory ESP32 Firmware
* [google/snappy](https://github.com/google/snappy) - A fast compressor/decompressor
* [tenacityteam/tenacity-legacy](https://github.com/tenacityteam/tenacity-legacy) - THIS REPO IS NOT MAINTAINED ANYMORE. Please see https://codeberg.org/tenacityteam/tenacity for Tenacity, which is maintained. *(archived)*
* [halide/Halide](https://github.com/halide/Halide) - a language for fast, portable data-parallel computation
* [doxygen/doxygen](https://github.com/doxygen/doxygen) - Official doxygen git repository
* [openMVG/openMVG](https://github.com/openMVG/openMVG) - open Multiple View Geometry library. Basis for 3D computer vision and Structure from Motion.
* [OpenMW/openmw](https://github.com/OpenMW/openmw) - OpenMW is an open-source open-world RPG game engine that supports playing Morrowind. Main repo and issue tracker can be found here: https://gitlab.com/OpenMW/openmw/
* [pixie-io/pixie](https://github.com/pixie-io/pixie) - Instant Kubernetes-Native Application Observability
* [kvcache-ai/Mooncake](https://github.com/kvcache-ai/Mooncake) - Mooncake is the serving platform for Kimi, a leading LLM service provided by Moonshot AI.
* [hedge-dev/XenonRecomp](https://github.com/hedge-dev/XenonRecomp) - A tool for recompiling Xbox 360 games to native executables.
* [HackerPoet/NonEuclidean](https://github.com/HackerPoet/NonEuclidean) - A Non-Euclidean Rendering Engine for 3D scenes.
* [NVIDIA/FasterTransformer](https://github.com/NVIDIA/FasterTransformer) - Transformer related optimization, including BERT, GPT
* [CodingGay/BlackDex](https://github.com/CodingGay/BlackDex) - BlackDex is an Android unpack(dexdump) tool, it supports Android 5.0~12 and need not rely to any environment. BlackDex can run on any Android mobile phone or emulator, you can unpack APK File in several seconds.
* [sz3/libcimbar](https://github.com/sz3/libcimbar) - Optimized implementation for color-icon-matrix barcodes
* [flashlight/wav2letter](https://github.com/flashlight/wav2letter) - Facebook AI Research's Automatic Speech Recognition Toolkit
* [liuruoze/EasyPR](https://github.com/liuruoze/EasyPR) - (CGCSTCD'2017) An easy, flexible, and accurate plate recognition project for Chinese licenses in unconstrained situations. CGCSTCD = China Graduate Contest on Smart-city Technology and Creative Design
* [google/perfetto](https://github.com/google/perfetto) - Production-grade client-side tracing, profiling, and analysis for complex software systems.
* [tony9402/baekjoon](https://github.com/tony9402/baekjoon) - 코딩테스트 대비 문제집(Baekjoon Online Judge)
* [kdrag0n/safetynet-fix](https://github.com/kdrag0n/safetynet-fix) - Google SafetyNet attestation workarounds for Magisk
* [microsoft/Detours](https://github.com/microsoft/Detours) - Detours is a software package for monitoring and instrumenting API calls on Windows. It is distributed in source code form.
* [tensorflow/serving](https://github.com/tensorflow/serving) - A flexible, high-performance serving system for machine learning models
* [google-ai-edge/LiteRT-LM](https://github.com/google-ai-edge/LiteRT-LM) - LiteRT-LM is Google's production-ready, high-performance, open-source inference framework for deploying Large Language Models on edge devices.
* [swig/swig](https://github.com/swig/swig) - SWIG is a software development tool that connects programs written in C and C++ with a variety of high-level programming languages.
* [wondertrader/wondertrader](https://github.com/wondertrader/wondertrader) - WonderTrader——量化研发交易一站式框架
* [AlexandreRouma/SDRPlusPlus](https://github.com/AlexandreRouma/SDRPlusPlus) - Cross-Platform SDR Software
* [facebook/redex](https://github.com/facebook/redex) - A bytecode optimizer for Android apps
* [spotify/pedalboard](https://github.com/spotify/pedalboard) - 🎛 🔊 A Python library for audio.
* [defold/defold](https://github.com/defold/defold) - Defold is a completely free to use game engine for development of desktop, console, mobile and web games.
* [szad670401/HyperLPR](https://github.com/szad670401/HyperLPR) - High Performance Chinese License Plate Recognition Framework.
* [gnuradio/gnuradio](https://github.com/gnuradio/gnuradio) - GNU Radio – the Free and Open Software Radio Ecosystem
* [epezent/implot](https://github.com/epezent/implot) - Immediate Mode Plotting
* [wjakob/instant-meshes](https://github.com/wjakob/instant-meshes) - Interactive field-aligned mesh generator
* [Tencent/puerts](https://github.com/Tencent/puerts) - PUER(普洱) Typescript. Let's write your game in UE or Unity with TypeScript.
* [valhalla/valhalla](https://github.com/valhalla/valhalla) - Open Source Routing Engine for OpenStreetMap
* [cisco/openh264](https://github.com/cisco/openh264) - Open Source H.264 Codec
* [PlotJuggler/PlotJuggler](https://github.com/PlotJuggler/PlotJuggler) - The Time Series Visualization Tool that you deserve.
* [OpenAtomFoundation/pikiwidb](https://github.com/OpenAtomFoundation/pikiwidb) - Pikiwidb is a Redis-Compatible database developed by Qihoo's infrastructure team.
* [OSGeo/gdal](https://github.com/OSGeo/gdal) - GDAL is an open source MIT licensed translator library for raster and vector geospatial data formats.
* [GothenburgBitFactory/taskwarrior](https://github.com/GothenburgBitFactory/taskwarrior) - Taskwarrior - Command line Task Management
* [ledger/ledger](https://github.com/ledger/ledger) - Double-entry accounting system with a command-line reporting interface
* [HKUST-Aerial-Robotics/VINS-Mono](https://github.com/HKUST-Aerial-Robotics/VINS-Mono) - A Robust and Versatile Monocular Visual-Inertial State Estimator
* [rainmeter/rainmeter](https://github.com/rainmeter/rainmeter) - Desktop customization tool for Windows
* [LANDrop/LANDrop](https://github.com/LANDrop/LANDrop) - Drop any files to any devices on your LAN.
* [duilib/duilib](https://github.com/duilib/duilib)
* [tranek/GASDocumentation](https://github.com/tranek/GASDocumentation) - My understanding of Unreal Engine 5's GameplayAbilitySystem plugin with a simple multiplayer sample project.
* [Redot-Engine/redot-engine](https://github.com/Redot-Engine/redot-engine) - Redot Engine – Multi-platform 2D and 3D game engine
* [ethereum-mining/ethminer](https://github.com/ethereum-mining/ethminer) - Ethereum miner with OpenCL, CUDA and stratum support *(archived)*
* [0xZ0F/Z0FCourse_ReverseEngineering](https://github.com/0xZ0F/Z0FCourse_ReverseEngineering) - Reverse engineering focusing on x64 Windows.
* [alibaba/AliSQL](https://github.com/alibaba/AliSQL) - AliSQL is a MySQL branch originated from Alibaba Group. Fetch document from Release Notes at bottom.
* [pbek/QOwnNotes](https://github.com/pbek/QOwnNotes) - QOwnNotes is a plain-text file notepad and todo-list manager with Markdown support and Nextcloud / ownCloud integration.
* [trapexit/mergerfs](https://github.com/trapexit/mergerfs) - a featureful union filesystem
* [luau-lang/luau](https://github.com/luau-lang/luau) - A small, fast, and embeddable programming language based on Lua with a gradual type system.
* [vcmi/vcmi](https://github.com/vcmi/vcmi) - Open-source engine for Heroes of Might and Magic III
* [cnr-isti-vclab/meshlab](https://github.com/cnr-isti-vclab/meshlab) - The open source mesh processing system
* [google/highway](https://github.com/google/highway) - Performance-portable, length-agnostic SIMD with runtime dispatch
* [NVIDIA/DALI](https://github.com/NVIDIA/DALI) - A GPU-accelerated library containing highly optimized building blocks and an execution engine for data processing to accelerate deep learning training and inference applications.
* [ffffffff0x/1earn](https://github.com/ffffffff0x/1earn) - ffffffff0x 团队维护的安全知识框架,内容包括不仅限于 web安全、工控安全、取证、应急、蓝队设施部署、后渗透、Linux安全、各类靶机writup
* [ethz-asl/kalibr](https://github.com/ethz-asl/kalibr) - The Kalibr visual-inertial calibration toolbox
* [jellyfin/jellyfin-desktop](https://github.com/jellyfin/jellyfin-desktop) - Jellyfin Desktop Client
* [Vita3K/Vita3K](https://github.com/Vita3K/Vita3K) - Experimental PlayStation Vita emulator
* [geo-tp/ESP32-Bit-Pirate](https://github.com/geo-tp/ESP32-Bit-Pirate) - A Hardware Hacking Tool with Web-Based CLI That Speaks Every Protocol
* [ConfettiFX/The-Forge](https://github.com/ConfettiFX/The-Forge) - The Forge Cross-Platform Framework PC Windows, Steamdeck (native), Ray Tracing, macOS / iOS, Android, XBOX, PS4, PS5, Switch, Quest 2
* [shader-slang/slang](https://github.com/shader-slang/slang) - Making it easier to work with shaders
* [mhammond/pywin32](https://github.com/mhammond/pywin32) - Python for Windows (pywin32) Extensions
* [leela-zero/leela-zero](https://github.com/leela-zero/leela-zero) - Go engine with no human-provided knowledge, modeled after the AlphaGo Zero paper.
* [KDE/kdenlive](https://github.com/KDE/kdenlive) - Free and open source video editor, based on MLT Framework and KDE Frameworks
* [lemonade-sdk/lemonade](https://github.com/lemonade-sdk/lemonade) - Lemonade helps users discover and run local AI apps by serving optimized LLMs right from their own GPUs and NPUs. Join our discord: https://discord.gg/5xXzkMu8Zk
* [google/bloaty](https://github.com/google/bloaty) - Bloaty: a size profiler for binaries
* [NatronGitHub/Natron](https://github.com/NatronGitHub/Natron) - Open-source video compositing software. Node-graph based. Similar in functionalities to Adobe After Effects and Nuke by The Foundry.
* [chrxh/alien](https://github.com/chrxh/alien) - ALIEN is a CUDA-powered artificial life simulation program.
* [zcash/zcash](https://github.com/zcash/zcash) - Zcash - Internet Money *(archived)*
* [DarthTon/Blackbone](https://github.com/DarthTon/Blackbone) - Windows memory hacking library
* [intel/hyperscan](https://github.com/intel/hyperscan) - High-performance regular expression matching library
* [google-deepmind/open_spiel](https://github.com/google-deepmind/open_spiel) - OpenSpiel is a collection of environments and algorithms for research in general reinforcement learning and search/planning in games.
* [xfangfang/wiliwili](https://github.com/xfangfang/wiliwili) - 第三方B站客户端，目前可以运行在PC全平台、PSVita、PS4 、Xbox 和 Nintendo Switch上
* [tjanczuk/edge](https://github.com/tjanczuk/edge) - Run .NET and Node.js code in-process on Windows, MacOS, and Linux
* [OHF-Voice/piper1-gpl](https://github.com/OHF-Voice/piper1-gpl) - Fast and local neural text-to-speech engine
* [crosire/reshade](https://github.com/crosire/reshade) - A generic post-processing injector for games and video software.
* [praydog/REFramework](https://github.com/praydog/REFramework) - Mod loader, scripting platform, and VR support for all RE Engine games
* [id-Software/DOOM-3-BFG](https://github.com/id-Software/DOOM-3-BFG) - Doom 3 BFG Edition
* [qpdf/qpdf](https://github.com/qpdf/qpdf) - qpdf: A content-preserving PDF document transformer
* [apache/mesos](https://github.com/apache/mesos) - Apache Mesos
* [KhronosGroup/Vulkan-Samples](https://github.com/KhronosGroup/Vulkan-Samples) - One stop solution for all Vulkan samples
* [ssloy/tinyraytracer](https://github.com/ssloy/tinyraytracer) - A brief computer graphics / rendering course
* [google/tcmalloc](https://github.com/google/tcmalloc)
* [nmslib/hnswlib](https://github.com/nmslib/hnswlib) - Header-only C++/python library for fast approximate nearest neighbors
* [Librum-Reader/Librum](https://github.com/Librum-Reader/Librum) - The Librum client application
* [EsotericSoftware/spine-runtimes](https://github.com/EsotericSoftware/spine-runtimes) - 2D skeletal animation runtimes for Spine.
* [ProjectPhysX/FluidX3D](https://github.com/ProjectPhysX/FluidX3D) - The fastest and most memory efficient lattice Boltzmann CFD software, running on all GPUs and CPUs via OpenCL. Free for non-commercial use.
* [Ardour/ardour](https://github.com/Ardour/ardour) - Mirror of Ardour Source Code
* [includeos/IncludeOS](https://github.com/includeos/IncludeOS) - A minimal, resource efficient unikernel for cloud services
* [google-ar/arcore-android-sdk](https://github.com/google-ar/arcore-android-sdk) - ARCore SDK for Android Studio
* [kasmtech/KasmVNC](https://github.com/kasmtech/KasmVNC) - Modern VNC Server and client, web based and secure
* [blinker-iot/blinker-library](https://github.com/blinker-iot/blinker-library) - An IoT Solution,Blinker library for embedded hardware. Works with Arduino R4, ESP32.
* [TwilitRealm/dusklight](https://github.com/TwilitRealm/dusklight) - Dusklight brings a classic adventure to PC and mobile platforms with a variety of fixes and improvements.
* [wangyu-/UDPspeeder](https://github.com/wangyu-/UDPspeeder) - A Tunnel which Improves your Network Quality on a High-latency Lossy Link by using Forward Error Correction, possible for All Traffics(TCP/UDP/ICMP)
* [KDAB/hotspot](https://github.com/KDAB/hotspot) - The Linux perf GUI for performance analysis.
* [RikkaApps/Riru](https://github.com/RikkaApps/Riru) - Inject into zygote process *(archived)*
* [ThePhD/sol2](https://github.com/ThePhD/sol2) - Sol3 (sol2 v3.0) - a C++ <-> Lua API wrapper with advanced features and top notch performance - is here, and it's great! Documentation:
* [hku-mars/FAST_LIO](https://github.com/hku-mars/FAST_LIO) - A computationally efficient and robust LiDAR-inertial odometry (LIO) package
* [phusion/passenger](https://github.com/phusion/passenger) - A fast and robust web server and application server for Ruby, Python and Node.js
* [opentrack/opentrack](https://github.com/opentrack/opentrack) - Head tracking software for MS Windows, Linux, and Apple OSX
* [mmp/pbrt-v3](https://github.com/mmp/pbrt-v3) - Source code for pbrt, the renderer described in the third edition of "Physically Based Rendering: From Theory To Implementation", by Matt Pharr, Wenzel Jakob, and Greg Humphreys.
* [cmu-db/bustub](https://github.com/cmu-db/bustub) - The BusTub Relational Database Management System (Educational)
* [lightvector/KataGo](https://github.com/lightvector/KataGo) - GTP engine and self-play learning in Go
* [justadudewhohacks/opencv4nodejs](https://github.com/justadudewhohacks/opencv4nodejs) - Nodejs bindings to OpenCV 3 and OpenCV 4
* [XiaoMi/mace](https://github.com/XiaoMi/mace) - MACE is a deep learning inference framework optimized for mobile heterogeneous computing platforms.
* [itinance/react-native-fs](https://github.com/itinance/react-native-fs) - Native filesystem access for react-native
* [NVIDIA/nccl](https://github.com/NVIDIA/nccl) - Optimized primitives for collective multi-GPU communication
* [MAZHARMIK/Interview_DS_Algo](https://github.com/MAZHARMIK/Interview_DS_Algo) - Super Repository for Coding Interview Preperation
* [sorayuki/obs-multi-rtmp](https://github.com/sorayuki/obs-multi-rtmp) - OBS複数サイト同時配信プラグイン
* [Arduino-IRremote/Arduino-IRremote](https://github.com/Arduino-IRremote/Arduino-IRremote) - Infrared remote library for Arduino: send and receive infrared signals with multiple protocols
* [microsoft/SPTAG](https://github.com/microsoft/SPTAG) - A distributed approximate nearest neighborhood search (ANN) library which provides a high quality vector index build, search and distributed online serving toolkits for large scale vector search scenario.
* [hedge-dev/UnleashedRecomp](https://github.com/hedge-dev/UnleashedRecomp) - An unofficial PC port of the Xbox 360 version of Sonic Unleashed created through the process of static recompilation.
* [dropbox/lepton](https://github.com/dropbox/lepton) - Lepton is a tool and file format for losslessly compressing JPEGs by an average of 22%. *(archived)*
* [melonDS-emu/melonDS](https://github.com/melonDS-emu/melonDS) - DS emulator, sorta
* [qTox/qTox](https://github.com/qTox/qTox) - qTox is a chat, voice, video, and file transfer IM client using the encrypted peer-to-peer Tox protocol. *(archived)*
* [KDE/ghostwriter](https://github.com/KDE/ghostwriter) - Text editor for Markdown
* [bambulab/BambuStudio](https://github.com/bambulab/BambuStudio) - PC Software for BambuLab and other 3D printers
* [paolo-projects/auto-unlocker](https://github.com/paolo-projects/auto-unlocker) - Unlocker for VMWare macOS
* [zufuliu/notepad4](https://github.com/zufuliu/notepad4) - Notepad4 (Notepad2⨯2, Notepad2++) is a light-weight Scintilla based text editor for Windows with syntax highlighting, code folding, auto-completion and API list for many programming languages and documents, bundled with file browser plugin matepath.
* [Nukem9/dlssg-to-fsr3](https://github.com/Nukem9/dlssg-to-fsr3) - Adds AMD FSR 3 Frame Generation to games by replacing Nvidia DLSS Frame Generation (nvngx_dlssg).
* [begeekmyfriend/yasea](https://github.com/begeekmyfriend/yasea) - RTMP live streaming client for Android
* [mg-chao/snow-apps](https://github.com/mg-chao/snow-apps) - Snow Apps repository, providing source code for Snow Shot and Snow Image Viewer.
* [Chlumsky/msdfgen](https://github.com/Chlumsky/msdfgen) - Multi-channel signed distance field generator
* [anyrtcIO-Community/anyRTC-RTMP-OpenSource](https://github.com/anyrtcIO-Community/anyRTC-RTMP-OpenSource) - RTMP 推流器，RTMP(HLS)秒开播放器，直播点播，跨平台（Win,IOS,Android）开源代码
* [TixiaoShan/LIO-SAM](https://github.com/TixiaoShan/LIO-SAM) - LIO-SAM: Tightly-coupled Lidar Inertial Odometry via Smoothing and Mapping
* [google/liquidfun](https://github.com/google/liquidfun) - 2D physics engine for games *(archived)*
* [mavlink/qgroundcontrol](https://github.com/mavlink/qgroundcontrol) - Cross-platform ground control station for drones (Android, iOS, Mac OS, Linux, Windows)
* [wjakob/nanogui](https://github.com/wjakob/nanogui) - Minimalistic GUI library for OpenGL
* [R3nzTheCodeGOD/R3nzSkin](https://github.com/R3nzTheCodeGOD/R3nzSkin) - Skin changer for League of Legends (LOL) *(archived)*
* [rakshasa/rtorrent](https://github.com/rakshasa/rtorrent) - rTorrent BitTorrent client
* [jmpews/Dobby](https://github.com/jmpews/Dobby) - a lightweight, multi-platform, multi-architecture hook framework.
* [MegEngine/MegEngine](https://github.com/MegEngine/MegEngine) - MegEngine 是一个快速、可拓展、易于使用且支持自动求导的深度学习框架
* [fritzing/fritzing-app](https://github.com/fritzing/fritzing-app) - Fritzing desktop application
* [dfranx/SHADERed](https://github.com/dfranx/SHADERed) - Lightweight, cross-platform & full-featured shader IDE
* [ydb-platform/ydb](https://github.com/ydb-platform/ydb) - YDB is an open source Distributed SQL Database that combines high availability and scalability with strong consistency and ACID transactions
* [urho3d/urho3d](https://github.com/urho3d/urho3d) - Game engine *(archived)*
* [MaaXYZ/MaaFramework](https://github.com/MaaXYZ/MaaFramework) - 基于图像识别的自动化黑盒测试框架 | An automation black-box testing framework based on image recognition
* [NVIDIA-Omniverse/PhysX](https://github.com/NVIDIA-Omniverse/PhysX) - NVIDIA PhysX SDK
* [YosysHQ/yosys](https://github.com/YosysHQ/yosys) - Yosys Open SYnthesis Suite
* [PancakeTAS/lsfg-vk](https://github.com/PancakeTAS/lsfg-vk) - Lossless Scaling Frame Generation on Linux
* [BespokeSynth/BespokeSynth](https://github.com/BespokeSynth/BespokeSynth) - Software modular synth
* [mindspore-ai/mindspore](https://github.com/mindspore-ai/mindspore) - MindSpore is a new open source deep learning training/inference framework that could be used for mobile, edge and cloud scenarios.
* [infiniflow/infinity](https://github.com/infiniflow/infinity) - The AI-native database built for LLM applications, providing incredibly fast hybrid search of dense vector, sparse vector, tensor (multi-vector), and full-text.
* [HKUST-Aerial-Robotics/VINS-Fusion](https://github.com/HKUST-Aerial-Robotics/VINS-Fusion) - An optimization-based multi-sensor state estimator
* [xxnuo/MTranServer](https://github.com/xxnuo/MTranServer) - Offline translation model server with low resource consumption, fast speed, and private deployment capability. 低资源占用速度快可私有部署的离线翻译模型服务器
* [MultiMC/Launcher](https://github.com/MultiMC/Launcher) - A custom launcher for Minecraft that allows you to easily manage multiple installations of Minecraft at once
* [microsoft/WindowsAppSDK](https://github.com/microsoft/WindowsAppSDK) - The Windows App SDK empowers all Windows desktop apps with modern Windows UI, APIs, and platform features, including back-compat support, shipped via NuGet.
* [f3d-app/f3d](https://github.com/f3d-app/f3d) - Fast and minimalist 3D viewer.
* [ros-navigation/navigation2](https://github.com/ros-navigation/navigation2) - ROS 2 Navigation Framework and System
* [Tencent/TNN](https://github.com/Tencent/TNN) - TNN: developed by Tencent Youtu Lab and Guangying Lab, a uniform deep learning inference framework for mobile、desktop and server. TNN is distinguished by several outstanding features, including its cross-platform capability, high performance, model compression and code pruning. Based on ncnn and Rapidnet, TNN further strengthens the support and performance optimization for mobile devices, and also draws on the advantages of good extensibility and high performance from existed open source efforts. TNN has been deployed in multiple Apps from Tencent, such as Mobile QQ, Weishi, Pitu, etc. Contributions are welcome to work in collaborative with us and make TNN a better framework.
* [vaibhavpandeyvpz/apkstudio](https://github.com/vaibhavpandeyvpz/apkstudio) - Open-source, cross platform Qt6 based IDE for reverse-engineering Android application packages. It features a friendly IDE-like layout including code editor with syntax highlighting support for *.smali code files.
* [seetaface/SeetaFaceEngine](https://github.com/seetaface/SeetaFaceEngine)
* [TTimo/doom3.gpl](https://github.com/TTimo/doom3.gpl) - Doom 3 GPL source release
* [mapsme/omim](https://github.com/mapsme/omim) - 🗺️ MAPS.ME — Offline OpenStreetMap maps for iOS and Android
* [zhuzichu520/FluentUI](https://github.com/zhuzichu520/FluentUI) - FluentUI for QML
* [cyberbotics/webots](https://github.com/cyberbotics/webots) - Webots Robot Simulator
* [rime/librime](https://github.com/rime/librime) - Rime Input Method Engine, the core library
* [hku-mars/FAST-LIVO2](https://github.com/hku-mars/FAST-LIVO2) - FAST-LIVO2: Fast, Direct LiDAR-Inertial-Visual Odometry
* [Almamu/linux-wallpaperengine](https://github.com/Almamu/linux-wallpaperengine) - Wallpaper Engine backgrounds for Linux!
* [plaidml/plaidml](https://github.com/plaidml/plaidml) - PlaidML is a framework for making deep learning work everywhere. *(archived)*
* [kripken/ammo.js](https://github.com/kripken/ammo.js) - Direct port of the Bullet physics engine to JavaScript using Emscripten
* [Maplespe/DWMBlurGlass](https://github.com/Maplespe/DWMBlurGlass) - Add custom effect to global system title bar, support win10 and win11.
* [OAID/Tengine](https://github.com/OAID/Tengine) - Tengine is a lite, high performance, modular inference engine for embedded device
* [keepassx/keepassx](https://github.com/keepassx/keepassx) - KeePassX is a cross platform port of the windows application “Keepass Password Safe”. *(archived)*
* [DistroAV/DistroAV](https://github.com/DistroAV/DistroAV) - DistroAV (formerly OBS-NDI): NDI integration for OBS Studio
* [openxla/xla](https://github.com/openxla/xla) - A machine learning compiler for GPUs, CPUs, and ML accelerators
* [kungfu-systems/kungfu](https://github.com/kungfu-systems/kungfu) - Your agents don’t hand off the work. Kungfu keeps the same Work moving across Codex, Claude, OpenCode, and your own execution surface.
* [royshil/obs-backgroundremoval](https://github.com/royshil/obs-backgroundremoval) - An OBS plugin for removing background in portrait images (video), making it easy to replace the background when recording or streaming.
* [thedmd/imgui-node-editor](https://github.com/thedmd/imgui-node-editor) - Node Editor built using Dear ImGui
* [flutter-webrtc/flutter-webrtc](https://github.com/flutter-webrtc/flutter-webrtc) - WebRTC plugin for Flutter Mobile/Desktop/Web
* [dcajasn/Riskfolio-Lib](https://github.com/dcajasn/Riskfolio-Lib) - Portfolio Optimization in Python
* [praydog/UEVR](https://github.com/praydog/UEVR) - Universal Unreal Engine VR Mod (4.8 - 5.4)
* [PowerDNS/pdns](https://github.com/PowerDNS/pdns) - PowerDNS Authoritative, PowerDNS Recursor, dnsdist
* [taurusxin/ncmdump](https://github.com/taurusxin/ncmdump) - 转换网易云音乐 ncm 到 mp3 / flac. Convert Netease Cloud Music ncm files to mp3/flac files.
* [mapbox/mapbox-gl-native](https://github.com/mapbox/mapbox-gl-native) - Interactive, thoroughly customizable maps in native Android, iOS, macOS, Node.js, and Qt applications, powered by vector tiles and OpenGL *(archived)*
* [tdlib/telegram-bot-api](https://github.com/tdlib/telegram-bot-api) - Telegram Bot API server
* [ic005k/OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) - Cross-platform GUI management tools for OpenCore（OCAT）
* [apache/kvrocks](https://github.com/apache/kvrocks) - Apache Kvrocks is a distributed key value NoSQL database that uses RocksDB as storage engine and is compatible with Redis protocol.
* [projectM-visualizer/projectm](https://github.com/projectM-visualizer/projectm) - projectM - Cross-platform Music Visualization Library. Open-source and Milkdrop-compatible.
* [VCVRack/Rack](https://github.com/VCVRack/Rack) - The virtual Eurorack studio
* [oceanbase/miniob](https://github.com/oceanbase/miniob) - MiniOB is a compact database that assists developers in understanding the fundamental workings of a database.
* [mikke89/RmlUi](https://github.com/mikke89/RmlUi) - RmlUi - The HTML/CSS User Interface library evolved
* [amazon-archives/amazon-dsstne](https://github.com/amazon-archives/amazon-dsstne) - Deep Scalable Sparse Tensor Network Engine (DSSTNE) is an Amazon developed library for building Deep Learning (DL) machine learning (ML) models *(archived)*
* [peterbraden/node-opencv](https://github.com/peterbraden/node-opencv) - OpenCV Bindings for node.js
* [CalcProgrammer1/OpenRGB](https://github.com/CalcProgrammer1/OpenRGB) - Open source RGB lighting control that doesn't depend on manufacturer software. Supports Windows, Linux, MacOS. Mirror of https://gitlab.com/CalcProgrammer1/OpenRGB. Releases can be found on GitLab.
* [fxsound2/fxsound-app](https://github.com/fxsound2/fxsound-app) - FxSound application and DSP source code
* [hzeller/rpi-rgb-led-matrix](https://github.com/hzeller/rpi-rgb-led-matrix) - Controlling up to three chains of 64x64, 32x32, 16x32 or similar RGB LED displays using Raspberry Pi GPIO
* [PixlOne/logiops](https://github.com/PixlOne/logiops) - An unofficial userspace driver for HID++ Logitech devices
* [ValveSoftware/halflife](https://github.com/ValveSoftware/halflife) - Half-Life 1 engine based games
* [obsproject/obs-websocket](https://github.com/obsproject/obs-websocket) - Remote-control of OBS Studio through WebSocket
* [apache/incubator-pagespeed-ngx](https://github.com/apache/incubator-pagespeed-ngx) - Automatic PageSpeed optimization module for Nginx *(archived)*
* [vslavik/diff-pdf](https://github.com/vslavik/diff-pdf) - A simple tool for visually comparing two PDF files
* [unum-cloud/USearch](https://github.com/unum-cloud/USearch) - Fast Open-Source Search & Clustering engine × for Vectors & Arbitrary Objects × in C++, C, Python, JavaScript, Rust, Java, Objective-C, Swift, C#, GoLang, and Wolfram 🔍
* [x64dbg/ScyllaHide](https://github.com/x64dbg/ScyllaHide) - Advanced usermode anti-anti-debugger. Forked from https://bitbucket.org/NtQuery/scyllahide
* [JonathanSalwan/Triton](https://github.com/JonathanSalwan/Triton) - Triton is a dynamic binary analysis library. Build your own program analysis tools, automate your reverse engineering, perform software verification or just emulate code.
* [DDoSolitary/LxRunOffline](https://github.com/DDoSolitary/LxRunOffline) - A full-featured utility for managing Windows Subsystem for Linux (WSL)
* [SteamClientHomebrew/Millennium](https://github.com/SteamClientHomebrew/Millennium) - Open-source modding framework for creating and managing Steam Client themes and plugins.
* [wang-bin/QtAV](https://github.com/wang-bin/QtAV) - A cross-platform multimedia framework based on Qt and FFmpeg. 基于Qt和FFmpeg的跨平台高性能音视频播放框架. Recommand to use new sdk https://github.com/wang-bin/mdk-sdk
* [citizenfx/fivem](https://github.com/citizenfx/fivem) - The source code for the Cfx modification frameworks, such as FiveM and RedM, as well as FXServer.
* [OneLoneCoder/olcPixelGameEngine](https://github.com/OneLoneCoder/olcPixelGameEngine) - The official distribution of olcPixelGameEngine, a tool used in javidx9's YouTube videos and projects
* [nefarius/ViGEmBus](https://github.com/nefarius/ViGEmBus) - Windows kernel-mode driver emulating well-known USB game controllers. *(archived)*
* [TokisanGames/Terrain3D](https://github.com/TokisanGames/Terrain3D) - A high performance, editable terrain system for Godot 4.
* [mausimus/ShaderGlass](https://github.com/mausimus/ShaderGlass) - Overlay for running GPU shaders on top of Windows desktop and Wine
* [PurpleI2P/i2pd](https://github.com/PurpleI2P/i2pd) - 🛡 I2P: End-to-End encrypted and anonymous Internet
* [Vhonowslend/StreamFX-Public](https://github.com/Vhonowslend/StreamFX-Public) - StreamFX is a plugin for OBS® Studio which adds many new effects, filters, sources, transitions and encoders! Be it 3D Transform, Blur, complex Masking, or even custom shaders, you'll find it all here.
* [Maplespe/ExplorerBlurMica](https://github.com/Maplespe/ExplorerBlurMica) - Add background Blur effect or Acrylic (Mica for win11) effect to explorer for win10 and win11
* [RobotLocomotion/drake](https://github.com/RobotLocomotion/drake) - Model-based design and verification for robotics.
* [KDE/heaptrack](https://github.com/KDE/heaptrack) - A heap memory profiler for Linux
* [univrsal/input-overlay](https://github.com/univrsal/input-overlay) - Show keyboard, gamepad and mouse input on stream
* [RawTherapee/RawTherapee](https://github.com/RawTherapee/RawTherapee) - A powerful cross-platform raw photo processing program
* [GDRETools/gdsdecomp](https://github.com/GDRETools/gdsdecomp) - Godot reverse engineering tools
* [SeriousCache/UABE](https://github.com/SeriousCache/UABE) - Asset Bundle Extractor. No longer supported. Consider using https://github.com/nesrak1/UABEA *(archived)*
* [ton-blockchain/ton](https://github.com/ton-blockchain/ton) - Main TON monorepo
* [solvespace/solvespace](https://github.com/solvespace/solvespace) - Parametric 2d/3d CAD
* [JoseExposito/touchegg](https://github.com/JoseExposito/touchegg) - Linux multi-touch gesture recognizer
* [cdcseacave/openMVS](https://github.com/cdcseacave/openMVS) - open Multi-View Stereo reconstruction library
* [1technophile/OpenMQTTGateway](https://github.com/1technophile/OpenMQTTGateway) - MQTT gateway for ESP8266 or ESP32 with bidirectional 433mhz/315mhz/868mhz, Infrared communications, BLE, Bluetooth, beacons detection, mi flora, mi jia, LYWSD02, LYWSD03MMC, Mi Scale, TPMS, BBQ thermometer compatibility & LoRa.
* [google/nsjail](https://github.com/google/nsjail) - A lightweight process isolation tool that utilizes Linux namespaces, cgroups, rlimits and seccomp-bpf syscall filters, leveraging the Kafel BPF language for enhanced security.
* [DS-Homebrew/TWiLightMenu](https://github.com/DS-Homebrew/TWiLightMenu) - DSi Menu replacement for DS/DSi/3DS/2DS
* [google/angle](https://github.com/google/angle) - A conformant OpenGL ES implementation for Windows, Mac, Linux, iOS and Android.
* [fireice-uk/xmr-stak](https://github.com/fireice-uk/xmr-stak) - Free Monero RandomX Miner and unified CryptoNight miner
* [robbert-vdh/yabridge](https://github.com/robbert-vdh/yabridge) - A modern and transparent way to use Windows VST2, VST3 and CLAP plugins on Linux
* [srsran/srsRAN_4G](https://github.com/srsran/srsRAN_4G) - Open source SDR 4G software suite from Software Radio Systems (SRS) https://docs.srsran.com/projects/4g
* [me-no-dev/ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer) - Async Web Server for ESP8266 and ESP32 *(archived)*
* [Motion-Project/motion](https://github.com/Motion-Project/motion) - Motion, a software motion detector. Home page: https://motion-project.github.io/
* [uxlfoundation/oneDNN](https://github.com/uxlfoundation/oneDNN) - oneAPI Deep Neural Network Library (oneDNN)
* [km1994/nlp_paper_study](https://github.com/km1994/nlp_paper_study) - 该仓库主要记录 NLP 算法工程师相关的顶会论文研读笔记
* [kuzudb/kuzu](https://github.com/kuzudb/kuzu) - Embedded property graph database built for speed. Vector search and full-text search built in. Implements Cypher. *(archived)*
* [microsoft/SEAL](https://github.com/microsoft/SEAL) - Microsoft SEAL is an easy-to-use and powerful homomorphic encryption library.
* [openthread/openthread](https://github.com/openthread/openthread) - OpenThread released by Google is an open-source implementation of the Thread networking protocol
* [knolleary/pubsubclient](https://github.com/knolleary/pubsubclient) - A client library for the Arduino Ethernet Shield that provides support for MQTT.
* [CedricGuillemet/ImGuizmo](https://github.com/CedricGuillemet/ImGuizmo) - Immediate mode 3D gizmo for scene editing and other controls based on Dear Imgui
* [baidu/lac](https://github.com/baidu/lac) - 百度NLP：分词，词性标注，命名实体识别，词重要性
* [Blynk-Technologies/blynk-library](https://github.com/Blynk-Technologies/blynk-library) - Blynk library for IoT boards. Works with Arduino, ESP32, ESP8266, Raspberry Pi, Particle, etc.
* [introlab/rtabmap](https://github.com/introlab/rtabmap) - RTAB-Map library and standalone application
* [spring/spring](https://github.com/spring/spring) - A powerful free cross-platform RTS game engine. - Report issues at https://springrts.com/mantis/
* [windirstat/windirstat](https://github.com/windirstat/windirstat) - WinDirStat is a disk usage statistics viewer and cleanup tool for Microsoft Windows
* [google/lyra](https://github.com/google/lyra) - A Very Low-Bitrate Codec for Speech Compression
* [kiwibrowser/src.next](https://github.com/kiwibrowser/src.next) - Source-code for Kiwi Next, a Kiwi Browser auto-rebased with latest Chromium
* [KDE/kdeconnect-kde](https://github.com/KDE/kdeconnect-kde) - Multi-platform app that allows your devices to communicate
* [mapnik/mapnik](https://github.com/mapnik/mapnik) - Mapnik is an open source toolkit for developing mapping applications
* [AntiMicroX/antimicrox](https://github.com/AntiMicroX/antimicrox) - Graphical program used to map keyboard buttons and mouse controls to a gamepad. Useful for playing games with no gamepad support.
* [balloonwj/flamingo](https://github.com/balloonwj/flamingo) - flamingo 一款高性能轻量级开源即时通讯软件
* [facebookresearch/StarSpace](https://github.com/facebookresearch/StarSpace) - Learning embeddings for classification, retrieval and ranking. *(archived)*
* [f4exb/sdrangel](https://github.com/f4exb/sdrangel) - SDR Rx/Tx software for Airspy, Airspy HF+, BladeRF, HackRF, LimeSDR, PlutoSDR, RTL-SDR, SDRplay and FunCube
* [johang/btfs](https://github.com/johang/btfs) - A bittorrent filesystem based on FUSE.
* [cifertech/ESP32-DIV](https://github.com/cifertech/ESP32-DIV) - ESP32DIV is a multi-purpose wireless offensive and defensive toolkit powered by an ESP32
* [strawberrymusicplayer/strawberry](https://github.com/strawberrymusicplayer/strawberry) - :strawberry: Strawberry Music Player
* [Warzone2100/warzone2100](https://github.com/Warzone2100/warzone2100) - Command the forces of The Project in a battle to rebuild the world after mankind has been nearly destroyed by nuclear missiles. A 100% free and open source real-time strategy game for Windows, macOS, Linux, BSD+
* [ricochet-im/ricochet](https://github.com/ricochet-im/ricochet) - Anonymous peer-to-peer instant messaging
* [abcz316/SKRoot-linuxKernelRoot](https://github.com/abcz316/SKRoot-linuxKernelRoot) - 新一代 SKRoot，完美隐藏Root功能，无视全网检测手段，实现SELinux零触碰、无挂载！ 通杀所有内核，免源码直接 Patch 原厂内核，完美保留官方内核所有特性。
* [iree-org/iree](https://github.com/iree-org/iree) - A retargetable MLIR-based machine learning compiler and runtime toolkit.
* [visualboyadvance-m/visualboyadvance-m](https://github.com/visualboyadvance-m/visualboyadvance-m) - The continuing development of the legendary VBA gameboy advance emulator.
* [facebookarchive/scribe](https://github.com/facebookarchive/scribe) - Scribe is a server for aggregating log data streamed in real time from a large number of servers. *(archived)*
* [newsboat/newsboat](https://github.com/newsboat/newsboat) - An RSS/Atom feed reader for text terminals
* [Zylann/godot_voxel](https://github.com/Zylann/godot_voxel) - Voxel module for Godot Engine
* [callmePicacho/Data-Structres](https://github.com/callmePicacho/Data-Structres) - 浙江大学《数据结构》上课笔记 + 数据结构实现 + 课后题题解
* [hasherezade/pe-sieve](https://github.com/hasherezade/pe-sieve) - Scans a given process. Recognizes and dumps a variety of potentially malicious implants (replaced/injected PEs, shellcodes, hooks, in-memory patches).
* [tinyobjloader/tinyobjloader](https://github.com/tinyobjloader/tinyobjloader) - Tiny but powerful single file wavefront obj loader
* [MisterTea/EternalTerminal](https://github.com/MisterTea/EternalTerminal) - Re-Connectable secure remote shell
* [yuaotian/antigravity-proxy](https://github.com/yuaotian/antigravity-proxy) - 🚀 Transparent proxy injector for Antigravity. Force SOCKS5/HTTP proxy without TUN mode on Windows. | 专为 Antigravity 打造的免 TUN 强制代理工具，支持 DLL 注入与进程流量劫持。
* [nextcloud/desktop](https://github.com/nextcloud/desktop) - 💻 Desktop sync client for Nextcloud
* [dendibakh/perf-ninja](https://github.com/dendibakh/perf-ninja) - This is an online course where you can learn and master the skill of low-level performance analysis and tuning.
* [hyperion-project/hyperion.ng](https://github.com/hyperion-project/hyperion.ng) - The successor to Hyperion aka Hyperion Next Generation
* [tindy2013/stairspeedtest-reborn](https://github.com/tindy2013/stairspeedtest-reborn) - Proxy performance batch tester based on Shadowsocks(R) and V2Ray
* [ip7z/7zip](https://github.com/ip7z/7zip) - 7-Zip
* [facebookresearch/habitat-sim](https://github.com/facebookresearch/habitat-sim) - A flexible, high-performance 3D simulator for Embodied AI research.
* [tildearrow/furnace](https://github.com/tildearrow/furnace) - a multi-system chiptune tracker compatible with DefleMask modules
* [domoticz/domoticz](https://github.com/domoticz/domoticz) - Free open source home automation system for Linux, Windows, Raspberry Pi. Supports Z-Wave, Zigbee, MQTT, and 150+ devices.
* [sorbet/sorbet](https://github.com/sorbet/sorbet) - A fast, powerful type checker designed for Ruby
* [hasherezade/pe-bear](https://github.com/hasherezade/pe-bear) - Portable Executable reversing tool with a friendly GUI
* [pqrs-org/Karabiner-archived](https://github.com/pqrs-org/Karabiner-archived) - Karabiner (KeyRemap4MacBook) is a powerful utility for keyboard customization. *(archived)*
* [google/fuzzing](https://github.com/google/fuzzing) - Tutorials, examples, discussions, research proposals, and other resources related to fuzzing *(archived)*
* [LibreVR/Revive](https://github.com/LibreVR/Revive) - Play Oculus-exclusive games on the HTC Vive or Valve Index, scroll down for downloads and installation instructions.
* [ravenscroftj/turbopilot](https://github.com/ravenscroftj/turbopilot) - Turbopilot is an open source large-language-model based code completion engine that runs locally on CPU *(archived)*
* [farbrausch/fr_public](https://github.com/farbrausch/fr_public) - Farbrausch demo tools 2001-2011
* [odriverobotics/ODrive](https://github.com/odriverobotics/ODrive) - High performance motor control
* [MaaEnd/MaaEnd](https://github.com/MaaEnd/MaaEnd) - MaaEnd 终末地小助手：基于视觉 AI 的「明日方舟：终末地」自动化工具
* [FLIF-hub/FLIF](https://github.com/FLIF-hub/FLIF) - Free Lossless Image Format
* [LUX-Core/lux](https://github.com/LUX-Core/lux) - LUX - Hybrid PoW/PoS & Unique PHI2 Algorithm | Masternode | Parallel masternode | Segwit | Smartcontract | Luxgate | Proof of file storage (Decentralised distributed file storage)
* [microsoft/verona](https://github.com/microsoft/verona) - Research programming language for concurrent ownership
* [stack-of-tasks/pinocchio](https://github.com/stack-of-tasks/pinocchio) - A fast and flexible implementation of Rigid Body Dynamics algorithms and their analytical derivatives
* [audiorouterdev/audio-router](https://github.com/audiorouterdev/audio-router) - Routes audio from programs to different audio devices.
* [wjakob/nanobind](https://github.com/wjakob/nanobind) - nanobind: tiny and efficient C++/Python bindings
* [pavel-odintsov/fastnetmon](https://github.com/pavel-odintsov/fastnetmon) - Very fast DDoS sensor with sFlow/Netflow/IPFIX/SPAN support
* [raboof/nethogs](https://github.com/raboof/nethogs) - Linux 'net top' tool
* [paceholder/nodeeditor](https://github.com/paceholder/nodeeditor) - Qt Node Editor. Dataflow programming framework
* [mmp/pbrt-v4](https://github.com/mmp/pbrt-v4) - Source code to pbrt, the ray tracer described in the forthcoming 4th edition of the "Physically Based Rendering: From Theory to Implementation" book.
* [Overv/VulkanTutorial](https://github.com/Overv/VulkanTutorial) - Tutorial for the Vulkan graphics and compute API
* [gqrx-sdr/gqrx](https://github.com/gqrx-sdr/gqrx) - Software defined radio receiver powered by GNU Radio and Qt.
* [FrictionalGames/AmnesiaTheDarkDescent](https://github.com/FrictionalGames/AmnesiaTheDarkDescent)
* [BrunoLevy/learn-fpga](https://github.com/BrunoLevy/learn-fpga) - Learning FPGA, yosys, nextpnr, and RISC-V
* [es3n1n/defendnot](https://github.com/es3n1n/defendnot) - An even funnier way to disable windows defender (through WSC api)
* [slic3r/Slic3r](https://github.com/slic3r/Slic3r) - Open Source toolpath generator for 3D printers
* [libjxl/libjxl](https://github.com/libjxl/libjxl) - JPEG XL image format reference implementation
* [steveicarus/iverilog](https://github.com/steveicarus/iverilog) - Icarus Verilog
* [TASEmulators/desmume](https://github.com/TASEmulators/desmume) - DeSmuME is a Nintendo DS emulator
* [texstudio-org/texstudio](https://github.com/texstudio-org/texstudio) - TeXstudio is a fully featured LaTeX editor. Our goal is to make writing LaTeX documents as easy and comfortable as possible.
* [NerdLang/nerd](https://github.com/NerdLang/nerd) - 🔱 Javascript's God Mode. No VM. No Bytecode. No GC. Just native binaries.
* [yue/yue](https://github.com/yue/yue) - A library for creating native cross-platform GUI apps
* [openscenegraph/OpenSceneGraph](https://github.com/openscenegraph/OpenSceneGraph) - OpenSceneGraph git repository
* [apache/singa](https://github.com/apache/singa) - a distributed deep learning platform
* [laserpants/qt-material-widgets](https://github.com/laserpants/qt-material-widgets) - :art: Qt widgets-based implementation of the Material Design specification.
* [Haivision/srt](https://github.com/Haivision/srt) - Secure, Reliable, Transport
* [NVIDIAGameWorks/PhysX](https://github.com/NVIDIAGameWorks/PhysX) - NVIDIA PhysX SDK
* [letscontrolit/ESPEasy](https://github.com/letscontrolit/ESPEasy) - Easy MultiSensor device based on ESP8266/ESP32
* [nullptrlabs/pgmodeler](https://github.com/nullptrlabs/pgmodeler) - Open-source data modeling tool designed for PostgreSQL. No more typing DDL commands. Let pgModeler do the work for you!
* [nmslib/nmslib](https://github.com/nmslib/nmslib) - Non-Metric Space Library (NMSLIB): An efficient similarity search library and a toolkit for evaluation of k-NN methods for generic non-metric spaces.
* [unicode-org/icu](https://github.com/unicode-org/icu) - The home of the ICU project source code.
* [ai-winter/ros_motion_planning](https://github.com/ai-winter/ros_motion_planning) - Motion planning and Navigation of AGV/AMR：ROS planner plugin implementation of A*, JPS, D*, LPA*, D* Lite, Theta*, RRT, RRT*, RRT-Connect, Informed RRT*, ACO, PSO, Voronoi, PID, LQR, MPC, DWA, APF, Pure Pursuit etc.
* [crankyoldgit/IRremoteESP8266](https://github.com/crankyoldgit/IRremoteESP8266) - Infrared remote library for ESP8266/ESP32: send and receive infrared signals with multiple protocols. Based on: https://github.com/shirriff/Arduino-IRremote/
* [mpromonet/webrtc-streamer](https://github.com/mpromonet/webrtc-streamer) - WebRTC streamer for V4L2 capture devices, RTSP sources and Screen Capture
* [pond3r/ggpo](https://github.com/pond3r/ggpo) - Good Game, Peace Out Rollback Network SDK
* [acidanthera/AppleALC](https://github.com/acidanthera/AppleALC) - Native macOS HD audio for not officially supported codecs
* [KhronosGroup/glslang](https://github.com/KhronosGroup/glslang) - Khronos-reference front end for GLSL/ESSL, partial front end for HLSL, and a SPIR-V generator.
* [momo5502/sogen](https://github.com/momo5502/sogen) - 🪅 Windows & Linux userspace emulator
* [alibaba/GraphScope](https://github.com/alibaba/GraphScope) - 🔨 🍇 💻 🚀 GraphScope: A One-Stop Large-Scale Graph Computing System from Alibaba | 一站式图计算系统
* [OpenXRay/xray-16](https://github.com/OpenXRay/xray-16) - Improved version of the X-Ray Engine, the game engine used in the world-famous S.T.A.L.K.E.R. game series by GSC Game World. Join OpenXRay! ;)
* [rathena/rathena](https://github.com/rathena/rathena) - rAthena is an open-source cross-platform MMORPG server.
* [laverdet/node-fibers](https://github.com/laverdet/node-fibers) - Fiber/coroutine support for v8 and node.
* [tensorflow/minigo](https://github.com/tensorflow/minigo) - An open-source implementation of the AlphaGoZero algorithm *(archived)*
* [tnodir/fort](https://github.com/tnodir/fort) - Fort Firewall for Windows
* [helio-fm/helio-sequencer](https://github.com/helio-fm/helio-sequencer) - Libre music sequencer for desktop and mobile platforms
* [nanocurrency/nano-node](https://github.com/nanocurrency/nano-node) - Nano is digital currency. Its ticker is: XNO and its currency symbol is: Ӿ
* [MuShibo/Micro-Wheeled_leg-Robot](https://github.com/MuShibo/Micro-Wheeled_leg-Robot) - 全球最小的桌面级双轮腿机器人！
* [microsoft/GW-BASIC](https://github.com/microsoft/GW-BASIC) - The original source code of Microsoft GW-BASIC from 1983 *(archived)*
* [jurplel/qView](https://github.com/jurplel/qView) - Practical and minimal image viewer
* [Anttwo/SuGaR](https://github.com/Anttwo/SuGaR) - [CVPR 2024] Official PyTorch implementation of SuGaR: Surface-Aligned Gaussian Splatting for Efficient 3D Mesh Reconstruction and High-Quality Mesh Rendering
* [zjhellofss/KuiperInfer](https://github.com/zjhellofss/KuiperInfer) - 校招、秋招、春招、实习好项目！带你从零实现一个高性能的深度学习推理库，支持大模型 llama2 、Unet、Yolov5、Resnet等模型的推理。Implement a high-performance deep learning inference library step by step
* [sbarex/QLMarkdown](https://github.com/sbarex/QLMarkdown) - macOS Quick Look extension for Markdown files.
* [alicevision/AliceVision](https://github.com/alicevision/AliceVision) - 3D Computer Vision Framework
* [asb2m10/dexed](https://github.com/asb2m10/dexed) - DX7 FM multi plaform/multi format plugin
* [kth-competitive-programming/kactl](https://github.com/kth-competitive-programming/kactl) - KTH Algorithm Competition Template Library (... eller KTHs AC-tillverkande lapp)
* [huxingyi/dust3d](https://github.com/huxingyi/dust3d) - Dust3D is a cross-platform 3D modeling software that makes it easy to create low poly 3D models for video games, 3D printing, and more.
* [petercorke/robotics-toolbox-python](https://github.com/petercorke/robotics-toolbox-python) - Robotics Toolbox for Python
* [google/robotstxt](https://github.com/google/robotstxt) - The repository contains Google's robots.txt parser and matcher as a C++ library (compliant to C++11).
* [isledecomp/isle](https://github.com/isledecomp/isle) - A decompilation of LEGO Island (1997)
* [nihui/waifu2x-ncnn-vulkan](https://github.com/nihui/waifu2x-ncnn-vulkan) - waifu2x converter ncnn version, runs fast on intel / amd / nvidia / apple-silicon GPU with vulkan
* [RainerKuemmerle/g2o](https://github.com/RainerKuemmerle/g2o) - g2o: A General Framework for Graph Optimization
* [ihhub/fheroes2](https://github.com/ihhub/fheroes2) - fheroes2 is a recreation of Heroes of Might and Magic II game engine
* [clab/dynet](https://github.com/clab/dynet) - DyNet: The Dynamic Neural Network Toolkit
* [banach-space/llvm-tutor](https://github.com/banach-space/llvm-tutor) - A collection of out-of-tree LLVM passes for teaching and learning
* [HowardHinnant/date](https://github.com/HowardHinnant/date) - A date and time library based on the C++11/14/17 <chrono> header
* [epasveer/seer](https://github.com/epasveer/seer) - Seer - a gui frontend to gdb
* [huxingyi/autoremesher](https://github.com/huxingyi/autoremesher) - Automatic quad remeshing tool
* [ungive/discord-music-presence](https://github.com/ungive/discord-music-presence) - The Discord music status that works with any media player
* [alexkay/spek](https://github.com/alexkay/spek) - Acoustic spectrum analyser
* [appjs/appjs](https://github.com/appjs/appjs) - (Deprecated!) SDK on top of nodejs to build desktop apps using HTML5/CSS/JS
* [adafruit/Adafruit_NeoPixel](https://github.com/adafruit/Adafruit_NeoPixel) - Arduino library for controlling single-wire LED pixels (NeoPixel, WS2812, etc.)
* [yandex/perforator](https://github.com/yandex/perforator) - Perforator is a cluster-wide continuous profiling tool designed for large data centers
* [snort3/snort3](https://github.com/snort3/snort3) - Snort++
* [pytorch/ELF](https://github.com/pytorch/ELF) - ELF: a platform for game research with AlphaGoZero/AlphaZero reimplementation *(archived)*
* [google/lmctfy](https://github.com/google/lmctfy) - lmctfy is the open source version of Google’s container stack, which provides Linux application containers. *(archived)*
* [mortbopet/Ripes](https://github.com/mortbopet/Ripes) - A graphical processor simulator and assembly editor for the RISC-V ISA
* [tomlooman/EpicSurvivalGame](https://github.com/tomlooman/EpicSurvivalGame) - Third-person Survival Game for Unreal Engine (Sample Project)
* [anthwlock/untrunc](https://github.com/anthwlock/untrunc) - Restore a truncated mp4/mov. Improved version of ponchio/untrunc
* [AcademySoftwareFoundation/openvdb](https://github.com/AcademySoftwareFoundation/openvdb) - OpenVDB - Sparse volume data structure and tools
* [keshavbhatt/whatsie](https://github.com/keshavbhatt/whatsie) - Feature rich WhatsApp Client for Desktop Linux
* [tpoechtrager/osxcross](https://github.com/tpoechtrager/osxcross) - MacOS Cross-Toolchain for Linux and *BSD
* [HKUST-Aerial-Robotics/Fast-Planner](https://github.com/HKUST-Aerial-Robotics/Fast-Planner) - A Robust and Efficient Trajectory Planner for Quadrotors
* [acidanthera/WhateverGreen](https://github.com/acidanthera/WhateverGreen) - Various patches necessary for certain ATI/AMD/Intel/Nvidia GPUs
* [KwaiAppTeam/KOOM](https://github.com/KwaiAppTeam/KOOM) - KOOM is an OOM killer on mobile platform by Kwai.
* [Kitt-AI/snowboy](https://github.com/Kitt-AI/snowboy) - Future versions with model training module will be maintained through a forked version here: https://github.com/seasalt-ai/snowboy
* [davidrmiller/biosim4](https://github.com/davidrmiller/biosim4) - Biological evolution simulator
* [GarageGames/Torque3D](https://github.com/GarageGames/Torque3D) - MIT Licensed Open Source version of Torque 3D from GarageGames
* [directvt/vtm](https://github.com/directvt/vtm) - Text-based desktop environment
* [google-ai-edge/LiteRT](https://github.com/google-ai-edge/LiteRT) - LiteRT, successor to TensorFlow Lite. is Google's On-device framework for high-performance ML & GenAI deployment on edge platforms, via efficient conversion, runtime, and optimization
* [nodejs/nan](https://github.com/nodejs/nan) - Native Abstractions for Node.js
* [nihui/opencv-mobile](https://github.com/nihui/opencv-mobile) - The minimal opencv for Android, iOS, ARM Linux, Windows, Linux, MacOS, HarmonyOS, WebAssembly, watchOS, tvOS, visionOS
* [facebook/mcrouter](https://github.com/facebook/mcrouter) - Mcrouter is a memcached protocol router for scaling memcached deployments.
* [maestron/botnets](https://github.com/maestron/botnets) - This is a collection of #botnet source codes, unorganized. For EDUCATIONAL PURPOSES ONLY
* [jmoon018/PacVim](https://github.com/jmoon018/PacVim)
* [intel/pcm](https://github.com/intel/pcm) - Intel® Performance Counter Monitor (Intel® PCM)
* [pytorch/glow](https://github.com/pytorch/glow) - Compiler for Neural Network hardware accelerators *(archived)*
* [armory3d/armory](https://github.com/armory3d/armory) - 3D Engine with Blender Integration
* [randombit/botan](https://github.com/randombit/botan) - Cryptography Toolkit
* [snes9xgit/snes9x](https://github.com/snes9xgit/snes9x) - Snes9x - Portable Super Nintendo Entertainment System (TM) emulator
* [ksnip/ksnip](https://github.com/ksnip/ksnip) - ksnip the cross-platform screenshot and annotation tool
* [mit-biomimetics/Cheetah-Software](https://github.com/mit-biomimetics/Cheetah-Software)
* [std-microblock/breeze-shell](https://github.com/std-microblock/breeze-shell) - An alternative Windows context menu, and more.
* [bytedance/lightseq](https://github.com/bytedance/lightseq) - LightSeq: A High Performance Library for Sequence Processing and Generation *(archived)*
* [taylorconor/tinytetris](https://github.com/taylorconor/tinytetris) - 80x23 terminal tetris!
* [root-project/root](https://github.com/root-project/root) - The official repository for ROOT: analyzing, storing and visualizing big data, scientifically
* [openjdk/jfx](https://github.com/openjdk/jfx) - JavaFX mainline development
* [SpacehuhnTech/WiFiDuck](https://github.com/SpacehuhnTech/WiFiDuck) - Wireless keystroke injection attack platform
* [MiSTer-devel/Main_MiSTer](https://github.com/MiSTer-devel/Main_MiSTer) - Main MiSTer binary and Wiki
* [derceg/explorerplusplus](https://github.com/derceg/explorerplusplus) - Explorer++ is a lightweight and fast file manager for Windows
* [pafuhana1213/KawaiiPhysics](https://github.com/pafuhana1213/KawaiiPhysics) - KawaiiPhysics : Simple Bone Physics for UnrealEngine 4 & 5
* [OvenMediaLabs/OvenMediaEngine](https://github.com/OvenMediaLabs/OvenMediaEngine) - OvenMediaEngine (OME) is a Sub-Second Latency Live Streaming Server with Large-Scale and High-Definition. #WebRTC #LLHLS
* [Genivia/ugrep](https://github.com/Genivia/ugrep) - 🔍 ugrep 7.8 file pattern searcher -- a user-friendly, faster, more capable grep replacement. Includes a TUI, Google-like Boolean search with AND/OR/NOT, fuzzy search, hexdumps, searches (nested) archives (zip, 7z, tar, pax, cpio), compressed files (gz, Z, bz2, lzma, xz, lz4, zstd, brotli), pdfs, docs, and more
* [ErrorFlynn/ytdlp-interface](https://github.com/ErrorFlynn/ytdlp-interface) - Windows graphical interface for yt-dlp, designed as a simple YouTube downloader
* [jwise/HoRNDIS](https://github.com/jwise/HoRNDIS) - Android USB tethering driver for Mac OS X
* [homenc/HElib](https://github.com/homenc/HElib) - HElib is an open-source software library that implements homomorphic encryption. It supports the BGV scheme with bootstrapping and the Approximate Number CKKS scheme. HElib also includes optimizations for efficient homomorphic evaluation, focusing on effective use of ciphertext packing techniques and on the Gentry-Halevi-Smart optimizations.
* [horsicq/DIE-engine](https://github.com/horsicq/DIE-engine) - DIE engine
* [HailToDodongo/pyrite64](https://github.com/HailToDodongo/pyrite64) - N64 Game-Engine and Editor using libdragon & tiny3d
* [amov-lab/Prometheus](https://github.com/amov-lab/Prometheus) - Open source software for autonomous drones.
* [mbasso/asm-dom](https://github.com/mbasso/asm-dom) - A minimal WebAssembly virtual DOM to build C++ SPA (Single page applications)
* [jlblancoc/nanoflann](https://github.com/jlblancoc/nanoflann) - nanoflann: a C++11 header-only library for Nearest Neighbor (NN) search with KD-trees
* [nodejs/node-addon-api](https://github.com/nodejs/node-addon-api) - Module for using Node-API from C++
* [aws/aws-sdk-cpp](https://github.com/aws/aws-sdk-cpp) - AWS SDK for C++
* [charto/nbind](https://github.com/charto/nbind) - :sparkles: Magical headers that make your C++ library accessible from JavaScript :rocket:
* [wichtounet/thor-os](https://github.com/wichtounet/thor-os) - Simple operating system in C++, written from scratch
* [vygr/ChrysaLisp](https://github.com/vygr/ChrysaLisp) - Parallel OS, with GUI, Terminal, OO Assembler, Class libraries, C-Script compiler, Lisp interpreter and more...
* [gigablast/open-source-search-engine](https://github.com/gigablast/open-source-search-engine) - Nov 20 2017 -- A distributed open source search engine and spider/crawler written in C/C++ for Linux on Intel/AMD. From gigablast dot com, which has binaries for download. See the README.md file at the very bottom of this page for instructions.
* [facebook/CacheLib](https://github.com/facebook/CacheLib) - Pluggable in-process caching engine to build and scale high performance services
* [Bareflank/hypervisor](https://github.com/Bareflank/hypervisor) - lightweight hypervisor SDK written in C++ with support for Windows, Linux and UEFI
* [enewhuis/liquibook](https://github.com/enewhuis/liquibook) - Modern C++ order matching engine
* [cabinpkg/cabin](https://github.com/cabinpkg/cabin) - C/C++ package manager and build system, inspired by Cargo
* [meganz/sdk](https://github.com/meganz/sdk) - MEGA C++ SDK
* [pegasusTrader/PandoraTrader](https://github.com/pegasusTrader/PandoraTrader) - 高频量化交易平台 C++ Trade Platform for quant developer 【浮生着甚苦奔忙，量化之路阻且长。 行行代码凝心血，十年辛苦不寻常】
* [CopernicaMarketingSoftware/PHP-CPP](https://github.com/CopernicaMarketingSoftware/PHP-CPP) - Library to build PHP extensions with C++
* [ucbrise/confluo](https://github.com/ucbrise/confluo) - Real-time Monitoring and Analysis of Data Streams
* [facebookarchive/Flicks](https://github.com/facebookarchive/Flicks) - A unit of time defined in C++. *(archived)*
* [open-telemetry/opentelemetry-cpp](https://github.com/open-telemetry/opentelemetry-cpp) - The OpenTelemetry C++ Client
* [lean-dojo/LeanCopilot](https://github.com/lean-dojo/LeanCopilot) - LLMs as Copilots for Theorem Proving in Lean
* [LemonOSProject/LemonOS](https://github.com/LemonOSProject/LemonOS) - The Lemon Operating System
* [tensorflow/community](https://github.com/tensorflow/community) - Stores documents used by the TensorFlow developer community *(archived)*
* [graphql/libgraphqlparser](https://github.com/graphql/libgraphqlparser) - A GraphQL query parser in C++ with C and C++ APIs *(archived)*
* [cocaine/cocaine-core](https://github.com/cocaine/cocaine-core) - An open platform to build your own PaaS clouds.
* [ErisBlastar/cplusequality](https://github.com/ErisBlastar/cplusequality) - Feminist Software Foundation C+=, a new language for us feminists
* [standardese/standardese](https://github.com/standardese/standardese) - A (work-in-progress) nextgen Doxygen for C++
* [pmed/v8pp](https://github.com/pmed/v8pp) - Bind C++ functions and classes into V8 JavaScript engine
* [nieklinnenbank/FreeNOS](https://github.com/nieklinnenbank/FreeNOS) - FreeNOS (Free Niek's Operating System) is an experimental microkernel based operating system for learning purposes written in C++. You may use the code as you wish under the terms of the GPLv3.
* [swoole/phpx](https://github.com/swoole/phpx) - C++ wrapper for Zend API
* [ktock/container2wasm](https://github.com/ktock/container2wasm) - Container to WASM converter. Moved to https://github.com/container2wasm/container2wasm
