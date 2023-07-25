## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[5] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> All tabular figures must have the same width across the RIBBI-family. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/family/tnum_horizontal_metrics">com.google.fonts/check/family/tnum_horizontal_metrics</a>)</summary><div>


* 🔥 **FAIL** The most common tabular glyph width is 449. But there are other tabular glyphs with different widths such as the following ones:
	{488: ['uni0662.tnum', 'uni0664.tnum', 'uni0666.tnum', 'uni0669.tnum']}. [code: inconsistent-widths]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoNaskhArabicUI/googlefonts/ttf', 'fonts/NotoNaskhArabicUI/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that OS/2.fsSelection bold & italic settings are unique for each NameID1 (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.adobe.fonts/check/family/bold_italic_unique_for_nameid1">com.adobe.fonts/check/family/bold_italic_unique_for_nameid1</a>)</summary><div>


* 🔥 **FAIL** Family 'Noto Naskh Arabic UI' has 2 fonts (should be no more than 1) with the same OS/2.fsSelection bold & italic settings: Bold=False, Italic=False [code: unique-fsselection]
</div></details><br></div></details><details><summary><b>[12] NotoNaskhArabicUI-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2026 (HORIZONTAL ELLIPSIS)


	- 0x002A (ASTERISK)


	- 0x0023 (NUMBER SIGN)


	- 0x002F (SOLIDUS)


	- 0x005C (REVERSE SOLIDUS)


	- 0x002D (HYPHEN-MINUS)


	- 0x0028 (LEFT PARENTHESIS)


	- 0x0029 (RIGHT PARENTHESIS)


	- 0x007B (LEFT CURLY BRACKET)


	- 0x007D (RIGHT CURLY BRACKET)
 

	- 302 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Naskh Arabic UI [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1200, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 419, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0654 

	- uni065B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
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

	- 32 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0616 (U+0616): L<<18.0,698.0>--<18.0,738.0>> -> L<<18.0,738.0>--<15.0,810.0>>

	* uni0616 (U+0616): L<<18.0,738.0>--<15.0,810.0>> -> L<<15.0,810.0>--<8.0,907.0>>

	* uni0616 (U+0616): L<<46.0,879.0>--<48.0,813.0>> -> L<<48.0,813.0>--<48.0,792.0>>

	* uni0616 (U+0616): L<<48.0,813.0>--<48.0,792.0>> -> L<<48.0,792.0>--<45.0,703.0>>

	* uni065E (U+065E): L<<8.0,696.0>--<22.0,715.0>> -> L<<22.0,715.0>--<37.0,734.0>>

	* uni06AD (U+06AD): L<<269.0,688.0>--<295.0,714.0>> -> L<<295.0,714.0>--<319.0,739.0>>

	* uni06AD (U+FBD3): L<<269.0,688.0>--<295.0,714.0>> -> L<<295.0,714.0>--<319.0,739.0>>

	* uni06D9 (U+06D9): L<<58.0,825.0>--<58.0,819.0>> -> L<<58.0,819.0>--<60.0,783.0>>

	* uni06DB (U+06DB): L<<5.0,718.0>--<31.0,744.0>> -> L<<31.0,744.0>--<55.0,769.0>>

	* uniFBC1 (U+FBC1): L<<143.0,50.0>--<143.0,36.0>> -> L<<143.0,36.0>--<146.0,-15.0>> 

	* 17 more.

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

	* 137 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoNaskhArabicUI-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2026 (HORIZONTAL ELLIPSIS)


	- 0x002A (ASTERISK)


	- 0x0023 (NUMBER SIGN)


	- 0x002F (SOLIDUS)


	- 0x005C (REVERSE SOLIDUS)


	- 0x002D (HYPHEN-MINUS)


	- 0x0028 (LEFT PARENTHESIS)


	- 0x0029 (RIGHT PARENTHESIS)


	- 0x007B (LEFT CURLY BRACKET)


	- 0x007D (RIGHT CURLY BRACKET)
 

	- 302 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Naskh Arabic UI Medium [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1200, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 419, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0654 

	- uni065B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
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

	- 32 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0616 (U+0616): L<<20.0,702.0>--<20.0,739.0>> -> L<<20.0,739.0>--<17.0,810.0>>

	* uni0616 (U+0616): L<<20.0,739.0>--<17.0,810.0>> -> L<<17.0,810.0>--<10.0,907.0>>

	* uni0616 (U+0616): L<<41.0,881.0>--<43.0,813.0>> -> L<<43.0,813.0>--<43.0,792.0>>

	* uni0616 (U+0616): L<<43.0,813.0>--<43.0,792.0>> -> L<<43.0,792.0>--<40.0,706.0>>

	* uni065E (U+065E): L<<11.0,700.0>--<24.0,718.0>> -> L<<24.0,718.0>--<38.0,735.0>>

	* uni0695 (U+0695): L<<11.0,-111.0>--<27.0,-107.0>> -> L<<27.0,-107.0>--<42.0,-104.0>>

	* uni06AD (U+06AD): L<<251.0,679.0>--<275.0,703.0>> -> L<<275.0,703.0>--<296.0,725.0>>

	* uni06AD (U+FBD3): L<<251.0,679.0>--<275.0,703.0>> -> L<<275.0,703.0>--<296.0,725.0>>

	* uni06D9 (U+06D9): L<<59.0,826.0>--<59.0,819.0>> -> L<<59.0,819.0>--<61.0,771.0>>

	* uni06DB (U+06DB): L<<9.0,722.0>--<33.0,746.0>> -> L<<33.0,746.0>--<54.0,768.0>> 

	* 19 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uniFDFA (U+FDFA): B<<675.5,625.5>-<668.0,627.0>-<662.0,629.0>>/B<<662.0,629.0>-<692.0,613.0>-<702.5,605.0>> = 9.637538112930923

	* uniFEF6 (U+FEF6): B<<461.0,433.0>-<458.0,478.0>-<454.0,534.0>>/L<<454.0,534.0>--<451.0,507.0>> = 10.425808525884747

	* uniFEF8 (U+FEF8): B<<461.0,433.0>-<458.0,478.0>-<454.0,534.0>>/L<<454.0,534.0>--<451.0,507.0>> = 10.425808525884747

	* uniFEFA (U+FEFA): B<<461.0,433.0>-<458.0,478.0>-<454.0,534.0>>/L<<454.0,534.0>--<451.0,507.0>> = 10.425808525884747 

	* uniFEFC (U+FEFC): B<<461.0,433.0>-<458.0,478.0>-<454.0,534.0>>/L<<454.0,534.0>--<451.0,507.0>> = 10.425808525884747 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni066D (U+066D): L<<21.0,418.0>--<156.0,417.0>> 

	* uni066D (U+066D): L<<243.0,417.0>--<380.0,418.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoNaskhArabicUI-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2026 (HORIZONTAL ELLIPSIS)


	- 0x002A (ASTERISK)


	- 0x0023 (NUMBER SIGN)


	- 0x002F (SOLIDUS)


	- 0x005C (REVERSE SOLIDUS)


	- 0x002D (HYPHEN-MINUS)


	- 0x0028 (LEFT PARENTHESIS)


	- 0x0029 (RIGHT PARENTHESIS)


	- 0x007B (LEFT CURLY BRACKET)


	- 0x007D (RIGHT CURLY BRACKET)
 

	- 302 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Naskh Arabic UI [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1200, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 419, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0654 

	- uni065B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
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

	- 32 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0616 (U+0616): L<<21.0,704.0>--<21.0,739.0>> -> L<<21.0,739.0>--<18.0,810.0>>

	* uni0616 (U+0616): L<<21.0,739.0>--<18.0,810.0>> -> L<<18.0,810.0>--<11.0,907.0>>

	* uni0616 (U+0616): L<<39.0,882.0>--<41.0,813.0>> -> L<<41.0,813.0>--<41.0,792.0>>

	* uni0616 (U+0616): L<<41.0,813.0>--<41.0,792.0>> -> L<<41.0,792.0>--<38.0,707.0>>

	* uni065E (U+065E): L<<12.0,702.0>--<25.0,720.0>> -> L<<25.0,720.0>--<38.0,736.0>>

	* uni0695 (U+0695): L<<16.0,-115.0>--<32.0,-111.0>> -> L<<32.0,-111.0>--<47.0,-108.0>>

	* uni06AD (U+06AD): L<<242.0,674.0>--<265.0,697.0>> -> L<<265.0,697.0>--<285.0,718.0>>

	* uni06AD (U+FBD3): L<<242.0,674.0>--<265.0,697.0>> -> L<<265.0,697.0>--<285.0,718.0>>

	* uni06D9 (U+06D9): L<<59.0,827.0>--<60.0,819.0>> -> L<<60.0,819.0>--<62.0,765.0>>

	* uni06DB (U+06DB): L<<11.0,724.0>--<34.0,747.0>> -> L<<34.0,747.0>--<54.0,768.0>> 

	* 19 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uniFDFA (U+FDFA): B<<691.0,623.0>-<670.0,623.0>-<651.0,630.0>>/B<<651.0,630.0>-<675.0,618.0>-<688.0,611.0>> = 6.34019174590985

	* uniFEF6 (U+FEF6): B<<458.5,417.5>-<455.0,468.0>-<450.0,540.0>>/L<<450.0,540.0>--<447.0,513.0>> = 10.312687686660533

	* uniFEF8 (U+FEF8): B<<458.5,417.5>-<455.0,468.0>-<450.0,540.0>>/L<<450.0,540.0>--<447.0,513.0>> = 10.312687686660533

	* uniFEFA (U+FEFA): B<<458.5,417.5>-<455.0,468.0>-<450.0,540.0>>/L<<450.0,540.0>--<447.0,513.0>> = 10.312687686660533 

	* uniFEFC (U+FEFC): B<<458.5,417.5>-<455.0,468.0>-<450.0,540.0>>/L<<450.0,540.0>--<447.0,513.0>> = 10.312687686660533 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoNaskhArabicUI[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x2026 (HORIZONTAL ELLIPSIS)


	- 0x002A (ASTERISK)


	- 0x0023 (NUMBER SIGN)


	- 0x002F (SOLIDUS)


	- 0x005C (REVERSE SOLIDUS)


	- 0x002D (HYPHEN-MINUS)


	- 0x0028 (LEFT PARENTHESIS)


	- 0x0029 (RIGHT PARENTHESIS)


	- 0x007B (LEFT CURLY BRACKET)


	- 0x007D (RIGHT CURLY BRACKET)
 

	- 302 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Naskh Arabic UI [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1200, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 419, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0654 

	- uni065B [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
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

	- 32 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Detect any interpolation issues in the font. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/interpolation_issues">com.google.fonts/check/interpolation_issues</a>)</summary><div>


* ⚠ **WARN** Interpolation issues were found in the font: 	- Contour 0 start point differs in glyph 'uni0602' between location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7f0fa1514690> and location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7f0fa2063810> [code: interpolation-issues]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 4 | 25 | 30 | 455 | 26 | 393 | 0 |
| 0% | 3% | 3% | 49% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
