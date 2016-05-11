# <center>**C++ Web Template Library Project**</center> 
**Software Requirements Specification** 
**Author**: Pedro Henrique 
**Contact**: ph.geekstuff@gmail.com 
**Document Name**: srs.md (Markdown)
**Document Version**: 0.1b (for Coimbra Engineering Institute) 
**Updated at**: May 10, 2016 
**GitHub**: https://github.com/phgeekstuff/wtl.git

### 1. History

| Date | Responsible | Description |
|---|---|---|
| May 7, 2016 | Pedro Henrique | First Specification. |
| May 10, 2016 | Pedro Henrique | Specifying **FR0005**.|
| May 11, 2016 | Pedro Henrique | .|

### 2. Overview
	
The goal of the project is to build and maintain a high-level abstraction for C/C++ developers to take advantage of all modern standards of web, such as: HTTP, HTML, CSS, JavaScript, SOAP and RESTFul web services, and so on. Also, the idea is to provide tools for easy migration of legacy code and apps to web/connected environment. 

### 3. Introduction

The goal of this document is to keep track of all requirements related to C++ Web Template Library Project. 

### 4. User Types

1. Developer
2. IT Analyst
3. UI/UX Designer

### 5. Functional Requirements

[**MUST**] **FR0001:** C++ Code Main Namespace   

All code written in C++ related to C++ Web Template Library must be in _"wtl"_ namespace.

[**MUST**] **FR0002:** HTML Integration

HTML tags of _wtl_ must start with "wtl:" prefix. It helps to avoid any problem with other technologies.

[**MUST**] **FR0003:** HTML Templates

All _wtl_ tags must start with "wtl:" prefix. It to helps avoid any problem with other technologies.

[**SHOULD**] **FR0004** STL code style is Preferred 

All types should be named or aliases following STL code common convention.

[**MUST**] **FR0005:** C++ Base Headers

Basic headers must be provide as following:

| Header Name | Description |
|-------------|-------------|
|<center>&lt;wtl&gt;</center> | Main types of _wtl_.|
|<center>&lt;wtlhttp&gt;</center>| Basic abstraction for HTTP.
|<center>&lt;wtlhtml&gt;</center> | Basic abstraction for HTML.|
|<center>&lt;wtlxml&gt;</center> | Basic abstraction for XML.|
|<center>&lt;wtljson&gt;</center> | Basic abstraction for JSON.|
|<center>&lt;wtlio&gt;</center> | Basic IO types which work over HTTP.|
|<center>&lt;wtlservice&gt;</center> | Basic types for Web Services.|
|<center>&lt;wtl&gt;</center> | .|


### 6. Non-Functional Requirements

[**MUST**] **NFR1000:** Legacy Code Compliance 

It must be compatible to ANSI C (at least C99) and C++98 languages. Supporting legacy code.

[**MUST**] **NFR1001:** Modern Code Compliance 

It must be compatible to C11 and Modern C++ (at least C++11) languages. Supporting modern code.

[**MUST**] **NFR1003:** Complete standard code 

It must support standard C/C++ code, and run in any platform that supports C/C++ standard code. 

[**MUST**] **NFR1004:** Runtime Deployment 

It must not require a specific framework despite web server and http handler modules (i.e. different to .net framework or jre).

[**MUST**] **NFR1005** Ansi C Compliance 

It must be coded in a way that can be integrated transparently to Ansi C Standard Library.

[**MUST**] **NFR1006** STL Compliance 

It must be coded in a way that can be integrated transparently to STL (Standard Template Library)

[**MUST**] **NFR1007**  Generic Programming is Preferred 

Generic Programming must be considered the main mindset behind wtl, considering C++ common sense.

[**SHOULD**] **NFR1008** Object Oriented Programming is the second choice 

Considering C++ common sense, Object Oriented Programming should be the second choice for coding. 

[**SHOULD**] **NFR1009** All common paradigms should be supported

Considering C++ common sense, Object Oriented Programming should be the second choice for coding. 

### 7. Glossary

* <em>**css**</em>: Cascade Stylesheet
* <em>**html**</em>: Hypertext Markup Language
* <em>**http**</em>: Hypertext Transfer Protocol 
* <em>**json**</em>: JavaScript Object Notation
* <em>**rest**</em>: Representational State Transfer
* <em>**soap**</em>: Simple Access Object Protocol
* <em>**stl**</em>: C++ Standard Template Library
* <em>**wtl**</em>: C++ Web Template Library

### 8. References

* [Markdown Markup Language](https://guides.github.com/features/mastering-markdown)
* [ISO C++](https://isocpp.org)
* [Stroustrup C++](http://www.stroustrup.com/C++.html)
* [ISO C Official Web Site](http://www.open-std.org/jtc1/sc22/wg14/)


