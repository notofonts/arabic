## FontBakery report

fontbakery version: 0.13.2





## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoNaskhArabic[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check base characters have non-zero advance width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#base-has-width">base_has_width</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs had zero advance width:
- u10EFD (U+10EFD)</p>
<pre><code>- u10EFE (U+10EFE)

- u10EFF (U+10EFF)
</code></pre>
 [code: zero-width-bases]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[13] NotoNaskhArabic[wght].ttf</summary>
<div>
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
    <summary>⚠️ <b>WARN</b> Check if uppercase glyphs are vertically centered. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#caps-vertically-centered">caps_vertically_centered</a></summary>
    <div>







* ⚠️ **WARN** <p>Uppercase glyphs are not vertically centered in the em box.</p>
 [code: vertical-metrics-not-centered]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#interpolation-issues">interpolation_issues</a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 point 26 in glyph 'uni0665.lf' has a kink between location wght=400 and location wght=700

- Contour 0 point 72 in glyph 'uni06AA' has a kink between location wght=400 and location wght=700
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#mandatory-avar-table">mandatory_avar_table</a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table. Most variable fonts should include an avar table to correctly define axes progression rates.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 579:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* uni089D (U+089D): L&lt;&lt;26.0,748.0&gt;--&lt;20.0,750.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
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
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#valid-glyphnames">valid_glyphnames</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
twodotshorizontalabove_tahabovear, twodotshorizontalabovear.diagonal, twodotshorizontalbelow_tahabovear and twodotshorizontalcenter_tahabovear</p>
 [code: legacy-long-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoNaskhArabic/googlefonts/variable-ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, tifinagh, syriac, tai-le, canadian-aboriginal, coptic, hebrew, todhri, malayalam, duployan, math</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+08E2 ARABIC DISPUTED END OF AYAH: not included in any glyphset definition</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, phags-pa, nko, thaana, hebrew</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: mongolian, yi, phags-pa</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: modi, marchen, masaram-gondi, sogdian, osage, tai-tham, sinhala, batak, miao, syriac, khudawadi, mahajani, manichaean, saurashtra, symbols, limbu, tagbanwa, javanese, music, balinese, rejang, thai, hebrew, old-permic, cham, wancho, tagalog, tamil, gunjala-gondi, myanmar, oriya, kayah-li, math, buhid, gujarati, mende-kikakui, siddham, khmer, malayalam, tibetan, tifinagh, tirhuta, buginese, lao, meetei-mayek, elbasan, bengali, mandaic, dogra, tai-viet, grantha, lepcha, brahmi, takri, kaithi, psalter-pahlavi, warang-citi, soyombo, bhaiksuki, zanabazar-square, telugu, ahom, sundanese, tai-le, canadian-aboriginal, kannada, khojki, pahawh-hmong, devanagari, phags-pa, nko, kharoshthi, armenian, chakma, sharada, duployan, coptic, newa, syloti-nagri, new-tai-lue, caucasian-albanian, hanunoo, mongolian, gurmukhi, hanifi-rohingya, adlam, thaana, yi, bassa-vah</li>
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
| 0 | 0 | 2 | 12 | 86 | 6 | 130 | 0 | 
| 0% | 0% | 1% | 5% | 36% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
