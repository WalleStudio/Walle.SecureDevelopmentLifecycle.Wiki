# Tool box

[✔] OPPO Already In Use 

[TOC]

## Secure Coding

### Find Bugs [IDE Integration] [✔] 

A  program which uses static analysis to look for bugs in Java code.  It is free software.

### DevSkim [IDE Integration]

https://github.com/Microsoft/DevSkim

###  Semmle CodeQL

> https://semmle.com/case-studies/semmle-microsoft-vulnerability-hunting
> https://lgtm.com/help/lgtm/getting-started
> https://lgtm.com/help/lgtm/analysis-faqs#which-languages-are-supported

CodeQL helps you explore code quickly to find and eradicate all variants of vulnerabilities before they become a problem.
By automating variant analysis, CodeQL enables product security teams to find zero-days and variants of critical vulnerabilities.

### Code Sight [IDE Integration]

https://www.youtube.com/watch?v=PR5g_1-MNkM

Integrate application security analysis seamlessly into your *IntelliJ, Eclipse, or Visual Studio IDE* with the Polaris Code Sight™ IDE plugin.  It can also provide some suggestions about the code. It's analysis rule can be updated with the  server.

![image-20200417145607668](C:\Users\FenghuiXu\AppData\Roaming\Typora\typora-user-images\image-20200417145607668.png)

>I have made contact with Code Sight production team in china , they will respond me ASAP about Android Studio .* 



### Coverity Static Analysis. [TFS Integration] [✔]

Identify critical quality defects and security vulnerabilities early in the SDL, when it’s least expensive to

remediate, with our comprehensive static analysis solution.

### Black Duck [OSS] [TFS Integration]

Detect and manage open source and third-party component risks in development and production with our industry-leading software composition analysis tools.


### WhiteSource-Bolt [OSS] [TFS Integration]

> https://bolt.whitesourcesoftware.com/full-solution/
> https://www.whitesourcesoftware.com/
> https://bolt.whitesourcesoftware.com/azure/

WhiteSource sends you immediate automatic alerts when:

- You add components with **known security vulnerabilities**
- **New security vulnerabilities** are discovered in components you’re using, you will even get alerts regarding historic versions you are not actively working on (unlike other tools, such as Black Duck Hub)
- **New fixes** are released for any of the components used in your software
- **Updates** are available of any of your software’s open source components





## Secure Testing 

### OPPO 慧眼分析平台 [✔]

[OPPO 慧眼分析平台](HuiYan.md)  

### Drozer [✔]

> https://labs.f-secure.com
>
> https://labs.f-secure.com/tools/drozer/

Comprehensive security and attack framework for Android.

[Drozer](https://labs.f-secure.com/assets/BlogFiles/mwri-drozer-user-guide-2015-03-23.pdf) is open source software, released under a BSD license and maintained by MWR Info Security. 
Drozer allows you to assume the role of an *Android app* and interact with other apps. It can do anything that an installed application can do, such as make use of Android’s Inter-Process Communication (IPC) mechanism and interact with the underlying operating system.

Drozer also helps to you to remotely exploit Android devices, by building malicious files or web pages that exploit known vulnerabilities. The payload that is used in these exploits is a rogue drozer agent that is essentially a remote administration tool. Depending on the permissions granted to the vulnerable app, drozer can install a full agent, inject a limited agent into the process using a novel technique or spawn a reverse shell.

### Android AFL [✔]

> http://lcamtuf.coredump.cx/afl

Fuzzing Android program with [american fuzzy lop (AFL)](http://lcamtuf.coredump.cx/afl/)

```android-afl ```is a modified version of AFL that supports fuzzing on Android, the SHM has been replaced with ASHMEM because of Android disable SHM in the kernel. Extra codes have been added in ```afl-gcc.c```, ```afl-as.c ```and ```afl-as.h``` to support arm arch. Android.mk has been added to support Android build system and ```llvm_mode```. Please refer to the [android-afl.patch](https://github.com/ele7enxxh/android-afl/blob/master/android-patch/afl-2.33b-android.patch) for more details.



### MFFA [✔]

>  https://github.com/fuzzing/MFFA

Media Fuzzing Framework for Android .

The main idea behind this project is to create corrupt but structurally valid media files, direct them to the appropriate software components in Android to be decoded and/or played and monitor the system for potential issues (i.e. system crashes) that may lead to exploitable vulnerabilities. Custom developed Python scripts are used to send the malformed data across a distributed infrastructure of Android devices, log the findings and monitor for possible issues, in an automated manner. The actual decoding of the media files on the Android devices is done using the Stage fright command line interface. The results are sorted out, in an attempt to find only the unique issues, using a custom built triage mechanism.

### libfuzzer [✔]

> https://llvm.org/docs/libfuzzer.html
>
> https://source.android.google.cn/devices/tech/debug/libfuzzer?hl=zh-cn

Fuzzing, which is simply providing potentially invalid, unexpected, or random data as an input to a program, is an extremely effective way of finding bugs in large software systems, and is an important part of the software development life cycle.

Android's build system supports fuzzing through the inclusion of [libFuzzer](http://llvm.org/docs/LibFuzzer.html) from the LLVM compiler infrastructure project project. ```LibFuzzer``` is linked with the library under test and handles all input selection, mutation, and crash reporting that occurs during a fuzzing session. LLVM's sanitizers are used to aid in memory corruption detection and code coverage metrics.


### Syzkaller [✔]

> https://github.com/google/syzkaller

syzkaller is an unsupervised coverage-guided kernel fuzzer.

###  Honggfuzz 

> https://github.com/google/honggfuzz

A security oriented, feedback-driven, evolutionary, easy-to-use fuzzer with interesting analysis options. 

**Android** - Android SDK/NDK. Also see [this detailed doc](https://github.com/google/honggfuzz/blob/master/docs/Android.md) on how to build and run it

###  Defensics Dynamic Analysis 

> old name: Codenomicon

Test running applications for common security weaknesses and vulnerabilities with our innovative dynamic analysis offerings, Seeker interactive application security testing and Defensics fuzz testing.



## Others Tools

###  OWASP Series

[FuzzingTools Suggested by OWASP](FuzzingTools.md) 

 [OWASP All Tools](OWASP.md) 

### MSRD

[MSRD](MSRD.md) 

### Threat Modeling Tools

 [Threat Modeling Tools](..\5. Threat modeling\Tools.md) 

## Concepts

- [Why Fuzzing?](./Concepts/Fuzzing-Basics.md)
- [OWASP Mobile Security](..\99.Concepts\OWASP.md) 

