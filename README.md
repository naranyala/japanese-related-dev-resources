# Awesome Japanese Developer Resources 🇯🇵

A curated list of awesome Japanese-related developer resources, libraries, APIs, datasets, open data, and communities.

## Contents
- [Natural Language Processing](#natural-language-processing)
- [Character Processing](#character-processing)
- [Geography, Maps & Addresses](#geography-maps--addresses)
- [Dates & Holidays](#dates--holidays)
- [Dictionaries & Datasets](#dictionaries--datasets)
- [Fonts](#fonts)
- [APIs](#apis)
- [Machine Learning & AI](#machine-learning--ai)
- [Data Analysis & Finance](#data-analysis--finance)
- [E-Commerce & Payments](#e-commerce--payments)
- [Social & Messaging Integrations](#social--messaging-integrations)
- [Cloud & Infrastructure](#cloud--infrastructure)
- [Anime & Manga APIs](#anime--manga-apis)
- [Audio, Speech & Input Methods](#audio-speech--input-methods)
- [Open Data & GeoJSON](#open-data--geojson)
- [CLI & GUI Tools](#cli--gui-tools)
- [Videos & Conferences](#videos--conferences)
- [Forums & Communities](#forums--communities)
- [Articles, Blogs & Platforms](#articles-blogs--platforms)
- [Related Awesome Lists](#related-awesome-lists)

## Natural Language Processing
Libraries for tokenization, morphological analysis, and POS tagging.

*   **Java**
    *   [Kuromoji](https://www.atilika.com/en/kuromoji/) - Open source Japanese morphological analyzer.
    *   [Sudachi](https://github.com/WorksApplications/Sudachi) - A Japanese morphological analyzer.
*   **Python**
    *   [Fugashi](https://github.com/polm/fugashi) - A Cython wrapper for MeCab, widely used in Python.
    *   [Janome](https://mocobeta.github.io/janome/) - Japanese morphological analysis engine written in pure Python.
    *   [spaCy Japanese](https://spacy.io/models/ja) - Japanese models for spaCy (using Sudachi/MeCab under the hood).
    *   [Ginza](https://github.com/megagonlabs/ginza) - Japanese NLP Library based on spaCy and SudachiPy.
*   **C/C++**
    *   [MeCab](https://taku910.github.io/mecab/) - Yet Another Part-of-Speech and Morphological Analyzer.

## Character Processing
Tools for converting between Kanji, Hiragana, Katakana, and Romaji.

*   **JavaScript / TypeScript**
    *   [WanaKana](https://wanakana.com/) - Utility library for checking and converting between Kanji, Hiragana, Katakana, and Romaji.
    *   [Kuroshiro](https://github.com/hexenq/kuroshiro) - Converts Japanese sentences to Hiragana, Katakana or Romaji with furigana support.
*   **Python**
    *   [Cutlet](https://github.com/polm/cutlet) - A Japanese to Romaji converter.
    *   [pykakasi](https://github.com/miurahr/pykakasi) - Python implementation of Kakasi (Kanji Kana Simple Inverter).
*   **Ruby**
    *   [Moji](https://github.com/gimite/moji) - Ruby library for processing Japanese characters.
*   **C**
    *   [Kakasi](http://kakasi.namazu.org/) - Kanji Kana Simple Inverter.

## Geography, Maps & Addresses
APIs and tools related to Japanese addresses, postal codes, and maps.

### Address Parsing & Geocoding
*   **Rust** - [japanese-address-parser](https://github.com/YuukiToriyama/japanese-address-parser) - Robust library to handle various Japanese address notations (also has Python/Wasm bindings).
*   **Node.js** - [jp-address-parser](https://github.com/pasear/jp-address-parser) - Parses Japanese addresses by matching input against prebuilt city data.
*   **Ruby** - [japanese_address_parser](https://github.com/yamat47/japanese_address_parser) - Ruby gem for parsing Japanese addresses.
*   **Python** - [jageocoder](https://github.com/t-sagara/jageocoder) - Provides geocoding and reverse-geocoding functionality for Japanese addresses.

### General Maps & APIs
*   [HeartRails Geo API](http://geoapi.heartrails.com/) - Free API for geographical data in Japan (prefectures, cities, postal codes, stations).
*   [YubinBango](https://github.com/yubinbango/yubinbango) - JavaScript library to automatically fill in addresses from Japanese postal codes.
*   [RESAS API](https://opendata.resas-portal.go.jp/) - Regional Economy Society Analyzing System API provided by the Japanese government.
*   [zipcloud](https://zipcloud.ibsnet.co.jp/doc/api) - Free Japanese postal code search API.
*   [Japan GSI Maps](https://maps.gsi.go.jp/development/) - Geospatial Information Authority of Japan mapping APIs and tiles.

## Dates & Holidays
Working with Japanese eras (Gengo) and national holidays.

*   **Python** - [python-shukujitsu](https://github.com/sakurai-youhei/python-shukujitsu) - Dict-like interface to check for Japanese holidays.
*   **Node.js** - [japanese-holidays](https://github.com/KushibikiMashu/japanese-holidays) - Library to determine Japanese national holidays.
*   **Ruby** - [koyomi](https://github.com/yui-knk/koyomi) - Ruby gem for Japanese calendar and holidays.
*   **Swift** - [JapaneseHoliday](https://github.com/417-72KI/JapaneseHoliday) - Library designed for calculating Japanese holidays using Swift.
*   **Java / Kotlin** - [holiday_jp-java](https://github.com/holiday-jp/holiday_jp-java) - Java library for checking holidays.
*   **Rust** - [holidays_jp](https://github.com/nabetama/holidays_jp) - Library and CLI tool for checking holidays.
*   **Other** - The [holiday-jp](https://github.com/holiday-jp) GitHub organization maintains repositories for Go, PHP, Elixir, etc.

## Dictionaries & Datasets
*   [JMdict / EDICT](http://www.edrdg.org/jmdict/edict.html) - Extensive Japanese-English dictionary project.
*   [KANJIDIC](http://www.edrdg.org/kanjidic/kanjd2index.html) - Comprehensive database of Kanji information.
*   [JMDict-Simplified](https://github.com/scriptin/jmdict-simplified) - Simplified JSON version of JMdict.
*   [Tatoeba](https://tatoeba.org/en/) - A large database of example sentences with translations.
*   [Wikipedia Japanese Dumps](https://dumps.wikimedia.org/jawiki/) - Useful corpus for training NLP models.

## Fonts
High-quality open-source Japanese typography.

*   [Google Noto Fonts (Japanese)](https://fonts.google.com/noto/specimen/Noto+Sans+JP) - Noto Sans JP and Noto Serif JP.
*   [M PLUS Fonts](https://mplusfonts.github.io/) - Popular open-source Japanese font family.
*   [BIZ UDGothic](https://fonts.google.com/specimen/BIZ+UDGothic) - Universal Design font ideal for readability.

## APIs
*   [Ekispert Web Services](https://roote.ekispert.net/info/api/) - Comprehensive Japanese transit routing and station API.
*   [Yahoo! Japan Developer Network](https://developer.yahoo.co.jp/) - APIs for text analysis, maps, shopping, etc.
*   [Jisho API](https://jisho.org/forum/54fefc1f6e73340b1f160000-is-there-any-kind-of-api) - Unofficial API to search the popular Jisho.org dictionary.

## Machine Learning & AI
Frameworks, models, and curated lists specific to Japanese AI research.

*   [rinna Co., Ltd. (rinnakk)](https://github.com/rinnakk) - Prominent Japanese AI company releasing powerful Japanese LLMs (e.g., japanese-gpt-neox). Models are primarily hosted on [Hugging Face](https://huggingface.co/rinna).
*   [CuPy](https://github.com/cupy/cupy) - High-performance NumPy/SciPy-compatible array library for GPU computing, originally developed by Preferred Networks (PFN).
*   [awesome-japanese-llm](https://github.com/llm-jp/awesome-japanese-llm) - A comprehensive, curated list of Japanese Large Language Models (LLMs), datasets, and evaluation tools.

## Data Analysis & Finance
Tools for quantitative analysis, financial data, and official government statistics.

*   [e-Stat API](https://www.e-stat.go.jp/en/api) - The official portal and API for Japanese government statistics (population, labor, economy).
*   [J-Quants API](https://github.com/J-Quants/jquants-api-client-python) - Financial market data provided by the Japan Exchange Group (JPX) for algorithmic trading and analysis.
*   [kabukit](https://github.com/daizutabi/kabukit) - A high-performance toolkit that simplifies data access for both J-Quants and EDINET (financial disclosure) APIs.

## E-Commerce & Payments
Gateways and APIs for processing transactions in the Japanese market.

*   [KOMOJU](https://komoju.com/) - A comprehensive payment gateway tailored for Japan, offering a unified API for credit cards, Konbini (convenience store) payments, and digital wallets.
*   [PayPay API](https://developer.paypay.ne.jp/) - Developer portal for integrating PayPay, Japan's leading QR code and digital wallet payment system.
*   [Paidy](https://paidy.com/en/developer/) - The leading "Buy Now, Pay Later" (BNPL) service in Japan, allowing users to pay with just an email and phone number.

## Social & Messaging Integrations
APIs and tools for integrating with Japan's dominant communication platforms.

*   [LINE Messaging API](https://developers.line.biz/en/docs/messaging-api/) - Essential API for building LINE bots and sending messages to users. A must-have for B2C apps in Japan.
*   [LIFF (LINE Front-end Framework)](https://developers.line.biz/en/docs/liff/overview/) - A platform for running web apps inside the LINE app, seamlessly linking user profiles.
*   [create-liff-app](https://github.com/line/create-liff-app) - Official CLI tool to quickly bootstrap new LIFF projects using React, Vue, Next.js, or plain TypeScript.

## Cloud & Infrastructure
Domestic cloud providers highly popular among Japanese developers and enterprises.

*   [Sakura Cloud](https://cloud.sakura.ad.jp/) - Enterprise-grade IaaS platform by SAKURA internet. Highly stable, with strong Terraform support and Japanese data centers.
*   [ConoHa VPS](https://www.conoha.jp/vps/) - Developer-friendly, cost-effective VPS hosting. Known for fast deployment, hourly billing, and an OpenStack-compatible API.

## Anime & Manga APIs
Open-source APIs and wrappers for interacting with extensive anime and manga databases.

*   [Jikan API](https://jikan.moe/) - The most popular open-source, unofficial REST API for MyAnimeList. Has wrappers in almost every programming language.
*   [AniList API](https://anilist.co/) - Official GraphQL-based API for anime, manga, and character data. Highly flexible and robust.
*   [MangaDex API](https://mangadex.org/) - Official REST API for the most comprehensive manga/scanlation database.

## Audio, Speech & Input Methods
Open-source Text-to-Speech (TTS), Automatic Speech Recognition (ASR), and Input Method Editors.

*   **Speech Recognition (ASR)**
    *   [ReazonSpeech](https://github.com/reazon-research/ReazonSpeech) - A massive open-source corpus of Japanese speech and highly accurate ASR models.
    *   [ESPnet](https://github.com/espnet/espnet) - End-to-end speech processing toolkit (ASR, TTS, translation) heavily driven by Japanese researchers.
    *   [Julius](https://github.com/julius-speech/julius) - High-performance, small-footprint Japanese speech recognition engine.
*   **Text-to-Speech (TTS)**
    *   [VOICEVOX](https://github.com/VOICEVOX/voicevox) - High-quality, deep-learning based Japanese TTS engine that is free to use.
    *   [OpenJTalk](https://github.com/r9y9/pyopenjtalk) - Classic, lightweight HMM-based Japanese speech synthesis engine (link is to the popular Python wrapper).
*   **Input Methods (IME)**
    *   [Mozc](https://github.com/google/mozc) - The open-source foundation of Google Japanese Input. Widely used on Linux (with Fcitx/IBus) and other platforms.

## Open Data & GeoJSON
Official government data portals, and openly available spatial/geographical datasets.

### Government Portals & Repositories
*   [DATA.GO.JP](https://www.data.go.jp/) - The central, official portal for Japanese government open data (catalog of datasets across ministries).
*   [Digital Agency GitHub (digital-go-jp)](https://github.com/digital-go-jp) - The official GitHub organization for Japan's Digital Agency.
*   [code4fukui/localgovjp](https://github.com/code4fukui/localgovjp) - A highly useful, community-maintained list of all local governments in Japan in machine-readable JSON/CSV formats.

### Geographical Data (GeoJSON)
*   [dataofjapan/land](https://github.com/dataofjapan/land) - High-quality GeoJSON and TopoJSON files of Japanese prefectures, converted from official GSI data.
*   [niiyz/JapanCityGeoJson](https://github.com/niiyz/JapanCityGeoJson) - GeoJSON and TopoJSON data specifically for Japanese cities and municipalities.
*   [piuccio/open-data-jp-prefectures-geojson](https://github.com/piuccio/open-data-jp-prefectures-geojson) - Clean, simplified GeoJSON file of Japanese prefectures with utility methods.
*   [geolonia/japanese-boundaries](https://github.com/geolonia/japanese-boundaries) - Comprehensive boundary data for various administrative levels in Japan.

### SVG Maps & Visualizations
*   [geolonia/japanese-prefectures](https://github.com/geolonia/japanese-prefectures) - A clean SVG map of Japan designed for web interfaces, grouped by prefecture with data attributes for easy CSS styling.
*   [ka215/svg-japan](https://github.com/ka215/svg-japan) - A native JavaScript plugin that generates an interactive, SVG-formatted map of Japan with support for custom colors and events.
*   [wakabayashiyu/japan-clickable-map-svg](https://github.com/wakabayashiyu/japan-clickable-map-svg) - A repository specifically focused on a clickable SVG implementation of the Japan map.
*   [SaitoTsutomu/japanmap](https://github.com/SaitoTsutomu/japanmap) - A Python package to generate SVG or image-based Japan maps and colorize them based on data.

## CLI & GUI Tools
Developer tools, text editors, and command-line utilities specifically built for or excelling at Japanese text.

### Command Line Tools (CLI)
*   [textlint](https://github.com/textlint/textlint) - Pluggable linting tool for natural language. Extremely popular in Japan for proofreading Japanese Markdown and documentation.
*   [nkf (Network Kanji Filter)](https://github.com/nurse/nkf) - A classic, powerful CLI tool used to guess and convert Japanese character encodings (Shift_JIS, EUC-JP, UTF-8).
*   [Jisho CLI (llllllllll/jisho)](https://github.com/llllllllll/jisho) - A feature-rich terminal tool for querying Jisho.org, with local SQLite storage and Anki export.

### Graphical Interface Tools (GUI)
*   [Sakura Editor](https://github.com/sakura-editor/sakura) - A highly regarded, classic open-source text editor for Windows, built specifically to handle Japanese encodings perfectly.
*   [CotEditor](https://github.com/coteditor/CotEditor) - A lightweight, open-source macOS native text editor with excellent support for CJK languages and vertical text mode.
*   [Yomitan](https://github.com/themoeway/yomitan) - An open-source browser extension that acts as a pop-up Japanese dictionary. Essential for developers reading Japanese technical documentation.

## Videos & Conferences
Channels covering major Japanese developer events and tech talks (many include English subtitles or dual tracks).

*   [RubyKaigi](https://www.youtube.com/@rubykaigi4884) - The world's leading Ruby conference, originating in Japan.
*   [DroidKaigi](https://www.youtube.com/@DroidKaigi) - Developer-first Android conference from Japan, heavily focused on Kotlin and Jetpack.
*   [PHP Conference Japan](https://www.youtube.com/@PHPConferenceJapan) - Archives of the main PHP event in Japan.
*   [PyCon JP](https://www.youtube.com/c/PyConJP) - The premier Python community conference in Japan.
*   [iOSDC Japan](https://www.youtube.com/c/iosdc) - The largest conference for iOS and Swift developers in Japan.

## Forums & Communities
Places to ask technical questions, find local events, and network with other developers in Japan.

*   **Q&A Sites**
    *   [teratail (テラテイル)](https://teratail.com/) - A dedicated Q&A site for IT engineers and programmers, tailored for the Japanese language and development ecosystem.
    *   [Stack Overflow (Japanese)](https://ja.stackoverflow.com/) - The official Japanese-language version of Stack Overflow.
*   **Event & Community Platforms**
    *   [connpass](https://connpass.com/) - The premier IT study session and event management platform in Japan. Most developer meetups and community groups are hosted here.
    *   [Doorkeeper](https://www.doorkeeper.jp/) - Another popular platform used by Japanese developer communities to organize tech events and meetups.
*   **Communities for International Developers**
    *   [TokyoDev](https://www.tokyodev.com/) - A job board and a strong Discord community specifically focused on English-speaking software developers living in or looking to move to Japan.
    *   [Japan Dev](https://japandev.com/) - Similar to TokyoDev, providing roles, company insights, and community resources for foreign developers navigating the Japanese tech landscape.

## Articles, Blogs & Platforms
Where Japanese engineers share their knowledge, plus directories of tech companies' engineering blogs.

*   **Blogging Platforms**
    *   [Qiita](https://qiita.com/) - The largest technical knowledge-sharing platform for Japanese developers.
    *   [Zenn](https://zenn.dev/) - A modern platform popular for technical articles and "Zenn Books".
    *   [Publickey](https://www.publickey1.jp/) - Reliable, independent tech blog covering cloud and enterprise development trends in Japan.
    *   [gihyo.jp](https://gihyo.jp/) - Professional technical articles by Gijutsu-Hyohron Co., Ltd.
*   **Company Engineering Blogs**
    *   [Mercari Engineering](https://engineering.mercari.com/en/) - Deep dives into the tech behind Japan's biggest marketplace app (often in English).
    *   [LINE Engineering](https://engineering.linecorp.com/en/) - Articles on scaling services to hundreds of millions of users.
    *   [Cookpad Tech Life](https://techlife.cookpad.com/) - Highly respected blog from the pioneers of Ruby on Rails in Japan.

## Related Awesome Lists
*   [awesome-japan](https://github.com/snamiki1212/awesome-japan) - A broad, curated list covering various topics including companies using specific tech in Japan.
*   [awesome-japanese-nlp-resources](https://github.com/taishi-i/awesome-japanese-nlp-resources) - A premier resource for Japanese NLP (Python, LLMs, dicts, corpora).
*   [top-github-users-only-japan](https://github.com/yusukebe/top-github-users-only-japan) - Community-driven repository tracking the most active GitHub users in Japan.
*   [Awesome-Japanese (Language Learning)](https://github.com/yudataguy/Awesome-Japanese) - Comprehensive collection of resources for learning the Japanese language.
*   [Japanese Lingo for Developers](https://github.com/Wizcorp/japanese-lingo-for-developers) - A technical glossary of Japanese terms useful in software development environments.

## Contributing
Contributions are welcome! Please read the contribution guidelines before submitting a pull request.
