# About Meslo LG (Line Gap)

Meslo LG is a customized version of Apple's *Menlo-Regular* font
(which is a customized Bitstream Vera Sans Mono).

In Snow Leopard, Menlo-Regular is now the preferred default font
for Apple's developer tools and also the Terminal (unless you changed
the font settings yourself before upgrading to Snow Leopard, in
which case your changes will remain).

I really like Menlo but I have my nit-picky gripes with it:

* The default vertical (line) spacing is just way too cramped
* I am not particularity fond of the horizontal baseline alignment of the asterisk.

These issues are why I decided to customize Menlo. The tricky part
is keeping all the custom tables, hints, etc. intact when you adjust
the globally very affecting stuff that results in vertical spacing.

The LG in Meslo LG stands for Line Gap. The idea is to give the
user to have some control over vertical spacing by choosing one of
three line gap variants: small, medium and large (**Meslo LG S**,
**Meslo LG M** and **Meslo LG L** respectively).

If you're interested in looks, you can find comparisons on the wiki
[for OS X](http://github.com/andreberg/Meslo-Font/wiki/Menlo-Meslo-LG-Compared-%28Mac-OS-X%29)
and [Windows](http://github.com/andreberg/Meslo-Font/wiki/Meslo-LG-Examples-%28Windows%29).

To install Meslo LG in the Windows console, please see 
[Using Meslo LG with Windows Console](http://github.com/andreberg/Meslo-Font/wiki/Using-Meslo-LG-with-the-Windows-Console).

Check out [the FAQ](http://github.com/andreberg/Meslo-Font/wiki/Frequently-Answered-Questions) and [the wiki](http://github.com/andreberg/Meslo-Font/wiki).

Last but not least, for additional info and comparisons consult the **About...** PDF in the font directories.

Have Fun!

André Berg

h3. History

v0.1

Initial release.

v1.0

Meslo has changed its name to Meslo LG which now includes three variants: 
small, medium and large.

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

v1.0

Added a dotted zero version of Meslo LG which is called Meslo LG DZ.

v1.2

- reworked all OS/2 metrics to perform uniformly across platforms...

- ...which should fix issues with monospaced layout and line height on Windows.  
  (tests in Notepad, Eclipse and Visual Studio 2012 Express on Windows 7 x64 SP1  
  look promising).
  
v1.2.1

- improved ClearType and DirectWrite hinting on Windows 7+ systems.

- fixed a hinting issue on Windows making the 0 (zero) glyph appear taller for   
  some PPEM sizes.

*Note: if you are on OS X and are currently happy with Meslo v1.0
there is no need to upgrade to v1.2 since this version is just
fixes for Windows mostly. Also, sorry, no Arabic support yet since
I haven't found a Bitstream like font that allows extracting portions
of arabic code pages to be used in another font.*

h3. Copyright and Trademark Information

Menlo is a Trademark of Apple Inc. 
Bitstream Vera is a trademark of Bitstream, Inc., designed by Jim Lyles.

Menlo-Regular:

Copyright © 2009 Apple Inc. 
Copyright © 2006 by Tavmjong Bah. 
Copyright © 2003 by Bitstream, Inc. All Rights Reserved.

All other brands and product names not specifically listed are trademarks or 
registered trademarks of their respective owners.

h3. Thanks

Thank you to Jim Lyles and Bitstream for the Bitstream Vera family
of fonts.

Also, huge thanks to George Williams for the free font editing
program "FontForge":http://fontforge.org.
