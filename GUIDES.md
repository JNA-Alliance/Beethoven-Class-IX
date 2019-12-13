# Guides
---
This guide should help you to use this repository.

# Creating your Material
Material that is published here should be at least useful, helpful, insightful to read.
It can be anything! Your notes, previous exam questions, answers, etc.

## The File
The file must either be a Plain-Text Document (`.txt`) or a Markdown Formatted Text (`.md`).
Markdown is **highly recommended** because it adds a lot of features that Plain-Text Document don't have such as formatting!

## The Workflow
You're advised to use **Sublime Text 3** or **Visual Studio Code** as your editor to create and manipulate the file as it is faster, has a dark theme, and supports Extenstions!
Clone this repository locally and on your editor, go to `File > Open Folder` and select the locally cloned repository.
You're now one step away from getting started!

## The Structure
The file must be highly organized. It is recomended that a new file is created for each topic.
Place the files on the apropriate directory as it will help you and others to find the file in the future.

Inside the `Materi` folder, lies all the materials. One level below `Materi` is the subject folder. One level below the subject folder is `Bahan Ujian`, `Soal Ujian`, and `Catatan` folder. Where all materials are sorted accordingly.

- `Bahan Ujian` folder will store all files related to the test. File is then named `<Test Title>.md` such as `Semester I.md` and `Mid II.md`
- `Soal Ujian` folder will store all files with the previous exam questions along with the anser. The file is named with the same system as `Bahan Ujian`'s.

## The Formatting
Unless it is a Plain-Text Document, the material must be formatted using Markdown for **DILLINGER.IO** (General Markdown) instead of for GitHub as materials are printed from dillinger.io and not from GitHub.
Each material must start with a title (H1), followed by a single horizontal line. Then you may add the contents or add attributions before the content.
**NOTE**: Try to make the materials compatible with the Mock Test feature if possible. Anything that is **bold** will be flagged as an answer and thus will be replaced with dots as a placeholder.

# Mock Test
Mock test is a new feature to help users memorize answers and test the user's knowledge.

## How it works?
A pure PHP parser will parse the file for any bolded text and replace them with dots. Simple.

## Future plan
There's a plan to make it work like **Quizlet**. Why don't we just use Quizlet? Quizlet is highly limited to terms and definitions. As this Mock Test can cover pretty much anything.