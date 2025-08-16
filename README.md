# OV1115 Notes - Term 1

## Description

This is a repository for notes made teaching on the OV1115 module at CSGUoL.

## Introduction

The main tex file for was created in December 2023 by Benjamin Evans.

Primarily to avoid having to read my own handwriting when reviewing solutions
and going through longer solutions for students during drop-in sessions.

## :writing_hand: :dizzy: Style guidelines

- Line limit of 80 characters. You can normally add an option to show this limit
  in your editor. This is primarily here to make it easier to review changes
  made. It makes each document taller, but collaboration easier.

## Usage

The notes use the `exam` class and the `ov1115_notes_style` package. This
package is adapted from the OV1114 worksheet package (also created by BE for
personal use).

This class takes options including:

- `numSolsPos` and `workedSols`

- `workedSols` - Prints full worked solutions to each question (entered manually
  inside each question file)

These are included in the event that one wished to produce a student version of
this document that did not contain worked solutions.

## Potential future plans

1. Use these notes to replace the existing OV1115 booklet.

   Advantages:

   - Would make it clearer for students and avoid having pages of corrections
     that can be a bit messy (particularly for W7)

   - Would include solutions so it's easier for educators to review

   Disadvantages:

   - Time consuming to add in all questions

   I have left this as a set of notes and have no reason to develop it further,
   but the functionality set up so far could easily be expanded upon for this
   purpose.

1. Add makefiles to auto-compile with the different class options

   This only makes sense to implement if one needs to create different versions
   of these notes, but is easy to do if required.
