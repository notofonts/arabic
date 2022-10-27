## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[4] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> All tabular figures must have the same width across the RIBBI-family. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/family/tnum_horizontal_metrics">com.google.fonts/check/family/tnum_horizontal_metrics</a>)</summary><div>


* 🔥 **FAIL** The most common tabular glyph width is 488. But there are other tabular glyphs with different widths such as the following ones:
	{449: ['uni0662.tnum', 'uni0664.tnum', 'uni0666.tnum', 'uni0669.tnum']}. [code: inconsistent-widths]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoNaskhArabic/googlefonts/ttf', 'fonts/NotoNaskhArabic/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[10] NotoNaskhArabic-Bold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0608
	* uni0613
	* uni0616
	* uni06D6
	* uni06D7
	* uni06E5
	* uni077A.init
	* uni077A.medi
	* uni077B.init
	* uni077B.medi and 6 more.

Use -F or --full-lists to disable shortening of long lists.
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

	- _1518

	- _531.001

	- _539

	- _540

	- _782

	- _786

	- _874

	- _986

	- _twodotstah

	- _uniFBB2.001 

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

	* uni0616 (U+0616): L<<18.0,564.0>--<18.0,604.0>> -> L<<18.0,604.0>--<15.0,676.0>>

	* uni0616 (U+0616): L<<18.0,604.0>--<15.0,676.0>> -> L<<15.0,676.0>--<8.0,773.0>>

	* uni0616 (U+0616): L<<46.0,745.0>--<48.0,679.0>> -> L<<48.0,679.0>--<48.0,658.0>>

	* uni0616 (U+0616): L<<48.0,679.0>--<48.0,658.0>> -> L<<48.0,658.0>--<45.0,569.0>>

	* uni065E (U+065E): L<<9.0,696.0>--<23.0,715.0>> -> L<<23.0,715.0>--<38.0,734.0>>

	* uni06AD (U+06AD): L<<269.0,892.0>--<295.0,918.0>> -> L<<295.0,918.0>--<319.0,943.0>>

	* uni06AD (U+FBD3): L<<269.0,892.0>--<295.0,918.0>> -> L<<295.0,918.0>--<319.0,943.0>>

	* uni06D9 (U+06D9): L<<58.0,825.0>--<58.0,819.0>> -> L<<58.0,819.0>--<60.0,783.0>>

	* uni06DB (U+06DB): L<<5.0,717.0>--<31.0,743.0>> -> L<<31.0,743.0>--<55.0,768.0>>

	* uniFBC1 (U+FBC1): L<<143.0,-85.0>--<143.0,-99.0>> -> L<<143.0,-99.0>--<146.0,-150.0>> 

	* And 17 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uniFBE5 (U+FBE5): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFBF6 (U+FBF6): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFBF7 (U+FBF7): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFBF9 (U+FBF9): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFBFA (U+FBFA): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFBFD (U+FBFD): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFC03 (U+FC03): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFC04 (U+FC04): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFC09 (U+FC09): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFC0A (U+FC0A): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361 

	* And 142 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<101.0,122.0>--<100.0,646.0>>

	* h (U+0068): L<<252.0,309.0>--<253.0,118.0>> 

	* And sterling (U+00A3): L<<428.0,346.0>--<270.0,347.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] NotoNaskhArabic-Medium.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0608
	* uni06E5
	* uni077A.init
	* uni077A.medi
	* uni077B.init
	* uni077B.medi
	* uni08F3 and uniFDFD
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
 FONT_FAMILY_NAME = 'Noto Naskh Arabic Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x0020 is called "uni0020": Change to "space" [code: not-recommended-0020]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- _1518

	- _531.001

	- _539

	- _540

	- _782

	- _786

	- _874

	- _986

	- _twodotstah

	- _uniFBB2.001 

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

	* uni0616 (U+0616): L<<20.0,567.0>--<20.0,604.0>> -> L<<20.0,604.0>--<17.0,675.0>>

	* uni0616 (U+0616): L<<20.0,604.0>--<17.0,675.0>> -> L<<17.0,675.0>--<10.0,772.0>>

	* uni0616 (U+0616): L<<41.0,746.0>--<43.0,678.0>> -> L<<43.0,678.0>--<43.0,657.0>>

	* uni0616 (U+0616): L<<43.0,678.0>--<43.0,657.0>> -> L<<43.0,657.0>--<40.0,571.0>>

	* uni065E (U+065E): L<<11.0,700.0>--<24.0,718.0>> -> L<<24.0,718.0>--<38.0,735.0>>

	* uni0695 (U+0695): L<<11.0,-263.0>--<27.0,-259.0>> -> L<<27.0,-259.0>--<42.0,-256.0>>

	* uni06AD (U+06AD): L<<250.0,883.0>--<274.0,907.0>> -> L<<274.0,907.0>--<296.0,930.0>>

	* uni06AD (U+FBD3): L<<250.0,883.0>--<274.0,907.0>> -> L<<274.0,907.0>--<296.0,930.0>>

	* uni06DB (U+06DB): L<<8.0,722.0>--<32.0,746.0>> -> L<<32.0,746.0>--<54.0,769.0>>

	* uni08A0 (U+08A0): L<<278.0,-85.0>--<294.0,-81.0>> -> L<<294.0,-81.0>--<309.0,-78.0>> 

	* And 18 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uniFDFA (U+FDFA): B<<675.5,490.5>-<668.0,492.0>-<662.0,494.0>>/B<<662.0,494.0>-<692.0,478.0>-<702.5,470.0>> = 9.637538112930923

	* uniFEF6 (U+FEF6): B<<461.0,298.0>-<458.0,343.0>-<454.0,399.0>>/L<<454.0,399.0>--<451.0,372.0>> = 10.425808525884747

	* uniFEF8 (U+FEF8): B<<461.0,298.0>-<458.0,343.0>-<454.0,399.0>>/L<<454.0,399.0>--<451.0,372.0>> = 10.425808525884747

	* uniFEFA (U+FEFA): B<<461.0,298.0>-<458.0,343.0>-<454.0,399.0>>/L<<454.0,399.0>--<451.0,372.0>> = 10.425808525884747 

	* And uniFEFC (U+FEFC): B<<461.0,298.0>-<458.0,343.0>-<454.0,399.0>>/L<<454.0,399.0>--<451.0,372.0>> = 10.425808525884747 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<106.0,117.0>--<105.0,649.0>>

	* uni066D (U+066D): L<<21.0,283.0>--<156.0,282.0>> 

	* And uni066D (U+066D): L<<243.0,282.0>--<380.0,283.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[9] NotoNaskhArabic-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0608
	* uni06E5
	* uni077A.init
	* uni077A.medi
	* uni077B.init
	* uni077B.medi
	* uni08F3 and uniFDFD
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

	- _1518

	- _531.001

	- _539

	- _540

	- _782

	- _786

	- _874

	- _986

	- _twodotstah

	- _uniFBB2.001 

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

	* uni0616 (U+0616): L<<21.0,569.0>--<21.0,604.0>> -> L<<21.0,604.0>--<18.0,675.0>>

	* uni0616 (U+0616): L<<21.0,604.0>--<18.0,675.0>> -> L<<18.0,675.0>--<11.0,772.0>>

	* uni0616 (U+0616): L<<39.0,747.0>--<41.0,678.0>> -> L<<41.0,678.0>--<41.0,657.0>>

	* uni0616 (U+0616): L<<41.0,678.0>--<41.0,657.0>> -> L<<41.0,657.0>--<38.0,572.0>>

	* uni065E (U+065E): L<<12.0,702.0>--<25.0,720.0>> -> L<<25.0,720.0>--<38.0,736.0>>

	* uni0695 (U+0695): L<<16.0,-270.0>--<32.0,-266.0>> -> L<<32.0,-266.0>--<47.0,-263.0>>

	* uni06AD (U+06AD): L<<241.0,879.0>--<264.0,902.0>> -> L<<264.0,902.0>--<284.0,923.0>>

	* uni06AD (U+FBD3): L<<241.0,879.0>--<264.0,902.0>> -> L<<264.0,902.0>--<284.0,923.0>>

	* uni06D9 (U+06D9): L<<60.0,827.0>--<61.0,819.0>> -> L<<61.0,819.0>--<63.0,765.0>>

	* uni06DB (U+06DB): L<<10.0,725.0>--<33.0,748.0>> -> L<<33.0,748.0>--<53.0,769.0>> 

	* And 19 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uniFDFA (U+FDFA): B<<691.0,488.0>-<670.0,488.0>-<651.0,495.0>>/B<<651.0,495.0>-<675.0,483.0>-<688.0,476.0>> = 6.34019174590985

	* uniFEF6 (U+FEF6): B<<458.5,282.5>-<455.0,333.0>-<450.0,405.0>>/L<<450.0,405.0>--<447.0,378.0>> = 10.312687686660533

	* uniFEF8 (U+FEF8): B<<458.5,282.5>-<455.0,333.0>-<450.0,405.0>>/L<<450.0,405.0>--<447.0,378.0>> = 10.312687686660533

	* uniFEFA (U+FEFA): B<<458.5,282.5>-<455.0,333.0>-<450.0,405.0>>/L<<450.0,405.0>--<447.0,378.0>> = 10.312687686660533 

	* And uniFEFC (U+FEFC): B<<458.5,282.5>-<455.0,333.0>-<450.0,405.0>>/L<<450.0,405.0>--<447.0,378.0>> = 10.312687686660533 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[9] NotoNaskhArabic[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
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
</div></details><details><summary>⚠ <b>WARN:</b> Ensure variable fonts include an avar table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mandatory_avar_table">com.google.fonts/check/mandatory_avar_table</a>)</summary><div>


* ⚠ **WARN** This variable font does not have an avar table. [code: missing-avar]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x0020 is called "uni0020": Change to "space" [code: not-recommended-0020]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- _1518

	- _531.001

	- _539

	- _540

	- _782

	- _786

	- _874

	- _986

	- _twodotstah

	- _uniFBB2.001 

	- And 50 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 3 | 4 | 36 | 422 | 26 | 372 | 0 |
| 0% | 0% | 4% | 49% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
