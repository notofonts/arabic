## FontBakery report

fontbakery version: 0.10.3

<details><summary><b>[2] Experimental checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 🔥 **FAIL** GF_Arabic_Core/ar_Arab (Arabic): [FAIL: Shaper didn't attach uni0670 to None, FAIL: Shaper didn't attach uni064E to space, FAIL: Shaper didn't attach uni064C to space, FAIL: Shaper didn't attach uni0651 to space, FAIL: Shaper didn't attach uni064D to space, FAIL: Shaper didn't attach uni064B to space, FAIL: Shaper didn't attach uni0652 to space, FAIL: Shaper didn't attach uni0650 to space, FAIL: Shaper didn't attach uni064F to space] [code: failed-language-shaping]
* 🔥 **FAIL** GF_Arabic_Core/fa_Arab (Persian): [FAIL: Shaper didn't attach uni064C to space, FAIL: Shaper didn't attach uni0654 to space, FAIL: Shaper didn't attach uni0651 to space, FAIL: Shaper didn't attach uni064D to space, FAIL: Shaper didn't attach uni064B to space] [code: failed-language-shaping]
* 🔥 **FAIL** GF_Latin_Core/br_Latn (Breton): [FAIL: Some base glyphs were missing: cʼh, FAIL: Shaper produced a .notdef] [code: failed-language-shaping]
* 🔥 **FAIL** GF_Latin_Core/haw_Latn (Hawaiian): [FAIL: Some base glyphs were missing: ʻ, FAIL: Shaper produced a .notdef] [code: failed-language-shaping]
* 🔥 **FAIL** GF_Latin_Core/mh_Latn (Marshallese): [FAIL: Some base glyphs were missing: Ḷ, ḷ, Ṃ, ṃ, Ṇ, ṇ, Ọ, ọ, FAIL: Some mark glyphs were missing: ◌̣, FAIL: Shaper produced a .notdef] [code: failed-language-shaping]
* 🔥 **FAIL** GF_Latin_Core/qu_Latn (Quechua): [FAIL: Some base glyphs were missing: chʼ, kʼ, pʼ, qʼ, tʼ, FAIL: Shaper produced a .notdef] [code: failed-language-shaping]
* 🔥 **FAIL** GF_Latin_Core/scn_Latn (Sicilian): [FAIL: Some base glyphs were missing: Ḍ, ḍ, FAIL: Shaper produced a .notdef] [code: failed-language-shaping]
* 🔥 **FAIL** GF_Latin_Core/teo_Latn (Teso): [FAIL: Some base glyphs were missing: Ɔ, Ɛ, Ɨ, Ʉ, ɔ, ɛ, ɨ, ʉ, ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᵘ, ᶤ, ᶶ, ⁱ, FAIL: Shaper produced a .notdef] [code: failed-language-shaping]
* 🔥 **FAIL** GF_Arabic_Plus/ps_Arab (Pashto): [FAIL: Shaper didn't attach uni0670 to None, FAIL: Shaper didn't attach uni064C to space, FAIL: Shaper didn't attach uni064E to space, FAIL: Shaper didn't attach uni0654 to space, FAIL: Shaper didn't attach uni0651 to space, FAIL: Shaper didn't attach uni064D to space, FAIL: Shaper didn't attach uni064B to space, FAIL: Shaper didn't attach uni0652 to space, FAIL: Shaper didn't attach uni0650 to space, FAIL: Shaper didn't attach uni064F to space] [code: failed-language-shaping]
* ⚠ **WARN** GF_Latin_Core/lg_Latn (Ganda): [WARN: No variant glyphs were found for Eng] [code: warning-language-shaping]
* ⚠ **WARN** GF_Latin_Core/dyo_Latn (Jola-Fonyi): [WARN: No variant glyphs were found for Eng] [code: warning-language-shaping]
* ⚠ **WARN** GF_Latin_Core/ny_Latn (Nyanja): [WARN: No variant glyphs were found for Eng] [code: warning-language-shaping]
* ⚠ **WARN** GF_Latin_Core/wo_Latn (Wolof): [WARN: No variant glyphs were found for Eng] [code: warning-language-shaping]
* ⚠ **WARN** GF_Arabic_Plus/ku_Arab (Kurdish (Arabic)): [WARN: No exemplar glyphs were defined for language Kurdish (Arabic)] [code: warning-language-shaping]
* ⚠ **WARN** GF_Arabic_Plus/ms_Arab (Malay (Arabic)): [WARN: No exemplar glyphs were defined for language Malay (Arabic)] [code: warning-language-shaping]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that Arabic spacing symbols U+FBB2–FBC1 aren't classified as marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/arabic_spacing_symbols">com.google.fonts/check/arabic_spacing_symbols</a>)</summary><div>


* 🔥 **FAIL** "tahbelowar" is defined in GDEF as a mark (class 3). [code: mark-in-gdef]
* 🔥 **FAIL** "dotabovear" is defined in GDEF as a mark (class 3). [code: mark-in-gdef]
* 🔥 **FAIL** "dotbelowar" is defined in GDEF as a mark (class 3). [code: mark-in-gdef]
* 🔥 **FAIL** "twodotsverticalabovear" is defined in GDEF as a mark (class 3). [code: mark-in-gdef]
* 🔥 **FAIL** "twodotsverticalbelowar" is defined in GDEF as a mark (class 3). [code: mark-in-gdef]
* 🔥 **FAIL** "twodotshorizontalabovear" is defined in GDEF as a mark (class 3). [code: mark-in-gdef]
* 🔥 **FAIL** "twodotshorizontalbelowar" is defined in GDEF as a mark (class 3). [code: mark-in-gdef]
* 🔥 **FAIL** "threedotsdownabovear" is defined in GDEF as a mark (class 3). [code: mark-in-gdef]
* 🔥 **FAIL** "threedotsdownbelowar" is defined in GDEF as a mark (class 3). [code: mark-in-gdef]
* 🔥 **FAIL** "threedotsupabovear" is defined in GDEF as a mark (class 3). [code: mark-in-gdef]
* 🔥 **FAIL** "threedotsupbelowar" is defined in GDEF as a mark (class 3). [code: mark-in-gdef]
* 🔥 **FAIL** "fourdotsabovear" is defined in GDEF as a mark (class 3). [code: mark-in-gdef]
* 🔥 **FAIL** "fourdotsbelowar" is defined in GDEF as a mark (class 3). [code: mark-in-gdef]
* 🔥 **FAIL** "ringar" is defined in GDEF as a mark (class 3). [code: mark-in-gdef]
</div></details><br></div></details><details><summary><b>[13] NotoSansArabicUI[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 512, but got 293 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that legacy accents aren't used in composite glyphs. (derived from com.google.fonts/check/legacy_accents) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/legacy_accents">com.google.fonts/check/legacy_accents</a>)</summary><div>


* 🔥 **FAIL** Glyph "Aacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Acircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Adieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Agrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Aring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Cacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ccaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ccedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Cdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Dcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Eacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ecaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ecircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Edieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Edotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Egrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Eogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Iacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Icircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Idieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Idotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Igrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Lacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Nacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ncaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Oacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ocircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Odieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ograve" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Racute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Rcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Sacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Scaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Scedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Tcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ucircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Udieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ugrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wcircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wdieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wgrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Yacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ycircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ydieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ygrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "acircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "acutecomb" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "adieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "agrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0306" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "cacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030C" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ccaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ccedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "cdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0327" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0302" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0308" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0307" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "eacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ecaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ecircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "edieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "edotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "egrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gravecomb" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030B" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "iacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "icircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "idieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "igrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "lacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "nacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ncaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "oacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ocircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "odieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0328" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ograve" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "racute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "rcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030A" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "sacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "scaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "scedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "tildecomb" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ucircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "udieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ugrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wcircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wdieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wgrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "yacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ycircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ydieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ygrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
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

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, coptic, cherokee
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, coptic, old-permic, canadian-aboriginal, tai-le, syriac, math, malayalam
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
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: lepcha, balinese, gujarati, limbu, warang-citi, sogdian, pahawh-hmong, hanunoo, kayah-li, gurmukhi, avestan, tamil, syloti-nagri, grantha, psalter-pahlavi, tagbanwa, myanmar, tifinagh, tagalog, kharoshthi, sinhala, thai, duployan, saurashtra, phags-pa, nko, sundanese, manichaean, devanagari, takri, cham, tirhuta, tai-tham, telugu, thaana, buginese, kaithi, hatran, gunjala-gondi, batak, kannada, bengali, newa, syriac, tai-le, khudawadi, javanese, new-tai-lue, tibetan, malayalam, yi, hanifi-rohingya, buhid, oriya, khojki, khmer, brahmi, siddham, tai-viet, sharada, rejang, mahajani, mandaic, mongolian, meetei-mayek, chakma, dogra, modi
 * U+200D ZERO WIDTH JOINER: try adding one of: lepcha, balinese, gujarati, limbu, warang-citi, pahawh-hmong, hanunoo, kayah-li, gurmukhi, avestan, tamil, syloti-nagri, grantha, psalter-pahlavi, tagbanwa, myanmar, tifinagh, tagalog, kharoshthi, sinhala, thai, duployan, saurashtra, phags-pa, nko, sundanese, manichaean, devanagari, takri, cham, tirhuta, tai-tham, telugu, thaana, buginese, kaithi, gunjala-gondi, batak, kannada, bengali, newa, syriac, tai-le, khudawadi, javanese, new-tai-lue, tibetan, malayalam, yi, hanifi-rohingya, buhid, oriya, khojki, old-hungarian, brahmi, siddham, tai-viet, sharada, rejang, mahajani, mandaic, mongolian, meetei-mayek, chakma, dogra, modi
 * U+200E LEFT-TO-RIGHT MARK: try adding one of: phags-pa, nko, thaana, syriac
 * U+200F RIGHT-TO-LEFT MARK: try adding one of: phags-pa, nko, thaana, syriac
 * U+2010 HYPHEN: try adding one of: coptic, kharoshthi, kaithi, lisu, kayah-li, sora-sompeng, syloti-nagri, sundanese, yi, cham
 * U+2011 NON-BREAKING HYPHEN: try adding one of: syloti-nagri, yi
 * U+204F REVERSED SEMICOLON: try adding adlam
 * U+25CC DOTTED CIRCLE: try adding one of: lepcha, bhaiksuki, tamil, psalter-pahlavi, tagbanwa, tagalog, sinhala, old-permic, nko, manichaean, thaana, gunjala-gondi, kannada, siddham, brahmi, rejang, math, masaram-gondi, soyombo, myanmar, kharoshthi, marchen, duployan, phags-pa, tirhuta, takri, syriac, elbasan, khudawadi, tibetan, coptic, khmer, sharada, miao, mongolian, chakma, dogra, adlam, balinese, gujarati, sogdian, hanunoo, syloti-nagri, tifinagh, symbols, lao, devanagari, cham, mende-kikakui, buginese, kaithi, zanabazar-square, batak, newa, bengali, new-tai-lue, malayalam, wancho, mahajani, mandaic, hebrew, music, meetei-mayek, thai, limbu, caucasian-albanian, kayah-li, pahawh-hmong, gurmukhi, grantha, sundanese, telugu, osage, tai-le, bassa-vah, javanese, yi, hanifi-rohingya, buhid, oriya, khojki, tai-viet, modi, ahom
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

	- Contour 2 start point differs in glyph 'uni08A5.fina' between location wght=400,wdth=100 and location wght=900,wdth=100

	- Contour 3 start point differs in glyph 'uni08A5.fina' between location wght=400,wdth=100 and location wght=900,wdth=100

	- Contour 2 start point differs in glyph 'uni08A5.fina' between location wght=400,wdth=100 and location wght=900,wdth=62

	- Contour 3 start point differs in glyph 'uni08A5.fina' between location wght=400,wdth=100 and location wght=900,wdth=62

	- Contour 5 start point differs in glyph 'uniFD3E' between location wght=400,wdth=100 and location wght=704,wdth=100

	- Contour 5 start point differs in glyph 'uniFD3E' between location wght=400,wdth=100 and location wght=704,wdth=62 [code: interpolation-issues]
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

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Ejagham (Latn, 120,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Belarusian (Cyrl, 10,064,517 speakers), Lugbara (Latn, 2,200,000 speakers), Dan (Latn, 1,099,244 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Ebira (Latn, 2,200,000 speakers), Nateni (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 6 | 9 | 101 | 8 | 131 | 0 |
| 0% | 2% | 4% | 40% | 3% | 51% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
