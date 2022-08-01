## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[4] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> All tabular figures must have the same width across the RIBBI-family. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/family/tnum_horizontal_metrics">com.google.fonts/check/family/tnum_horizontal_metrics</a>)</summary><div>


* 🔥 **FAIL** The most common tabular glyph width is 488. But there are other tabular glyphs with different widths such as the following ones:
	{449: ['uni0662.tnum', 'uni0664.tnum', 'uni0666.tnum', 'uni0669.tnum']}. [code: inconsistent-widths]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoNaskhArabicUI/googlefonts/ttf', 'fonts/NotoNaskhArabicUI/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[12] NotoNaskhArabicUI-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1200, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 419, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0654 

	- And uni065B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uniFEDF + uniFEE0

	- uniFEE0 + uniFBA7

	- uniFBA7 + uniFEE0

	- uniFEE0 + uniFEEA

	- uni0627 + uniFEDF

	- uniFEE0 + uni0651_uni0670

	- uni0651_uni0670 + uniFBA7

	- uniFBA7 + uniFEDF 

	- And uni0651_uni0670 + uniFEEA [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x0020 is called "uni0020": Change to "space" [code: not-recommended-0020]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni06BD.medi

	- exclam

	- _540

	- uniFBB2.001

	- dotamiddlear

	- alrahem

	- period

	- two

	- _539

	- uni00A0 

	- And 50 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0616 (U+0616): L<<18.0,698.0>--<18.0,738.0>> -> L<<18.0,738.0>--<15.0,810.0>>

	* uni0616 (U+0616): L<<18.0,738.0>--<15.0,810.0>> -> L<<15.0,810.0>--<8.0,907.0>>

	* uni0616 (U+0616): L<<46.0,879.0>--<48.0,813.0>> -> L<<48.0,813.0>--<48.0,792.0>>

	* uni0616 (U+0616): L<<48.0,813.0>--<48.0,792.0>> -> L<<48.0,792.0>--<45.0,703.0>>

	* uni065E (U+065E): L<<8.0,696.0>--<22.0,715.0>> -> L<<22.0,715.0>--<37.0,734.0>>

	* uni06AD (U+06AD): L<<269.0,893.0>--<295.0,919.0>> -> L<<295.0,919.0>--<319.0,944.0>>

	* uni06AD (U+FBD3): L<<269.0,893.0>--<295.0,919.0>> -> L<<295.0,919.0>--<319.0,944.0>>

	* uni06D9 (U+06D9): L<<58.0,825.0>--<58.0,819.0>> -> L<<58.0,819.0>--<60.0,783.0>>

	* uni06DB (U+06DB): L<<5.0,718.0>--<31.0,744.0>> -> L<<31.0,744.0>--<55.0,769.0>>

	* uniFBC1 (U+FBC1): L<<143.0,50.0>--<143.0,36.0>> -> L<<143.0,36.0>--<146.0,-15.0>> 

	* And 17 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uniFBE5 (U+FBE5): B<<590.5,152.0>-<563.0,156.0>-<543.0,161.0>>/B<<543.0,161.0>-<584.0,142.0>-<605.5,131.0>> = 10.827453103825361

	* uniFBF6 (U+FBF6): B<<590.5,152.0>-<563.0,156.0>-<543.0,161.0>>/B<<543.0,161.0>-<584.0,142.0>-<605.5,131.0>> = 10.827453103825361

	* uniFBF7 (U+FBF7): B<<590.5,152.0>-<563.0,156.0>-<543.0,161.0>>/B<<543.0,161.0>-<584.0,142.0>-<605.5,131.0>> = 10.827453103825361

	* uniFBF9 (U+FBF9): B<<590.5,152.0>-<563.0,156.0>-<543.0,161.0>>/B<<543.0,161.0>-<584.0,142.0>-<605.5,131.0>> = 10.827453103825361

	* uniFBFA (U+FBFA): B<<590.5,152.0>-<563.0,156.0>-<543.0,161.0>>/B<<543.0,161.0>-<584.0,142.0>-<605.5,131.0>> = 10.827453103825361

	* uniFBFD (U+FBFD): B<<590.5,152.0>-<563.0,156.0>-<543.0,161.0>>/B<<543.0,161.0>-<584.0,142.0>-<605.5,131.0>> = 10.827453103825361

	* uniFC03 (U+FC03): B<<590.5,152.0>-<563.0,156.0>-<543.0,161.0>>/B<<543.0,161.0>-<584.0,142.0>-<605.5,131.0>> = 10.827453103825361

	* uniFC04 (U+FC04): B<<590.5,152.0>-<563.0,156.0>-<543.0,161.0>>/B<<543.0,161.0>-<584.0,142.0>-<605.5,131.0>> = 10.827453103825361

	* uniFC09 (U+FC09): B<<590.5,152.0>-<563.0,156.0>-<543.0,161.0>>/B<<543.0,161.0>-<584.0,142.0>-<605.5,131.0>> = 10.827453103825361

	* uniFC0A (U+FC0A): B<<590.5,152.0>-<563.0,156.0>-<543.0,161.0>>/B<<543.0,161.0>-<584.0,142.0>-<605.5,131.0>> = 10.827453103825361 

	* And 142 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<101.0,122.0>--<100.0,646.0>>

	* h (U+0068): L<<252.0,309.0>--<253.0,118.0>> 

	* And sterling (U+00A3): L<<428.0,346.0>--<270.0,347.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoNaskhArabicUI-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1200, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 419, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0654 

	- And uni065B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uniFEDF + uniFEE0

	- uniFEE0 + uniFBA7

	- uniFBA7 + uniFEE0

	- uniFEE0 + uniFEEA

	- uni0627 + uniFEDF

	- uniFEE0 + uni0651_uni0670

	- uni0651_uni0670 + uniFBA7

	- uniFBA7 + uniFEDF 

	- And uni0651_uni0670 + uniFEEA [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Naskh Arabic UI Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x0020 is called "uni0020": Change to "space" [code: not-recommended-0020]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni06BD.medi

	- exclam

	- _540

	- uniFBB2.001

	- dotamiddlear

	- alrahem

	- period

	- two

	- _539

	- uni00A0 

	- And 50 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0616 (U+0616): L<<20.0,702.0>--<20.0,739.0>> -> L<<20.0,739.0>--<17.0,810.0>>

	* uni0616 (U+0616): L<<20.0,739.0>--<17.0,810.0>> -> L<<17.0,810.0>--<10.0,907.0>>

	* uni0616 (U+0616): L<<41.0,881.0>--<43.0,813.0>> -> L<<43.0,813.0>--<43.0,792.0>>

	* uni0616 (U+0616): L<<43.0,813.0>--<43.0,792.0>> -> L<<43.0,792.0>--<40.0,706.0>>

	* uni065E (U+065E): L<<11.0,700.0>--<24.0,718.0>> -> L<<24.0,718.0>--<38.0,735.0>>

	* uni0695 (U+0695): L<<11.0,-111.0>--<27.0,-107.0>> -> L<<27.0,-107.0>--<42.0,-104.0>>

	* uni06AD (U+06AD): L<<251.0,883.0>--<275.0,907.0>> -> L<<275.0,907.0>--<296.0,929.0>>

	* uni06AD (U+FBD3): L<<251.0,883.0>--<275.0,907.0>> -> L<<275.0,907.0>--<296.0,929.0>>

	* uni06D9 (U+06D9): L<<59.0,826.0>--<59.0,819.0>> -> L<<59.0,819.0>--<61.0,771.0>>

	* uni06DB (U+06DB): L<<9.0,722.0>--<33.0,746.0>> -> L<<33.0,746.0>--<54.0,768.0>> 

	* And 19 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uniFDFA (U+FDFA): B<<675.5,625.5>-<668.0,627.0>-<662.0,629.0>>/B<<662.0,629.0>-<692.0,613.0>-<702.5,605.0>> = 9.637538112930923

	* uniFEF6 (U+FEF6): B<<461.0,433.0>-<458.0,478.0>-<454.0,534.0>>/L<<454.0,534.0>--<451.0,507.0>> = 10.425808525884747

	* uniFEF8 (U+FEF8): B<<461.0,433.0>-<458.0,478.0>-<454.0,534.0>>/L<<454.0,534.0>--<451.0,507.0>> = 10.425808525884747

	* uniFEFA (U+FEFA): B<<461.0,433.0>-<458.0,478.0>-<454.0,534.0>>/L<<454.0,534.0>--<451.0,507.0>> = 10.425808525884747 

	* And uniFEFC (U+FEFC): B<<461.0,433.0>-<458.0,478.0>-<454.0,534.0>>/L<<454.0,534.0>--<451.0,507.0>> = 10.425808525884747 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<106.0,117.0>--<105.0,649.0>>

	* uni066D (U+066D): L<<21.0,418.0>--<156.0,417.0>> 

	* And uni066D (U+066D): L<<243.0,417.0>--<380.0,418.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] NotoNaskhArabicUI-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1200, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 419, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0654 

	- And uni065B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uniFEDF + uniFEE0

	- uniFEE0 + uniFBA7

	- uniFBA7 + uniFEE0

	- uniFEE0 + uniFEEA

	- uni0627 + uniFEDF

	- uniFEE0 + uni0651_uni0670

	- uni0651_uni0670 + uniFBA7

	- uniFBA7 + uniFEDF 

	- And uni0651_uni0670 + uniFEEA [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x0020 is called "uni0020": Change to "space" [code: not-recommended-0020]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni06BD.medi

	- exclam

	- _540

	- uniFBB2.001

	- dotamiddlear

	- alrahem

	- period

	- two

	- _539

	- uni00A0 

	- And 50 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0616 (U+0616): L<<21.0,704.0>--<21.0,739.0>> -> L<<21.0,739.0>--<18.0,810.0>>

	* uni0616 (U+0616): L<<21.0,739.0>--<18.0,810.0>> -> L<<18.0,810.0>--<11.0,907.0>>

	* uni0616 (U+0616): L<<39.0,882.0>--<41.0,813.0>> -> L<<41.0,813.0>--<41.0,792.0>>

	* uni0616 (U+0616): L<<41.0,813.0>--<41.0,792.0>> -> L<<41.0,792.0>--<38.0,707.0>>

	* uni065E (U+065E): L<<12.0,702.0>--<25.0,720.0>> -> L<<25.0,720.0>--<38.0,736.0>>

	* uni0695 (U+0695): L<<16.0,-115.0>--<32.0,-111.0>> -> L<<32.0,-111.0>--<47.0,-108.0>>

	* uni06AD (U+06AD): L<<242.0,878.0>--<265.0,901.0>> -> L<<265.0,901.0>--<285.0,922.0>>

	* uni06AD (U+FBD3): L<<242.0,878.0>--<265.0,901.0>> -> L<<265.0,901.0>--<285.0,922.0>>

	* uni06D9 (U+06D9): L<<59.0,827.0>--<60.0,819.0>> -> L<<60.0,819.0>--<62.0,765.0>>

	* uni06DB (U+06DB): L<<11.0,724.0>--<34.0,747.0>> -> L<<34.0,747.0>--<54.0,768.0>> 

	* And 19 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uniFDFA (U+FDFA): B<<691.0,623.0>-<670.0,623.0>-<651.0,630.0>>/B<<651.0,630.0>-<675.0,618.0>-<688.0,611.0>> = 6.34019174590985

	* uniFEF6 (U+FEF6): B<<458.5,417.5>-<455.0,468.0>-<450.0,540.0>>/L<<450.0,540.0>--<447.0,513.0>> = 10.312687686660533

	* uniFEF8 (U+FEF8): B<<458.5,417.5>-<455.0,468.0>-<450.0,540.0>>/L<<450.0,540.0>--<447.0,513.0>> = 10.312687686660533

	* uniFEFA (U+FEFA): B<<458.5,417.5>-<455.0,468.0>-<450.0,540.0>>/L<<450.0,540.0>--<447.0,513.0>> = 10.312687686660533 

	* And uniFEFC (U+FEFC): B<<458.5,417.5>-<455.0,468.0>-<450.0,540.0>>/L<<450.0,540.0>--<447.0,513.0>> = 10.312687686660533 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[10] NotoNaskhArabicUI[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure variable fonts include an avar table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mandatory_avar_table">com.google.fonts/check/mandatory_avar_table</a>)</summary><div>


* 🔥 **FAIL** This variable font does not have an avar table. [code: missing-avar]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1200, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 419, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0654 

	- And uni065B [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 264. [code: invalid-default-instance-subfamily-nameid:264]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uniFEDF + uniFEE0

	- uniFEE0 + uniFBA7

	- uniFBA7 + uniFEE0

	- uniFEE0 + uniFEEA

	- uni0627 + uniFEDF

	- uniFEE0 + uni0651_uni0670

	- uni0651_uni0670 + uniFBA7

	- uniFBA7 + uniFEDF 

	- And uni0651_uni0670 + uniFEEA [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x0020 is called "uni0020": Change to "space" [code: not-recommended-0020]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni06BD.medi

	- exclam

	- _540

	- uniFBB2.001

	- dotamiddlear

	- alrahem

	- period

	- two

	- _539

	- uni00A0 

	- And 50 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 4 | 14 | 32 | 439 | 26 | 380 | 0 |
| 0% | 2% | 4% | 49% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
