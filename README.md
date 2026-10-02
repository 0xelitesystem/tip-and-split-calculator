# Tip and Split Calculator

> Set a tip, split the check, or round each share up to a clean total.

**Live demo:** https://0xelitesystem.github.io/tip-and-split-calculator/

Single HTML file. Runs in the browser with no build step, no server, no tracking, and no data leaving the page.

## What it does

- Splits a bill across any number of people with quick tip presets or a custom percent
- Optionally rounds each person up to the nearest dollar amount you choose
- Shows the extra collected over the bill when rounding is on
- Updates live as you type, no submit button

## What it is not

- Not a payments tool. It does not move money or connect to any account
- Not a receipt scanner. You enter the bill total yourself

## Use

Open the hosted page: https://0xelitesystem.github.io/tip-and-split-calculator/

Or download `index.html` and open it in any browser. It works offline.

1. Enter the bill amount.
2. Pick a tip preset (15, 18, 20 or 25 percent) or type a tip percent.
3. Set how many people to split between.
4. Optionally tick "Round each person up to the nearest" and set the dollar amount. Results update as you type.

## Why this exists

Splitting a check with tip in your head goes wrong at the table, and most calculator sites come wrapped in ads and trackers. This does the math locally. It is one HTML file with no tracking and no network calls, released under MIT.

## Privacy

Everything runs client-side. No analytics, no cookies, no network calls, no local storage.

One exception to "no local storage": your light or dark theme choice is saved in localStorage under the key `theme`. Nothing you type is stored.

## Run locally

```
git clone https://github.com/0xelitesystem/tip-and-split-calculator
cd tip-and-split-calculator
```

Open `index.html` in any browser. Or serve the folder and visit http://localhost:8000:

```
python -m http.server 8000
```

## Build

No build step. The whole tool is one `index.html` file with inline CSS and JavaScript.

## Related

- [invoice-total-builder](https://github.com/0xelitesystem/invoice-total-builder)
- [savings-goal-planner](https://github.com/0xelitesystem/savings-goal-planner)

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## Third-party notices

The page embeds subsets of the fonts below as base64 data inside `index.html`. Each font is used under its own license, not under the MIT License of this repository. Copyright lines are copied verbatim from each font's upstream license file.

- **Anton**, https://github.com/google/fonts/tree/main/ofl/anton. Copyright 2020 The Anton Project Authors (https://github.com/googlefonts/AntonFont.git). License: SIL Open Font License, Version 1.1. Taken: a subset of the font, embedded in `index.html`.
- **Courier Prime**, https://github.com/google/fonts/tree/main/ofl/courierprime. Copyright 2015 The Courier Prime Project Authors (https://github.com/quoteunquoteapps/CourierPrime). License: SIL Open Font License, Version 1.1. Taken: a subset of the font, embedded in `index.html`.

### SIL Open Font License, Version 1.1

```text
This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at:
http://scripts.sil.org/OFL


-----------------------------------------------------------
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007
-----------------------------------------------------------

PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide
development of collaborative font projects, to support the font creation
efforts of academic and linguistic communities, and to provide a free and
open framework in which fonts may be shared and improved in partnership
with others.

The OFL allows the licensed fonts to be used, studied, modified and
redistributed freely as long as they are not sold by themselves. The
fonts, including any derivative works, can be bundled, embedded, 
redistributed and/or sold with any software provided that any reserved
names are not used by derivative works. The fonts and derivatives,
however, cannot be released under any other type of license. The
requirement for fonts to remain under this license does not apply
to any document created using the fonts or their derivatives.

DEFINITIONS
"Font Software" refers to the set of files released by the Copyright
Holder(s) under this license and clearly marked as such. This may
include source files, build scripts and documentation.

"Reserved Font Name" refers to any names specified as such after the
copyright statement(s).

"Original Version" refers to the collection of Font Software components as
distributed by the Copyright Holder(s).

"Modified Version" refers to any derivative made by adding to, deleting,
or substituting -- in part or in whole -- any of the components of the
Original Version, by changing formats or by porting the Font Software to a
new environment.

"Author" refers to any designer, engineer, programmer, technical
writer or other person who contributed to the Font Software.

PERMISSION & CONDITIONS
Permission is hereby granted, free of charge, to any person obtaining
a copy of the Font Software, to use, study, copy, merge, embed, modify,
redistribute, and sell modified and unmodified copies of the Font
Software, subject to the following conditions:

1) Neither the Font Software nor any of its individual components,
in Original or Modified Versions, may be sold by itself.

2) Original or Modified Versions of the Font Software may be bundled,
redistributed and/or sold with any software, provided that each copy
contains the above copyright notice and this license. These can be
included either as stand-alone text files, human-readable headers or
in the appropriate machine-readable metadata fields within text or
binary files as long as those fields can be easily viewed by the user.

3) No Modified Version of the Font Software may use the Reserved Font
Name(s) unless explicit written permission is granted by the corresponding
Copyright Holder. This restriction only applies to the primary font name as
presented to the users.

4) The name(s) of the Copyright Holder(s) or the Author(s) of the Font
Software shall not be used to promote, endorse or advertise any
Modified Version, except to acknowledge the contribution(s) of the
Copyright Holder(s) and the Author(s) or with their explicit written
permission.

5) The Font Software, modified or unmodified, in part or in whole,
must be distributed entirely under this license, and must not be
distributed under any other license. The requirement for fonts to
remain under this license does not apply to any document created
using the Font Software.

TERMINATION
This license becomes null and void if any of the above conditions are
not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
OF COPYRIGHT, PATENT, TRADEMARK, OR OTHER RIGHT. IN NO EVENT SHALL THE
COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
INCLUDING ANY GENERAL, SPECIAL, INDIRECT, INCIDENTAL, OR CONSEQUENTIAL
DAMAGES, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM
OTHER DEALINGS IN THE FONT SOFTWARE.
```

## License

MIT, copyright 0xelitesystem 2026.
