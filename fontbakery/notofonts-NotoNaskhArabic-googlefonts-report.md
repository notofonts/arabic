## FontBakery report

fontbakery version: 0.12.7



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoNaskhArabic[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoNaskhArabic/googlefonts/variable-ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[13] NotoNaskhArabic[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check that glyph for U+0675 ARABIC LETTER HIGH HAMZA is not a mark. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.arabic.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The arabic letter high hamza (U+0675) should have roughly the same size the arabic letter hamza (U+0621), but a different glyph outline area was detected.</p>
 [code: glyph-area]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- acutecomb

- gravecomb

- tildecomb

- uni0302

- uni0304

- uni0306

- uni0307

- uni0308

- uni030A

- uni030B

- uni030C

- uni0610

- uni0611

- uni0612

- uni0613

- uni0614

- uni0618

- uni0619

- uni08E0

- uni08E1
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Arabic_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ar_Arab (Arabic)</td>
<td align="left">Shaper didn't attach uni0655 to None</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper didn't attach uni0655 to space</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Arabic_Plus glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ms_Arab (Malay (Arabic))</td>
<td align="left">No exemplar glyphs were defined for language Malay (Arabic)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



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
<p>Width = 310:
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
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Gulay (Latn, 250,478 speakers), Cicipu (Latn, 44,000 speakers), South Central Banda (Latn, 244,000 speakers), Basaa (Latn, 332,940 speakers), Ngbaka (Latn, 1,020,000 speakers), Igbo (Latn, 27,823,640 speakers), Mfumte (Latn, 79,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Zapotec (Latn, 490,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ejagham (Latn, 120,000 speakers), Southern Kisi (Latn, 360,000 speakers), Nzakara (Latn, 50,000 speakers), Fur (Latn, 1,230,163 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Aghem (Latn, 38,843 speakers), Mango (Latn, 77,000 speakers), Ma’di (Latn, 584,000 speakers), Vute (Latn, 21,000 speakers), Ekpeye (Latn, 226,000 speakers), Kom (Latn, 360,685 speakers), Mundani (Latn, 34,000 speakers), Nateni (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Avokaya (Latn, 100,000 speakers), Makaa (Latn, 221,000 speakers), Dan (Latn, 1,099,244 speakers), Lugbara (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Yala (Latn, 200,000 speakers), Navajo (Latn, 166,319 speakers).</p>
 [code: soft-dotted]



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
<li>U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, cherokee, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: syriac, canadian-aboriginal, tifinagh, math, old-permic, coptic, tai-le, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+08E2 ARABIC DISPUTED END OF AYAH: not included in any glyphset definition</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, thaana, nko, phags-pa, hebrew</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: bassa-vah, syriac, osage, phags-pa, kaithi, ahom, kannada, oriya, sundanese, javanese, lepcha, takri, buhid, grantha, kharoshthi, psalter-pahlavi, syloti-nagri, old-permic, warang-citi, telugu, miao, brahmi, devanagari, hanunoo, pahawh-hmong, mandaic, bhaiksuki, soyombo, balinese, elbasan, marchen, hebrew, siddham, music, tifinagh, mongolian, tibetan, yi, sinhala, mende-kikakui, newa, zanabazar-square, symbols, math, kayah-li, khojki, nko, gurmukhi, tamil, wancho, tai-tham, masaram-gondi, new-tai-lue, buginese, coptic, cham, lao, canadian-aboriginal, tagalog, tirhuta, tai-le, tai-viet, limbu, dogra, batak, myanmar, gunjala-gondi, bengali, armenian, mahajani, sharada, tagbanwa, duployan, gujarati, khmer, chakma, rejang, malayalam, sogdian, modi, adlam, manichaean, thaana, meetei-mayek, saurashtra, thai, khudawadi, caucasian-albanian, hanifi-rohingya</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>arabic</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



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
| 0 | 0 | 4 | 10 | 92 | 7 | 135 | 0 | 
| 0% | 0% | 2% | 4% | 37% | 3% | 54% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
