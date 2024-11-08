## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[13] NotoNaskhArabic[wght].ttf</summary>
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
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 point 26 in glyph 'uni0665.lf' has a kink between location wght=400 and location wght=700

- Contour 0 point 72 in glyph 'uni06AA' has a kink between location wght=400 and location wght=700
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 579:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- alayh.1

- alayh.2

- fatha.1

- la.1

- radiya.1

- uni0640.wide

- uni06F7.mark
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphnames.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
twodotshorizontalabove_tahabovear, twodotshorizontalabovear.diagonal, twodotshorizontalbelow_tahabovear and twodotshorizontalcenter_tahabovear</p>
 [code: legacy-long-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoNaskhArabic/googlefonts/variable-ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: hebrew, syriac, tifinagh, tai-le, old-permic, canadian-aboriginal, math, todhri, malayalam, coptic, duployan</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+08E2 ARABIC DISPUTED END OF AYAH: not included in any glyphset definition</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: hebrew, syriac, phags-pa, thaana, nko</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, phags-pa, yi</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: oriya, takri, tagbanwa, khojki, siddham, cham, mongolian, tai-tham, hanifi-rohingya, gunjala-gondi, bassa-vah, syriac, buhid, old-permic, miao, warang-citi, coptic, caucasian-albanian, limbu, symbols, zanabazar-square, newa, bhaiksuki, hanunoo, kayah-li, tai-viet, sogdian, tamil, duployan, sinhala, lao, buginese, tai-le, kharoshthi, gujarati, thaana, tirhuta, kannada, batak, meetei-mayek, gurmukhi, bengali, yi, malayalam, kaithi, marchen, modi, devanagari, osage, nko, soyombo, new-tai-lue, sharada, masaram-gondi, tagalog, mende-kikakui, pahawh-hmong, armenian, syloti-nagri, music, ahom, chakma, phags-pa, math, brahmi, elbasan, saurashtra, psalter-pahlavi, khudawadi, grantha, thai, lepcha, tibetan, hebrew, khmer, javanese, tifinagh, telugu, myanmar, adlam, canadian-aboriginal, rejang, mahajani, manichaean, mandaic, wancho, balinese, dogra, sundanese</li>
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
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Kom (Latn, 360,685 speakers), Zapotec (Latn, 490,000 speakers), Cicipu (Latn, 44,000 speakers), Dan (Latn, 1,099,244 speakers), Southern Kisi (Latn, 360,000 speakers), Avokaya (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Nateni (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Heiltsuk (Latn, 300 speakers), Vute (Latn, 21,000 speakers), Lugbara (Latn, 2,200,000 speakers), Han (Latn, 6 speakers), Navajo (Latn, 166,319 speakers), Ejagham (Latn, 120,000 speakers), Kaska (Latn, 125 speakers), Mango (Latn, 77,000 speakers), Sar (Latn, 500,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Nzakara (Latn, 50,000 speakers), Fur (Latn, 1,230,163 speakers), Mfumte (Latn, 79,000 speakers), Ebira (Latn, 2,200,000 speakers), Makaa (Latn, 221,000 speakers), Gulay (Latn, 250,478 speakers), South Central Banda (Latn, 244,000 speakers), Bafut (Latn, 158,146 speakers), Ngbaka (Latn, 1,020,000 speakers), Aghem (Latn, 38,843 speakers), Ekpeye (Latn, 226,000 speakers), Yala (Latn, 200,000 speakers), Igbo (Latn, 27,823,640 speakers), Dii (Latn, 71,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Ma’di (Latn, 584,000 speakers), Basaa (Latn, 332,940 speakers), Mundani (Latn, 34,000 speakers), Koonzime (Latn, 40,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- uni0627 + uni0644.init

- uni0644.init + uni0644.medi

- uni0644.medi + uni06510670

- uni06510670 + uni0647.fina

- uni06510670 + uni06C1.fina
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



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
| 1 | 0 | 2 | 10 | 94 | 7 | 137 | 0 | 
| 0% | 0% | 1% | 4% | 37% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
