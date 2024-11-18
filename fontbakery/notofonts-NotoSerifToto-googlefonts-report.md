## FontBakery report

fontbakery version: 0.12.10



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSerifToto[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoAscender value should be greater than 931, but got 925 instead</p>
 [code: typoAscender]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[7] NotoSerifToto[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking font version fields (head and name table). <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.head.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>head version is &quot;2.00200&quot; while name version string (for platform 3, encoding 1) is &quot;Version 2.001&quot;.</p>
 [code: mismatch]



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
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifToto/googlefonts/variable-ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, coptic, math, tai-le, todhri, syriac, duployan, hebrew, tifinagh, canadian-aboriginal, old-permic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: kharoshthi, tai-le, bhaiksuki, siddham, newa, saurashtra, gunjala-gondi, hebrew, tagalog, myanmar, javanese, adlam, duployan, mende-kikakui, tagbanwa, phags-pa, grantha, khudawadi, oriya, batak, elbasan, rejang, mongolian, psalter-pahlavi, devanagari, marchen, chakma, bassa-vah, balinese, takri, manichaean, meetei-mayek, tamil, tai-viet, canadian-aboriginal, hanifi-rohingya, tifinagh, symbols, sogdian, mandaic, tai-tham, warang-citi, lao, new-tai-lue, buginese, modi, gujarati, syloti-nagri, dogra, syriac, hanunoo, old-permic, sinhala, kaithi, osage, soyombo, sharada, pahawh-hmong, miao, limbu, thaana, masaram-gondi, khojki, buhid, coptic, math, tirhuta, caucasian-albanian, cham, khmer, zanabazar-square, tibetan, ahom, kayah-li, sundanese, kannada, gurmukhi, mahajani, malayalam, armenian, lepcha, bengali, telugu, thai, nko, music, brahmi, yi, wancho</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>toto</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Bete-Bendi (Latn, 100,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ebira (Latn, 2,200,000 speakers), Ma’di (Latn, 584,000 speakers), Cicipu (Latn, 44,000 speakers), Heiltsuk (Latn, 300 speakers), Makaa (Latn, 221,000 speakers), Navajo (Latn, 166,319 speakers), Nzakara (Latn, 50,000 speakers), Mango (Latn, 77,000 speakers), Zapotec (Latn, 490,000 speakers), Aghem (Latn, 38,843 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ejagham (Latn, 120,000 speakers), South Central Banda (Latn, 244,000 speakers), Ekpeye (Latn, 226,000 speakers), Han (Latn, 6 speakers), Igbo (Latn, 27,823,640 speakers), Kaska (Latn, 125 speakers), Nateni (Latn, 100,000 speakers), Southern Kisi (Latn, 360,000 speakers), Koonzime (Latn, 40,000 speakers), Mundani (Latn, 34,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Yala (Latn, 200,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Basaa (Latn, 332,940 speakers), Gulay (Latn, 250,478 speakers), Dan (Latn, 1,099,244 speakers), Teke-Ebo (Latn, 260,000 speakers), Vute (Latn, 21,000 speakers), Avokaya (Latn, 100,000 speakers), Bafut (Latn, 158,146 speakers), Sar (Latn, 500,000 speakers), Kom (Latn, 360,685 speakers), Dii (Latn, 71,000 speakers), Mfumte (Latn, 79,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Fur (Latn, 1,230,163 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

* uni0122 (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

* OE (U+0152): X=425.5,Y=722.0 (should be at cap-height 720?)

* b (U+0062): X=26.0,Y=718.0 (should be at cap-height 720?)

* b (U+0062): X=18.0,Y=718.0 (should be at cap-height 720?)

* bracketleft (U+005B): X=323.0,Y=718.0 (should be at cap-height 720?)

* bracketleft (U+005B): X=280.0,Y=718.0 (should be at cap-height 720?)

* bracketright (U+005D): X=80.0,Y=718.0 (should be at cap-height 720?)

* bracketright (U+005D): X=37.0,Y=718.0 (should be at cap-height 720?)

* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

* d (U+0064): X=330.0,Y=718.0 (should be at cap-height 720?)

* d (U+0064): X=322.0,Y=718.0 (should be at cap-height 720?)

* dcaron (U+010F): X=330.0,Y=718.0 (should be at cap-height 720?)

* dcaron (U+010F): X=322.0,Y=718.0 (should be at cap-height 720?)

* dcroat (U+0111): X=330.0,Y=718.0 (should be at cap-height 720?)

* dcroat (U+0111): X=322.0,Y=718.0 (should be at cap-height 720?)

* Euro (U+20AC): X=361.0,Y=722.0 (should be at cap-height 720?)

* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

* uni0123 (U+0123): X=263.0,Y=718.0 (should be at cap-height 720?)

* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

* germandbls (U+00DF): X=333.0,Y=718.0 (should be at cap-height 720?)

* h (U+0068): X=26.0,Y=718.0 (should be at cap-height 720?)

* h (U+0068): X=18.0,Y=718.0 (should be at cap-height 720?)

* hbar (U+0127): X=26.0,Y=718.0 (should be at cap-height 720?)

* hbar (U+0127): X=18.0,Y=718.0 (should be at cap-height 720?)

* k (U+006B): X=26.0,Y=718.0 (should be at cap-height 720?)

* k (U+006B): X=18.0,Y=718.0 (should be at cap-height 720?)

* uni0137 (U+0137): X=26.0,Y=718.0 (should be at cap-height 720?)

* uni0137 (U+0137): X=18.0,Y=718.0 (should be at cap-height 720?)

* l (U+006C): X=26.0,Y=718.0 (should be at cap-height 720?)

* l (U+006C): X=13.0,Y=718.0 (should be at cap-height 720?)

* lacute (U+013A): X=26.0,Y=718.0 (should be at cap-height 720?)

* lacute (U+013A): X=13.0,Y=718.0 (should be at cap-height 720?)

* lcaron (U+013E): X=26.0,Y=718.0 (should be at cap-height 720?)

* lcaron (U+013E): X=13.0,Y=718.0 (should be at cap-height 720?)

* uni013C (U+013C): X=26.0,Y=718.0 (should be at cap-height 720?)

* uni013C (U+013C): X=13.0,Y=718.0 (should be at cap-height 720?)

* lslash (U+0142): X=41.0,Y=718.0 (should be at cap-height 720?)

* lslash (U+0142): X=28.0,Y=718.0 (should be at cap-height 720?)

* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

* one (U+0031): X=282.0,Y=718.0 (should be at cap-height 720?)

* one (U+0031): X=346.0,Y=718.0 (should be at cap-height 720?)

* ordfeminine (U+00AA): X=191.0,Y=719.0 (should be at cap-height 720?)

* ordmasculine (U+00BA): X=200.0,Y=719.0 (should be at cap-height 720?)

* paragraph (U+00B6): X=576.0,Y=718.0 (should be at cap-height 720?)

* paragraph (U+00B6): X=563.0,Y=718.0 (should be at cap-height 720?)

* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?)

* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

* section (U+00A7): X=152.5,Y=718.5 (should be at cap-height 720?)

* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

* thorn (U+00FE): X=26.0,Y=718.0 (should be at cap-height 720?)

* thorn (U+00FE): X=18.0,Y=718.0 (should be at cap-height 720?)

* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

* commaaccentrotate: X=234.0,Y=718.0 (should be at cap-height 720?)
</code></pre>
 [code: found-misalignments]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 3 | 5 | 97 | 8 | 138 | 0 | 
| 0% | 0% | 1% | 2% | 39% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
