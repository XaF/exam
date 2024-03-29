> A more up to date version of this class is available on the website
> of the original author: https://math.mit.edu/~psh/#ExamCls
>
> This version is mostly including some modifications I needed at some
> point, that I did not push upstream since there was not git repository
> to make a pull request to. I am not the original author of this class,
> and I do not intend to maintain it. I am just sharing it in case it
> might be useful to someone else.


This is version 2.402 of the exam document class, dated February 10, 2015.

The exam document class, together with its user's guide examdoc.tex,
attempts to make it easy for even a LaTeX novice to prepare exams.
Simple commands are provided to:

1. Create questions, parts of questions, subparts of parts, and
subsubparts of subparts, all with optional point values.

2. Create a grading table, indexed either by question number (listing
each question and the total possible points for that question) or by
page number (listing each page with points and the total possible
points for that page).  A grading table can cover the entire exam or
just a part of the exam.

3. Create headers and footers that are each specified in three parts:
One part to be left justified, one part to be centered, and one part
to be right justified.

4. Have headers and/or footers that are different on the first page of
the exam, different on the last page of the exam, and that vary
depending on whether the page number is odd or even, or on whether the
current page continues a question from a previous page, or on whether
the last question on the current page continues onto the following
page.

5. Have multiple line headers and/or footers, and to increase the part
of the page devoted to headers and/or footers to allow for this.

6. Include solutions and have these solutions either printed or
ignored (or replaced automatically by space in which the students can
write their answers) depending on a single command.

7. Change the words that are inserted by the document class (for,
e.g., point values, or table headings), so that they can be adapted to
personal taste and/or languages other than English.


The user's guide examdoc.tex attempts to explain all of the
possibilities in a readable way, with many specific examples.

--------------------------------------------------------------------

This work may be distributed and/or modified under the conditions of
the LaTeX Project Public License, either version 1.3 of this license
or (at your option) any later version.
