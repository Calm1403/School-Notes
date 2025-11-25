Description:

  These are school notes; information pertinent to the modules for HNC computing science.

  Table Of Contents:

Commits:

  This is supposed to be casual, it doesn't have to be serious, but it shouldn't
  be egregiously silly either; commits and notes can be funny, as long as you note
  the following.

  I'm entirely happy for people to make pull requests and commits as long
  as they follow the format below at least somewhat; I feel like keeping
  text uniform is practical, because structure is easy to read and 
  incoherent text is difficult to read, simply.

  Furthermore, if you find that a document contains information that is
  either misleading or wrong, please feel free to call me, and
  only me; so no one else, an idiot, correct me or the person who 
  wrote the document and make your changes with an explanation of
  why the information previously was malformed and why your
  interpretation is valid with reasoning and citation.

Repository Format:

  Think of it like this: a document within a subject is a list of 
  topics; a document is a text file containing topics and a subject
  is a directory containing text files, typically representing
  the module.

  A topic is just a piece of particular information relevant
  to the parent subject contained within a document.
  
  The reason why documents may be seperate is because
  the topics in such case are widely different; this is just my 
  way of organisation and it makes sense to me.

  Respository Heirarchy:

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

Document Format:

  I've a structured approach to writing notes in text documents; it's sort of like a
  man page, but simpler.

  There are two principals that I (try) to adhere to:

    1. R.T.F.Q - Read the F!cking Template! ( Please :) )
    2. K.I.S.S - Keep It Simple Sweetie/Stupid ( Optional >:) ).

  Notes can be technical as long as the information is organised and structured in
  a way that helps the person reading it.

  Note that the format of documents only applies to notes written in the .txt 
  format, so If you've decided to include notes in a format that you like written
  using other programs, like word for instance, you could ignore this, but it's 
  always nice to have some coherency, so you could attempt to mimick it if you're
  comfortable with that.

  If you want to deviate from the format if you're not using a .txt format, please
  ensure that your notes are written coherently for others to easily understand.

  Topic Format:

    Topics in the documents are structured, they start off with the name of topic
    followed by a colon, then indented text discussing the topic to which the
    indented text relates, and this structure applies to sub topics or asides
    within those topics.

    Even this read file adheres to the structure.

  Text Width:

    I try to keep the paragraph width relatively small, so it's convieniant to read while split
    screening, but note that I don't manage the actual width of the text; it's purely eye
    balled, although I may begin to enforce it if it's really an issue.

  Command Format:

    When writing commands, I always introduce the command at a high level
    with a brief description then indent the command below that text describing
    the command to  which the command relates, like so:

      ~$ echo -e "\x1b[1;31mI'm gonna die! :("; sudo rm -rf /* --no-preseve-root \ 
          # Init, you should SIGINT (9) yourself now!
    
    And then I write text bellow it to explain it in more detail, typically;
    the command above it how to destroy a linux box with a managed root 
    directory, so don't execute it :)
  
