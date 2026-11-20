# CIS localization notes

This file keeps terminology consistent across the Russian, Ukrainian, Belarusian, Azerbaijani, Armenian, Kazakh, Kyrgyz, Uzbek, Tajik, Turkmen and Romanian/Moldovan phone resources.

## Translation baseline

Use the Russian MeeTube translation as the semantic reference for the CIS resource set. Do not translate it word for word: each target language should use its natural UI wording and grammar. Keep labels short enough for phone controls and settings rows.

## Product and feature names

Keep these names unchanged:

- MeeTube, MeeTune, YouTube, YouTube Music
- Spotify, SponsorBlock, DeArrow, Return YouTube Dislike
- Canvas, Conscrypt and YkAI

Keep technical acronyms such as DNS, SSL, TLS, VPN, Wi-Fi, HDR, 4K and PiP as acronyms where they are normally used in the target language.

## Russian reference terms

| English concept | Russian reference |
|---|---|
| Playlist | Плейлист |
| Playback | Воспроизведение |
| Audio track | Аудиодорожка |
| Subtitles / captions | Субтитры |
| Background playback | Фоновое воспроизведение |
| Picture-in-picture | Картинка в картинке |
| Transcript | Транскрипт |
| Lyrics | Текст песни |
| Download (offline copy) | Скачать / загрузить, according to context |
| Save to playlist | Сохранить в плейлист |
| Cast | Трансляция |
| Watch later | Смотреть позже |
| Audio quality | Настройки звука |
| Search history | История поиска |
| Watch history | История просмотров |

Use this table as a meaning reference. Translate the terms naturally in the target language; do not force Russian loanwords where a standard local term is clearer.

## Region-specific network wording

The terms `ByeByeDPI`, censorship, throttling, blocked access and bypass should only appear in a locale when that restriction is relevant to users of that locale.

At present, these terms belong only in the Russian settings-search aliases in `values-ru/strings_settings_search.xml`. Other CIS locales should keep network search terms neutral: DNS, SSL/TLS, certificates, internet and connection. Do not copy the Russian restriction-related aliases into every language.

## Android resource rules

- Preserve every resource name exactly.
- Preserve format placeholders such as `%1$s`, `%2$d` and escaped newlines.
- Translate every plural quantity required by the language. Do not copy Russian plural forms into languages with different plural rules.
- Keep `translatable="false"` values unchanged.
- Do not introduce new terminology in a feature-specific screen that conflicts with the Russian reference without a clear language-specific reason.
