# annot
annot.el - a global annotator/highlighter for GNU Emacs

### Introduction ###

[![Video: annot.el at work](http://img.youtube.com/vi/cCIetEFzdvY/0.jpg)](http://www.youtube.com/watch?v=cCIetEFzdvY)

`annot.el' is a general (and scalable) annotation manager that works on GNU
Emacs.  It lets you add/edit/remove annotations, highlights, or even annotated
images on any file and manages them for you.  All annotations are stored
separately for each annotated file and get reproduced when the file is opened
again. You can even store annotations on non-editable files.  Because annot
keeps track of md5 checksums of annotated files, annotations won't disappear
even when file names are changed.


### Installation ###

To install annot.el, download the file directly from
https://raw.githubusercontent.com/zefew/annot/master/src/annot.el, place it
under one of your load paths, and add the following line into your ~/.emacs,
~/.emacs.el or ~/.emacs.d/init.el:

> (require 'annot)

### Commands: ###

```
[C-x a]    -  add a new annotation/highlight or edit an existing annotation/highlight.
              You can also use [C-x C-a]. (annot-edit/add)
[C-x r]    -  remove annotation at point. (annot-remove)
[C-x w]    -  insert an image at point. (annot-add-image)
[C-x A]    -  convert the text within the currently active region into an annot text annotation. (annot-convert)
```

### Screenshot ###

![http://annot.googlecode.com/files/annot_example3.png](http://annot.googlecode.com/files/annot_example3.png)

### Change List ###

List of changes: https://github.com/zefew/annot/commits/master

