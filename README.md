# [<img src="favicon.ico" width="25px" />](https://materialpalettes.com) &nbsp;[Material Design Palette Generator](https://materialpalettes.com)

<img src="/images/screenshot.png" />

## What is this?

This is a (slightly modified) clone of the [official Material Design palette generator](https://material.io/design/color/the-color-system.html#tools-for-picking-colors). It does a couple things:

1. Builds you a full color palette from a given hex color, based on Material Design standards, using Google's algorithm for color derivation
2. Provides you with complementary colors based off your primary color

## Why is this?

Google's official palette generator [is embedded and buried deep within the Material docs](https://material.io/design/color/the-color-system.html#tools-for-picking-colors). Since it's an inline tool, it's also hidden from search engines, making it difficult to discover or bookmark.

To make it a little easier to access and to preserve it for my own future use, I grabbed the obfuscated code (the original scripts do not appear to be public anywhere) and added some small interface improvements. I did _not_ change the way colors are derived.

The color output matches that produced in the [Material Theme Editor for Sketch](https://material.io/tools/theme-editor/), so it's a good companion for that.

## Credits

- Most of this is copyright Google Inc. If you do anything with their code, please maintain the licenses they indicate at the top of the large files.
- You can use any of our modifications without credit, except...
- Favicon image courtesy of [Roundicons](https://roundicons.com/) and pulled from [flaticon.com](https://flaticon.com). If you reuse it, please continue to credit the creator.

## Tech

It's just HTML, CSS, and JavaScript. Run it locally on your favorite server.
