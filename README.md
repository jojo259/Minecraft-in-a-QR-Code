# Minecraft-in-a-QR-Code
it's literally just minecraft stored on paper.


**instructions**

print this or take a picture directly from the document (or just download the pictures I already have)

https://docs.google.com/document/d/1IEYuL2panN8EVcPyZixLzO42TQxTmX7FqdUAkxwV4vk/edit?usp=sharing

install required python packages through `pip install -r requirements.txt`
64-bit Python required
Microsoft Visual C++ 14.0 or greater required https://visualstudio.microsoft.com/visual-cpp-build-tools/

## Usage

```
$ download my software and run python3 catridge.py --directory "directory where pictures of each page are stored"
$ there will be an output file called "OUTPUT.txt" that results after you run the program
$ next type base64 OUTPUT.txt > keyfile.kdb
$ once you have done that u will have a binary file ready to be compiled
$ to run this file do chmod +x keyfile.kdb
$ finally type in ./keyfile.kdb 
$ u have officially ran minecraft from a piece of paper :D
```
