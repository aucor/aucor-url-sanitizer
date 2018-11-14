# Aucor URL Sanitizer

**Contributors:** [Teemu Suoranta](https://github.com/TeemuSuoranta)

**Tags:** wordpress, i18n, slug, sanitize

**License:** GPLv2 or later

## Description

Converts Cyrillic, Georgian, Arabic and Chinese characters in post, term slugs and media file names to Latin characters.

This plugins uses parts from following plugins:
* [Arabic-to-latino](https://wordpress.org/plugins/arabic-to-lat/)
* [Cyr to Lat enhanced](https://wordpress.org/plugins/cyr3lat/)
* [Pinyin Slugs](https://wordpress.org/plugins/so-pinyin-slugs/)

## The problem

WordPress cannot sanitize all languages correctly which leaves pretty permalink with bare post ID. There are a few separate plugins to handle sanitazing but they won't generally play along nicley and end up often removing parts from other languages.

## The solution

This plugins combines the few working slug sanitazing plugins so that they will work together.

If you need only one of above plugins, you can (and probably should) use them instead of this. If you are in need of multiple of these plugins, this is the conflict-free combination for you.

## What this plugin sanitizes?

* Post slug
* Term slug
* Filename

These are sanitized with WordPress's filter and done in post save etc.

**Notice:** There is no bulk sanitizing option right now. If you are in need of it, some of the plugins above have their own solutions so adding the feature here wouldn't be such a big hassle. Send a PR!

## What about language X?

Send PR to add other languages to the mix.

## Changelog

### 2.0

 * Github release
