---
layout: math
title: Notes
nav_order: 2
mathjax: true
---

# Lecture Notes

* [Lecture Notes](https://uob.sharepoint.com/teams/grp-COMS30040/Shared%20Documents/General/notes.pdf)
* [Programming Proofs Notes](https://uob.sharepoint.com/teams/grp-COMS30040/Shared%20Documents/General/proofs.pdf)

There is a complete set of lecture notes for the assessed part of the unit (see [here](/schedule.html) for the distinction between the parts).  These notes are authoratative, you will not be assessed on anything that is not based on the contents of these notes.  

To pass the assessment, you will need to be able to write mathematical proofs.  I don't expect you to be able to do this at the start of the unit but it is a skill I expect you to have learned well by the end (and you will get some good practice).
We will cover a method of writing proofs as a form of programming in the first two supplementary lectures which is also the subject of the second set of notes.

You should read these notes and listen to the accompanying lectures even if you already believe you can write convincing proofs, because this perspective on proofs will be revisited as part of the core material towards the end of the unit.

## Optional Reading

There are lots of textbooks and articles on type systems and lambda calculus.  Here are some that I recommend:

* __Lambda Calculus and Combinators an Introduction__ *by Roger Hindley and Jonathan Seldin*.  This is a good, readable introduction to pure lambda calculus and types.  Be aware that it is the only presentation I know of that does not identify all terms that are the same modulo names of the free variables; consequently, the basic definitions are a bit larger.  Chapters 1,2,3,4 and 10 are the most relevant.  It does not cover type inference (core lectures 10 & 11) and Chapter 10 studies "simple types" which are a slight restriction on our system -- no types schemes are allowed.  This actually doesn't make a huge amount of difference to the issues involved.  In eBook format: https://www-cambridge-org.bris.idm.oclc.org/core/books/lambdacalculus-and-combinators/5E58FA156DE2129BE89BDFDCD7ECB645
* __Lambda Calculus: Syntax and Semantics__ *by Henk Barendregt*.  This is like the holy book of the pure untyped lambda calculus.  The first 6 core lectures cover a small part of Chapters 1-3.  Not bedtime reading.  In eBook format at https://ebookcentral.proquest.com/lib/bristol/detail.action?docID=428593
* __Basic Simple Type Theory__ *by Roger Hindley*.  This is a kind of book-length expansion of Hindley's chapter 10 from my first recommendation.  Chapters 2, 3 and 6 are the most relevant.  In particular, it covers type inference, but I think you will prefer our presentation in lectures 10 and 11 which is more modern.  In eBook format: https://www-cambridge-org.bris.idm.oclc.org/core/books/basic-simple-type-theory/0C0B4DB68D19B96E2F2F8AAF8DD738C7
* __Lambda Calculus with Types__ *by Barendregt, Dekkers and Statman*.  This is a somewhat more encyclopedic reference on three pure type theories: simple types (see previous entry), recursive types and intersection types.  Only the first part is (slighly) relevant.  In eBook format: https://www-cambridge-org.bris.idm.oclc.org/core/books/lambda-calculus-with-types/65DC18AC262498B0F93A688CBE748048
* __Types and Programming Languages__ *by Benjamin Pierce*.  This book is well known to every academic who works in programming languages research.  Whereas we study lambda calculus in a pure setting, here it is studied in the context of programming languages.  Our supplementary lectures will make the connection.  A disadvantage of the approach in this book is that there is not much depth and it reads more like a zoo of different typing features.  You will find this very easy to read by the end of this unit.  If you're really interested in programming language theory then I seriously recommend buying a copy.
* __Advanced Topics in Types and Programming Languages__ *edited by Pierce*.  This is a collection of articles on more advanced type system features than those in TAPL (previous).  It is interesting stuff, and is a kind of sequel to TAPL, but not so relevant to this unit.

