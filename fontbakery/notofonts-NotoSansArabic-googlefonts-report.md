## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[11] NotoSansArabic[wdth,wght].ttf</summary>
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
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- uni0615

- uni0616

- uni0617

- uni06D6

- uni06D7

- uni06D8

- uni06D9

- uni06DA

- uni06DB

- uni06DC

- uni06E8

- uni0898

- uni08CC

- uni08D4

- uni08D5

- uni08D6

- uni08D7

- uni08DA

- uni08DB

- uni08DC

- uni08DD

- uni08DE

- uni08DF
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- uni06BA.init

- uni06BA.medi

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







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansArabic/googlefonts/variable-ttf does not have an article.</p>
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
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: math, tai-le, malayalam, tifinagh, todhri, hebrew, duployan, canadian-aboriginal, syriac, old-permic, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+034F COMBINING GRAPHEME JOINER: not included in any glyphset definition</li>
<li>U+08E2 ARABIC DISPUTED END OF AYAH: not included in any glyphset definition</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: thaana, syriac, hebrew, phags-pa, nko</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: cham, wancho, brahmi, myanmar, malayalam, mahajani, coptic, balinese, tirhuta, mongolian, warang-citi, canadian-aboriginal, tagalog, manichaean, math, tai-le, yi, gurmukhi, buhid, kharoshthi, gujarati, armenian, oriya, sinhala, elbasan, masaram-gondi, thaana, khmer, khudawadi, adlam, duployan, gunjala-gondi, syloti-nagri, tai-viet, kayah-li, sundanese, batak, psalter-pahlavi, osage, old-permic, tai-tham, bassa-vah, mende-kikakui, telugu, lepcha, pahawh-hmong, kannada, lao, tibetan, tifinagh, caucasian-albanian, phags-pa, siddham, thai, ahom, rejang, saurashtra, music, sharada, devanagari, meetei-mayek, modi, hanunoo, kaithi, nko, soyombo, grantha, tamil, hanifi-rohingya, dogra, javanese, newa, miao, buginese, bhaiksuki, takri, hebrew, new-tai-lue, mandaic, khojki, limbu, chakma, marchen, tagbanwa, zanabazar-square, symbols, bengali, sogdian, syriac</li>
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
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Makaa (Latn, 221,000 speakers), Vute (Latn, 21,000 speakers), Ma’di (Latn, 584,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ebira (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Basaa (Latn, 332,940 speakers), Nzakara (Latn, 50,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers), Bete-Bendi (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Sar (Latn, 500,000 speakers), Bafut (Latn, 158,146 speakers), Han (Latn, 6 speakers), South Central Banda (Latn, 244,000 speakers), Dan (Latn, 1,099,244 speakers), Yala (Latn, 200,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kaska (Latn, 125 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Mfumte (Latn, 79,000 speakers), Fur (Latn, 1,230,163 speakers), Avokaya (Latn, 100,000 speakers), Koonzime (Latn, 40,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ngbaka (Latn, 1,020,000 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Ekpeye (Latn, 226,000 speakers), Dii (Latn, 71,000 speakers), Cicipu (Latn, 44,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Gulay (Latn, 250,478 speakers), Heiltsuk (Latn, 300 speakers), Mundani (Latn, 34,000 speakers), Mango (Latn, 77,000 speakers), Nateni (Latn, 100,000 speakers), Zapotec (Latn, 490,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- uni0627 + uni0644.init

- uni0644.init + uni0644.medi

- uni0644.medi + uni0651

- uni0651 + uni0670

- uni0670 + uni0647.fina

- uni0670 + uni06C1.fina
</code></pre>
 [code: lacks-kern-info]



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
| 1 | 0 | 3 | 7 | 92 | 7 | 141 | 0 | 
| 0% | 0% | 1% | 3% | 37% | 3% | 56% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
