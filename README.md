# Baduk lectures

## Baduk principles

_Baduk principles_ are recurring themes often repeated in baduk lessons and game commentaries.
Exmples of principles include "attack from distance" or "play from outside, not inside".

## Goal 

This repository is intended as organization of baduk principles as lessons with examples.
We hope it can be used in several ways:
- as an aid for baduk lessons and game commentaries,
- as a stand-alone baduk book, 
- as a source of standard vocabulary for discussing baduk principles,
- as a way to crowd-sources high quality baduk lessons.

## Effective learning

When illustrating baduk principles, one needs to give both positive and negative examples of a given principle.
With only positive examples, while the illusion of teaching is achieved, the effectiveness is low.
With both positive and negative examples, the reader might feel more confused, but the effectiveness is high.
[This applies to almost every topic, where learning is without interaction](https://www.youtube.com/watch?v=eVtCO84MDj8).

## Example driven lessons

It is often hard to find negative or positive examples for a given principle. 
It is _much easier_ for the teacher to indentify which principles apply to a given position.

Because of that we will not try to invent positions for a given principle (or even invent principles).
Instead we will encourage teachers to refer to principles in SGFs comments and use a program to accumulate all the positions for a given principle.
This is the "secret souce" of this project.

## Lecture structure

Each principle will be a separate lecture with text and illustrated with example diagrams from multiple games.
Ideally the principle text should be precise enough and general enough that it applies to 
Whenever someone comments an example refer to this repo, position should find its way to this repo.

## Audience

Most of the content should be useful anywhere from 15k to few dan.
It would be nice if we could support beginner players that do not have a strong player around.
We aim to do that by providing a standardized vocabulary of priniclples that even DDK (both teacher and student) can refer to.
Principles will allow to disscuss the games using shared unified language, and will provide additional examples.
It will also help weaker players to formulate questions for stronger players refering to the examples.

We will make an effort to support young promising players.

## Automation

Example diagrams are rendered from positions in SGF files.
In order to add a diagram, a teacher just needs to make a comment referring a specific principle and upload the SGF.
An automated script will extract all the positions with principle references and add diagrams to the section on that principle.

## Reading ease

It is important that the reading is engaging. 
This can be achieved through various means:
 - personal stories about the author or
 - some context on where the example position came from or
 - motivational story about the value of the current lesson or
 - strong and colorful language.

The last technique is probably the most useful. 
"Lessons in the Fundamentals of Go" by Toshiro Kageyama is probably the finest example of these teaching techniques.

## Similar books

The only books that I know that are similar to this project are:
- [Fundamental Principles of Go](https://www.goodreads.com/en/book/show/1485651.Fundamental_Principles_Of_Go)
- [Lessons in the Fundamentals of Go](https://www.goodreads.com/book/show/1241950.Lessons_in_the_Fundamentals_of_Go)

If you know other similar books, please let me know!

## Additional content

Here I (Lukasz Lew) list other ideas that I know how to describe.

- Basic shapes without cuts in tactical sequnces starting from small number of stones, usually 1 black and 1 white. (as presented on LSG'22)
- Tsumego decomposition into stone and liberty visualization, tree management and shape familiarity as presented on LSG'22.
- Section on deliberate practice in baduk.

## Details on the principle lesson structure

Principle should have a memorable name, that one can easily refer to from memory.
The principle description should be as precise as possible.
We should try to move most of the example comment to the general description.

- Duza iloscia przykladow "Zly ruch bo nie podaza za pryncypium" z jak najmiejsza iloscia tekstu (tylko gdy potrzebna poprawka do pryncypium). 
- Duza ilosc przykladow "Znajdz ruch do danego pryncypium" jako zadania z rozwiazaniem (lub wieloma) na nastepnej stronie.
- W przykladach prawie nie trzeba czytac sekwencji.
- Opis relacji do innych pryncypiow.
- Wyjatki, zaskakujace ruchy, slawne ruchy.
- Przyklady gdzie wydaje sie ze pryncypium mozna zastosowac ale bylby to blad gdyz inne pryncypium jest wazniejsze. 
- Principle exercises: Find a move for a given principle. Answer on the next page or hidden, perhaps with a commentary or anecdote.

## Positive and negative examples contrast

There are multiple dimensions on which positive examples might be contrasted with negative ones:
- Fixed position: one position with several moves, discuss which principles apply to which moves and their relative strengths.
- Fixed principle: one principle with several positions and moves, discsuu to which moves this principle applies and how strongly.

To illustrate subtle diffeneces we can contrast:
- take two similar principles and disscuss multiple positions where both apply but one or other principle is dominating, leading to a different judgement.
- take two similar positions and disccuss how multiple principles apply differently.

## Exercises

- Variant 1: Move is given, the reader is to guess which principle was driving the move, which principle applied but has less importance.
- Variant 2: Several good and bad moves are given. The reader is to separate them and find principles for all of them.

## AI use

We will aim to use AI and use its moves as long as the reason for the move is reflected by the principle.
For principle illustation, we avoid moves that rely on tactical sequences.

## Readers

Wiekszosc tematow i przykladow nie wymaga czytania sekwencji wiec stosuje sie do bardzo szerokiej gamy odbiorcow.
Cel jest by 20k-3k mialo duzo radochy z czytania.

## Value

The unique value of this effort comes from several sources:

- Large number of examples and non-examples supporting each principle and reinforcing each others.
- Ease of adding new examples by any teacher (just a commented SGF).
- Exercises.
- Crowd sourcing.

## Language

The main advantage of english language allows faster creation of the book by allowing a wider family of strong players to contribute.
The main advantage of other languages allows wider reading audience, especially children to access it.
We will start with english, since we need to have a content first.
