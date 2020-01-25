# Keep it Real

Original design based on spontaneous github status update.

Don't convert with pandoc directly: 

Makefile will run `pandoc sticker.md -o sticker-interim.pdf`

Then it will call `pdf2svg` to make an editable svg for `inkscape` or your tool of choice.
If you're dissatisfied with the kerning in the pdf here, you are free to do a better job
in those tools. I'm no kerning expert, but for a logo, the kern between the 'K' and 'e' was too high.
