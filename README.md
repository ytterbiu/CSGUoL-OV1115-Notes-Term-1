# OV1114-Worksheets

## Description

This is a repository for notes made teaching on the OV1115 module at CUoL.

## Introduction

The main tex file for was created in December 2023 by Benjamin Evans.

Primarily to avoid having to read my own handwriting when reviewing
solutions and going through longer solutions for students during drop-in
sessions.

## :writing_hand: :dizzy: Style guidelines

* Line limit of 80 characters. You can normally add an option to show this
limit in your editor. This is primarily here to make it easier to review
changes made. It makes each document taller, but collaboration easier.

## Usage

The notes use the `exam` class and the `ov1115_notes_style` package.
This package is adapted from the OV1114 worksheet package
(also created by BE for use at CUoL).

This class takes options including:

* `numSolsPos` and `workedSols`

* `workedSols` - Prints full worked solutions to each question (entered
manually inside each question file)

These are included in the event that one wished to produce a student version
of this document that did not contain worked solutions.

## Future plans

1. Use these notes to replace the existing OV1115 booklet.

    Advantages:

    * Would make it clearer for students and avoid having pages of corrections
    that can be a bit messy (particularly for W7)

    * Would include solutions so it's easier for educators to review

    Disadvantages:

    * Time consuming to add in all questions

    I have left this as a set of notes and have no reason to develop it further,
    but the functionality set up so far could easily be expanded upon for this
    purpose.

1. Add makefiles to auto-compile with the different class options

    This only makes sense to implement if one needs to create different versions of
    these notes, but is easy to do if required.

<!-- The `workedSols` option can be selected independently of the other three
options. If multiple options for the numerical solutions are selected only one
will be used, with the following heirarchy:
> `noSols` > `numSolsPre` > `numSolsPos`

The make file is set up to produce 4 pdfs, one for each option. Make sure the
lines
> `% \setcounter{printSols}{1}`
and
> `% \setcounter{printWorkedSols}{1}`
are commented out and that the counters have not been manually set if you wish
to use the make file.

Terminal commands for make file use (when in the directory of the main .tex
file)

> `make`

This will make the pdfs and all of the auxiliary files

> `make clean`

This will remove (clean) the auxiliary files, just leaving the four pdfs -->
