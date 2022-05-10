## Article 1

LUKE SMITH: blog
Wanna learn LaTeX?
Fri, 12 Feb 2021 22:44:31 +0300
[Source](https://lukesmith.xyz/articles/latex.html)

### Wanna learn LaTeX?

What is LaTeX?

Basically, it's how big boys write and format documents. Every public brief,
scientific article, book, cryptocurrency whitepaper or even outline written by
people who know what they're doing is written in LaTeX.

If you want to see examples of documents made with LaTeX, you can see my
Master's thesis [here][1] or another paper [here][2] that shows some diagrams and
other features you can have in LaTeX. Of course, LaTeX documents can be
infinitely customized.
[image][3]

"Is it hard?"

No. It's sort of like learing vim. People complain about how hard it is until
they take the bare minimum of time to learn it and realize how much more
effective they are with it. The return on investment is massive. I wrote the
thesis above in LaTeX in around a week of learning from the bare minimum.

"How is LaTeX different?"

LaTeX is a markup language, meaning that you write documents in whatever text
editor of your choosing and instead of manually moving margins and placing
things yourself, everything is optimally places when you compile the document
into a .pdf.

Markup languages are great because they separate the task of writing from the
task of formatting. It's somewhat similar to the difference between HTML (a
markup language) and CSS (which does styling) and Javascript (which does
scripting). LaTeX does the equivalent of all three, but it allows you to do them
all separately so you can easily extend documents.

"Why is LaTeX better than Microsoft Word and friends?"

  * Bibliographies are done totally automatically. For all the research papers
  I've written in the past 5 years, I have never written a bibliography page.
  You just tell LaTeX, "Oh, APA style, please" and it's done.
  * Section/page numbering and cross referencing is done automatically. That
  means if you refer people to a chart on page 52 multiple times or figure 5 or
  chapter 4, then you move pages or figures or chapters around, the references
  continues to refer to the page, figure or chapter you originally meant. That
  also means you can literally copy and paste text out of your document into a
  larger document and LaTeX will automatically reconfigure all cross-referenced
  numbers to be correctly referring to what you actually want them pointing to.
  * Text can easily be copied to a new format. I've written many term papers
  that latter became monographs or books and with LaTeX, you can just copy the
  raw text and it takes on the formatting of the document it is inside of.
  * It is scriptable. You can use coreutilities and other programs to search,
  modify and move text. This seems useless if you've never done it, but it makes
  a world of difference when you realize you can. You could use this, for
  example, to automatically take customer information on your computer and
  automatically-generate professional itemized invoices in LaTeX or the like.
  Also, being able to use sed -i and grep with .tex files is fantastic.
  * For more advanced users, LaTeX is more than a markup language too: and also
  has basic logic and tests (if statements and the like) that allow you to react
  dynamically to unknown content.
  * You can write LaTeX in literally anything. I write it in vim for its
  extensibility, but you can easily design your own workflow, instead of having
  to rely on the ever-changing idiosyncracies of Microsoft Word.

"But Word has some of those things!"

Niche features that basically no Word-user uses. Also they change with every new
update. This is the primary operating structure of LaTeX.

Installing LaTeX

The core LaTeX package (texlive) is fairly small, but I highly recommend you
download all the LaTeX packages out there at the beginning (a big download).
This is nice because as you learn more things, you won't have to manually
download new packages. You'll be able to experiment with new LaTeX abilities
through new packages seamlessly. Here's how you get them:

  * GNU/Linux

    * Arch-based (Artix, Manjaro, Parabola): `pacman -S texlive-most texlive-lang`
    * Debian-based (Ubuntu/Linux Mint): `apt-get install texlive-full`
    * Some distros (like Void) use tlmgr to install TeX packages instead of the main package manager.

  * Windows: [Here][4]. (Choose the net install to be able to install all
  packages.)
  * MacOS: [Here][5].

Once you've downloaded and installed that, you have a fully-featured LaTeX
engine on your machine! You can make lots of amazing things that you don't even
fullt realize yet.

LaTeX Video Tutorials

Basics

First thing to learn is how to compile documents with pdflatex and the basic
principles of the TeX lanugage. In this first video, I talk about how basic
text, paragraphs, titles, headings and more work. This in itself is enough to
make a professional write-up.

[Video](https://www.youtube.com/watch?v=25LExaNtdF0&list=PL-p5XmQHB_JSQvW8_mhBdcwEyxdVX0c1T&index=3)

Numbering and cross-referencing

As you make more complex documents, you'll want to automatically number and
interrelate section, figure and other numbers together. LaTeX makes this super
simple, and make it even easier to copy your file into a new file where it will
automatically update all cross-referenced numbers.
Click to Reveal Video.

Bibliographies with Biber and BibLaTeX

Bibliography management is a huge plus in LaTeX through biber. I haven't written
a bibliography in more than half a decade due to the fact that LaTeX only needs
a bibliography file of metadata and autogenerates citations for any needed
source.

[Video](https://www.youtube.com/watch?v=46piog3Fzp4&list=PL-p5XmQHB_JSQvW8_mhBdcwEyxdVX0c1T&index=4)

Images and Figures

TeX isn't all text either. You can insert and nicely format images in a way that
they are optimally placed without too much human interference.

[Video](https://www.youtube.com/watch?v=zgThRPjy-vw&list=PL-p5XmQHB_JSQvW8_mhBdcwEyxdVX0c1T&index=7)

Macros to make things easy

As you do more specific things, you might want to make your own macros and
functions. This really makes things easier, and you can do very complex things
very elegantly.

[Video](https://www.youtube.com/watch?v=rvgP7IMeUn8&list=PL-p5XmQHB_JSQvW8_mhBdcwEyxdVX0c1T&index=9)

Slide Presentations with Beamer

LaTeX isn't just for printable documents either. You can change your document
into a Beamer presentation, allowing you to present it as a slide show similar
to Microsoft PowerPoint's.

[Video](https://www.youtube.com/watch?v=zEjBCQhND2c&list=PL-p5XmQHB_JSQvW8_mhBdcwEyxdVX0c1T&index=8)

Making a Professional Résumé

Here, I also give some extra pointers while I make a résumé.

Part 1

[Video](https://www.youtube.com/watch?v=VjsX4tznW40&list=PL-p5XmQHB_JSQvW8_mhBdcwEyxdVX0c1T&index=5)

Part 2

[Video](https://www.youtube.com/watch?v=o5-BZ7JmYWk&list=PL-p5XmQHB_JSQvW8_mhBdcwEyxdVX0c1T&index=6)

## Article 2

### MIPT tutorial

There is a good LATEX tutorial from MIPT community.

[Text version in pdf format](https://github.com/MIPT-Group/Lectures_Tex_Club/tree/master/Course)

[Video](https://www.youtube.com/playlist?list=PL4_hYwCyhAvZtx63FR9d5_K0GMWF1XUc6)

[Source](https://mipt-ltc.github.io/latex/)


------------------------------------------------------------------------------

THE END


[1]: http://lukesmith.xyz/dox/papers/luke_thesis.pdf "link"
[2]: http://lukesmith.xyz/dox/papers/prelim2.pdf "link"
[3]: http://lukesmith.xyz/pix/write.gif "image"
[4]: https://miktex.org/download/#collapse264 "link"
[5]: https://tug.org/mactex/ "link"

