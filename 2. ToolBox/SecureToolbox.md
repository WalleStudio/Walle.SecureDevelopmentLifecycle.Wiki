# Secure Tool box

[TOC]

## Concepts

- [Why Fuzzing?](./Concepts/Fuzzing-Basics.md)
- [OWASP Mobile Security](./Concepts/OWASP.md)

## Secure Code Analysis 

### Coverity Static Analysis.

Identify critical quality defects and security vulnerabilities early in the SDL, when it’s least expensive to

remediate, with our comprehensive static analysis solution.

### Code Sight

Integrate application security analysis seamlessly into your *IntelliJ, Eclipse, or Visual Studio IDE* with the Polaris Code Sight™ IDE plugin.  It can also provide some suggestions about the code. It's analysis rule can be updated with the  server.

![image-20200417145607668](C:\Users\FenghuiXu\AppData\Roaming\Typora\typora-user-images\image-20200417145607668.png)

>I have made contact with Code Sight production team in china , they will respond me ASAP about Android Studio .* 

### Black Duck 

Detect and manage open source and third-party component risks in development and production with our industry-leading software composition analysis tools.

###  Defensics Dynamic Analysis

> old name: Codenomicon

Test running applications for common security weaknesses and vulnerabilities with our innovative dynamic analysis offerings, Seeker interactive application security testing and Defensics fuzz testing.

### Find Bugs 

A  program which uses static analysis to look for bugs in Java code.  It is free software.

## Pen-Test 

### Drozer

> https://labs.f-secure.com

[Drozer](https://labs.f-secure.com/assets/BlogFiles/mwri-drozer-user-guide-2015-03-23.pdf) is open source software, released under a BSD license and maintained by MWR Info Security. 
Drozer allows you to assume the role of an *Android app* and interact with other apps. It can do anything that an installed application can do, such as make use of Android’s Inter-Process Communication (IPC) mechanism and interact with the underlying operating system.

Drozer also helps to you to remotely exploit Android devices, by building malicious files or web pages that exploit known vulnerabilities. The payload that is used in these exploits is a rogue drozer agent that is essentially a remote administration tool. Depending on the permissions granted to the vulnerable app, drozer can install a full agent, inject a limited agent into the process using a novel technique or spawn a reverse shell.

### Android AFL

> http://lcamtuf.coredump.cx/afl



### MFFA

>  https://github.com/fuzzing/MFFA

Media Fuzzing Framework for Android .

The main idea behind this project is to create corrupt but structurally valid media files, direct them to the appropriate software components in Android to be decoded and/or played and monitor the system for potential issues (i.e system crashes) that may lead to exploitable vulnerabilities. Custom developed Python scripts are used to send the malformed data across a distributed infrastructure of Android devices, log the findings and monitor for possible issues, in an automated manner. The actual decoding of the media files on the Android devices is done using the Stagefright command line interface. The results are sorted out, in an attempt to find only the unique issues, using a custom built triage mechanism.

### libfuzzer

> https://llvm.org/docs/libfuzzer.html


### Mobile Security Framework

> http://github.com/mwrlabs


### Syzkaller

> https://github.com/google/syzkaller

###  Honggfuzz

> https://github.com/google/honggfuzz