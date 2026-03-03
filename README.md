# mp3-tag-reader-editor
A command-line MP3 Tag Reader and Editor written in C that reads and modifies ID3v2 metadata using low-level file handling, structures, and pointer manipulation.


# 🎵 MP3 Tag Reader & Editor (C)

A command-line application written in **C programming language** to read and edit ID3v2 metadata tags from MP3 files.

This project demonstrates strong understanding of:

- Low-level file handling
- Binary file processing
- Structures and pointers
- Command-line argument parsing
- Modular programming in C

---

## 📌 Project Description

MP3 files store metadata such as Title, Artist, Album, and Year inside ID3 tags.

This application:

✔ Reads ID3v2 header  
✔ Displays MP3 metadata  
✔ Edits selected tag fields  
✔ Handles errors safely  
✔ Works with binary file structures  

---

## 🛠️ Technologies Used

- C Programming
- GCC Compiler
- Linux Environment
- File Handling (`fopen`, `fread`, `fwrite`, `fseek`)
- Structures and Pointers

---
Usage:
create makefile
1. make

View MP3 Tags
./mp3 -v sample.mp3
🔹 Edit Title
./mp3 -e -t "New Title" sample.mp3
🔹 Edit Artist
./mp3 -e -a "New Artist" sample.mp3
🔹 Edit Album
./mp3 -e -A "New Album" sample.mp3
