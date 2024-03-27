~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  This concludes the Vim Tutor.  It was intended to give a brief overview of
  the Vim editor, just enough to allow you to use the editor fairly easily.
  It is far from complete as Vim has many many more commands.  Read the user
  manual next: ":help user-manual".

  For further reading and studying, this book is recommended:
        Vim - Vi Improved - by Steve Oualline
        Publisher: New Riders
  The first book completely dedicated to Vim.  Especially useful for beginners.
  There are many examples and pictures.
  See https://iccf-holland.org/click5.html

  This book is older and more about Vi than Vim, but also recommended:
        Learning the Vi Editor - by Linda Lamb
        Publisher: O'Reilly & Associates Inc.
  It is a good book to get to know almost anything you want to do with Vi.
  The sixth edition also includes information on Vim.

  This tutorial was written by Michael C. Pierce and Robert K. Ware,
  Colorado School of Mines using ideas supplied by Charles Smith,
  Colorado State University.  E-mail: bware@mines.colorado.edu.

  Modified for Vim by Bram Moolenaar.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


Opening Vim:

To open Vim, simply type vim in your terminal and press Enter.
Modes:

Vim has several modes. The most common ones are:
Normal mode: This is the default mode for navigating and manipulating text.
Insert mode: This is where you can type and edit text.
Visual mode: This is for selecting and manipulating blocks of text.
You can switch between modes using keyboard shortcuts.
Basic Navigation:

In Normal mode, you can navigate through the file using the following keys:
h: Move left.
j: Move down.
k: Move up.
l: Move right.
Alternatively, you can use arrow keys for navigation.
Basic Editing:

To enter Insert mode and start typing, press i.
To delete characters, move to the character you want to delete and press x.
To delete a whole line, press dd.
To save your changes and exit, press :wq and Enter.
Advanced Editing:

Vim has powerful editing commands:
Search and Replace: Press :/pattern to search for a pattern, and :%s/pattern/replace/g to replace all occurrences of a pattern with another string.
Copy and Paste: Use yy to copy a line, p to paste it below the cursor, and P to paste it above the cursor.
Undo and Redo: Press u to undo and Ctrl + r to redo.
Indentation: Use >> to indent a line, and << to unindent a line.
Exiting Vim:

To exit Vim without saving changes, press :q! and Enter.
To save changes and exit, press :wq and Enter.
To just save changes, press :w and Enter.
Customization:

Vim is highly customizable. You can customize it by editing your ~/.vimrc file.
Help:

Vim has comprehensive built-in documentation. You can access it by typing :help.
