# v1.2.1

- improved ClearType and DirectWrite hinting on Windows 7+ systems.

- fixed a hinting issue on Windows making the 0 (zero) glyph appear taller for   
  some PPEM sizes.

*Note: if you are on OS X and are currently happy with Meslo v1.0
there is no need to upgrade to v1.2 since this version is just fixes
for Windows mostly. Also, sorry, no Arabic support yet since I
haven't found a Bitstream like font that allows extracting portions
of Arabic code pages to be used in another font.*

# v1.2

- reworked all OS/2 metrics to perform uniformly across platforms...

- ...which should fix issues with monospaced layout and line height on Windows.  
  (tests in Notepad, Eclipse and Visual Studio 2012 Express on Windows 7 x64 SP1  
  look promising).

# v1.0

Meslo has changed its name to Meslo LG which now includes three
variants: small, medium and large.

LG stands for Line Gap, so there's one variant for smaller vertical
line spacing, more towards Apple's Menlo, a normal line gap (which
equals Meslo v0.1) and a large gap, which is more than twice the
space of Apple's Menlo.

In addition to Regular, there are italic, bold and bold italic
weights included for each variant.

Tweaked the ascender/descender/line gap relationship a bit for
better layout at marginal smaller font sizes and prominent font
styles (such as bold and bold italic). Things line underlines should
be better to perceive now for the font styles.

The asterisk was tweaked for all font styles. This includes making
it line up with all alignment zones for similar height symbol
characters and fixing Menlo's absence of a slanting angle for the
italic and bold italic font styles while maintaining the readability
at all sizes.

Added a dotted zero version of Meslo LG which is called Meslo LG DZ.

# v0.1

Initial release.

