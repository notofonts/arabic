## FontBakery report

fontbakery version: 0.10.0

<details><summary><b>[12] NotoKufiArabic[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics_regressions">com.google.fonts/check/vertical_metrics_regressions</a>)</summary><div>


* 🔥 **FAIL** Noto Kufi Arabic Regular: OS/2 sTypoAscender is 1374 when it should be 1282 [code: bad-typo-ascender]
* 🔥 **FAIL** Noto Kufi Arabic Regular: OS/2 sTypoDescender is -738 when it should be -615 [code: bad-typo-descender]
* 🔥 **FAIL** Noto Kufi Arabic Regular: hhea Ascender is 1374 when it should be 1282 [code: bad-hhea-ascender]
* 🔥 **FAIL** Noto Kufi Arabic Regular: hhea Descender is -738 when it should be -615 [code: bad-hhea-descender]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1507, but got 1374 instead [code: ascent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, math, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, math, syriac, old-permic, tifinagh, coptic, malayalam, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0605 ARABIC NUMBER MARK ABOVE: not included in any glyphset definition
 * U+08E2 ARABIC DISPUTED END OF AYAH: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: manichaean, khudawadi, tai-le, gujarati, nko, kharoshthi, phags-pa, tifinagh, mongolian, tamil, javanese, kayah-li, mahajani, gunjala-gondi, dogra, grantha, buginese, modi, psalter-pahlavi, hatran, lepcha, siddham, warang-citi, syloti-nagri, thaana, tirhuta, new-tai-lue, malayalam, balinese, sundanese, kaithi, tai-viet, tagalog, tai-tham, newa, brahmi, pahawh-hmong, sinhala, sogdian, rejang, batak, khojki, chakma, kannada, saurashtra, buhid, sharada, yi, bengali, limbu, tibetan, hanifi-rohingya, oriya, syriac, devanagari, gurmukhi, myanmar, thai, telugu, avestan, duployan, tagbanwa, mandaic, takri, meetei-mayek, khmer, cham, hanunoo
 * U+200D ZERO WIDTH JOINER: try adding one of: manichaean, khudawadi, tai-le, old-hungarian, gujarati, nko, kharoshthi, phags-pa, tifinagh, mongolian, tamil, javanese, kayah-li, mahajani, gunjala-gondi, dogra, grantha, buginese, modi, psalter-pahlavi, lepcha, siddham, warang-citi, syloti-nagri, thaana, tirhuta, new-tai-lue, malayalam, balinese, sundanese, kaithi, tai-viet, tagalog, tai-tham, newa, brahmi, pahawh-hmong, sinhala, rejang, batak, khojki, chakma, kannada, saurashtra, buhid, sharada, yi, bengali, limbu, tibetan, hanifi-rohingya, oriya, syriac, devanagari, gurmukhi, myanmar, thai, telugu, avestan, duployan, tagbanwa, mandaic, takri, meetei-mayek, cham, hanunoo
 * U+200E LEFT-TO-RIGHT MARK: try adding one of: phags-pa, nko, syriac, thaana
 * U+200F RIGHT-TO-LEFT MARK: try adding one of: phags-pa, nko, syriac, thaana
 * U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian
 * U+204F REVERSED SEMICOLON: try adding adlam
 * U+221A SQUARE ROOT: try adding math
 * U+25CC DOTTED CIRCLE: try adding one of: lao, kharoshthi, tifinagh, kayah-li, mahajani, psalter-pahlavi, dogra, grantha, mende-kikakui, modi, siddham, thaana, pahawh-hmong, miao, elbasan, rejang, khojki, buhid, sharada, yi, hebrew, devanagari, gurmukhi, myanmar, takri, meetei-mayek, khmer, khudawadi, symbols, gujarati, bassa-vah, phags-pa, math, lepcha, syloti-nagri, new-tai-lue, malayalam, sinhala, zanabazar-square, batak, ahom, thai, telugu, tagbanwa, mandaic, tai-le, mongolian, tamil, sundanese, marchen, masaram-gondi, adlam, brahmi, kannada, bengali, oriya, soyombo, duployan, bhaiksuki, tibetan, tirhuta, manichaean, nko, wancho, javanese, osage, coptic, gunjala-gondi, buginese, balinese, kaithi, tai-viet, tagalog, old-permic, newa, sogdian, caucasian-albanian, chakma, limbu, hanifi-rohingya, syriac, music, cham, hanunoo
 * U+2E41 REVERSED COMMA: try adding adlam
 * U+10EFD ARABIC SMALL LOW WORD SAKTA: not included in any glyphset definition
 * U+10EFE ARABIC SMALL LOW WORD QASR: not included in any glyphset definition
 * U+10EFF ARABIC SMALL LOW WORD MADDA: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `arabic`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* uni0600
	* uni0603
	* uni0647
	* uni0657
	* uni0675
	* uni0676
	* uni0677
	* uni0678
	* uni0683
	* uni06AB
	* uni06AD
	* uni06B0
	* uni06B7
	* uni06B8
	* uni06C4
	* uni06D0
	* uni06D1
	* uni06DF
	* uni06E4
	* uni0750
	* uni0767
	* uniFB77
	* uniFBD4
	* uniFBDA
	* uniFBDC
	* uniFBDF
	* uniFBE3
	* uniFBE5
	* uniFD3E
	* uniFD3F
	* uniFE86 and uniFE9E
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni0627 + uni0644.init

	- uni0644.init + uni0644.medi

	- uni0644.medi + uni0651

	- uni0651 + uni0670

	- uni0670 + uni0647.fina

	- uni0647.fina + uni0644.init

	- uni0670 + uni06C1.fina [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure variable fonts include an avar table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mandatory_avar_table">com.google.fonts/check/mandatory_avar_table</a>)</summary><div>


* ⚠ **WARN** This variable font does not have an avar table. [code: missing-avar]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
twodotshorizontalabove_tahabovear, twodotshorizontalabovear.diagonal, twodotshorizontalbelow_tahabovear and twodotshorizontalcenter_tahabovear [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni06F7.mark
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Nateni (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Dan (Latn, 1,099,244 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Belarusian (Cyrl, 10,064,517 speakers), Koonzime (Latn, 40,000 speakers), Ejagham (Latn, 120,000 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers), Lugbara (Latn, 2,200,000 speakers), Igbo (Latn, 27,823,640 speakers), Avokaya (Latn, 100,000 speakers), Dutch (Latn, 31,709,104 speakers), Kom (Latn, 360,685 speakers), Ma’di (Latn, 584,000 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 3 | 9 | 99 | 8 | 131 | 0 |
| 0% | 1% | 4% | 40% | 3% | 52% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
