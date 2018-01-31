# sortl
A simple but powerful Tasklist Management Method.

**WIP.**

<!-- toc -->
- [sortl](#sortl)
  - [Demo](#demo)
  - [sortl Work Flow](#sortl-work-flow)
- [How to sort](#how-to-sort)
  - [Text editor](#text-editor)
  - [Browser](#browser)
  - [Excel (Windows)](#excel-windows)
  - [Console (Windows)](#console-windows)
  - [Console (Linux/MacOS)](#console-linuxmacos)

## Demo
Compare belows.

- Before) Original tasklist (Not Readable)
- After ) sortled tasklist (Readable!)

With `sortl`, you can get the readable tasklist easily.

## sortl Work Flow
`sortl` consists of 3-step work flow.

- 1: Enumerate ... Write tasks to a file as **1-task 1-line**.
- 2: Prepend ...  Write **prefix** to each line for sorting.
- 3: Sort ... Sort lines with some tool.

All you need to do is to enumerate your tasks, prepend prefixes, and sort lines repeatedly. In other words, **follow the sortl Cycle!**.

# How to sort
There are various ways to sort lines.

## Text editor
- Enumerate: To your text editor.
- Prepend: To each line of the ediotor.
- Sort: Use the editor's function, extension or external command execution to call sorting.

## Browser
- Enumerate: To the text area on your browser.
- Prepend: To each line of the text area.
- Sort: Use an online sorter.
  - Ex1. [Sorter](https://sortl.github.io/sortl/) - very simple sorter on this github pages.
  - Ex2. [Online Sort, Reformat or Clean Your List](https://www.online-utility.org/text/sort.jsp)

## Excel (Windows)
- Enumerate: To cells.
- Prepend: To each cell.
- Sort: Move to the upper cell and Click `Home > Sort&Filter > Sort A to Z`.

## Console (Windows)
- Enumerate: to the text file.
- Prepend: to each line of the file.
- Sort: Do `sort yourlist.txt /o yourlist.txt`

## Console (Linux/MacOS)
- Enumerate: to the text file.
- Prepend: to each line of the file.
- Sort: Do `sort yourlist.txt -o yourlist.txt`
