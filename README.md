# sortl
A simple but powerful Tasklist Management Method.

<!-- toc -->
- [sortl](#sortl)
  - [Demo](#demo)
  - [sortl cycle](#sortl-cycle)
  - [How to sort](#how-to-sort)
    - [Text Editor](#text-editor)
    - [Browser](#browser)
    - [Excel (Windows)](#excel-windows)
    - [Console (Windows)](#console-windows)
    - [Console (Linux/MacOS)](#console-linuxmacos)

## Demo
For example, I will explain with 'tasks about writing a book'.

Compare 'After' with 'Before'.

- Before) [Original Tasklist](01_tasklist_enumerate.md). (Not Readable)
- After ) [Tasklist following sortl](03_tasklist_sort.md). (Readable!)

With `sortl`, you can get the readable tasklist easily.

## sortl cycle
`sortl` consists of 3-step work flow simply.

- 1: Enumerate ... Write tasks with **1-task 1-line**.
- 2: Prepend ...  Write **prefix** to each line for sorting.
- 3: Sort ... **Sort lines** with some tool.

All you need to do is to enumerate your tasks, prepend prefixes, and sort lines repeatedly. In other words, **follow the Sortl Cycle!**

About demo tasklist, like this:

- 1: [Enumerate](01_tasklist_enumerate.md)
- 2: [Prepend](02_tasklist_prepend.md)
- 3: [Sort](03_tasklist_sort.md)

## How to sort
There are various ways to sort lines.

### Text Editor
- Enumerate: To your text editor.
- Prepend: To each line of the ediotor.
- Sort: Use the editor's function, extension or external command execution to call sorting.

### Browser
- Enumerate: To the text area on your browser.
- Prepend: To each line of the text area.
- Sort: Use an online sorter.
  - Ex1. [Sorter](https://sortl.github.io/sortl/) - very simple sorter on this github pages.
  - Ex2. [Online Sort, Reformat or Clean Your List](https://www.online-utility.org/text/sort.jsp)

### Excel (Windows)
- Enumerate: To cells.
- Prepend: To each cell.
- Sort: Move to the upper cell and Click `Home > Sort&Filter > Sort A to Z`.

### Console (Windows)
- Enumerate: to the text file.
- Prepend: to each line of the file.
- Sort: Do `sort yourlist.txt /o yourlist.txt`

### Console (Linux/MacOS)
- Enumerate: to the text file.
- Prepend: to each line of the file.
- Sort: Do `sort yourlist.txt -o yourlist.txt`
