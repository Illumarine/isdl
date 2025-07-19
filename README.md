# ISDL

Illumarine System Documentation Language

## Why ISDL?

Illumarine System Documentation Language, or ISDL for short, is a work in progress plain-text documentation
language that is easy to read, easy to write, and easy to export into HTML and PDF. It was created by the
developers of the [Illumarine](https://illumarineos.com) operating system (an illumos-based operating system)
for the sole purpose to create a powerful, yet readable documentation language.

Why not Markdown? Markdown is great for simple README files, but once you dive deep into the weeds, you will
ultimately have to use HTML within Markdown, or alternatively find a different solution altogether. Tools like
MDX make Markdown passable as a documentation language, if you're willing to use JSX or other JavaScript tools,
but it still falls behind in creating heavy production-ready documentation.

Why not AsciiDoc? While more powerful than Markdown in many ways we want it to be, there are many things that
plain Markdown just does better. Links, lists, code snippets to name a few. There are other things that neither
AsciiDoc or Markdown provide like being able to provide both a cohesive website and seperate PDF documentation
with different styles.

Why not `[insert other solution here]`? Ultimately having worked with HTML, restructuredText, DITA, DocBook,
LaTeX, DGSs, Pandoc, and even newer (good) solutions like Unidok, we ultimately decided that working wih our
very specific needs we needed a new language.

Inspired by Unidok, Markdown, and AsciiDoc, we introduce to the world a new documentation language: ISDL.

## How Will ISDL Work?

ISDL will read very similarly to Unidok and Markdown, with added features inspired by AsciiDoc. It will also come
with a `isdl.config.toml` system designed to be used for styling, export configurations, and more.

## Authors

- Samantha of Illumarine [@BBBensonDev](https://github.com/BBBensonDev)
