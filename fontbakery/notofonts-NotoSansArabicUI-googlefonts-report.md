## FontBakery report

fontbakery version: 0.13.2





## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSansArabicUI[wdth,wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check base characters have non-zero advance width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#base-has-width">base_has_width</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs had zero advance width:
- dotabovear (U+FBB2)</p>
<pre><code>- dotbelowar (U+FBB3)

- twodotshorizontalabovear (U+FBB4)

- twodotshorizontalbelowar (U+FBB5)

- threedotsupabovear (U+FBB6)

- threedotsupbelowar (U+FBB7)

- threedotsdownabovear (U+FBB8)

- threedotsdownbelowar (U+FBB9)

- fourdotsabovear (U+FBBA)

- fourdotsbelowar (U+FBBB)

- twodotsverticalabovear (U+FBBD)

- twodotsverticalbelowar (U+FBBE)

- ringar (U+FBBF)

- tahbelowar (U+FBC1)
</code></pre>
 [code: zero-width-bases]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[15] NotoSansArabicUI[wdth,wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check that Arabic spacing symbols U+FBB2–FBC1 aren't classified as marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#arabic-spacing-symbols">arabic_spacing_symbols</a></summary>
    <div>







* 🔥 **FAIL** <p>&quot;dotabovear&quot; is defined in GDEF as a mark (class 3).</p>
 [code: mark-in-gdef]



* 🔥 **FAIL** <p>&quot;dotbelowar&quot; is defined in GDEF as a mark (class 3).</p>
 [code: mark-in-gdef]



* 🔥 **FAIL** <p>&quot;twodotshorizontalabovear&quot; is defined in GDEF as a mark (class 3).</p>
 [code: mark-in-gdef]



* 🔥 **FAIL** <p>&quot;twodotshorizontalbelowar&quot; is defined in GDEF as a mark (class 3).</p>
 [code: mark-in-gdef]



* 🔥 **FAIL** <p>&quot;threedotsupabovear&quot; is defined in GDEF as a mark (class 3).</p>
 [code: mark-in-gdef]



* 🔥 **FAIL** <p>&quot;threedotsupbelowar&quot; is defined in GDEF as a mark (class 3).</p>
 [code: mark-in-gdef]



* 🔥 **FAIL** <p>&quot;threedotsdownabovear&quot; is defined in GDEF as a mark (class 3).</p>
 [code: mark-in-gdef]



* 🔥 **FAIL** <p>&quot;threedotsdownbelowar&quot; is defined in GDEF as a mark (class 3).</p>
 [code: mark-in-gdef]



* 🔥 **FAIL** <p>&quot;fourdotsabovear&quot; is defined in GDEF as a mark (class 3).</p>
 [code: mark-in-gdef]



* 🔥 **FAIL** <p>&quot;fourdotsbelowar&quot; is defined in GDEF as a mark (class 3).</p>
 [code: mark-in-gdef]



* 🔥 **FAIL** <p>&quot;twodotsverticalabovear&quot; is defined in GDEF as a mark (class 3).</p>
 [code: mark-in-gdef]



* 🔥 **FAIL** <p>&quot;twodotsverticalbelowar&quot; is defined in GDEF as a mark (class 3).</p>
 [code: mark-in-gdef]



* 🔥 **FAIL** <p>&quot;ringar&quot; is defined in GDEF as a mark (class 3).</p>
 [code: mark-in-gdef]



* 🔥 **FAIL** <p>&quot;tahbelowar&quot; is defined in GDEF as a mark (class 3).</p>
 [code: mark-in-gdef]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 512, but got 293 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-description-has-article">googlefonts/description/has_article</a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- acutecomb

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

- uni0326

- uni0327

- uni0328

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

- uni08D5.1

- uni08D6

- uni08D6.1

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

- uni08FF
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-non-mark-chars">opentype/gdef_non_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+FBB2, U+FBB3, U+FBB4, U+FBB5, U+FBB6, U+FBB7, U+FBB8, U+FBB9, U+FBBA, U+FBBB, U+FBBD, U+FBBE, U+FBBF and U+FBC1</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check that glyph for U+0674 ARABIC LETTER HIGH HAMZA is not a mark. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#arabic-high-hamza">arabic_high_hamza</a></summary>
    <div>







* ⚠️ **WARN** <p>The arabic letter high hamza (U+0674) should have roughly the same size the arabic letter hamza (U+0621) while raised above baseline, but a different glyph outline area was detected.</p>
 [code: glyph-area]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure files are not too large. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#file-size">file_size</a></summary>
    <div>







* ⚠️ **WARN** <p>Font file is 1.0Mb; ideally it should be less than 1.0Mb</p>
 [code: large-font]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#interpolation-issues">interpolation_issues</a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 2 start point differs in glyph 'uni08A5' between location wght=704,wdth=100 and location wght=900,wdth=100

- Contour 2 in glyph 'uni08A5': becomes underweight between wght=704,wdth=100 and wght=900,wdth=100.

- Contour 3 start point differs in glyph 'uni08A5' between location wght=704,wdth=100 and location wght=900,wdth=100

- Contour 3 in glyph 'uni08A5': becomes underweight between wght=704,wdth=100 and wght=900,wdth=100.

- Contour 2 start point differs in glyph 'uni08A5' between location wght=900,wdth=100 and location wght=100,wdth=62

- Contour 2 in glyph 'uni08A5': becomes underweight between wght=900,wdth=100 and wght=100,wdth=62.

- Contour 3 start point differs in glyph 'uni08A5' between location wght=900,wdth=100 and location wght=100,wdth=62

- Contour 3 in glyph 'uni08A5': becomes underweight between wght=900,wdth=100 and wght=100,wdth=62.

- Contour 2 start point differs in glyph 'uni08A5' between location wght=704,wdth=62 and location wght=900,wdth=62

- Contour 2 in glyph 'uni08A5': becomes underweight between wght=704,wdth=62 and wght=900,wdth=62.

- Contour 3 start point differs in glyph 'uni08A5' between location wght=704,wdth=62 and location wght=900,wdth=62

- Contour 3 in glyph 'uni08A5': becomes underweight between wght=704,wdth=62 and wght=900,wdth=62.

- Contour 2 start point differs in glyph 'uni08A5.fina' between location wght=704,wdth=100 and location wght=900,wdth=100

- Contour 2 in glyph 'uni08A5.fina': becomes underweight between wght=704,wdth=100 and wght=900,wdth=100.

- Contour 3 start point differs in glyph 'uni08A5.fina' between location wght=704,wdth=100 and location wght=900,wdth=100

- Contour 3 in glyph 'uni08A5.fina': becomes underweight between wght=704,wdth=100 and wght=900,wdth=100.

- Contour 2 start point differs in glyph 'uni08A5.fina' between location wght=900,wdth=100 and location wght=100,wdth=62

- Contour 2 in glyph 'uni08A5.fina': becomes underweight between wght=900,wdth=100 and wght=100,wdth=62.

- Contour 3 start point differs in glyph 'uni08A5.fina' between location wght=900,wdth=100 and location wght=100,wdth=62

- Contour 3 in glyph 'uni08A5.fina': becomes underweight between wght=900,wdth=100 and wght=100,wdth=62.

- Contour 2 start point differs in glyph 'uni08A5.fina' between location wght=704,wdth=62 and location wght=900,wdth=62

- Contour 2 in glyph 'uni08A5.fina': becomes underweight between wght=704,wdth=62 and wght=900,wdth=62.

- Contour 3 start point differs in glyph 'uni08A5.fina' between location wght=704,wdth=62 and location wght=900,wdth=62

- Contour 3 in glyph 'uni08A5.fina': becomes underweight between wght=704,wdth=62 and wght=900,wdth=62.

- Contour 5 start point differs in glyph 'uniFD3E' between location wght=100,wdth=100 and location wght=704,wdth=100

- Contour 5 in glyph 'uniFD3E': becomes underweight between wght=100,wdth=100 and wght=704,wdth=100.

- Contour 5 start point differs in glyph 'uniFD3E' between location wght=704,wdth=100 and location wght=900,wdth=100

- Contour 5 in glyph 'uniFD3E': becomes underweight between wght=704,wdth=100 and wght=900,wdth=100.

- Contour 5 start point differs in glyph 'uniFD3E' between location wght=100,wdth=62 and location wght=704,wdth=62

- Contour 5 in glyph 'uniFD3E': becomes underweight between wght=100,wdth=62 and wght=704,wdth=62.

- Contour 5 start point differs in glyph 'uniFD3E' between location wght=704,wdth=62 and location wght=900,wdth=62

- Contour 5 in glyph 'uniFD3E': becomes underweight between wght=704,wdth=62 and wght=900,wdth=62.
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- uni06060607.pt

- uni06440622.isol

- uni06440623.isol

- uni06440625.isol

- uni06440627.isol

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
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#valid-glyphnames">valid_glyphnames</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
behThreedotsupbelowVabovear.fina, behThreedotsupbelowVabovear.init, behThreedotsupbelowVabovear.medi, dalTwodotsverticalbelowTahabovear.fina, seenThreedotsbelowthreedotsar.fina, seenThreedotsbelowthreedotsar.init and seenThreedotsbelowthreedotsar.medi</p>
 [code: legacy-long-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansArabicUI/googlefonts/variable-ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: syriac, coptic, hebrew, malayalam, old-permic, tai-le, tifinagh, todhri, duployan, canadian-aboriginal, math</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+034F COMBINING GRAPHEME JOINER: not included in any glyphset definition</li>
<li>U+08E2 ARABIC DISPUTED END OF AYAH: not included in any glyphset definition</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, hebrew, phags-pa, nko, thaana</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: mahajani, modi, warang-citi, javanese, telugu, adlam, sundanese, nko, duployan, batak, myanmar, coptic, mandaic, bassa-vah, kaithi, tifinagh, ahom, bhaiksuki, tibetan, tai-viet, zanabazar-square, masaram-gondi, gurmukhi, mende-kikakui, limbu, syloti-nagri, devanagari, lao, lepcha, sogdian, khudawadi, tamil, caucasian-albanian, hanunoo, soyombo, new-tai-lue, mongolian, meetei-mayek, tagalog, buginese, thaana, armenian, kharoshthi, wancho, cham, tai-tham, tai-le, manichaean, osage, music, dogra, takri, rejang, phags-pa, siddham, math, syriac, malayalam, sinhala, miao, chakma, balinese, elbasan, hebrew, newa, old-permic, tirhuta, hanifi-rohingya, kannada, canadian-aboriginal, kayah-li, bengali, khojki, thai, symbols, brahmi, gunjala-gondi, sharada, oriya, psalter-pahlavi, khmer, grantha, tagbanwa, marchen, saurashtra, buhid, yi, gujarati, pahawh-hmong</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>arabic</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* ⚠️ **WARN** <p>GF_TransLatin_Arabic glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni064E to uni25CC when shaping the text '◌َ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0650 to uni25CC when shaping the text '◌ِ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni064F to uni25CC when shaping the text '◌ُ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0652 to uni25CC when shaping the text '◌ْ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0656 to the base glyph when shaping the text '◌ٖ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0670 to uni25CC when shaping the text '◌ٰ'</td>
<td align="left">fa_Arab (Persian) and fa_Arab (Persian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni064B to uni25CC when shaping the text '◌ً'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni064C to uni25CC when shaping the text '◌ٌ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni064D to uni25CC when shaping the text '◌ٍ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni064E to uni25CC when shaping the text '◌َ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni064F to uni25CC when shaping the text '◌ُ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0650 to uni25CC when shaping the text '◌ِ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0651 to uni25CC when shaping the text '◌ّ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0652 to uni25CC when shaping the text '◌ْ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0654 to uni25CC when shaping the text '◌ٔ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0656 to the base glyph when shaping the text '◌ٖ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0657 to the base glyph when shaping the text '◌ٗ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0658 to the base glyph when shaping the text '◌٘'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0670 to uni25CC when shaping the text '◌ٰ'</td>
<td align="left">ur_Arab (Urdu) and ur_Arab (Urdu)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni064B to uni25CC when shaping the text '◌ً'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni064C to uni25CC when shaping the text '◌ٌ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni064D to uni25CC when shaping the text '◌ٍ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni064E to uni25CC when shaping the text '◌َ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni064F to uni25CC when shaping the text '◌ُ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0650 to uni25CC when shaping the text '◌ِ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0651 to uni25CC when shaping the text '◌ّ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0652 to uni25CC when shaping the text '◌ْ'</td>
<td align="left">ckb_Arab (Central Kurdish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni064E to uni25CC when shaping the text '◌َ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni064F to uni25CC when shaping the text '◌ُ'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0650 to uni25CC when shaping the text '◌ِ'</td>
<td align="left">sd_Arab (Sindhi)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŀ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʻ</td>
<td align="left">en_Latn (English)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ǯ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǥ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ʒ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ǯ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŧ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŋ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŧ</td>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ĳ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ĳ</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 5 | 11 | 88 | 6 | 126 | 0 | 
| 0% | 0% | 2% | 5% | 37% | 3% | 53% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
