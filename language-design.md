_Fill in each this file with your responses, placing each response after its
corresponding question._

---

**Question**

Pick three quotes from the readings about language design. Good candidates
are:

- Something you agreed with / resonates with your own experience
- Something you disagree with
- Something that is interesting, a new idea or perspective you'd like to remember
- Something you didn't understand

For each quote, describe what it was about the quote that led you pick it.

**Response**

"If you give a person tools, he can make a fishing pole—and lots of other tools! He can
build a machine to crank out fishing poles. In this way he can help other persons to catch fish." [Steele, 1998]
- I really enjoyed this quote's extension on the saying about teaching a man how
to fish. Here, Steele continued to get his main point across, that programming
languages need to provide a way to design something, like building one's own
fishing pole machine. Additionally, he uses a well known saying to get his point
across. I think that this is wise because he reminds people of the lesson taught
in this saying, and extends the lesson taught to be applicable to his argument.

"If it's hard to find good names, go back to the drawing board. Don't be afraid
to split or merge an API, or embed it in a more general setting. If names start
falling into place, you're on the right track." [Bloch, 2006]
- I thought this argument is very interesting, that one way to determine if
your API is intuitive and designed well is if the names are easy to create. I
think this is a very neat trick to checking if you API will make sense to users.

"The broad computer science academic community as not paid a tremendous amount
of attention to programming language usability. I think that our discipline mostly
uses anecdotes to argue about programming languages." [Pavlus, 2012]
- As I am starting to learn more formally about programming languages in CS131
and in this course, it is interesting to see where studying programming languages
fits into the wider computer science community. It is very interesting to learn
that academics are not focused on the usability of programming languages, I am
curious how the "ivory tower" of CS thinks about the wide uses of programming
languages, and this quote argues that is abstracts the argument by using
anecdotes.

---

**Question**

How would you know a well-designed language? What are the symptoms? How would
you know a poorly designed language? What are the symptoms?

**Response**

A well designed language is intuitive and accessible to learn properly and allows
one to built onto it through creating libraries that apply seamlessly into the
language. These ideas are heavily emphasized in the Steele reading, where Steele
explains that the best languages are those that grow quickly. Specifically, the
language must take feedback and code written by users, and then quickly apply the
best of this code to the language [Steele, 1998]. Additionally, the code must be
easy to learn and have exemplary examples, as these examples "will be the
archetypes for thousands of programs" [Bloch, 2006]. Therefore, the more intuitive
and accessible it is to learn the language, users will be able to use the language
better, and it is thus well-designed. 

A poorly designed language would be un-intuitive, and would make it difficult for
users to write code that fits seamlessly into the language itself. For example,
Steele writes that a flaw in the language APL is that "there was no way for a
user to grow the language in a smooth way" [Steele, 1998]. To learn about
unintuitive design, we can look to the article about Perl, which explains that
"we have observed that novices learning to program at the university or younger
levels can have signiﬁcant difﬁculty learning the syntax of general purpose
programming languages, which may initially seem arbitrary” [Pavlus, 2012]. Here,
it is explained that many programming languages have syntax which is difficult
to understand without a prior deep understanding of computer science. Therefore,
combining this information, we can observe that a badly designed language is one
that is difficult for users to understand quickly and build off of easily.

---

**Question**

How might the themes of _Growing a Language_ relate to notions from Fowler?

**Response**

Fowler focuses on domain specific languages, where Steele is focused on general
purpose programming languages. However, there are a few key themes that appear
in both texts. I am going to discuss three that I found interesting.

When discussing internal DSLs, Flower writes that an internal DSL "is nothing
more than a quirky API" but that "a command-query API defines the vocabulary of
the abstraction, whereas an internal DSL adds a grammar" [Fowler, 2010]. In
_Growing a Language_, Steele emphasizes that languages must have the ability
to grow. Creating an API and adding an internal DSL are both ways in which a
language can grow. Therefore, the idea of an internal DSL itself would be very
exciting for Steele, as internal DSLs are written in the general language, and
are a very important contribution to the general language. Internal DSLs are a
growth of general purpose languages.

I also find it interesting that Fowler heavily encourages using DSLs. The first
reason that he cites is that DSLs improve development productivity as a DSL
"provides a means to more clearly communicate the intent of a part of a system"
[Fowler, 2010]. Fowler's understanding of why DSLs are useful connects to
Steele's focus on language growth improving the language. Using a DSL makes
one's use of a general purpose language better, as the DSL allows for additional
efficiency through having less code needed in order to best communicate intent
to the system. Therefore, DSLs are a great example of why language growth can
be so beneficial.

The last topic that I want to discuss is Fowler's concern about the cost of
building DSLs, as he writes that there is "still cost to write, and above all to
maintain" a DSL. Steele also writes about cost through discussing the rate of
growth of a language. Steele says "If one person does all the work, then growth
will be slow. But if one lets the users help do the work, growth can be quick.
If many persons work side by side, and the best work is added with care and good
taste, a great deal can be added in a short time" [Steele, 1998]. I think that
Steele would argue that there one great way to make the cost of DSL creation
low, is to allow for collaboration through making the DSL code open source.

---

**Question**

In what way is an API a language?

**Response**

---

**Question**

What does the post on grayscale tell us about the process of API design?

**Response**

---

**Question**

The Pavlus article mentions the researchers' comments that people preferred
"natural-language replacements for some of the more abstruse syntax". In other
words, people found it easier to work with code that looks more like a human language (e.g.,
English). Consider the following quote by William R. Cook, one of the creators
of AppleScript:

> The experiment in designing a language that resembled natural languages (English
> and Japanese) was not successful. It was assumed that scripts should be
> presented in “natural language” so that average people could read and write
> them. … In the end the syntactic variations and flexibility did more to confuse
> programmers than to help them out. It is not clear whether it is easier for
> novice users to work with a scripting language that resembles natural language,
> with all its special cases and idiosyncrasies. The main problem is that
> AppleScript only appears to be a natural language: in fact, it is an artificial
> language, like any other programming language. … even small changes to the
> script may introduce subtle syntactic errors that baffle users. It is easy to
> read AppleScript, but quite hard to write it.
> [[Cook 2007, page 1-20]](https://dl.acm.org/citation.cfm?doid=1238844.1238845)

Are these two experiences of natural languages at odds with one another? Would
you choose to include natural language in the design of a DSL? If so, how might
you do so? If not, why not?

**Response**

---
