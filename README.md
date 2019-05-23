
# obclone
[![NPM](https://nodei.co/npm/unifont.png)](https://www.npmjs.org/package/unifont)

[![npm version](https://img.shields.io/npm/v/unifont.svg?style=flat-square)](https://www.npmjs.org/package/unifont)
[![Build Status](https://travis-ci.org/nepsho/unifont.svg?branch=master)](https://travis-ci.org/nepsho/unifont)
[![npm license](https://img.shields.io/static/v1.svg?label=License&message=MIT&color=informational)](https://github.com/nepsho/unifont/blob/master/LICENSE)
[![npm repository](https://img.shields.io/static/v1.svg?label=Repository&message=GitHub&color=yellow)](https://github.com/nepsho/unifont)
[![npm author](https://img.shields.io/static/v1.svg?label=Author&message=bcrazydreamer&color=success)](https://www.npmjs.com/~bcrazydreamer)

>**unifont:** NodeJs fonts api that support multiple fonts styles in NodeJs
## Features
- Multiple CMD fonts.
- Can also use these fonts for other purpose also.

## Support
>All node versions

## Installing
[![NPM](https://nodei.co/npm/unifont.png?mini=true)](https://www.npmjs.org/package/unifont)

**Using npm:**
```bash
$ npm install unifont
```

**Using bower:**

```bash
$ bower install unifont
```

**Using yarn:**

```bash
$ yarn add unifont
```

## UniFont
```
 font([text],[option]);
```
> Where as
>  **[text]** should be *string*.
> **[option]** can be *Object* and *String* only or ever *null* or *undefined*.

## Option
Option can be null/undefined in case null/undefined it will not change any thing. It can be string but when its a sting then it must be a font name.
In case of string it will consider that as font and create **option.font** (Where option will be object)

## option.font
option.font = normalEn | BorderBlock | DotBlock | GaintBold | Btalic | GaintItalic | Alphol | Bubble | BubbleFill | Cursive
You can use any one one font named above.

## Available Fonts (option.font)
> **normalEn:** Simple alphabets.
>```Its a example```
>
> **SolidBlock:**
>```🅸🆃🆂  🅰  🅴🆇🅰🅼🅿🅻🅴```
>  
> **BorderBlock:**
>```🄸🅃🅂	🄰  🄴🅇🄰🄼🄿🄻🄴```
>
> **DotBlock:**
>```🇮 🇹 🇸​  🇦  ​🇪 🇽​ 🇦 ​🇲 ​🇵 ​🇱 ​🇪 ```
>
> **GaintBold:**
>```𝗜𝘁𝘀  𝗮  𝗲𝘅𝗮𝗺𝗽𝗹𝗲```
>
> **Btalic:**
>```𝙄𝙩𝙨 𝙖 𝙚𝙭𝙖𝙢𝙥𝙡𝙚```
>
> **GaintItalic:**
>```𝘐𝘵𝘴 𝘢 𝘦𝘹𝘢𝘮𝘱𝘭𝘦```
>
>**Alphol:**
>```𝕀𝕥𝕤 𝕒 𝕖𝕩𝕒𝕞𝕡𝕝𝕖```
>
>**Bubble:**
>```Ⓘⓣⓢ ⓐ ⓔⓧⓐⓜⓟⓛⓔ```
>
> **BubbleFill:**
>```🅘🅣🅢  🅐  🅔🅧🅐🅜🅟🅛🅔```
>
> **Cursive:**
>```𝐼𝓉𝓈 𝒶 𝑒𝓍𝒶𝓂𝓅𝓁𝑒```

## Available Style (option.style)
>**Bold:**
>**Its a example**
>
>**Italic:**
>*Its a example*
>
>**Underline:**
> ͟I͟t͟s͟ ͟a͟ ͟e͟x͟a͟m͟p͟l͟e͟
>
>**upr:**
>(its used to convert letters in lowercase with font)
>its a example
>
>**lwr:**
>(its used to convert letters in uppercase with font)
>ITS A EXAMPLE
>
>**cap**
>(its used to capitalize first letter with font)
>Its a example

## Examples

```js
>>const font = require("unifont");
```
```js
>> var option = {
... 	font : "Bubble",
... 	style : ""
... }
>>var text = font("Its a example",option);
>>console.log(text)
>>🅘🅣🅢  🅐  🅔🅧🅐🅜🅟🅛🅔
```
## licence
MIT [licence](https://opensource.org/licenses/MIT)

## Author
@BCrazyDreamer
