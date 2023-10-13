## FontBakery report

fontbakery version: 0.10.0

<details><summary><b>[12] NotoSansArabicUI[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 512, but got 293 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- acutecomb

	- dotabovear

	- dotbelowar

	- fourdotsabovear

	- fourdotsbelowar

	- gravecomb

	- ringar

	- tahbelowar

	- threedotsdownabovear

	- threedotsdownbelowar

	- threedotsupabovear

	- threedotsupbelowar

	- tildecomb

	- twodotshorizontalabovear

	- twodotshorizontalbelowar

	- twodotsverticalabovear

	- twodotsverticalbelowar

	- uni0302

	- uni0304

	- uni0306

	- uni0307

	- uni0308

	- uni030A

	- uni030B

	- uni030C

	- uni0312

	- uni0326

	- uni0327

	- uni0328

	- uni0610

	- uni0611

	- uni0612

	- uni0613

	- uni0614

	- uni0615

	- uni0616

	- uni0617

	- uni0618

	- uni0619

	- uni061A

	- uni064B

	- uni064C

	- uni064D

	- uni064E

	- uni064F

	- uni0650

	- uni0651

	- uni0652

	- uni0653

	- uni0654

	- uni0655

	- uni0656

	- uni0657

	- uni0658

	- uni0659

	- uni065A

	- uni065B

	- uni065C

	- uni065D

	- uni065E

	- uni065F

	- uni0670

	- uni06DC

	- uni06DF

	- uni06E0

	- uni06E1

	- uni06E2

	- uni06E3

	- uni06E4

	- uni06E7

	- uni06E8

	- uni06EA

	- uni06EB

	- uni06EC

	- uni06ED

	- uni08D3

	- uni08D4

	- uni08D5

	- uni08D6

	- uni08D7

	- uni08D8

	- uni08D9

	- uni08DA

	- uni08DB

	- uni08DC

	- uni08DD

	- uni08DE

	- uni08DF

	- uni08E0

	- uni08E1

	- uni08E3

	- uni08E4

	- uni08E5

	- uni08E6

	- uni08E7

	- uni08E8

	- uni08E9

	- uni08EA

	- uni08EB

	- uni08EC

	- uni08ED

	- uni08EE

	- uni08EF

	- uni08F0

	- uni08F1

	- uni08F2

	- uni08F3

	- uni08F4

	- uni08F5

	- uni08F6

	- uni08F7

	- uni08F8

	- uni08F9

	- uni08FA

	- uni08FB

	- uni08FC

	- uni08FD

	- uni08FE

	- uni08FF [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, malayalam, canadian-aboriginal, tai-le, old-permic, math, coptic, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+034F COMBINING GRAPHEME JOINER: not included in any glyphset definition
 * U+0605 ARABIC NUMBER MARK ABOVE: not included in any glyphset definition
 * U+08E2 ARABIC DISPUTED END OF AYAH: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: javanese, khojki, malayalam, mandaic, duployan, siddham, sharada, batak, mongolian, takri, balinese, avestan, devanagari, khudawadi, manichaean, nko, sundanese, cham, buginese, saurashtra, buhid, grantha, limbu, syloti-nagri, mahajani, gunjala-gondi, rejang, tamil, telugu, gujarati, modi, bengali, phags-pa, hatran, psalter-pahlavi, gurmukhi, syriac, kharoshthi, thai, brahmi, sinhala, warang-citi, tifinagh, pahawh-hmong, tai-tham, kannada, hanunoo, tibetan, dogra, lepcha, myanmar, chakma, sogdian, khmer, hanifi-rohingya, tirhuta, yi, kaithi, tagalog, thaana, kayah-li, tai-le, oriya, newa, tagbanwa, meetei-mayek, tai-viet, new-tai-lue
 * U+200D ZERO WIDTH JOINER: try adding one of: javanese, khojki, malayalam, mandaic, duployan, siddham, sharada, batak, mongolian, takri, balinese, avestan, devanagari, khudawadi, manichaean, nko, sundanese, cham, buginese, saurashtra, buhid, grantha, limbu, syloti-nagri, mahajani, gunjala-gondi, rejang, tamil, telugu, gujarati, modi, bengali, phags-pa, psalter-pahlavi, gurmukhi, syriac, kharoshthi, thai, brahmi, sinhala, warang-citi, tifinagh, pahawh-hmong, tai-tham, kannada, hanunoo, tibetan, dogra, lepcha, myanmar, chakma, yi, hanifi-rohingya, tirhuta, kaithi, tagalog, thaana, kayah-li, old-hungarian, tai-le, oriya, newa, tagbanwa, meetei-mayek, tai-viet, new-tai-lue
 * U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, phags-pa, nko, thaana
 * U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, phags-pa, nko, thaana
 * U+2010 HYPHEN: try adding one of: kaithi, yi, syloti-nagri, kayah-li, sundanese, coptic, lisu, kharoshthi, cham, sora-sompeng
 * U+2011 NON-BREAKING HYPHEN: try adding one of: yi, syloti-nagri
 * U+204F REVERSED SEMICOLON: try adding adlam
 * U+25CC DOTTED CIRCLE: try adding one of: mandaic, siddham, math, takri, devanagari, bassa-vah, rejang, telugu, bengali, psalter-pahlavi, kharoshthi, masaram-gondi, khmer, tirhuta, kaithi, soyombo, khojki, sharada, mongolian, coptic, khudawadi, buginese, tamil, zanabazar-square, miao, modi, gurmukhi, sinhala, tifinagh, ahom, music, wancho, hanunoo, myanmar, hanifi-rohingya, thaana, tagalog, kayah-li, tai-le, oriya, tagbanwa, duployan, osage, batak, balinese, sundanese, cham, buhid, syloti-nagri, gujarati, kannada, chakma, sogdian, meetei-mayek, tai-viet, new-tai-lue, elbasan, javanese, malayalam, adlam, nko, manichaean, grantha, limbu, mahajani, gunjala-gondi, symbols, phags-pa, caucasian-albanian, syriac, thai, brahmi, pahawh-hmong, mende-kikakui, marchen, tibetan, dogra, lepcha, yi, hebrew, bhaiksuki, lao, newa, old-permic
 * U+2E41 REVERSED COMMA: try adding adlam

Or you can add the above codepoints to one of the subsets supported by the font: `arabic`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure files are not too large. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/file_size">com.google.fonts/check/file_size</a>)</summary><div>


* ⚠ **WARN** Font file is 1.0Mb; ideally it should be less than 1.0Mb [code: large-font]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
behThreedotsupbelowVabovear.fina, behThreedotsupbelowVabovear.init, behThreedotsupbelowVabovear.medi, dalTwodotsverticalbelowTahabovear, dalTwodotsverticalbelowTahabovear.fina, seenThreedotsbelowthreedotsar.fina, seenThreedotsbelowthreedotsar.init and seenThreedotsbelowthreedotsar.medi [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni06060607.pt

	- uni06440671.001

	- uni06440671.isol

	- uni06440672.isol

	- uni06440673.isol

	- uni064406D2.fina

	- uni06B50627.isol

	- uni06B60627.isol

	- uni06B70627.isol

	- uni06B80627.isol

	- uniFDFD.001

	- uniFEF5.isol

	- uniFEF7.isol

	- uniFEF9.isol

	- uniFEFB.isol
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Detect any interpolation issues in the font. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/interpolation_issues">com.google.fonts/check/interpolation_issues</a>)</summary><div>


* ⚠ **WARN** Interpolation issues were found in the font:

	- Contour 2 start point differs in glyph 'uni08A5' between location wght=400,wdth=100 and location wght=900,wdth=100

	- Contour 3 start point differs in glyph 'uni08A5' between location wght=400,wdth=100 and location wght=900,wdth=100

	- Contour 2 start point differs in glyph 'uni08A5' between location wght=400,wdth=100 and location wght=900,wdth=62

	- Contour 3 start point differs in glyph 'uni08A5' between location wght=400,wdth=100 and location wght=900,wdth=62

	- Contour 5 start point differs in glyph 'uniFD3E' between location wght=400,wdth=100 and location wght=704,wdth=100

	- Contour 5 start point differs in glyph 'uniFD3E' between location wght=400,wdth=100 and location wght=704,wdth=62

	- Contour 2 start point differs in glyph 'uni08A5.fina' between location wght=400,wdth=100 and location wght=900,wdth=100

	- Contour 3 start point differs in glyph 'uni08A5.fina' between location wght=400,wdth=100 and location wght=900,wdth=100

	- Contour 2 start point differs in glyph 'uni08A5.fina' between location wght=400,wdth=100 and location wght=900,wdth=62

	- Contour 3 start point differs in glyph 'uni08A5.fina' between location wght=400,wdth=100 and location wght=900,wdth=62 [code: interpolation-issues]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+FBB2, U+FBB3, U+FBB4, U+FBB5, U+FBB6, U+FBB7, U+FBB8, U+FBB9, U+FBBA, U+FBBB, U+FBBD, U+FBBE, U+FBBF and U+FBC1 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Lugbara (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Avokaya (Latn, 100,000 speakers), Basaa (Latn, 332,940 speakers), Kom (Latn, 360,685 speakers), Dutch (Latn, 31,709,104 speakers), Nateni (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ejagham (Latn, 120,000 speakers), Ma’di (Latn, 584,000 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 3 | 9 | 100 | 8 | 130 | 0 |
| 0% | 1% | 4% | 40% | 3% | 52% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
