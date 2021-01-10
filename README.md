!["Two Original Key Encryption"](./Documentation/LOGO%20PANJANG.png?raw=true "Two Original Key Encryption")
![Visitor](https://visitor-badge.laobi.icu/badge?page_id=rahmatagungj.toke) [![Linkedin Badge](https://img.shields.io/badge/-rahmatagungj-red?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rahmatagungj/)](https://www.linkedin.com/in/rahmatagungj/) [![Instagram Badge](https://img.shields.io/badge/-rahmatagungj-purple?style=flat-square&logo=instagram&logoColor=white&link=https://instagram.com/rahmatagungj/)](https://instagram.com/rahmatagungj) [![Gmail Badge](https://img.shields.io/badge/-rahmatagungj@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:rahmatagungj@gmail.com)](mailto:rahmatagungj@gmail.com)
## Table Of Content
- [About](#about)
- [How does it work?](#how-does-it-work-)
- [Supported characters](#supported-characters)
- [Extension](#extension)
    + [Regarding TL1E and TL2E](#regarding-tl1e-and-tl2e)
- [Notes](#notes)

## About 
**TOKE** (*Two Original Key Encryption*) is a security method through data encryption in the form of numbers and characters, this system uses a mathematical algorithm that can be used to secure certain messages. This service may convert ordinary messages in human language into more secure data.

## How does it work?
The messages entered to the system will be converted into 2 files containing the message keys, these 2 files have different contents (in the form of numbers and characters).

!["How TOKE System Works"](./Documentation/flow.png?raw=true "TOKE Algorithm Works")

## Supported characters
There are several types that are supported by the TOKE system, such as letters, numbers and symbols.

No | Type | Status
--- | --- | ---
1 | `Alphabet` | **YES**
2 | `Numeric` | **YES**
3 | `Symbol` | **YES**

There are models that cannot be done in this system, such as newlines and capital letters. (_I'm working on it_)

## Extension
Users who will run the TOKE system will get a program with the extension .EXE and an encrypted message will produce 2 files with the extension .TL1E and .TL2E.

#### Regarding TL1E and TL2E
TL1E and TL2E are extensions of files containing encrypted messages, TL1E is the first file that contains the first security data and TL1E is the second file containing the second security data.

> **TL1E** is TOKE Layer 1 Encryption.

> **TL2E** is TOKE Layer 2 Encryption.

Both of these files have contents in the form of encrypted data where each file has different contents, when these two files are merged and declared suitable, the message will be successfully decrypted.
When a user decrypts a message, the user must have 2 files containing message data, namely TL1E and TL2E. If the data from TL1E and TL2E match and can be received, a message will appear in the TOKE application, but if there is a data mismatch in the two files, the message cannot be translated.

## Notes
1. The TOKE application can only run on the windows platform.
