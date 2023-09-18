## FontBakery report

fontbakery version: 0.9.0

<details><summary><b>[4] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoNaskhArabic/googlefonts/ttf', 'fonts/NotoNaskhArabic/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that OS/2.fsSelection bold & italic settings are unique for each NameID1 (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.adobe.fonts/check/family/bold_italic_unique_for_nameid1">com.adobe.fonts/check/family/bold_italic_unique_for_nameid1</a>)</summary><div>


* 🔥 **FAIL** Family 'Noto Naskh Arabic' has 2 fonts (should be no more than 1) with the same OS/2.fsSelection bold & italic settings: Bold=False, Italic=False [code: unique-fsselection]
</div></details><details><summary>⚠ <b>WARN:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* ⚠ **WARN** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>⚠ <b>WARN:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* ⚠ **WARN** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[19] NotoNaskhArabic-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 💔 **ERROR** Failed with KeyError: 'uni0661.ccmp'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1408, but got 1069 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* exclamdown
	* uni0604
	* uni0647
	* uni066B
	* uni066C
	* uni0678
	* uni06C7
	* uni0750
	* uni08AC
	* uni204F and 3 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0627 + uni0644.init

	- uni0644.init + uni0644.medi

	- uni0644.medi + uni06510670

	- uni06510670 + uni0647.fina

	- uni0647.fina + uni0644.init

	- uni06510670 + uni06C1.fina [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
twodotshorizontalabove_tahabovear, twodotshorizontalabovear.diagonal, twodotshorizontalbelow_tahabovear and twodotshorizontalcenter_tahabovear [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- alayh.1

	- alayh.2

	- fatha.1

	- la.1

	- radiya.1

	- uni0640.wide

	- uni06F7.mark
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0616 (U+0616): L<<215.0,1117.0>--<215.0,1157.0>> -> L<<215.0,1157.0>--<212.0,1229.0>>

	* uni0616 (U+0616): L<<215.0,1157.0>--<212.0,1229.0>> -> L<<212.0,1229.0>--<205.0,1326.0>>

	* uni0616 (U+0616): L<<243.0,1298.0>--<245.0,1232.0>> -> L<<245.0,1232.0>--<245.0,1211.0>>

	* uni0616 (U+0616): L<<245.0,1232.0>--<245.0,1211.0>> -> L<<245.0,1211.0>--<242.0,1122.0>>

	* uni0637.init (U+FEC3): L<<0.0,127.0>--<83.0,128.0>> -> L<<83.0,128.0>--<103.0,128.0>>

	* uni065E (U+065E): L<<107.0,763.0>--<121.0,782.0>> -> L<<121.0,782.0>--<136.0,801.0>>

	* uni06AD (U+06AD): L<<270.0,493.0>--<296.0,519.0>> -> L<<296.0,519.0>--<320.0,544.0>>

	* uni06AD (U+FBD3): L<<270.0,493.0>--<296.0,519.0>> -> L<<296.0,519.0>--<320.0,544.0>>

	* uni06DB (U+06DB): L<<105.0,1094.0>--<131.0,1120.0>> -> L<<131.0,1120.0>--<155.0,1145.0>>

	* uni08C3 (U+08C3): L<<239.0,725.0>--<265.0,751.0>> -> L<<265.0,751.0>--<289.0,776.0>>

	* 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0649.fina (U+FBFD): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uni0649.fina (U+FEF0): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFBE5 (U+FBE5): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFBF6 (U+FBF6): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFBF7 (U+FBF7): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFBF9 (U+FBF9): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFBFA (U+FBFA): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFC03 (U+FC03): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFC04 (U+FC04): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* uniFC09 (U+FC09): B<<590.5,17.0>-<563.0,21.0>-<543.0,26.0>>/B<<543.0,26.0>-<584.0,7.0>-<605.5,-4.0>> = 10.827453103825361

	* 159 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<101.0,122.0>--<100.0,646.0>>

	* h (U+0068): L<<252.0,309.0>--<253.0,118.0>>

	* sterling (U+00A3): L<<428.0,346.0>--<270.0,347.0>>

	* uni0890 (U+0890): L<<644.0,893.0>--<926.0,895.0>>

	* uni0891 (U+0891): L<<724.0,895.0>--<1006.0,893.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] NotoNaskhArabic-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1408, but got 1069 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* exclamdown
	* uni0604
	* uni0647
	* uni066B
	* uni066C
	* uni0678
	* uni0750
	* uni08AC and uniFDFD
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0627 + uni0644.init

	- uni0644.init + uni0644.medi

	- uni0644.medi + uni06510670

	- uni06510670 + uni0647.fina

	- uni0647.fina + uni0644.init

	- uni06510670 + uni06C1.fina [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Naskh Arabic Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
twodotshorizontalabove_tahabovear, twodotshorizontalabovear.diagonal, twodotshorizontalbelow_tahabovear and twodotshorizontalcenter_tahabovear [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- alayh.1

	- alayh.2

	- fatha.1

	- la.1

	- radiya.1

	- uni0640.wide

	- uni06F7.mark
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0616 (U+0616): L<<215.0,1124.0>--<215.0,1161.0>> -> L<<215.0,1161.0>--<212.0,1232.0>>

	* uni0616 (U+0616): L<<215.0,1161.0>--<212.0,1232.0>> -> L<<212.0,1232.0>--<205.0,1329.0>>

	* uni0616 (U+0616): L<<236.0,1303.0>--<238.0,1235.0>> -> L<<238.0,1235.0>--<238.0,1214.0>>

	* uni0616 (U+0616): L<<238.0,1235.0>--<238.0,1214.0>> -> L<<238.0,1214.0>--<235.0,1128.0>>

	* uni0637.init (U+FEC3): L<<0.0,93.0>--<83.0,94.0>> -> L<<83.0,94.0>--<92.0,94.0>>

	* uni065E (U+065E): L<<106.0,766.0>--<120.0,784.0>> -> L<<120.0,784.0>--<133.0,801.0>>

	* uni0695 (U+0695): L<<11.0,-263.0>--<27.0,-259.0>> -> L<<27.0,-259.0>--<42.0,-256.0>>

	* uni06AD (U+06AD): L<<251.0,472.0>--<275.0,496.0>> -> L<<275.0,496.0>--<296.0,518.0>>

	* uni06AD (U+FBD3): L<<251.0,472.0>--<275.0,496.0>> -> L<<275.0,496.0>--<296.0,518.0>>

	* uni06DB (U+06DB): L<<105.0,1096.0>--<129.0,1120.0>> -> L<<129.0,1120.0>--<150.0,1142.0>>

	* 14 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* sallaallahar (U+FDFA): B<<675.5,490.5>-<668.0,492.0>-<662.0,494.0>>/B<<662.0,494.0>-<692.0,478.0>-<702.5,470.0>> = 9.637538112930923

	* uniFD46 (U+FD46): B<<677.5,490.5>-<670.0,492.0>-<664.0,494.0>>/B<<664.0,494.0>-<694.0,478.0>-<704.0,470.0>> = 9.637538112930923

	* uniFD47 (U+FD47): B<<695.0,447.0>-<694.0,462.0>-<693.0,472.0>>/B<<693.0,472.0>-<689.0,436.0>-<685.0,406.0>> = 12.050784883409548

	* uniFD48 (U+FD48): B<<822.0,447.0>-<821.0,462.0>-<821.0,472.0>>/B<<821.0,472.0>-<817.0,436.0>-<813.0,406.0>> = 6.340191745909908

	* uniFD49 (U+FD49): B<<562.0,447.0>-<561.0,462.0>-<560.0,472.0>>/B<<560.0,472.0>-<556.0,436.0>-<552.0,406.0>> = 12.050784883409548

	* uniFD4A (U+FD4A): B<<486.0,487.5>-<485.0,503.0>-<484.0,512.0>>/B<<484.0,512.0>-<480.0,476.0>-<476.0,446.0>> = 12.680383491819825

	* uniFD4A (U+FD4A): B<<490.0,164.0>-<489.0,179.0>-<488.0,188.0>>/B<<488.0,188.0>-<484.0,153.0>-<480.0,122.5>> = 12.859993497566874

	* uniFD4C (U+FD4C): B<<975.5,490.5>-<968.0,492.0>-<962.0,494.0>>/B<<962.0,494.0>-<992.0,478.0>-<1002.5,470.0>> = 9.637538112930923

	* uniFD4D (U+FD4D): B<<570.0,447.0>-<569.0,462.0>-<568.0,472.0>>/B<<568.0,472.0>-<564.0,436.0>-<560.0,406.0>> = 12.050784883409548

	* uniFDCF (U+FDCF): B<<785.0,426.0>-<784.0,441.0>-<784.0,450.0>>/B<<784.0,450.0>-<780.0,415.0>-<776.0,384.5>> = 6.5198017516569164

	* 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<106.0,117.0>--<105.0,649.0>>

	* uni066D (U+066D): L<<21.0,283.0>--<156.0,282.0>>

	* uni066D (U+066D): L<<243.0,282.0>--<380.0,283.0>>

	* uni0890 (U+0890): L<<644.0,879.0>--<966.0,881.0>>

	* uni0891 (U+0891): L<<684.0,881.0>--<1006.0,879.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] NotoNaskhArabic-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 💔 **ERROR** Failed with KeyError: 'uni0661.ccmp'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1408, but got 1069 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* exclamdown
	* uni0604
	* uni0647
	* uni066B
	* uni066C
	* uni0678
	* uni0750
	* uni08AC
	* uni204F and uniFDFD
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0627 + uni0644.init

	- uni0644.init + uni0644.medi

	- uni0644.medi + uni06510670

	- uni06510670 + uni0647.fina

	- uni0647.fina + uni0644.init

	- uni06510670 + uni06C1.fina [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
twodotshorizontalabove_tahabovear, twodotshorizontalabovear.diagonal, twodotshorizontalbelow_tahabovear and twodotshorizontalcenter_tahabovear [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- alayh.1

	- alayh.2

	- fatha.1

	- la.1

	- radiya.1

	- uni0640.wide

	- uni06F7.mark
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0616 (U+0616): L<<215.0,1128.0>--<215.0,1163.0>> -> L<<215.0,1163.0>--<212.0,1234.0>>

	* uni0616 (U+0616): L<<215.0,1163.0>--<212.0,1234.0>> -> L<<212.0,1234.0>--<205.0,1331.0>>

	* uni0616 (U+0616): L<<233.0,1306.0>--<235.0,1237.0>> -> L<<235.0,1237.0>--<235.0,1216.0>>

	* uni0616 (U+0616): L<<235.0,1237.0>--<235.0,1216.0>> -> L<<235.0,1216.0>--<232.0,1131.0>>

	* uni0637.init (U+FEC3): L<<0.0,76.0>--<83.0,77.0>> -> L<<83.0,77.0>--<86.0,77.0>>

	* uni065E (U+065E): L<<106.0,767.0>--<119.0,785.0>> -> L<<119.0,785.0>--<132.0,801.0>>

	* uni0695 (U+0695): L<<16.0,-270.0>--<32.0,-266.0>> -> L<<32.0,-266.0>--<47.0,-263.0>>

	* uni06AD (U+06AD): L<<242.0,461.0>--<265.0,484.0>> -> L<<265.0,484.0>--<285.0,505.0>>

	* uni06AD (U+FBD3): L<<242.0,461.0>--<265.0,484.0>> -> L<<265.0,484.0>--<285.0,505.0>>

	* uni06DB (U+06DB): L<<105.0,1097.0>--<128.0,1120.0>> -> L<<128.0,1120.0>--<148.0,1141.0>>

	* 14 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* sallaallahar (U+FDFA): B<<691.0,488.0>-<670.0,488.0>-<651.0,495.0>>/B<<651.0,495.0>-<675.0,483.0>-<688.0,476.0>> = 6.34019174590985

	* uniFD46 (U+FD46): B<<691.0,488.0>-<670.0,488.0>-<651.0,495.0>>/B<<651.0,495.0>-<675.0,483.0>-<688.0,476.0>> = 6.34019174590985

	* uniFD47 (U+FD47): B<<686.0,432.0>-<685.0,448.0>-<685.0,459.0>>/B<<685.0,459.0>-<683.0,443.0>-<680.0,419.5>> = 7.125016348901757

	* uniFD48 (U+FD48): B<<816.0,432.0>-<815.0,448.0>-<815.0,459.0>>/B<<815.0,459.0>-<813.0,443.0>-<810.0,419.5>> = 7.125016348901757

	* uniFD49 (U+FD49): B<<549.0,432.0>-<548.0,448.0>-<548.0,459.0>>/B<<548.0,459.0>-<546.0,443.0>-<543.0,419.5>> = 7.125016348901757

	* uniFD4A (U+FD4A): B<<477.0,476.0>-<476.0,492.0>-<476.0,503.0>>/B<<476.0,503.0>-<474.0,487.0>-<471.0,463.5>> = 7.125016348901757

	* uniFD4A (U+FD4A): B<<482.0,152.0>-<481.0,168.0>-<481.0,179.0>>/B<<481.0,179.0>-<479.0,163.0>-<476.0,139.5>> = 7.125016348901757

	* uniFD4C (U+FD4C): B<<981.0,488.0>-<960.0,488.0>-<941.0,495.0>>/B<<941.0,495.0>-<965.0,483.0>-<978.0,476.0>> = 6.34019174590985

	* uniFD4D (U+FD4D): B<<559.0,432.0>-<558.0,448.0>-<558.0,459.0>>/B<<558.0,459.0>-<556.0,443.0>-<553.0,419.5>> = 7.125016348901757

	* uniFDCF (U+FDCF): B<<783.0,427.0>-<782.0,443.0>-<782.0,454.0>>/B<<782.0,454.0>-<780.0,438.0>-<777.0,414.5>> = 7.125016348901757

	* 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0890 (U+0890): L<<644.0,872.0>--<986.0,874.0>>

	* uni0891 (U+0891): L<<664.0,874.0>--<1006.0,872.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] NotoNaskhArabic-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1408, but got 1069 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* exclamdown
	* uni0604
	* uni0647
	* uni066B
	* uni066C
	* uni0678
	* uni0750
	* uni08AC and uniFDFD
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0627 + uni0644.init

	- uni0644.init + uni0644.medi

	- uni0644.medi + uni06510670

	- uni06510670 + uni0647.fina

	- uni0647.fina + uni0644.init

	- uni06510670 + uni06C1.fina [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Naskh Arabic SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
twodotshorizontalabove_tahabovear, twodotshorizontalabovear.diagonal, twodotshorizontalbelow_tahabovear and twodotshorizontalcenter_tahabovear [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- alayh.1

	- alayh.2

	- fatha.1

	- la.1

	- radiya.1

	- uni0640.wide

	- uni06F7.mark
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0616 (U+0616): L<<215.0,1121.0>--<215.0,1159.0>> -> L<<215.0,1159.0>--<212.0,1231.0>>

	* uni0616 (U+0616): L<<215.0,1159.0>--<212.0,1231.0>> -> L<<212.0,1231.0>--<205.0,1328.0>>

	* uni0616 (U+0616): L<<240.0,1301.0>--<242.0,1234.0>> -> L<<242.0,1234.0>--<242.0,1213.0>>

	* uni0616 (U+0616): L<<242.0,1234.0>--<242.0,1213.0>> -> L<<242.0,1213.0>--<239.0,1125.0>>

	* uni0637.init (U+FEC3): L<<0.0,110.0>--<83.0,111.0>> -> L<<83.0,111.0>--<97.0,111.0>>

	* uni065E (U+065E): L<<107.0,764.0>--<120.0,783.0>> -> L<<120.0,783.0>--<135.0,801.0>>

	* uni06AD (U+06AD): L<<261.0,482.0>--<286.0,507.0>> -> L<<286.0,507.0>--<309.0,531.0>>

	* uni06AD (U+FBD3): L<<261.0,482.0>--<286.0,507.0>> -> L<<286.0,507.0>--<309.0,531.0>>

	* uni06DB (U+06DB): L<<105.0,1095.0>--<130.0,1120.0>> -> L<<130.0,1120.0>--<153.0,1144.0>>

	* uni08C3 (U+08C3): L<<237.0,720.0>--<262.0,745.0>> -> L<<262.0,745.0>--<285.0,769.0>>

	* 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* sallaallahar (U+FDFA): B<<681.5,490.0>-<677.0,491.0>-<673.0,492.0>>/B<<673.0,492.0>-<698.0,479.0>-<706.0,470.5>> = 13.438188158350664

	* uni0649.fina (U+FBFD): B<<617.5,11.0>-<573.0,16.0>-<542.0,23.0>>/B<<542.0,23.0>-<590.0,0.0>-<610.0,-11.0>> = 12.8778318660194

	* uni0649.fina (U+FEF0): B<<617.5,11.0>-<573.0,16.0>-<542.0,23.0>>/B<<542.0,23.0>-<590.0,0.0>-<610.0,-11.0>> = 12.8778318660194

	* uniFBE5 (U+FBE5): B<<617.5,11.0>-<573.0,16.0>-<542.0,23.0>>/B<<542.0,23.0>-<590.0,0.0>-<610.0,-11.0>> = 12.8778318660194

	* uniFBF6 (U+FBF6): B<<617.5,11.0>-<573.0,16.0>-<542.0,23.0>>/B<<542.0,23.0>-<590.0,0.0>-<610.0,-11.0>> = 12.8778318660194

	* uniFBF7 (U+FBF7): B<<617.5,11.0>-<573.0,16.0>-<542.0,23.0>>/B<<542.0,23.0>-<590.0,0.0>-<610.0,-11.0>> = 12.8778318660194

	* uniFBF9 (U+FBF9): B<<617.5,11.0>-<573.0,16.0>-<542.0,23.0>>/B<<542.0,23.0>-<590.0,0.0>-<610.0,-11.0>> = 12.8778318660194

	* uniFBFA (U+FBFA): B<<617.5,11.0>-<573.0,16.0>-<542.0,23.0>>/B<<542.0,23.0>-<590.0,0.0>-<610.0,-11.0>> = 12.8778318660194

	* uniFC03 (U+FC03): B<<617.5,11.0>-<573.0,16.0>-<542.0,23.0>>/B<<542.0,23.0>-<590.0,0.0>-<610.0,-11.0>> = 12.8778318660194

	* uniFC04 (U+FC04): B<<617.5,11.0>-<573.0,16.0>-<542.0,23.0>>/B<<542.0,23.0>-<590.0,0.0>-<610.0,-11.0>> = 12.8778318660194

	* 145 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<235.0,313.0>--<236.0,115.0>>

	* sterling (U+00A3): L<<419.0,343.0>--<261.0,344.0>>

	* uni0890 (U+0890): L<<644.0,886.0>--<946.0,888.0>>

	* uni0891 (U+0891): L<<704.0,888.0>--<1006.0,886.0>>

	* uniFD40 (U+FD40): L<<610.0,556.0>--<609.0,335.0>>

	* uniFD41 (U+FD41): L<<689.0,545.0>--<688.0,323.0>>

	* uniFD42 (U+FD42): L<<729.0,631.0>--<728.0,409.0>>

	* uniFD44 (U+FD44): L<<827.0,644.0>--<826.0,423.0>>

	* uniFD45 (U+FD45): L<<797.0,644.0>--<796.0,423.0>>

	* uniFD4C (U+FD4C): L<<1043.0,174.0>--<1044.0,1.0>>

	* 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[20] NotoNaskhArabic[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check that no collisions are found while shaping (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/collides">com.google.fonts/check/shaping/collides</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'collidoscope'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1408, but got 1069 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* exclamdown
	* uni0604
	* uni0647
	* uni066B
	* uni066C
	* uni0678
	* uni0750
	* uni204F and uniFDFD
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0627 + uni0644.init

	- uni0644.init + uni0644.medi

	- uni0644.medi + uni06510670

	- uni06510670 + uni0647.fina

	- uni0647.fina + uni0644.init

	- uni06510670 + uni06C1.fina [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure variable fonts include an avar table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mandatory_avar_table">com.google.fonts/check/mandatory_avar_table</a>)</summary><div>


* ⚠ **WARN** This variable font does not have an avar table. [code: missing-avar]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if uppercase glyphs are vertically centered. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/caps_vertically_centered">com.google.fonts/check/caps_vertically_centered</a>)</summary><div>


* ⚠ **WARN** Uppercase glyphs are not vertically centered in the em box. [code: vertical-metrics-not-centered]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
twodotshorizontalabove_tahabovear, twodotshorizontalabovear.diagonal, twodotshorizontalbelow_tahabovear and twodotshorizontalcenter_tahabovear [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- alayh.1

	- alayh.2

	- fatha.1

	- la.1

	- radiya.1

	- uni0640.wide

	- uni06F7.mark
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Detect any interpolation issues in the font. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/interpolation_issues">com.google.fonts/check/interpolation_issues</a>)</summary><div>


* ⚠ **WARN** Interpolation issues were found in the font: 	- Contour 0 start point differs in glyph 'uni0602' between location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fc5d0cc5a50> and location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fc5d0cc40d0> [code: interpolation-issues]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 26 | 12 | 62 | 560 | 27 | 495 | 0 |
| 2% | 1% | 5% | 47% | 2% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
