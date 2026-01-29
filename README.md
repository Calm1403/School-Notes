## Description:

These are school notes; information pertinent to the modules for HNC computing science.

Please note that this repo is changing constantly, that I'm open minded about the
state of the repository and that I'm personally, currently in the process of migrating
my written notes over to this repository, so not everything will be here.

## Table Of Contents:

    Description - A description of what this is.
    Table Of Contents - A list of information.
    'Vibed' info - A disclaimer regarding AI.
    Commits - Information about commit style.
    Repository Format - Information about the style of the repo.
    Repository Heirarchy - Visualisation of the style.
    Document Format - Format of notes.
    Topic Format - Format of topics within notes.
    Command Format - Format of commands within notes.

## 'Vibed' info:

AI may be used to find sources related to a topic, in order to compile your own information; much akin to
wikipedia's citations. However, I personally refuse to use artificial intelligence to search for
information; I compile my own information together through manual research, and I take time to ensure that
information I find is creditable.

If I have reason to speculate that information submitted through a pull request is mindlessly 'vibed,' I
simply won't allow it to be merged. This is only to ensure that information remains creditable, which
is also why I ask for you to provide citation when validating your reasoning for uploading
notes.

## Commits:

This is supposed to be casual, it doesn't have to be serious, but it shouldn't
be egregiously silly either; commits and notes can be funny, as long as you note
the following.

I'm entirely happy for people to make pull requests and commits as long
as they follow the repository/document format below at least somewhat; I
feel like keeping text uniform is practical, because structure is easy to read
and incoherent text is difficult to read, simply.

If you're going to make commits, it may be helpful to place
references in the commit message from where the information is derived
along with a brief description of the addition.

Furthermore, if you find that a document contains information that is
either misleading or wrong, please feel free to make a correction to the document through
a pull request with a justification describing why the information previously
was malformed, along with creditable citations to better sources.

## Repository Format:

Think of it like this: a document within a subject is a list of 
topics; a document is a text file containing topics and a subject
is a directory typically representing a module containing those
documents.

A topic is just a piece of particular information relevant
to the parent subject, contained within a document.

The reason why documents may be separate is because
the topics in such case are widely different; this is just my 
way of organisation and it makes sense to me.

As a concrete example, documents on the nmap program are part of
the ethical hacking subject in the hacking directory, where topics 
pertaining to nmap may include things like the distinction between scan types
and their practicalities over each other, and scripts that
nmap can perform like cache snooping DNS servers or
vulnerability determination of hosts.

## Respository Heirarchy:

    SUBJECT 1:
      DOCUMENT 1.TXT:
        TOPIC 1:
          Blah Blah Blah..
        TOPIC 2:
          Blah Blah Blah..
        ... Further Topics.
        
      DOCUMENT 2.TXT:
        TOPIC 1:
          Blah Blah Blah..
        TOPIC 2:
          Blah Blah Blah..
        ... Further Topics.
        
      DOCUMENT 3.TXT:
        TOPIC 1:
          Blah Blah Blah..
        TOPIC 2:
          Blah Blah Blah..
        ... Further Topics.
      ... Further Documents.
      
    SUBJECT 2:
      ... Stuff in subject 2 like subject 1.
    ... Further Subjects.

## Document Format:

I've a structured approach to writing notes in text documents; it's sort of like a
man page, but simpler.

There are two principals that I (try) to adhere to:

1. R.T.F.T - Read the Fncking Template!
2. K.I.S.S - Keep It Simple Sweetie/Stupid.

Notes can be technical as long as the information is structured
and clarified in a way that helps the person reading it; they
should be brief and well contained, but informative enough to
not be trivial.

Note that the format of documents only applies to notes written in the .txt 
format, so If you've decided to include notes in a format that you like written
using other programs, like word for instance, you could ignore this, but it's 
always nice to have some coherency, so you could attempt to mimic it if you're
comfortable with that.

If you want to deviate from the internal document format if you're not using
a .txt format, please ensure that your notes are written coherently for others to
easily understand.

Note that I would prefer if you do write in the .txt format, just to
simplify things by having one common data type to facilitate
data manipulation and to reduce the size of the repository.

## Topic Format:

Topics in the documents are structured, they start off with the name of topic
followed by a colon, then indented text discussing the topic to which the
indented text relates, and this structure applies to sub topics or asides
within those topics.

This read file is a poor example, because it's in markdown as opposed
to raw text, but it does adhere to this structure.

I try to keep the paragraph width relatively small, so it's convenient to read while split
screening, but note that I don't manage the actual width of the text; it's purely eye
balled, although I may begin to enforce it if it's really an issue.

## Command Format:

When exemplifying commands, I always introduce the command at a high level
with a brief description; the command is often below the text that describes it
like so:

    ~$ echo -e "\x1b[1;31mI'm gonna die! :("; sudo rm -rf /* --no-preseve-root \ 
        # Init, you should SIGINT (9) yourself now!
  
And then I write text bellow it to explain it in more detail, typically;
the command above is a quick way to destroy a linux box with a managed root 
directory, removing everything stored within, so please don't try execute it
on an actual machine :)
  
