## FontBakery report

fontbakery version: 0.13.1





## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Panchanan-Regular.ttf</summary>
<div>
<details>
    <summary>✅ <b>PASS</b> Check base characters have non-zero advance width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#base-has-width">base_has_width</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[218] Panchanan-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 2467, but got 2183 instead</p>
 [code: ascent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontbakery-version">fontbakery_version</a></summary>
    <div>







* 🔥 **FAIL** <p>Current FontBakery version is 0.13.1, while a newer 0.13.2 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Name table records must not have trailing spaces. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#name-trailing-spaces">name/trailing_spaces</a></summary>
    <div>







* 🔥 **FAIL** <p>Name table record with key = (3, 1, 1033, 10) has trailing spaces that must be removed: 'Digital Re[...] Karmakar '</p>
 [code: trailing-space]



* 🔥 **FAIL** <p>Name table record with key = (3, 1, 1093, 258) has trailing spaces that must be removed: 'alternate vowel marks '</p>
 [code: trailing-space]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure indic fonts have the Indian Rupee Sign glyph. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#rupee">rupee</a></summary>
    <div>







* 🔥 **FAIL** <p>Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9.</p>
 [code: missing-rupee]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Font contains glyphs for whitespace characters? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#whitespace-glyphs">whitespace_glyphs</a></summary>
    <div>







* 🔥 **FAIL** <p>Whitespace glyph missing for codepoint 0x00A0.</p>
 [code: missing-whitespace-glyph-0x00A0]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>No GF glyphset was found to be supported &gt;80%, so language shaping support couldn't get checked.</p>
 [code: no-glyphset-supported]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2025 Panchanan Project Authors (github.com/mitradranirban/panchanan)&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-license-OFL-copyright">googlefonts/license/OFL_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- bn_hasanta

- bn_likaar

- bn_llikaar

- bn_nukta

- bn_rikaar

- bn_rrikaar

- bn_ukaar

- bn_uukaar
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left"><strong>Panchanan Regular</strong></td>
<td align="left"><strong>Panchanan</strong></td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Panchanan Regular</td>
<td align="left">Panchanan Regular</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left">Panchanan-Regular</td>
<td align="left">Panchanan-Regular</td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left"><strong>Panchanan</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left"><strong>Regular</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0021 (EXCLAMATION MARK)


- 0x0022 (QUOTATION MARK)


- 0x0023 (NUMBER SIGN)


- 0x0024 (DOLLAR SIGN)


- 0x0025 (PERCENT SIGN)


- 0x0026 (AMPERSAND)


- 0x0027 (APOSTROPHE)


- 0x0028 (LEFT PARENTHESIS)


- 0x0029 (RIGHT PARENTHESIS)


- 0x002A (ASTERISK)


- 0x002B (PLUS SIGN)


- 0x002C (COMMA)


- 0x002D (HYPHEN-MINUS)


- 0x002E (FULL STOP)


- 0x002F (SOLIDUS)


- 0x0030 (DIGIT ZERO)


- 0x0031 (DIGIT ONE)


- 0x0032 (DIGIT TWO)


- 0x0033 (DIGIT THREE)


- 0x0034 (DIGIT FOUR)


- 0x0035 (DIGIT FIVE)


- 0x0036 (DIGIT SIX)


- 0x0037 (DIGIT SEVEN)


- 0x0038 (DIGIT EIGHT)


- 0x0039 (DIGIT NINE)


- 0x003A (COLON)


- 0x003B (SEMICOLON)


- 0x003C (LESS-THAN SIGN)


- 0x003D (EQUALS SIGN)


- 0x003E (GREATER-THAN SIGN)


- 0x003F (QUESTION MARK)


- 0x0040 (COMMERCIAL AT)


- 0x0041 (LATIN CAPITAL LETTER A)


- 0x0042 (LATIN CAPITAL LETTER B)


- 0x0043 (LATIN CAPITAL LETTER C)


- 0x0044 (LATIN CAPITAL LETTER D)


- 0x0045 (LATIN CAPITAL LETTER E)


- 0x0046 (LATIN CAPITAL LETTER F)


- 0x0047 (LATIN CAPITAL LETTER G)


- 0x0048 (LATIN CAPITAL LETTER H)


- 0x0049 (LATIN CAPITAL LETTER I)


- 0x004A (LATIN CAPITAL LETTER J)


- 0x004B (LATIN CAPITAL LETTER K)


- 0x004C (LATIN CAPITAL LETTER L)


- 0x004D (LATIN CAPITAL LETTER M)


- 0x004E (LATIN CAPITAL LETTER N)


- 0x004F (LATIN CAPITAL LETTER O)


- 0x0050 (LATIN CAPITAL LETTER P)


- 0x0051 (LATIN CAPITAL LETTER Q)


- 0x0052 (LATIN CAPITAL LETTER R)


- 0x0053 (LATIN CAPITAL LETTER S)


- 0x0054 (LATIN CAPITAL LETTER T)


- 0x0055 (LATIN CAPITAL LETTER U)


- 0x0056 (LATIN CAPITAL LETTER V)


- 0x0057 (LATIN CAPITAL LETTER W)


- 0x0058 (LATIN CAPITAL LETTER X)


- 0x0059 (LATIN CAPITAL LETTER Y)


- 0x005A (LATIN CAPITAL LETTER Z)


- 0x005B (LEFT SQUARE BRACKET)


- 0x005C (REVERSE SOLIDUS)


- 0x005D (RIGHT SQUARE BRACKET)


- 0x005E (CIRCUMFLEX ACCENT)


- 0x005F (LOW LINE)


- 0x0060 (GRAVE ACCENT)


- 0x0061 (LATIN SMALL LETTER A)


- 0x0062 (LATIN SMALL LETTER B)


- 0x0063 (LATIN SMALL LETTER C)


- 0x0064 (LATIN SMALL LETTER D)


- 0x0065 (LATIN SMALL LETTER E)


- 0x0066 (LATIN SMALL LETTER F)


- 0x0067 (LATIN SMALL LETTER G)


- 0x0068 (LATIN SMALL LETTER H)


- 0x0069 (LATIN SMALL LETTER I)


- 0x006A (LATIN SMALL LETTER J)


- 0x006B (LATIN SMALL LETTER K)


- 0x006C (LATIN SMALL LETTER L)


- 0x006D (LATIN SMALL LETTER M)


- 0x006E (LATIN SMALL LETTER N)


- 0x006F (LATIN SMALL LETTER O)


- 0x0070 (LATIN SMALL LETTER P)


- 0x0071 (LATIN SMALL LETTER Q)


- 0x0072 (LATIN SMALL LETTER R)


- 0x0073 (LATIN SMALL LETTER S)


- 0x0074 (LATIN SMALL LETTER T)


- 0x0075 (LATIN SMALL LETTER U)


- 0x0076 (LATIN SMALL LETTER V)


- 0x0077 (LATIN SMALL LETTER W)


- 0x0078 (LATIN SMALL LETTER X)


- 0x0079 (LATIN SMALL LETTER Y)


- 0x007A (LATIN SMALL LETTER Z)


- 0x007B (LEFT CURLY BRACKET)


- 0x007C (VERTICAL LINE)


- 0x007D (RIGHT CURLY BRACKET)


- 0x007E (TILDE)


- 0x00A0 (NO-BREAK SPACE)


- 0x00A1 (INVERTED EXCLAMATION MARK)


- 0x00A2 (CENT SIGN)


- 0x00A3 (POUND SIGN)


- 0x00A5 (YEN SIGN)


- 0x00A7 (SECTION SIGN)


- 0x00A8 (DIAERESIS)


- 0x00A9 (COPYRIGHT SIGN)


- 0x00AA (FEMININE ORDINAL INDICATOR)


- 0x00AB (LEFT-POINTING DOUBLE ANGLE QUOTATION MARK)


- 0x00AE (REGISTERED SIGN)


- 0x00AF (MACRON)


- 0x00B0 (DEGREE SIGN)


- 0x00B4 (ACUTE ACCENT)


- 0x00B6 (PILCROW SIGN)


- 0x00B7 (MIDDLE DOT)


- 0x00B8 (CEDILLA)


- 0x00BA (MASCULINE ORDINAL INDICATOR)


- 0x00BB (RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK)


- 0x00BF (INVERTED QUESTION MARK)


- 0x00C0 (LATIN CAPITAL LETTER A WITH GRAVE)


- 0x00C1 (LATIN CAPITAL LETTER A WITH ACUTE)


- 0x00C2 (LATIN CAPITAL LETTER A WITH CIRCUMFLEX)


- 0x00C3 (LATIN CAPITAL LETTER A WITH TILDE)


- 0x00C4 (LATIN CAPITAL LETTER A WITH DIAERESIS)


- 0x00C5 (LATIN CAPITAL LETTER A WITH RING ABOVE)


- 0x00C6 (LATIN CAPITAL LETTER AE)


- 0x00C7 (LATIN CAPITAL LETTER C WITH CEDILLA)


- 0x00C8 (LATIN CAPITAL LETTER E WITH GRAVE)


- 0x00C9 (LATIN CAPITAL LETTER E WITH ACUTE)


- 0x00CA (LATIN CAPITAL LETTER E WITH CIRCUMFLEX)


- 0x00CB (LATIN CAPITAL LETTER E WITH DIAERESIS)


- 0x00CC (LATIN CAPITAL LETTER I WITH GRAVE)


- 0x00CD (LATIN CAPITAL LETTER I WITH ACUTE)


- 0x00CE (LATIN CAPITAL LETTER I WITH CIRCUMFLEX)


- 0x00CF (LATIN CAPITAL LETTER I WITH DIAERESIS)


- 0x00D0 (LATIN CAPITAL LETTER ETH)


- 0x00D1 (LATIN CAPITAL LETTER N WITH TILDE)


- 0x00D2 (LATIN CAPITAL LETTER O WITH GRAVE)


- 0x00D3 (LATIN CAPITAL LETTER O WITH ACUTE)


- 0x00D4 (LATIN CAPITAL LETTER O WITH CIRCUMFLEX)


- 0x00D5 (LATIN CAPITAL LETTER O WITH TILDE)


- 0x00D6 (LATIN CAPITAL LETTER O WITH DIAERESIS)


- 0x00D7 (MULTIPLICATION SIGN)


- 0x00D8 (LATIN CAPITAL LETTER O WITH STROKE)


- 0x00D9 (LATIN CAPITAL LETTER U WITH GRAVE)


- 0x00DA (LATIN CAPITAL LETTER U WITH ACUTE)


- 0x00DB (LATIN CAPITAL LETTER U WITH CIRCUMFLEX)


- 0x00DC (LATIN CAPITAL LETTER U WITH DIAERESIS)


- 0x00DD (LATIN CAPITAL LETTER Y WITH ACUTE)


- 0x00DE (LATIN CAPITAL LETTER THORN)


- 0x00DF (LATIN SMALL LETTER SHARP S)


- 0x00E0 (LATIN SMALL LETTER A WITH GRAVE)


- 0x00E1 (LATIN SMALL LETTER A WITH ACUTE)


- 0x00E2 (LATIN SMALL LETTER A WITH CIRCUMFLEX)


- 0x00E3 (LATIN SMALL LETTER A WITH TILDE)


- 0x00E4 (LATIN SMALL LETTER A WITH DIAERESIS)


- 0x00E5 (LATIN SMALL LETTER A WITH RING ABOVE)


- 0x00E6 (LATIN SMALL LETTER AE)


- 0x00E7 (LATIN SMALL LETTER C WITH CEDILLA)


- 0x00E8 (LATIN SMALL LETTER E WITH GRAVE)


- 0x00E9 (LATIN SMALL LETTER E WITH ACUTE)


- 0x00EA (LATIN SMALL LETTER E WITH CIRCUMFLEX)


- 0x00EB (LATIN SMALL LETTER E WITH DIAERESIS)


- 0x00EC (LATIN SMALL LETTER I WITH GRAVE)


- 0x00ED (LATIN SMALL LETTER I WITH ACUTE)


- 0x00EE (LATIN SMALL LETTER I WITH CIRCUMFLEX)


- 0x00EF (LATIN SMALL LETTER I WITH DIAERESIS)


- 0x00F0 (LATIN SMALL LETTER ETH)


- 0x00F1 (LATIN SMALL LETTER N WITH TILDE)


- 0x00F2 (LATIN SMALL LETTER O WITH GRAVE)


- 0x00F3 (LATIN SMALL LETTER O WITH ACUTE)


- 0x00F4 (LATIN SMALL LETTER O WITH CIRCUMFLEX)


- 0x00F5 (LATIN SMALL LETTER O WITH TILDE)


- 0x00F6 (LATIN SMALL LETTER O WITH DIAERESIS)


- 0x00F7 (DIVISION SIGN)


- 0x00F8 (LATIN SMALL LETTER O WITH STROKE)


- 0x00F9 (LATIN SMALL LETTER U WITH GRAVE)


- 0x00FA (LATIN SMALL LETTER U WITH ACUTE)


- 0x00FB (LATIN SMALL LETTER U WITH CIRCUMFLEX)


- 0x00FC (LATIN SMALL LETTER U WITH DIAERESIS)


- 0x00FD (LATIN SMALL LETTER Y WITH ACUTE)


- 0x00FE (LATIN SMALL LETTER THORN)


- 0x00FF (LATIN SMALL LETTER Y WITH DIAERESIS)


- 0x0100 (LATIN CAPITAL LETTER A WITH MACRON)


- 0x0101 (LATIN SMALL LETTER A WITH MACRON)


- 0x0102 (LATIN CAPITAL LETTER A WITH BREVE)


- 0x0103 (LATIN SMALL LETTER A WITH BREVE)


- 0x0104 (LATIN CAPITAL LETTER A WITH OGONEK)


- 0x0105 (LATIN SMALL LETTER A WITH OGONEK)


- 0x0106 (LATIN CAPITAL LETTER C WITH ACUTE)


- 0x0107 (LATIN SMALL LETTER C WITH ACUTE)


- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


- 0x010C (LATIN CAPITAL LETTER C WITH CARON)


- 0x010D (LATIN SMALL LETTER C WITH CARON)


- 0x010E (LATIN CAPITAL LETTER D WITH CARON)


- 0x010F (LATIN SMALL LETTER D WITH CARON)


- 0x0110 (LATIN CAPITAL LETTER D WITH STROKE)


- 0x0111 (LATIN SMALL LETTER D WITH STROKE)


- 0x0112 (LATIN CAPITAL LETTER E WITH MACRON)


- 0x0113 (LATIN SMALL LETTER E WITH MACRON)


- 0x0116 (LATIN CAPITAL LETTER E WITH DOT ABOVE)


- 0x0117 (LATIN SMALL LETTER E WITH DOT ABOVE)


- 0x0118 (LATIN CAPITAL LETTER E WITH OGONEK)


- 0x0119 (LATIN SMALL LETTER E WITH OGONEK)


- 0x011A (LATIN CAPITAL LETTER E WITH CARON)


- 0x011B (LATIN SMALL LETTER E WITH CARON)


- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


- 0x011F (LATIN SMALL LETTER G WITH BREVE)


- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


- 0x0122 (LATIN CAPITAL LETTER G WITH CEDILLA)


- 0x0123 (LATIN SMALL LETTER G WITH CEDILLA)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x012A (LATIN CAPITAL LETTER I WITH MACRON)


- 0x012B (LATIN SMALL LETTER I WITH MACRON)


- 0x012E (LATIN CAPITAL LETTER I WITH OGONEK)


- 0x012F (LATIN SMALL LETTER I WITH OGONEK)


- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


- 0x0131 (LATIN SMALL LETTER DOTLESS I)


- 0x0136 (LATIN CAPITAL LETTER K WITH CEDILLA)


- 0x0137 (LATIN SMALL LETTER K WITH CEDILLA)


- 0x0139 (LATIN CAPITAL LETTER L WITH ACUTE)


- 0x013A (LATIN SMALL LETTER L WITH ACUTE)


- 0x013B (LATIN CAPITAL LETTER L WITH CEDILLA)


- 0x013C (LATIN SMALL LETTER L WITH CEDILLA)


- 0x013D (LATIN CAPITAL LETTER L WITH CARON)


- 0x013E (LATIN SMALL LETTER L WITH CARON)


- 0x0141 (LATIN CAPITAL LETTER L WITH STROKE)


- 0x0142 (LATIN SMALL LETTER L WITH STROKE)


- 0x0143 (LATIN CAPITAL LETTER N WITH ACUTE)


- 0x0144 (LATIN SMALL LETTER N WITH ACUTE)


- 0x0145 (LATIN CAPITAL LETTER N WITH CEDILLA)


- 0x0146 (LATIN SMALL LETTER N WITH CEDILLA)


- 0x0147 (LATIN CAPITAL LETTER N WITH CARON)


- 0x0148 (LATIN SMALL LETTER N WITH CARON)


- 0x0150 (LATIN CAPITAL LETTER O WITH DOUBLE ACUTE)


- 0x0151 (LATIN SMALL LETTER O WITH DOUBLE ACUTE)


- 0x0152 (LATIN CAPITAL LIGATURE OE)


- 0x0153 (LATIN SMALL LIGATURE OE)


- 0x0154 (LATIN CAPITAL LETTER R WITH ACUTE)


- 0x0155 (LATIN SMALL LETTER R WITH ACUTE)


- 0x0158 (LATIN CAPITAL LETTER R WITH CARON)


- 0x0159 (LATIN SMALL LETTER R WITH CARON)


- 0x015A (LATIN CAPITAL LETTER S WITH ACUTE)


- 0x015B (LATIN SMALL LETTER S WITH ACUTE)


- 0x015E (LATIN CAPITAL LETTER S WITH CEDILLA)


- 0x015F (LATIN SMALL LETTER S WITH CEDILLA)


- 0x0160 (LATIN CAPITAL LETTER S WITH CARON)


- 0x0161 (LATIN SMALL LETTER S WITH CARON)


- 0x0164 (LATIN CAPITAL LETTER T WITH CARON)


- 0x0165 (LATIN SMALL LETTER T WITH CARON)


- 0x016A (LATIN CAPITAL LETTER U WITH MACRON)


- 0x016B (LATIN SMALL LETTER U WITH MACRON)


- 0x016E (LATIN CAPITAL LETTER U WITH RING ABOVE)


- 0x016F (LATIN SMALL LETTER U WITH RING ABOVE)


- 0x0170 (LATIN CAPITAL LETTER U WITH DOUBLE ACUTE)


- 0x0171 (LATIN SMALL LETTER U WITH DOUBLE ACUTE)


- 0x0172 (LATIN CAPITAL LETTER U WITH OGONEK)


- 0x0173 (LATIN SMALL LETTER U WITH OGONEK)


- 0x0174 (LATIN CAPITAL LETTER W WITH CIRCUMFLEX)


- 0x0175 (LATIN SMALL LETTER W WITH CIRCUMFLEX)


- 0x0176 (LATIN CAPITAL LETTER Y WITH CIRCUMFLEX)


- 0x0177 (LATIN SMALL LETTER Y WITH CIRCUMFLEX)


- 0x0178 (LATIN CAPITAL LETTER Y WITH DIAERESIS)


- 0x0179 (LATIN CAPITAL LETTER Z WITH ACUTE)


- 0x017A (LATIN SMALL LETTER Z WITH ACUTE)


- 0x017B (LATIN CAPITAL LETTER Z WITH DOT ABOVE)


- 0x017C (LATIN SMALL LETTER Z WITH DOT ABOVE)


- 0x017D (LATIN CAPITAL LETTER Z WITH CARON)


- 0x017E (LATIN SMALL LETTER Z WITH CARON)


- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DA (RING ABOVE)


- 0x02DB (OGONEK)


- 0x02DC (SMALL TILDE)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x0300 (COMBINING GRAVE ACCENT)


- 0x0301 (COMBINING ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x0307 (COMBINING DOT ABOVE)


- 0x0308 (COMBINING DIAERESIS)


- 0x030A (COMBINING RING ABOVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x2013 (EN DASH)


- 0x2014 (EM DASH)


- 0x2018 (LEFT SINGLE QUOTATION MARK)


- 0x2019 (RIGHT SINGLE QUOTATION MARK)


- 0x201A (SINGLE LOW-9 QUOTATION MARK)


- 0x201C (LEFT DOUBLE QUOTATION MARK)


- 0x201D (RIGHT DOUBLE QUOTATION MARK)


- 0x201E (DOUBLE LOW-9 QUOTATION MARK)


- 0x2022 (BULLET)


- 0x2026 (HORIZONTAL ELLIPSIS)


- 0x2039 (SINGLE LEFT-POINTING ANGLE QUOTATION MARK)


- 0x203A (SINGLE RIGHT-POINTING ANGLE QUOTATION MARK)


- 0x20AC (EURO SIGN)


- 0x2122 (TRADE MARK SIGN)


- 0x2212 (MINUS SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Version format is correct in 'name' table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-version-format">googlefonts/name/version_format</a></summary>
    <div>







* 🔥 **FAIL** <p>The NameID.VERSION_STRING (nameID=5) value must follow the pattern &quot;Version X.Y&quot; with X.Y greater than or equal to 1.000. The &quot;Version &quot; prefix is a recommendation given by the OpenType spec. Current version string is: &quot;Version 0.500; ttfautohint (v1.8.4.7-5d5b)&quot;</p>
 [code: bad-version-strings]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure font can render its own name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-render-own-name">googlefonts/render_own_name</a></summary>
    <div>







* 🔥 **FAIL** <p>.notdef glyphs were found when attempting to render Panchanan Regular</p>
 [code: render-own-name]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-weightclass">googlefonts/weightclass</a></summary>
    <div>







* 🔥 **FAIL** <p>Best SubFamily name is 'Regular'. Expected OS/2 usWeightClass is 400, got 500.</p>
 [code: bad-value]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-mark-chars">opentype/gdef_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
bn_chandrabindu (U+0981)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: uni25CC	Contours detected: 9	Expected: 16 or 12

- Glyph name: uni25CC	Contours detected: 9	Expected: 16 or 12
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#gpos-kerning-info">gpos_kerning_info</a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- bn_D_ga

- bn_d_gha

- bn_half_asamese_ra

- bn_half_asamese_va

- bn_n_ma

- bn_ng_ga.alt

- bn_ng_ka.alt

- bn_post_ukaar

- bn_post_uukaar

- bn_r_rikaar

- bn_sh_ma
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* bn_aat (U+09EE): L&lt;&lt;432.0,966.0&gt;--&lt;432.0,940.0&gt;&gt; -&gt; L&lt;&lt;432.0,940.0&gt;--&lt;429.0,713.0&gt;&gt;

* bn_aikaar_init: L&lt;&lt;990.0,1458.0&gt;--&lt;1010.0,1458.0&gt;&gt; -&gt; L&lt;&lt;1010.0,1458.0&gt;--&lt;1196.0,1457.0&gt;&gt;

* bn_bha (U+09AD): L&lt;&lt;-22.0,1447.0&gt;--&lt;647.0,1441.0&gt;&gt; -&gt; L&lt;&lt;647.0,1441.0&gt;--&lt;1568.0,1430.0&gt;&gt;

* bn_bha_hasanta: L&lt;&lt;-22.0,1447.0&gt;--&lt;647.0,1441.0&gt;&gt; -&gt; L&lt;&lt;647.0,1441.0&gt;--&lt;1568.0,1430.0&gt;&gt;

* bn_bha_ra: L&lt;&lt;1309.0,1009.0&gt;--&lt;1310.0,756.0&gt;&gt; -&gt; L&lt;&lt;1310.0,756.0&gt;--&lt;1310.0,502.0&gt;&gt;

* bn_d_r_uukaar: L&lt;&lt;437.0,1190.0&gt;--&lt;425.0,1034.0&gt;&gt; -&gt; L&lt;&lt;425.0,1034.0&gt;--&lt;413.0,879.0&gt;&gt;

* bn_da (U+09A6): L&lt;&lt;344.0,1238.0&gt;--&lt;340.0,1100.0&gt;&gt; -&gt; L&lt;&lt;340.0,1100.0&gt;--&lt;340.0,1072.0&gt;&gt;

* bn_da_hasanta: L&lt;&lt;344.0,1238.0&gt;--&lt;340.0,1100.0&gt;&gt; -&gt; L&lt;&lt;340.0,1100.0&gt;--&lt;340.0,1072.0&gt;&gt;

* bn_da_ra: L&lt;&lt;344.0,1238.0&gt;--&lt;340.0,1100.0&gt;&gt; -&gt; L&lt;&lt;340.0,1100.0&gt;--&lt;340.0,1072.0&gt;&gt;

* bn_dda (U+09A1): L&lt;&lt;674.0,514.0&gt;--&lt;656.0,978.0&gt;&gt; -&gt; L&lt;&lt;656.0,978.0&gt;--&lt;646.0,1069.0&gt;&gt;

* bn_dda_dda: L&lt;&lt;1261.0,868.0&gt;--&lt;1251.0,978.0&gt;&gt; -&gt; L&lt;&lt;1251.0,978.0&gt;--&lt;1241.0,1069.0&gt;&gt;

* bn_dda_dda: L&lt;&lt;1956.0,602.0&gt;--&lt;1963.0,423.0&gt;&gt; -&gt; L&lt;&lt;1963.0,423.0&gt;--&lt;1969.0,245.0&gt;&gt;

* bn_dda_hasanta: L&lt;&lt;674.0,514.0&gt;--&lt;656.0,978.0&gt;&gt; -&gt; L&lt;&lt;656.0,978.0&gt;--&lt;646.0,1069.0&gt;&gt;

* bn_dda_ra: L&lt;&lt;1320.0,602.0&gt;--&lt;1326.0,423.0&gt;&gt; -&gt; L&lt;&lt;1326.0,423.0&gt;--&lt;1332.0,245.0&gt;&gt;

* bn_dda_ra: L&lt;&lt;665.0,868.0&gt;--&lt;656.0,978.0&gt;&gt; -&gt; L&lt;&lt;656.0,978.0&gt;--&lt;646.0,1069.0&gt;&gt;

* bn_gha (U+0998): L&lt;&lt;732.0,1461.0&gt;--&lt;806.0,1461.0&gt;&gt; -&gt; L&lt;&lt;806.0,1461.0&gt;--&lt;1514.0,1460.0&gt;&gt;

* bn_gha_hasanta: L&lt;&lt;732.0,1461.0&gt;--&lt;806.0,1461.0&gt;&gt; -&gt; L&lt;&lt;806.0,1461.0&gt;--&lt;1514.0,1460.0&gt;&gt;

* bn_gha_na: L&lt;&lt;913.0,1272.0&gt;--&lt;914.0,1003.0&gt;&gt; -&gt; L&lt;&lt;914.0,1003.0&gt;--&lt;914.0,930.0&gt;&gt;

* bn_gha_ra: L&lt;&lt;732.0,1461.0&gt;--&lt;806.0,1461.0&gt;&gt; -&gt; L&lt;&lt;806.0,1461.0&gt;--&lt;1514.0,1460.0&gt;&gt;

* bn_half_ja: L&lt;&lt;894.0,957.0&gt;--&lt;895.0,1015.0&gt;&gt; -&gt; L&lt;&lt;895.0,1015.0&gt;--&lt;895.0,1020.0&gt;&gt;

* bn_half_pha: L&lt;&lt;523.0,866.0&gt;--&lt;519.0,1030.0&gt;&gt; -&gt; L&lt;&lt;519.0,1030.0&gt;--&lt;519.0,1058.0&gt;&gt;

* bn_half_tha: L&lt;&lt;1002.0,1440.0&gt;--&lt;1031.0,1357.0&gt;&gt; -&gt; L&lt;&lt;1031.0,1357.0&gt;--&lt;1059.0,1274.0&gt;&gt;

* bn_half_tha: L&lt;&lt;1059.0,1274.0&gt;--&lt;951.0,1259.0&gt;&gt; -&gt; L&lt;&lt;951.0,1259.0&gt;--&lt;843.0,1245.0&gt;&gt;

* bn_ja_ja: L&lt;&lt;894.0,957.0&gt;--&lt;895.0,1015.0&gt;&gt; -&gt; L&lt;&lt;895.0,1015.0&gt;--&lt;895.0,1020.0&gt;&gt;

* bn_ja_ja_ba: L&lt;&lt;894.0,957.0&gt;--&lt;895.0,1015.0&gt;&gt; -&gt; L&lt;&lt;895.0,1015.0&gt;--&lt;895.0,1020.0&gt;&gt;

* bn_ja_jha: L&lt;&lt;894.0,957.0&gt;--&lt;895.0,1015.0&gt;&gt; -&gt; L&lt;&lt;895.0,1015.0&gt;--&lt;895.0,1020.0&gt;&gt;

* bn_k_ukaar: L&lt;&lt;673.0,731.0&gt;--&lt;587.0,816.0&gt;&gt; -&gt; L&lt;&lt;587.0,816.0&gt;--&lt;500.0,900.0&gt;&gt;

* bn_ka_ra.alt: L&lt;&lt;1336.0,1426.0&gt;--&lt;1346.0,1330.0&gt;&gt; -&gt; L&lt;&lt;1346.0,1330.0&gt;--&lt;1356.0,1235.0&gt;&gt;

* bn_ka_ssa_ma: L&lt;&lt;0.0,1382.0&gt;--&lt;532.0,1383.0&gt;&gt; -&gt; L&lt;&lt;532.0,1383.0&gt;--&lt;1065.0,1384.0&gt;&gt;

* bn_ma_da: L&lt;&lt;1104.0,1238.0&gt;--&lt;1100.0,1100.0&gt;&gt; -&gt; L&lt;&lt;1100.0,1100.0&gt;--&lt;1100.0,1072.0&gt;&gt;

* bn_ma_ma.alt: L&lt;&lt;418.0,899.0&gt;--&lt;320.0,902.0&gt;&gt; -&gt; L&lt;&lt;320.0,902.0&gt;--&lt;306.0,902.0&gt;&gt;

* bn_ma_pha: L&lt;&lt;554.0,145.0&gt;--&lt;551.0,299.0&gt;&gt; -&gt; L&lt;&lt;551.0,299.0&gt;--&lt;551.0,329.0&gt;&gt;

* bn_n_ya: L&lt;&lt;261.0,1030.0&gt;--&lt;521.0,1026.0&gt;&gt; -&gt; L&lt;&lt;521.0,1026.0&gt;--&lt;781.0,1023.0&gt;&gt;

* bn_na (U+09A8): L&lt;&lt;261.0,1030.0&gt;--&lt;521.0,1026.0&gt;&gt; -&gt; L&lt;&lt;521.0,1026.0&gt;--&lt;781.0,1023.0&gt;&gt;

* bn_na_da: L&lt;&lt;628.0,1094.0&gt;--&lt;635.0,1094.0&gt;&gt; -&gt; L&lt;&lt;635.0,1094.0&gt;--&lt;814.0,1093.0&gt;&gt;

* bn_na_da: L&lt;&lt;814.0,1093.0&gt;--&lt;807.0,1155.0&gt;&gt; -&gt; L&lt;&lt;807.0,1155.0&gt;--&lt;799.0,1217.0&gt;&gt;

* bn_na_da_ra: L&lt;&lt;628.0,1094.0&gt;--&lt;635.0,1094.0&gt;&gt; -&gt; L&lt;&lt;635.0,1094.0&gt;--&lt;814.0,1093.0&gt;&gt;

* bn_na_da_ra: L&lt;&lt;814.0,1093.0&gt;--&lt;807.0,1155.0&gt;&gt; -&gt; L&lt;&lt;807.0,1155.0&gt;--&lt;799.0,1217.0&gt;&gt;

* bn_na_hasanta: L&lt;&lt;261.0,1030.0&gt;--&lt;521.0,1026.0&gt;&gt; -&gt; L&lt;&lt;521.0,1026.0&gt;--&lt;781.0,1023.0&gt;&gt;

* bn_ng_ga: L&lt;&lt;680.0,715.0&gt;--&lt;680.0,692.0&gt;&gt; -&gt; L&lt;&lt;680.0,692.0&gt;--&lt;674.0,531.0&gt;&gt;

* bn_ng_gha: L&lt;&lt;31.0,570.0&gt;--&lt;120.0,572.0&gt;&gt; -&gt; L&lt;&lt;120.0,572.0&gt;--&lt;130.0,572.0&gt;&gt;

* bn_ng_gha: L&lt;&lt;690.0,445.0&gt;--&lt;686.0,165.0&gt;&gt; -&gt; L&lt;&lt;686.0,165.0&gt;--&lt;683.0,-114.0&gt;&gt;

* bn_nga (U+0999): L&lt;&lt;780.0,927.0&gt;--&lt;779.0,855.0&gt;&gt; -&gt; L&lt;&lt;779.0,855.0&gt;--&lt;779.0,840.0&gt;&gt;

* bn_nga_hasanta: L&lt;&lt;780.0,927.0&gt;--&lt;779.0,855.0&gt;&gt; -&gt; L&lt;&lt;779.0,855.0&gt;--&lt;779.0,840.0&gt;&gt;

* bn_ny_ja: L&lt;&lt;727.0,935.0&gt;--&lt;768.0,976.0&gt;&gt; -&gt; L&lt;&lt;768.0,976.0&gt;--&lt;809.0,1016.0&gt;&gt;

* bn_ny_ja: L&lt;&lt;809.0,1016.0&gt;--&lt;748.0,1066.0&gt;&gt; -&gt; L&lt;&lt;748.0,1066.0&gt;--&lt;688.0,1116.0&gt;&gt;

* bn_ph_la: L&lt;&lt;523.0,866.0&gt;--&lt;519.0,1030.0&gt;&gt; -&gt; L&lt;&lt;519.0,1030.0&gt;--&lt;519.0,1058.0&gt;&gt;

* bn_pha (U+09AB): L&lt;&lt;0.0,1480.0&gt;--&lt;1075.0,1481.0&gt;&gt; -&gt; L&lt;&lt;1075.0,1481.0&gt;--&lt;2149.0,1482.0&gt;&gt;

* bn_pha_hasanta: L&lt;&lt;0.0,1480.0&gt;--&lt;1075.0,1481.0&gt;&gt; -&gt; L&lt;&lt;1075.0,1481.0&gt;--&lt;2149.0,1482.0&gt;&gt;

* bn_rra (U+09DC): L&lt;&lt;1320.0,602.0&gt;--&lt;1326.0,423.0&gt;&gt; -&gt; L&lt;&lt;1326.0,423.0&gt;--&lt;1332.0,245.0&gt;&gt;

* bn_rra (U+09DC): L&lt;&lt;665.0,868.0&gt;--&lt;656.0,978.0&gt;&gt; -&gt; L&lt;&lt;656.0,978.0&gt;--&lt;646.0,1069.0&gt;&gt;

* bn_rra_hasanta: L&lt;&lt;1320.0,602.0&gt;--&lt;1326.0,423.0&gt;&gt; -&gt; L&lt;&lt;1326.0,423.0&gt;--&lt;1332.0,245.0&gt;&gt;

* bn_rra_hasanta: L&lt;&lt;665.0,868.0&gt;--&lt;656.0,978.0&gt;&gt; -&gt; L&lt;&lt;656.0,978.0&gt;--&lt;646.0,1069.0&gt;&gt;

* bn_s_ma: L&lt;&lt;484.0,699.0&gt;--&lt;551.0,699.0&gt;&gt; -&gt; L&lt;&lt;551.0,699.0&gt;--&lt;719.0,703.0&gt;&gt;

* bn_sa_tha: L&lt;&lt;1242.0,463.0&gt;--&lt;1132.0,448.0&gt;&gt; -&gt; L&lt;&lt;1132.0,448.0&gt;--&lt;1023.0,434.0&gt;&gt;

* bn_ssa_tta: L&lt;&lt;1363.0,1093.0&gt;--&lt;1403.0,1010.0&gt;&gt; -&gt; L&lt;&lt;1403.0,1010.0&gt;--&lt;1444.0,927.0&gt;&gt;

* bn_ssa_tta_ra: L&lt;&lt;1363.0,1093.0&gt;--&lt;1403.0,1010.0&gt;&gt; -&gt; L&lt;&lt;1403.0,1010.0&gt;--&lt;1444.0,927.0&gt;&gt;

* bn_tha_ba: L&lt;&lt;1002.0,1440.0&gt;--&lt;1031.0,1357.0&gt;&gt; -&gt; L&lt;&lt;1031.0,1357.0&gt;--&lt;1059.0,1274.0&gt;&gt;

* bn_tha_ba: L&lt;&lt;1059.0,1274.0&gt;--&lt;951.0,1259.0&gt;&gt; -&gt; L&lt;&lt;951.0,1259.0&gt;--&lt;843.0,1245.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* bn_aukaar (U+09CC): B&lt;&lt;616.0,1470.5&gt;-&lt;615.0,1471.0&gt;-&lt;613.0,1471.0&gt;&gt;/B&lt;&lt;613.0,1471.0&gt;-&lt;656.0,1476.0&gt;-&lt;696.0,1476.0&gt;&gt; = 6.632514615138473

* bn_ekaar (U+09C7): B&lt;&lt;616.0,1470.5&gt;-&lt;615.0,1471.0&gt;-&lt;613.0,1471.0&gt;&gt;/B&lt;&lt;613.0,1471.0&gt;-&lt;656.0,1476.0&gt;-&lt;696.0,1476.0&gt;&gt; = 6.632514615138473

* bn_ga_la: L&lt;&lt;1257.0,-103.0&gt;--&lt;1257.0,-116.0&gt;&gt;/B&lt;&lt;1257.0,-116.0&gt;-&lt;1256.0,-101.0&gt;-&lt;1237.5,-97.0&gt;&gt; = 3.8140748342903783

* bn_la_phala: L&lt;&lt;63.0,-211.0&gt;--&lt;63.0,-224.0&gt;&gt;/B&lt;&lt;63.0,-224.0&gt;-&lt;62.0,-209.0&gt;-&lt;43.5,-205.0&gt;&gt; = 3.8140748342903783

* bn_na_da_ra: B&lt;&lt;1529.5,-143.5&gt;-&lt;1523.0,-143.0&gt;-&lt;1516.0,-142.0&gt;&gt;/B&lt;&lt;1516.0,-142.0&gt;-&lt;1528.0,-146.0&gt;-&lt;1545.0,-149.5&gt;&gt; = 10.304846468766009

* bn_okaar (U+09CB): B&lt;&lt;616.0,1470.5&gt;-&lt;615.0,1471.0&gt;-&lt;613.0,1471.0&gt;&gt;/B&lt;&lt;613.0,1471.0&gt;-&lt;656.0,1476.0&gt;-&lt;696.0,1476.0&gt;&gt; = 6.632514615138473

* bn_pa_la: L&lt;&lt;819.0,-32.0&gt;--&lt;819.0,-45.0&gt;&gt;/B&lt;&lt;819.0,-45.0&gt;-&lt;818.0,-30.0&gt;-&lt;803.5,-26.0&gt;&gt; = 3.8140748342903783

* bn_ph_la: L&lt;&lt;895.0,-3.0&gt;--&lt;895.0,-16.0&gt;&gt;/B&lt;&lt;895.0,-16.0&gt;-&lt;894.0,-1.0&gt;-&lt;875.5,3.0&gt;&gt; = 3.8140748342903783

* bn_rra_ga: B&lt;&lt;978.5,1308.0&gt;-&lt;963.0,1286.0&gt;-&lt;937.0,1253.0&gt;&gt;/B&lt;&lt;937.0,1253.0&gt;-&lt;971.0,1286.0&gt;-&lt;1010.0,1299.0&gt;&gt; = 7.621272218819725

* bn_sa_la: L&lt;&lt;1060.0,21.0&gt;--&lt;1060.0,8.0&gt;&gt;/B&lt;&lt;1060.0,8.0&gt;-&lt;1059.0,23.0&gt;-&lt;1040.5,27.0&gt;&gt; = 3.8140748342903783

* bn_sh_la: L&lt;&lt;1391.0,-231.0&gt;--&lt;1391.0,-244.0&gt;&gt;/B&lt;&lt;1391.0,-244.0&gt;-&lt;1390.0,-229.0&gt;-&lt;1371.5,-225.0&gt;&gt; = 3.8140748342903783
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* bn_aikaar_init: L&lt;&lt;1010.0,1458.0&gt;--&lt;1196.0,1457.0&gt;&gt;

* bn_asamia_va (U+09F1): L&lt;&lt;1081.0,1249.0&gt;--&lt;1082.0,814.0&gt;&gt;

* bn_asamir_hasanta: L&lt;&lt;1081.0,1249.0&gt;--&lt;1082.0,814.0&gt;&gt;

* bn_aukaar (U+09CC): L&lt;&lt;696.0,1476.0&gt;--&lt;828.0,1477.0&gt;&gt;

* bn_ba (U+09AC): L&lt;&lt;1081.0,1249.0&gt;--&lt;1082.0,814.0&gt;&gt;

* bn_ba_hasanta: L&lt;&lt;1081.0,1249.0&gt;--&lt;1082.0,814.0&gt;&gt;

* bn_bha_ra: L&lt;&lt;1309.0,1009.0&gt;--&lt;1310.0,756.0&gt;&gt;

* bn_ca_cha: L&lt;&lt;-20.0,1430.0&gt;--&lt;242.0,1432.0&gt;&gt;

* bn_da (U+09A6): L&lt;&lt;761.0,1240.0&gt;--&lt;344.0,1238.0&gt;&gt;

* bn_da_hasanta: L&lt;&lt;761.0,1240.0&gt;--&lt;344.0,1238.0&gt;&gt;

* bn_da_ra: L&lt;&lt;761.0,1240.0&gt;--&lt;344.0,1238.0&gt;&gt;

* bn_ekaar (U+09C7): L&lt;&lt;696.0,1476.0&gt;--&lt;828.0,1477.0&gt;&gt;

* bn_ekaar_init: L&lt;&lt;696.0,1476.0&gt;--&lt;828.0,1477.0&gt;&gt;

* bn_gha (U+0998): L&lt;&lt;806.0,1461.0&gt;--&lt;1514.0,1460.0&gt;&gt;

* bn_gha_hasanta: L&lt;&lt;806.0,1461.0&gt;--&lt;1514.0,1460.0&gt;&gt;

* bn_gha_na: L&lt;&lt;913.0,1272.0&gt;--&lt;914.0,1003.0&gt;&gt;

* bn_gha_ra: L&lt;&lt;806.0,1461.0&gt;--&lt;1514.0,1460.0&gt;&gt;

* bn_h_ba: L&lt;&lt;1640.0,1249.0&gt;--&lt;1641.0,814.0&gt;&gt;

* bn_ha_la: L&lt;&lt;1674.0,1469.0&gt;--&lt;2460.0,1475.0&gt;&gt;

* bn_half_asamese_va: L&lt;&lt;678.0,1262.0&gt;--&lt;679.0,1001.0&gt;&gt;

* bn_half_ba: L&lt;&lt;641.0,1435.0&gt;--&lt;1168.0,1439.0&gt;&gt;

* bn_half_ra: L&lt;&lt;641.0,1435.0&gt;--&lt;1168.0,1439.0&gt;&gt;

* bn_ii (U+0988): L&lt;&lt;1386.0,1218.0&gt;--&lt;731.0,1223.0&gt;&gt;

* bn_iikaar (U+09C0): L&lt;&lt;282.0,924.0&gt;--&lt;283.0,1204.0&gt;&gt;

* bn_ikaar.alt: L&lt;&lt;505.0,1391.0&gt;--&lt;504.0,1265.0&gt;&gt;

* bn_ka_ssa_ma: L&lt;&lt;0.0,1382.0&gt;--&lt;532.0,1383.0&gt;&gt;

* bn_ka_ssa_ma: L&lt;&lt;532.0,1383.0&gt;--&lt;1065.0,1384.0&gt;&gt;

* bn_m_bh_ra: L&lt;&lt;786.0,1414.0&gt;--&lt;1127.0,1412.0&gt;&gt;

* bn_ma_bha: L&lt;&lt;786.0,1414.0&gt;--&lt;1127.0,1412.0&gt;&gt;

* bn_ma_da: L&lt;&lt;1521.0,1240.0&gt;--&lt;1104.0,1238.0&gt;&gt;

* bn_na_da: L&lt;&lt;635.0,1094.0&gt;--&lt;814.0,1093.0&gt;&gt;

* bn_na_da_ra: L&lt;&lt;635.0,1094.0&gt;--&lt;814.0,1093.0&gt;&gt;

* bn_nya_cha: L&lt;&lt;765.0,1442.0&gt;--&lt;1523.0,1436.0&gt;&gt;

* bn_okaar (U+09CB): L&lt;&lt;696.0,1476.0&gt;--&lt;828.0,1477.0&gt;&gt;

* bn_pha (U+09AB): L&lt;&lt;0.0,1480.0&gt;--&lt;1075.0,1481.0&gt;&gt;

* bn_pha (U+09AB): L&lt;&lt;1075.0,1481.0&gt;--&lt;2149.0,1482.0&gt;&gt;

* bn_pha_hasanta: L&lt;&lt;0.0,1480.0&gt;--&lt;1075.0,1481.0&gt;&gt;

* bn_pha_hasanta: L&lt;&lt;1075.0,1481.0&gt;--&lt;2149.0,1482.0&gt;&gt;

* bn_r_ukaar: L&lt;&lt;1760.0,1209.0&gt;--&lt;1446.0,1207.0&gt;&gt;

* bn_r_uukaar: L&lt;&lt;1293.0,1212.0&gt;--&lt;1007.0,1210.0&gt;&gt;

* bn_ra (U+09B0): L&lt;&lt;1081.0,1275.0&gt;--&lt;1082.0,840.0&gt;&gt;

* bn_ra_hasanta: L&lt;&lt;1081.0,1275.0&gt;--&lt;1082.0,840.0&gt;&gt;

* bn_rri (U+09E0): L&lt;&lt;971.0,1639.0&gt;--&lt;1255.0,1641.0&gt;&gt;

* bn_sa_ta_ra: L&lt;&lt;1049.0,14.0&gt;--&lt;1503.0,11.0&gt;&gt;

* zwj (U+200D): L&lt;&lt;-86.0,174.0&gt;--&lt;-92.0,908.0&gt;&gt;

* zwj (U+200D): L&lt;&lt;86.0,908.0&gt;--&lt;92.0,174.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics">googlefonts/vertical_metrics</a></summary>
    <div>







* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.68115234375x (3443)</p>
 [code: bad-hhea-range]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> List all superfamily filepaths <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#superfamily-list">superfamily/list</a></summary>
    <div>







* ℹ️ **INFO** <p>fonts/ttf</p>
 [code: family-path]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#hinting-impact">hinting_impact</a></summary>
    <div>







* ℹ️ **INFO** <p>Hinting filesize impact:</p>
<table>
<thead>
<tr>
<th align="left"></th>
<th align="right">fonts/ttf/Panchanan-Regular.ttf</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Dehinted Size</td>
<td align="right">165.9kb</td>
</tr>
<tr>
<td align="left">Hinted Size</td>
<td align="right">303.7kb</td>
</tr>
<tr>
<td align="left">Increase</td>
<td align="right">137.9kb</td>
</tr>
<tr>
<td align="left">Change</td>
<td align="right">83.1 %</td>
</tr>
</tbody>
</table>
 [code: size-impact]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Font contains all required tables? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#required-tables">required_tables</a></summary>
    <div>







* ℹ️ **INFO** <p>This font contains the following optional tables:</p>
<pre><code>- cvt 

- fpgm

- loca

- prep

- GPOS

- GSUB

- gasp
</code></pre>
 [code: optional-tables]



* ✅ **PASS** <p>Font contains all required tables.</p>
 



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-description-has-article">googlefonts/description/has_article</a></summary>
    <div>







* ℹ️ **INFO** <p>This font doesn't have an ARTICLE.en_us.html file.</p>
 [code: missing-article]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-gasp">googlefonts/gasp</a></summary>
    <div>







* ℹ️ **INFO** <p>These are the ppm ranges declared on the gasp table:</p>
<p>PPM &lt;= 65535:
flag = 0x0F
- Use grid-fitting
- Use grayscale rendering
- Use gridfitting with ClearType symmetric smoothing
- Use smoothing along multiple axes with ClearType®</p>
 [code: ranges]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check hhea.caretSlopeRise and hhea.caretSlopeRun <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-caret-slope">opentype/caret_slope</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check code page character ranges <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-code-pages">opentype/code_pages</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Font follows the family naming recommendations? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-family-naming-recommendations">opentype/family_naming_recommendations</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Checking font version fields (head and name table). <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-font-version">opentype/font_version</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Checking OS/2 fsSelection value. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-fsselection">opentype/fsselection</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-non-mark-chars">opentype/gdef_non_mark_chars</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-spacing-marks">opentype/gdef_spacing_marks</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check glyphs do not have duplicate components which have the same x,y coordinates. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-glyf-non-transformed-duplicate-components">opentype/glyf_non_transformed_duplicate_components</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Is there any unused data at the end of the glyf table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-glyf-unused-data">opentype/glyf_unused_data</a></summary>
    <div>







* ✅ **PASS** <p>There is no unused data at the end of the glyf table.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Checking post.italicAngle value. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-italic-angle">opentype/italic_angle</a></summary>
    <div>







* ✅ **PASS** <p>Value of post.italicAngle is 0.0 with style=&quot;Regular&quot;.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Is there a usable "kern" table declared in the font? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-kern-table">opentype/kern_table</a></summary>
    <div>







* ✅ **PASS** <p>Font does not declare an optional &quot;kern&quot; table.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Does the font have any invalid feature tags? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-layout-valid-feature-tags">opentype/layout_valid_feature_tags</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Does the font have any invalid language tags? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-layout-valid-language-tags">opentype/layout_valid_language_tags</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Does the font have any invalid script tags? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-layout-valid-script-tags">opentype/layout_valid_script_tags</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Does the number of glyphs in the loca table match the maxp table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-loca-maxp-num-glyphs">opentype/loca/maxp_num_glyphs</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Checking head.macStyle value. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-mac-style">opentype/mac_style</a></summary>
    <div>







* ✅ **PASS** <p>head macStyle ITALIC bit is properly set.</p>
 



* ✅ **PASS** <p>head macStyle BOLD bit is properly set.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> MaxAdvanceWidth is consistent with values in the Hmtx and Hhea tables? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-maxadvancewidth">opentype/maxadvancewidth</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Checking correctness of monospaced metadata. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-monospace">opentype/monospace</a></summary>
    <div>







* ✅ **PASS** <p>Font is not monospaced and all related metadata look good.</p>
 [code: good]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check name table for empty records. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-name-empty-records">opentype/name/empty_records</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Does full font name begin with the font family name? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-name-match-familyname-fullfont">opentype/name/match_familyname_fullfont</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Name table ID 6 (PostScript name) must be consistent across platforms. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-name-postscript-name-consistency">opentype/name/postscript_name_consistency</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check for points out of bounds. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-points-out-of-bounds">opentype/points_out_of_bounds</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> PostScript name follows OpenType specification requirements? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-postscript-name">opentype/postscript_name</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Font has correct post table version? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-post-table-version">opentype/post_table_version</a></summary>
    <div>







* ✅ **PASS** <p>Font has an acceptable post format 2.0 table version.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Checking unitsPerEm value is reasonable. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-unitsperem">opentype/unitsperem</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check if OS/2 xAvgCharWidth is correct. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-xavgcharwidth">opentype/xavgcharwidth</a></summary>
    <div>







* ✅ **PASS** <p>OS/2 xAvgCharWidth value is correct.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#alt-caron">alt_caron</a></summary>
    <div>







* ✅ **PASS** <p>Looks good!</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check that Arabic spacing symbols U+FBB2–FBC1 aren't classified as marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#arabic-spacing-symbols">arabic_spacing_symbols</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#case-mapping">case_mapping</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Color layers should have a minimum brightness. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#color-cpal-brightness">color_cpal_brightness</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Does font file include unacceptable control character glyphs? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#control-chars">control_chars</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Put an empty glyph on GID 1 right after the .notdef glyph for COLRv0 fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#empty-glyph-on-gid1-for-colrv0">empty_glyph_on_gid1_for_colrv0</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Ensure files are not too large. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#file-size">file_size</a></summary>
    <div>







* ✅ **PASS** <p>Font had a reasonable file size</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Familyname must be unique according to namecheck.fontdata.com <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontdata-namecheck">fontdata_namecheck</a></summary>
    <div>







* ✅ **PASS** <p>Font familyname seems to be unique.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Ensure that the font can be rasterized by FreeType. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#freetype-rasterizer">freetype_rasterizer</a></summary>
    <div>







* ✅ **PASS** <p>Font can be rasterized by FreeType.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Ensure no GPOS7 lookups are present. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#gpos7">gpos7</a></summary>
    <div>







* ✅ **PASS** <p>Font has no GPOS7 lookups</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> PPEM must be an integer on hinted fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#integer-ppem-if-hinted">integer_ppem_if_hinted</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check that legacy accents aren't used in composite glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#legacy-accents">legacy_accents</a></summary>
    <div>







* ✅ **PASS** <p>Looks good!</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#linegaps">linegaps</a></summary>
    <div>







* ✅ **PASS** <p>OS/2 sTypoLineGap and hhea lineGap are both 0.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Font contains '.notdef' as its first glyph? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#mandatory-glyphs">mandatory_glyphs</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ✅ **PASS** <p>Looks good.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Ensure small caps glyphs are available. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#missing-small-caps-glyphs">missing_small_caps_glyphs</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Are there disallowed characters in the NAME table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#name-char-restrictions">name/char_restrictions</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#name-family-and-style-max-length">name/family_and_style_max_length</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Description strings in the name table must not contain copyright info. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#name-no-copyright-on-description">name/no_copyright_on_description</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Ensure glyphs do not have components which are themselves components. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#nested-components">nested_components</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#os2-metrics-match-hhea">os2_metrics_match_hhea</a></summary>
    <div>







* ✅ **PASS** <p>OS/2.sTypoAscender/Descender values match hhea.ascent/descent.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Checking with ots-sanitize. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ots">ots</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ✅ **PASS** <p>No overlapping path segments found.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Font has the proper sfntVersion value? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#sfnt-version">sfnt_version</a></summary>
    <div>







* ✅ **PASS** <p>Font has the correct sfntVersion value.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Ensure smart dropout control is enabled in "prep" table instructions. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#smart-dropout">smart_dropout</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>







* ✅ **PASS** <p>Looks good!</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Ensure Stylistic Sets have description. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#stylisticset-description">stylisticset_description</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Ensure component transforms do not perform scaling or rotation. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#transformed-components">transformed_components</a></summary>
    <div>







* ✅ **PASS** <p>No glyphs had components with scaling or rotation</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Checking with fontTools.ttx <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ttx-roundtrip">ttx_roundtrip</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Font contains unique glyph names? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unique-glyphnames">unique_glyphnames</a></summary>
    <div>







* ✅ **PASS** <p>Glyph names are all unique.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Are there unwanted Apple tables? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unwanted-aat-tables">unwanted_aat_tables</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Are there unwanted tables? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unwanted-tables">unwanted_tables</a></summary>
    <div>







* ✅ **PASS** <p>There are no unwanted tables.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Glyph names are all valid? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#valid-glyphnames">valid_glyphnames</a></summary>
    <div>







* ✅ **PASS** <p>Glyph names are all valid.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Whitespace glyphs have ink? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#whitespace-ink">whitespace_ink</a></summary>
    <div>







* ✅ **PASS** <p>There is no whitespace glyph with ink.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check name ID 25 to end with "Italic" for Italic VFs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-valid-nameid25">googlefonts/metadata/valid_nameid25</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check family name for GF Guide compliance. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-family-name-compliance">googlefonts/family_name_compliance</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Name table entries should not contain line-breaks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-line-breaks">googlefonts/name/line_breaks</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check OFL body text is correct. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-license-OFL-body-text">googlefonts/license/OFL_body_text</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> License URL matches License text on name table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license-url">googlefonts/name/license_url</a></summary>
    <div>







* ✅ **PASS** <p>Font has a valid license URL in NAME table.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Name table strings must not contain the string 'Reserved Font Name'. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-rfn">googlefonts/name/rfn</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> A font repository should not include FontBakery report files <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-repo-fb-report">googlefonts/repo/fb_report</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> A font repository should not include ZIP files <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-repo-zip-files">googlefonts/repo/zip_files</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-alignment-miss">outline_alignment_miss</a></summary>
    <div>







* ✅ **PASS** <p>So many Y-coordinates of points were close to boundaries that this was probably by design.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-direction">outline_direction</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-short-segments">outline_short_segments</a></summary>
    <div>







* ✅ **PASS** <p>So many short segments were found that this was probably by design.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Checking file is named canonically. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-canonical-filename">googlefonts/canonical_filename</a></summary>
    <div>







* ✅ **PASS** <p>Font filename is correct, &quot;Panchanan-Regular.ttf&quot;.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Ensure font has the expected color font tables. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-colorfont-tables">googlefonts/colorfont_tables</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Checking OS/2 fsType does not impose restrictions. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-fstype">googlefonts/fstype</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Description strings in the name table must not exceed 200 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-description-max-length">googlefonts/name/description_max_length</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Make sure family name does not begin with a digit. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-familyname-first-char">googlefonts/name/familyname_first_char</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Font has all mandatory 'name' table entries? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-mandatory-entries">googlefonts/name/mandatory_entries</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Font has old ttfautohint applied? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-old-ttfautohint">googlefonts/old_ttfautohint</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Stricter unitsPerEm criteria for Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-unitsperem">googlefonts/unitsperem</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Is the CFF2 subr/gsubr call depth > 10? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-cff2-call-depth">opentype/cff2_call_depth</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_cff2</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Does the font's CFF table top dict strings fit into the ASCII range? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-cff-ascii-strings">opentype/cff_ascii_strings</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_cff</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Is the CFF subr/gsubr call depth > 10? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-cff-call-depth">opentype/cff_call_depth</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_cff</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Does the font use deprecated CFF operators or operations? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-cff-deprecated-operators">opentype/cff_deprecated_operators</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_cff</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Axes and named instances fall within correct ranges? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-fvar-axis-ranges-correct">opentype/fvar/axis_ranges_correct</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Axes and named instances fall within correct ranges? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-fvar-regular-coords-correct">opentype/fvar/regular_coords_correct</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> CFF table FontName must match name table ID 6 (PostScript name). <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-name-postscript-vs-cff">opentype/name/postscript_vs_cff</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_cff</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Checking direction of slnt axis angles. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-slant-direction">opentype/slant_direction</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Validates that all of the instance records in a given font have distinct data. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-varfont-distinct-instance-records">opentype/varfont/distinct_instance_records</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Validate foundry-defined design-variation axis tag names. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-varfont-foundry-defined-tag-name">opentype/varfont/foundry_defined_tag_name</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Validates that all of the instance records in a given font have the same size. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-varfont-same-size-instance-records">opentype/varfont/same_size_instance_records</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> All fvar axes have a correspondent Axis Record on STAT table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-varfont-STAT-axis-record-for-each-axis">opentype/varfont/STAT_axis_record_for_each_axis</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Validates subfamilyNameID and postScriptNameID for the default instance record <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-varfont-valid-default-instance-nameids">opentype/varfont/valid_default_instance_nameids</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Validates that all of the name IDs in an instance record are within the correct range <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-varfont-valid-nameids">opentype/varfont/valid_nameids</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Checking OS/2 achVendID against configuration. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-vendor-id">opentype/vendor_id</a></summary>
    <div>







* ⏩ **SKIP** <p>Add the <code>vendor_id</code> key to a <code>fontbakery.yaml</code> file on your font project directory to enable this check.
You'll also need to use the <code>--configuration</code> flag when invoking fontbakery.</p>
 



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Checking if OS/2 usWeightClass matches fvar. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-weight-class-fvar">opentype/weight_class_fvar</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font, has_wght_axis</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Each font in set of sibling families must have the same set of vertical metrics values. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#superfamily-vertical-metrics">superfamily/vertical_metrics</a></summary>
    <div>







* ⏩ **SKIP** <p>Sibling families were not detected.</p>
 



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check that glyph for U+0675 ARABIC LETTER HIGH HAMZA is not a mark. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#arabic-high-hamza">arabic_high_hamza</a></summary>
    <div>







* ⏩ **SKIP** <p>This check will only run on fonts that have both glyphs U+0621 and U+0675</p>
 [code: glyphs-missing]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check if uppercase glyphs are vertically centered. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#caps-vertically-centered">caps_vertically_centered</a></summary>
    <div>







* ⏩ **SKIP** <p>The implementation of this check relies on a few samples of uppercase latin characters that are not available in this font.</p>
 [code: lacks-ascii]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Does the font contain chws and vchw features? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#cjk-chws-feature">cjk_chws_feature</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_cjk_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Any CJK font should contain at least a minimal set of 150 CJK characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#cjk-not-enough-glyphs">cjk_not_enough_glyphs</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_claiming_to_be_cjk_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> All name entries referenced by fvar instances exist on the name table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fvar-name-entries">fvar_name_entries</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#interpolation-issues">interpolation_issues</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>







* ⏩ **SKIP** <p>No ligature glyphs found.</p>
 [code: no-ligatures]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#mandatory-avar-table">mandatory_avar_table</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check name table IDs 1, 2, 16, 17 to conform to Italic style. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#name-italic-names">name/italic_names</a></summary>
    <div>







* ⏩ **SKIP** <p>Font is not Italic.</p>
 



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Ensure 'smcp' (small caps) lookups are defined before ligature lookups in the 'GSUB' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#smallcaps-before-ligatures">smallcaps_before_ligatures</a></summary>
    <div>







* ⏩ **SKIP** <p>Font lacks 'smcp' or 'liga' features.</p>
 



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Checking STAT table entries in static fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#STAT-in-statics">STAT_in_statics</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: has_STAT_table</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check correctness of STAT table strings <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#STAT-strings">STAT_strings</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: has_STAT_table</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check tabular widths don't have kerning. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#tabular-kerning">tabular_kerning</a></summary>
    <div>







* ⏩ **SKIP** <p>Font has no numerals at all</p>
 



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#typoascender-exceeds-Agrave">typoascender_exceeds_Agrave</a></summary>
    <div>







* ⏩ **SKIP** <p>Font file lacks the /Agrave, so it can’t be compared with typoAscender</p>
 [code: lacks-Agrave]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> The variable font 'wght' (Weight) axis coordinate must be 700 on the 'Bold' instance. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#varfont-bold-wght-coord">varfont/bold_wght_coord</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font, has_wght_axis</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Ensure VFs with duplexed axes do not vary horizontal advance. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#varfont-duplexed-axis-reflow">varfont/duplexed_axis_reflow</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check variable font instances don't have duplicate names <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#varfont-duplicate-instance-names">varfont/duplicate_instance_names</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Ensure the font's instances are in the correct order. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#varfont-instances-in-order">varfont/instances_in_order</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: has_wght_axis</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Ensure VFs do not contain (yet) the ital axis. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#varfont-unsupported-axes">varfont/unsupported_axes</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Space and non-breaking space have the same width? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#whitespace-widths">whitespace_widths</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: not missing_whitespace_chars</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Validate METADATA.pb axes values are within gf_axisregistry bounds. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-axisregistry-bounds">googlefonts/metadata/axisregistry_bounds</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font, family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Validate METADATA.pb axes tags are defined in gf_axisregistry. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-axisregistry-valid-tags">googlefonts/metadata/axisregistry_valid_tags</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font, family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Does METADATA.pb copyright field contain broken links? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-broken-links">googlefonts/metadata/broken_links</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb: Font styles are named canonically? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-canonical-style-names">googlefonts/metadata/canonical_style_names</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: font_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb: Check that font weight has a canonical value. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-canonical-weight-value">googlefonts/metadata/canonical_weight_value</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: font_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check samples can be rendered. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-can-render-samples">googlefonts/metadata/can_render_samples</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Ensure METADATA.pb category field is valid. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-category">googlefonts/metadata/category</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check if category on METADATA.pb matches what can be inferred from the family name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-category-hints">googlefonts/metadata/category_hints</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Validate VF axes match the ones declared on METADATA.pb. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-consistent-axis-enumeration">googlefonts/metadata/consistent_axis_enumeration</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font, family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb: Check URL on copyright string is the same as in repository_url field. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-consistent-repo-urls">googlefonts/metadata/consistent_repo_urls</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Validate 'date_added' field on METADATA.pb. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-date-added">googlefonts/metadata/date_added</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb: Designers are listed correctly on the Google Fonts catalog? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-designer-profiles">googlefonts/metadata/designer_profiles</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Multiple values in font designer field in METADATA.pb must be separated by commas. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-designer-values">googlefonts/metadata/designer_values</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> At least one designer is declared in METADATA.pb <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-empty-designer">googlefonts/metadata/empty_designer</a></summary>
    <div>







* ⏩ **SKIP** <p>No applicable arguments</p>
 [code: no-arguments]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Ensure METADATA.pb does not use escaped strings. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-escaped-strings">googlefonts/metadata/escaped_strings</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: metadata_file</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check font family directory name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-family-directory-name">googlefonts/metadata/family_directory_name</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check that METADATA.pb family values are all the same. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-familyname">googlefonts/metadata/familyname</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb: Font filenames match font.filename entries? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-filenames">googlefonts/metadata/filenames</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Ensure there is a regular style defined in METADATA.pb. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-has-regular">googlefonts/metadata/has_regular</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check METADATA.pb includes production subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-includes-production-subsets">googlefonts/metadata/includes_production_subsets</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata, listed_on_gfonts_api</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb font.filename and font.post_script_name fields have equivalent values? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-match-filename-postscript">googlefonts/metadata/match_filename_postscript</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: font_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb font.full_name and font.post_script_name fields have equivalent values ? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-match-fullname-postscript">googlefonts/metadata/match_fullname_postscript</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: font_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb: Check font name is the same as family name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-match-name-familyname">googlefonts/metadata/match_name_familyname</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata, font_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb weight matches postScriptName for static fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-match-weight-postscript">googlefonts/metadata/match_weight_postscript</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: font_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb should contain at least "menu" and "latin" subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-menu-and-latin">googlefonts/metadata/menu_and_latin</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb: Validate family.minisite_url field. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-minisite-url">googlefonts/metadata/minisite_url</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb font.name and font.full_name fields match the values declared on the name table? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-nameid-family-and-full-names">googlefonts/metadata/nameid/family_and_full_names</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: font_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb font.name value should be same as the family name declared on the name table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-nameid-font-name">googlefonts/metadata/nameid/font_name</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: font_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Checks METADATA.pb font.post_script_name matches postscript name declared on the name table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-nameid-post-script-name">googlefonts/metadata/nameid/post_script_name</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: font_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check METADATA.pb parse correctly. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-parses">googlefonts/metadata/parses</a></summary>
    <div>







* ⏩ **SKIP** <p>Font family at 'fonts/ttf' lacks a METADATA.pb file.</p>
 [code: file-not-found]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb: Check for primary_script <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-primary-script">googlefonts/metadata/primary_script</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb: Regular should be 400. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-regular-is-400">googlefonts/metadata/regular_is_400</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata, has_regular_style</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check METADATA.pb file only contains a single CJK subset. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-single-cjk-subset">googlefonts/metadata/single_cjk_subset</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb subsets should be alphabetically ordered. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-subsets-order">googlefonts/metadata/subsets_order</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Ensure METADATA.pb lists all font binaries. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-undeclared-fonts">googlefonts/metadata/undeclared_fonts</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb: check if fonts field only has unique "full_name" values. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unique-full-name-values">googlefonts/metadata/unique_full_name_values</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb: check if fonts field only contains unique style:weight pairs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unique-weight-style-pairs">googlefonts/metadata/unique_weight_style_pairs</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check for METADATA subsets with zero support. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unsupported-subsets">googlefonts/metadata/unsupported_subsets</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb font.filename field contains font name in right format? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-valid-filename-values">googlefonts/metadata/valid_filename_values</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb font.full_name field contains font name in right format? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-valid-full-name-values">googlefonts/metadata/valid_full_name_values</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: font_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb font.post_script_name field contains font name in right format? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-valid-post-script-name-values">googlefonts/metadata/valid_post_script_name_values</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: font_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check METADATA.pb font weights are correct. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-weightclass">googlefonts/metadata/weightclass</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: font_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Does DESCRIPTION file contain broken links? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-description-broken-links">googlefonts/description/broken_links</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: description_and_article_html</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> DESCRIPTION.en_us.html should end in a linebreak. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-description-eof-linebreak">googlefonts/description/eof_linebreak</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: description</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> On a family update, the DESCRIPTION.en_us.html file should ideally also be updated. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-description-family-update">googlefonts/description/family_update</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: description</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Does DESCRIPTION file contain a upstream Git repo URL? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-description-git-url">googlefonts/description/git_url</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: description_html</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check the description doesn't contain unsupported html elements <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-description-has-unsupported-elements">googlefonts/description/has_unsupported_elements</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: description_and_article</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> DESCRIPTION.en_us.html must have more than 200 bytes. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-description-min-length">googlefonts/description/min_length</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: description</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> URLs on DESCRIPTION file must not display http(s) prefix. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-description-urls">googlefonts/description/urls</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: description_and_article_html</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Is this a proper HTML snippet? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-description-valid-html">googlefonts/description/valid_html</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: description_and_article</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check font has a license. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-family-has-license">googlefonts/family/has_license</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: gfonts_repo_structure</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb: Copyright notice is the same in all fonts? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-copyright">googlefonts/metadata/copyright</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> METADATA.pb license is "APACHE2", "UFL" or "OFL"? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-license">googlefonts/metadata/license</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: family_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Copyright notice on METADATA.pb should not contain 'Reserved Font Name'. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-reserved-font-name">googlefonts/metadata/reserved_font_name</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: font_metadata</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check upstream.yaml file contains all required fields <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-repo-upstream-yaml-has-required-fields">googlefonts/repo/upstream_yaml_has_required_fields</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: upstream_yaml</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> A static fonts directory, if present, must contain manually hinted fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-repo-vf-has-static-fonts">googlefonts/repo/vf_has_static_fonts</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: gfonts_repo_structure</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check that no collisions are found while shaping <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#shaping-collides">shaping/collides</a></summary>
    <div>







* ⏩ **SKIP** <p>Shaping test directory not defined in configuration file</p>
 



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check that no forbidden glyphs are found while shaping <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#shaping-forbidden">shaping/forbidden</a></summary>
    <div>







* ⏩ **SKIP** <p>Shaping test directory not defined in configuration file</p>
 



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check that texts shape as per expectation <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#shaping-regression">shaping/regression</a></summary>
    <div>







* ⏩ **SKIP** <p>Shaping test directory not defined in configuration file</p>
 



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⏩ **SKIP** <p>Font has no soft dotted characters or no mark above characters.</p>
 



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check if the axes match between the font and the Google Fonts version. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-axes-match">googlefonts/axes_match</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font, remote_style</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Validate defaults on fvar table match registered fallback names in GFAxisRegistry. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-axisregistry-fvar-axis-defaults">googlefonts/axisregistry/fvar_axis_defaults</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check font follows the Google Fonts CJK vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-cjk-vertical-metrics">googlefonts/cjk_vertical_metrics</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_cjk_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check if the vertical metrics of a CJK family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-cjk-vertical-metrics-regressions">googlefonts/cjk_vertical_metrics_regressions</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_cjk_font, regular_remote_style</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check variable font instances <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-fvar-instances">googlefonts/fvar_instances</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Font has ttfautohint params? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-has-ttfautohint-params">googlefonts/has_ttfautohint_params</a></summary>
    <div>







* ⏩ **SKIP** <p>Font appears to our heuristic as not hinted using ttfautohint.</p>
 [code: not-hinted]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Validate STAT particle names and values match the fallback names in GFAxisRegistry. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-STAT-axisregistry">googlefonts/STAT/axisregistry</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check a static ttf can be generated from a variable font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-varfont-generate-static">googlefonts/varfont/generate_static</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check that variable fonts have an HVAR table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-varfont-has-HVAR">googlefonts/varfont/has_HVAR</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: is_variable_font</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics-regressions">googlefonts/vertical_metrics_regressions</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: regular_remote_style</p>
 [code: unfulfilled-conditions]



</div>
</details>
</div>
</details>

<details><summary>[17] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-use-typo-metrics">googlefonts/use_typo_metrics</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Panchanan-Regular.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Check axis ordering on the STAT table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-STAT-axis-order">googlefonts/STAT/axis_order</a></summary>
    <div>







* ℹ️ **INFO** <p>All of the fonts lack a STAT table.</p>
 [code: summary]



* ⏩ **SKIP** <p>This font does not have a STAT table: Font(file='fonts/ttf/Panchanan-Regular.ttf', context=CheckRunContext(testables=[...], config={'file_size': {'WARN_SIZE': 1048576, 'FAIL_SIZE': 9437184}, 'custom_order': None, 'explicit_checks': None, 'exclude_checks': None, 'full_lists': True, 'skip_network': False}, is_multithreaded=True))</p>
 [code: missing-STAT]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Check that OS/2.fsSelection bold & italic settings are unique for each NameID1 <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-family-bold-italic-unique-for-nameid1">opentype/family/bold_italic_unique_for_nameid1</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Verify that family names in the name table are consistent across all fonts in the family. Checks Typographic Family name (nameID 16) if present, otherwise uses Font Family name (nameID 1) <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-family-consistent-family-name">opentype/family/consistent_family_name</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Make sure all font files have the same version value. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-family-equal-font-versions">opentype/family/equal_font_versions</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Verify that each group of fonts with the same nameID 1 has maximum of 4 fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-family-max-4-fonts-per-family-name">opentype/family/max_4_fonts_per_family_name</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Fonts have consistent PANOSE family type? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-family-panose-familytype">opentype/family/panose_familytype</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Fonts have consistent underline thickness? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-family-underline-thickness">opentype/family/underline_thickness</a></summary>
    <div>







* ✅ **PASS** <p>Fonts have consistent underline thickness.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Ensure VFs have 'ital' STAT axis. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-STAT-ital-axis">opentype/STAT/ital_axis</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Checking all files are in the same directory. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-single-directory">family/single_directory</a></summary>
    <div>







* ✅ **PASS** <p>All files are in the same directory.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Each font in a family must have the same set of vertical metrics values. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-vertical-metrics">family/vertical_metrics</a></summary>
    <div>







* ✅ **PASS** <p>Vertical metrics are the same across the family.</p>
 



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Fonts have equal codepoint coverage <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-family-equal-codepoint-coverage">googlefonts/family/equal_codepoint_coverage</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> Ensure Italic styles have Roman counterparts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-family-italics-have-roman-counterparts">googlefonts/family/italics_have_roman_counterparts</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>✅ <b>PASS</b> All tabular figures must have the same width across the RIBBI-family. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-family-tnum-horizontal-metrics">googlefonts/family/tnum_horizontal_metrics</a></summary>
    <div>







* ✅ **PASS** <p>All looks good!</p>
 [code: ok]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Check that family axis ranges are indentical <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-varfont-family-axis-ranges">opentype/varfont/family_axis_ranges</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: VFs</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Ensure that all variable font files have the same set of axes and axis ranges. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#varfont-consistent-axes">varfont/consistent_axes</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: VFs</p>
 [code: unfulfilled-conditions]



</div>
</details>

<details>
    <summary>⏩ <b>SKIP</b> Directory name in GFonts repo structure must match NameID 1 of the regular. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-repo-dirname-matches-nameid-1">googlefonts/repo/dirname_matches_nameid_1</a></summary>
    <div>







* ⏩ **SKIP** <p>Unfulfilled Conditions: gfonts_repo_structure</p>
 [code: unfulfilled-conditions]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 15 | 10 | 110 | 6 | 95 | 0 | 
| 0% | 0% | 6% | 4% | 47% | 3% | 40% | 0% | 



**Note:** The following loglevels were omitted in this report:


* DEBUG
