!["Two Original Key Encryption"](./Documentation/LOGO%20PANJANG.png?raw=true "Two Original Key Encryption")

<p align="center">
    <a href="https://github.com/rahmatagungj/toke/releases/latest"><img alt="undefined" src="https://img.shields.io/github/v/release/rahmatagungj/toke.svg?style=popout"></a>
    <a href="https://github.com/rahmatagungj/toke/releases/download/v.1.4/TOKE.exe" target="_blank"><img alt="undefined" src="https://badgen.net/badge/Download/Windows/?color=blue&icon=windows&label"></a>
</p>

## Table Of Content
- [About](#about)
- [How does it work?](#how-does-it-work-)
- [Supported file types](#supported-file-types)
- [Extension](#extension)
    + [Regarding TL1E and TL2E](#regarding-tl1e-and-tl2e)
- [Application](#application)
    + [Requirements](#requirements)
    + [Features](#features)
    + [Screenshot](#screenshot)
- [Wiki](#wiki)
- [Author](#author)

## About [![start with about](https://img.shields.io/badge/start%20with-about-brightgreen.svg?style=flat)](https://github.com/rahmatagungj/toke)
**TOKE** (*Two Original Key Encryption*) is a security method through encryption of data in the form of numbers and characters, this system uses a mathematical algorithm that can be used to secure certain messages. This service can convert ordinary messages in human language and files into more secure data.

## How does it work?
The message files that enter the system will be converted into 2 files containing the message keys, the 2 files have different contents (in the form of numbers and characters).

!["How TOKE System Works"](./Documentation/flow.jpg?raw=true "TOKE Algorithm Works")

## Supported file types
There are several types supported by the TOKE system, the following are file types that are supported:

No | Type | Status
--- | --- | ---
1 | `TXT` | **YES**
2 | `HTML` | **YES**
3 | `PHP` | **YES**
4 | `CSS` | **YES**
5 | `JS` | **YES**
6 | `JSX` | **YES**
7 | `XML` | **YES**
8 | `JSON` | **YES**
9 | `PY` | **YES**
10 | `LUA` | **YES**

The TOKE system can encrypt all files of any text type, but does not support files such as docx, xls and ppt.

## Extension
Users who will run the TOKE system will get a program with an .EXE extension and an encrypted message file will produce 2 files with the extension .TL1E and .TL2E.

#### Regarding TL1E and TL2E
TL1E and TL2E are extensions of files containing encrypted message files, TL1E is the first file containing the first security data and TL1E is the second file containing the second security data.

> **TL1E** is TOKE Layer 1 Encryption.

> **TL2E** is TOKE Layer 2 Encryption.

Both of these files have contents in the form of encrypted data where each file has different contents, when these two files are merged and declared suitable, the message will be successfully decrypted.
When a user opens an encrypted message file, the user must have 2 files that contain message data, namely TL1E and TL2E. If the data from TL1E and TL2E match and can be accepted, a message file will appear in the TOKE application, but if there is a mismatch of data in the two files, the message cannot be decrypted.

# Application
In the version there is a CLI based application, namely versions 1 to 1.5, but in version 1.6 the application is released using a GUI display so that it is easier to use.

### Requirements
The TOKE application can run on the Windows operating system and there are several requirements, including:

No | Name | Version
--- | --- | ---
1 | Windows OS | 32bit
2 | Windows OS | 64bit
3 | Browser | latest

TOKE requires a browser as an intermediary for display with the system, some supported browsers such as Chrome and Edge.

### Features

|                            | 32 Bit  | 64 Bit |
| -------------------------- | :----------------: | :-------------: |
| Memory optimization           |         ✔️         |        ✔️        |
| Multi layer algorithm             |         ✔️         |        ✔️        |
|Additional user validation        |        ❌          |        ✔️        |
| Automatically checks for updates |         ✔️         |        ✔️        |
| Fast math operations   |         ✔️         |        ✔️        |

The TOKE application supports 32bit and 64bit system architectures, but on the 64bit version the TOKE application will run faster.

### Screenshot

| | |
| -------------------------- | :----------------: |
|<img src="./Documentation/ui_1.png"/>|<img src="./Documentation/ui_2.png"/> |
|<img src="./Documentation/ui_3.png"/>|<img src="./Documentation/ui_4.png"/> |
|<img src="./Documentation/ui_5.png"/>|

* This screenshot is taken based on the latest released application.

## Wiki
Do you ***need some help***? Check the articles from the <a href="https://github.com/rahmatagungj/toke/wiki">wiki</a>.

## Author
![Visitor](https://visitor-badge.laobi.icu/badge?page_id=rahmatagungj.toke) [![Linkedin Badge](https://img.shields.io/badge/-rahmatagungj-red?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rahmatagungj/)](https://www.linkedin.com/in/rahmatagungj/) [![Instagram Badge](https://img.shields.io/badge/-rahmatagungj-purple?style=flat-square&logo=instagram&logoColor=white&link=https://instagram.com/rahmatagungj/)](https://instagram.com/rahmatagungj) [![Gmail Badge](https://img.shields.io/badge/-rahmatagungj@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:rahmatagungj@gmail.com)](mailto:rahmatagungj@gmail.com)
