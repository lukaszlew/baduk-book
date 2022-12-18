# Go Principles

## Goal 

The goal of this repository is an organization of lessons on various Go principles.
We hope it can be used in several ways:
- as an aid for live Go lessons and live Go game commentaries,
- as a source of a standard vocabulary for discussing Go principles,
- as a way to crowd-sources high quality Go lessons,
- as a stand-alone Go study resoursce (a book?).

## Secret sauce: automation and SGF lessons

Given a Go principle, it is often hard to find negative or positive examples. 
It is _much easier_ for a teacher to indentify a principle that applies to a given position.

Because of that we will not try to invent positions for a given lesson topic.
Instead we will encourage teachers to refer to Go principles in SGFs comments using hash-tags.
E.g. Teacher could write in a comment #attack-from-a-distance.
We will use an automated tool to accumulate all the Go positions for a given tag and render them as diagrams at that Go principle lesson.

In other words, to add a diagram, a teacher just needs to make a comment tagging a specific principle and upload the SGF.
This way we hope to grow the lessons quickly and crowd-source the example and principle production to Go teachers.

## Tags

When discussing some Go topics on a lesson or game commentary, a teacher often repeats the same comments.
Whenever we see such a recurring comments, it could be tagged and through that proposed as a principle.
Some bad tags: #ai-move, #good-move, #reading, #life-and-death
Some ok tags: #attack-from-a-distance, #play-from-outside-not-inside, #nakade

It will take a while and some experinence to distill a set of good tags to be used for lessons.
It is not essential to get the tag names exactly since the tool will allow tag renaming, ignoring and merging.

## Effective learning

### Example contrasting

When illustrating Go principles, one needs to give both positive and negative examples of a given principle.
With only positive examples, while the illusion of teaching is achieved, the effectiveness is low.
With both positive and negative examples, the reader might feel more confused, but the effectiveness is high.
[This applies to almost every topic, where learning is without interaction](https://www.youtube.com/watch?v=eVtCO84MDj8).

### Skill decomposition

Deliberate practice teaches us that it is most effective to practice skills separate (e.g. practicing musical scales in isolation).

### Exercises

Exercises are essential for learning. 
We aim to make the autmated tool support that, but we don't know how yet.

## Audience

Go players that want to learn from all levels.
Go teachears that what to scale up spreading of Go knowledge in an organized manner.

## Reading ease

It is important that the reading is engaging. 
This can be achieved through various means:
 - personal stories about the author or
 - some context on where the example position came from or
 - motivational story about the value of the current lesson or
 - strong and colorful language.

The last technique is probably the most useful. 
"Lessons in the Fundamentals of Go" by Toshiro Kageyama is probably the finest example of these teaching techniques.

## Inspirational books

There are some Go books that inspired me to this project:
- [Fundamental Principles of Go](https://www.goodreads.com/en/book/show/1485651.Fundamental_Principles_Of_Go)
- [Lessons in the Fundamentals of Go](https://www.goodreads.com/book/show/1241950.Lessons_in_the_Fundamentals_of_Go)

If you know other similar books, please let me know!

## Language

The main advantage of english language allows faster creation of the book by allowing a wider family of strong players to contribute.
The main advantage of other languages allows wider reading audience, especially children to access it.
We will start with english, since we need to have a content first.
