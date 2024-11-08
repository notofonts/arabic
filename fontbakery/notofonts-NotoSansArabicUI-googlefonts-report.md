## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[15] NotoSansArabicUI[wdth,wght].ttf</summary>
<div>
<details>
    <summary>💥 <b>ERROR</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 💥 **ERROR** <p>Failed with AttributeError: 'NoneType' object has no attribute 'get'</p>
<pre><code>  File &quot;/home/runner/work/arabic/arabic/venv/lib/python3.11/site-packages/fontbakery/checkrunner.py&quot;, line 213, in _run_check
    subresults = list(subresults)
                 ^^^^^^^^^^^^^^^^
  File &quot;/home/runner/work/arabic/arabic/venv/lib/python3.11/site-packages/fontbakery/checks/googlefonts/glyphset.py&quot;, line 145, in com_google_fonts_check_glyphsets_shape_languages
    reporter = shaperglot_checker.check(shaperglot_languages[language_code])
               ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File &quot;/home/runner/work/arabic/arabic/venv/lib/python3.11/site-packages/shaperglot/checker.py&quot;, line 53, in check
    for check_object in self.lang.get(&quot;shaperglot_checks&quot;, []):
                        ^^^^^^^^^^^^^

</code></pre>
 [code: failed-check]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check that glyph for U+0675 ARABIC LETTER HIGH HAMZA is not a mark. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.arabic.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The arabic letter high hamza (U+0675) should have roughly the same size the arabic letter hamza (U+0621), but a different glyph outline area was detected.</p>
 [code: glyph-area]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check that Arabic spacing symbols U+FBB2–FBC1 aren't classified as marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.arabic.html#"></a></summary>
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
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 512, but got 293 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
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
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+FBB2, U+FBB3, U+FBB4, U+FBB5, U+FBB6, U+FBB7, U+FBB8, U+FBB9, U+FBBA, U+FBBB, U+FBBD, U+FBBE, U+FBBF and U+FBC1</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 2 start point differs in glyph 'uni08A5.fina' between location wght=704,wdth=100 and location wght=900,wdth=100

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

- Contour 2 start point differs in glyph 'uni08A5' between location wght=704,wdth=100 and location wght=900,wdth=100

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
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
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
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphnames.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
behThreedotsupbelowVabovear.fina, behThreedotsupbelowVabovear.init, behThreedotsupbelowVabovear.medi, dalTwodotsverticalbelowTahabovear, dalTwodotsverticalbelowTahabovear.fina, seenThreedotsbelowthreedotsar.fina, seenThreedotsbelowthreedotsar.init and seenThreedotsbelowthreedotsar.medi</p>
 [code: legacy-long-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansArabicUI/googlefonts/variable-ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, coptic, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, coptic, tifinagh, canadian-aboriginal, syriac, tai-le, malayalam, hebrew, math, duployan, todhri</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+034F COMBINING GRAPHEME JOINER: not included in any glyphset definition</li>
<li>U+08E2 ARABIC DISPUTED END OF AYAH: not included in any glyphset definition</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: nko, phags-pa, syriac, hebrew, thaana</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: pahawh-hmong, yi, marchen, rejang, duployan, lao, bassa-vah, devanagari, lepcha, khojki, symbols, old-permic, chakma, adlam, zanabazar-square, mongolian, nko, coptic, cham, batak, hebrew, tifinagh, hanunoo, siddham, malayalam, takri, newa, gurmukhi, kharoshthi, bhaiksuki, thaana, mahajani, sundanese, sogdian, myanmar, tirhuta, khmer, bengali, wancho, gunjala-gondi, ahom, meetei-mayek, telugu, kaithi, mende-kikakui, oriya, sinhala, manichaean, syloti-nagri, syriac, modi, tai-viet, psalter-pahlavi, tibetan, grantha, soyombo, canadian-aboriginal, elbasan, warang-citi, masaram-gondi, mandaic, math, buhid, brahmi, sharada, thai, tai-tham, kayah-li, dogra, hanifi-rohingya, osage, limbu, new-tai-lue, buginese, balinese, khudawadi, kannada, gujarati, tagalog, music, caucasian-albanian, armenian, javanese, miao, tamil, phags-pa, tai-le, tagbanwa, saurashtra</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>arabic</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ekpeye (Latn, 226,000 speakers), Han (Latn, 6 speakers), Kaska (Latn, 125 speakers), Yala (Latn, 200,000 speakers), Ebira (Latn, 2,200,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Aghem (Latn, 38,843 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Fur (Latn, 1,230,163 speakers), Mango (Latn, 77,000 speakers), Cicipu (Latn, 44,000 speakers), Basaa (Latn, 332,940 speakers), Teke-Ebo (Latn, 260,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ejagham (Latn, 120,000 speakers), Dan (Latn, 1,099,244 speakers), Avokaya (Latn, 100,000 speakers), Koonzime (Latn, 40,000 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), South Central Banda (Latn, 244,000 speakers), Sar (Latn, 500,000 speakers), Nateni (Latn, 100,000 speakers), Zapotec (Latn, 490,000 speakers), Heiltsuk (Latn, 300 speakers), Lugbara (Latn, 2,200,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers), Southern Kisi (Latn, 360,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Vute (Latn, 21,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Makaa (Latn, 221,000 speakers), Mundani (Latn, 34,000 speakers), Ma’di (Latn, 584,000 speakers), Bete-Bendi (Latn, 100,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure files are not too large. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Font file is 1.0Mb; ideally it should be less than 1.0Mb</p>
 [code: large-font]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
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
| 1 | 0 | 5 | 9 | 94 | 7 | 135 | 0 | 
| 0% | 0% | 2% | 4% | 37% | 3% | 54% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
