# Go lessons

## Goal 

The goal of this repository is an organization of Go examples on various Go topics.
We hope it can be used in several ways:
- as an aid for live Go lessons and live Go game commentaries,
- as a source of a standard vocabulary for discussing Go principles,
- as a way to crowd-sources high quality Go lessons,
- as a stand-alone Go study resoursce (a book?).

## Audience

- Go players that want to learn from all levels.
- Go teachears that what to scale up spreading of Go knowledge in an organized manner.

## Secret sauce: automation and SGF lessons

Given a Go principle, it is often hard to find negative or positive examples. 
However, it is _much easier_ for a Go teacher to indentify a principle that applies to a given position.

Because of that we will not try to invent positions for a given lesson topic.
Instead we will encourage teachers to refer to Go principles in SGFs comments using hash-tags.
E.g. a teacher could write in an SGF comment '#attack-from-a-distance'.
We will use an automated tool to accumulate all the Go positions for a given tag and render them as diagrams as examples for that Go principle.

In other words, to add a diagram, a teacher just needs to make a comment tagging a specific principle and upload the SGF.
This way we hope to grow the lessons quickly and outsource the example and principle production to Go teachers.

## Tags

When discussing some Go topics during a lesson or a game commentary, a teacher often a comment he made already somewhere else in their life.
This could be a cue for tagging.
Whenever we see such a recurring comments, an example position could be tagged and through that proposed as a principle.

We will need other mechanism to add information to the last move on an example position.
E.g.: whether the principle was applied correctly or not, whether the move was good or not, etc.
It will take a while and some experinence to distill a set of good tags and mechanism to be used for a lesson creation.

It is not essential to get the tag names exactly since the tool will allow tag renaming, ignoring and merging.
Some bad tags: #ai-move, #good-move, #reading, #life-and-death
Some ok tags: #attack-from-a-distance, #play-from-outside-not-inside, #nakade

## Effective learning

Organization of Go examples is not the end.
We aim to provide good and effective Go lessons.
We describe how to make a good lessons in [effective-learning.md](effective-learning.md).

## Inspirational books

There are some Go books that inspired me to this project:
- [Fundamental Principles of Go](https://www.goodreads.com/en/book/show/1485651.Fundamental_Principles_Of_Go)
- [Lessons in the Fundamentals of Go](https://www.goodreads.com/book/show/1241950.Lessons_in_the_Fundamentals_of_Go)

If you know other similar books, please let me know!

## Language choice

The main advantage of english language allows faster creation of the content by allowing a wider family of strong players to contribute.
The main advantage of other languages allows wider reading audience, especially children to access it.
We will start with english, since we need to have a content first.
