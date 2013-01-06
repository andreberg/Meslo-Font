h1. About Meslo LG

h3. Version 1.21

Meslo LG is a customized version of Apple's Menlo-Regular font
(which is a customized Bitstream Vera Sans Mono).

In Snow Leopard, Menlo-Regular is now the preferred and default font for Apple's 
developer tools and also the Terminal (unless you changed the font settings for 
these apps yourself before upgrading to SL - your changes will stay in place).

I really like Menlo but I do have my nitpicky gripes with it: 

* The default vertical (line) spacing is just way to cramped for me, and also  
* I am not particularily fond of the horizontal baseline alignment of the asterisk.

That's why I decided to customize Menlo, regarding these "issues".
The tricky part is keeping all the custom tables, hints, etc. intact when you 
adjust the globally very affecting stuff that results in vertical spacing. 

The LG in Meslo LG stands for Line Gap. The idea behind it is to allow the user 
to have some control over vertical spacing by choosing one of three line gap 
variants: small, medium and large (Meslo LG S, Meslo LG M and Meslo LG L respectively). 

If you're interested in looks, you can find a "comparison":http://github.com/andreberg/Meslo-Font/wiki/Menlo-Meslo-LG-Compared-%28Mac-OS-X%29 (for Mac OS X) in the Wiki.
And here's some "example screenshots":http://github.com/andreberg/Meslo-Font/wiki/Meslo-LG-Examples-%28Windows%29 for Windows.

For a possible way to install this font on your Windows console please see 
"Using Meslo LG with the Windows Console":http://github.com/andreberg/Meslo-Font/wiki/Using-Meslo-LG-with-the-Windows-Console.

You can find a FAQ "here":http://github.com/andreberg/Meslo-Font/wiki/Frequently-Answered-Questions.

For more articles please refer to the "Meslo-Font Wiki":http://github.com/andreberg/Meslo-Font/wiki.
Last, but not least, for additional info and comparisons please consult the About PDF that comes with the 
downladable ZIP archive.

%{color:crimson}NOTE: the downloads tab is no longer supported on GitHub.%
%{color:crimson}This just means you now download the font through the repository ZIP<br>which you can get up top or% "HERE":http://github.com/andreberg/Meslo-Font/archive/master.zip

Have Fun!

André Berg

h3. History

v0.1

Initial release.

v1.0

Meslo has changed it's name to Meslo LG which now includes three variants: 
small, medium and large.

LG stands for Line Gap, so there's one variant for smaller vertical line spacing, 
more towards Apple's Menlo, a normal line gap (which equals Meslo v0.1) and 
a large gap, which is more than twice the space of Apple's Menlo.

In addition to Regular, there's Italic, Bold and Bold Italic font styles 
included for each LG variant.

Tweaked the ascender/descender/line gap relationship a bit for better layout 
at marginal smaller font sizes and prominent font styles (such as Bold and 
Bold Italic). Things line underlines should be better to perceive now for 
the font styles.

The asterisk (*) was tweaked for all font styles. 
This includes making it line up with all alignment zones for similar height 
symbol characters and fixing Menlo's absence of a slanting angle for the italic 
and bold italic font styles while maintaining the readability at all sizes.

v1.0

Added a dotted zero version of Meslo LG which is called Meslo LG DZ.

v1.2

- reworked all OS/2 metrics to perform uniformely across platforms...  

- ...which should fix issues with monospace layout and line height on Windows.  
  (tests in Notepad, Eclipse and Visual Studio 2012 Express on Windows 7 x64 SP1  
  look promising).
  
v1.2.1

- improved ClearType and DirectWrite hinting on Windows 7+ systems.

- fixed a hinting issue on Windows making the 0 (zero) glyph appear taller for   
  some PPEM sizes.

  <i>Note: if you are on OS X and are currently happy with Meslo v1.0 there is  
  no need to upgrade to v1.2 since this version is just fixes for Windows mostly.  
  Also, sorry, no Arabic support yet since I haven't found a Bitstream like font  
  that allows extracting portions of arabic code pages to be used in another font.</i>

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

Thank you to Jim Lyles and Bitstream for the Bitstream Vera family of fonts.
Also, huge thanks to George Williams for the free font editing program "FontForge":http://fontforge.org.

h3. License

Copyright 2009, 2010, 2013 André Berg

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
