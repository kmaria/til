# Testing UI with Long String

While groups of strings separated by spaces (i.e. sentences) might be more common, some of the supported localizations will not use spaces (e.g. Japanese) or will use very long compound words (e.g. German).

Japanese language does not use spaces in the formation of sentences, and certain titles can be very, very long. Also, Japanese characters usually utilize multibyte characters which occupy a lot more space.

Here's a clear example of a coherent and actual organization name for a division in the Ministry of Internal Affairs and Communications: 総務省総合通信基盤局電気通信事業部電気通信技術システム課番号企画室
Or, here's a trains station name in Kumamoto Prefecture in Japan: 南阿蘇水の生まれる里白水高原駅

Wikipedia article on the [Longest word in English](https://en.wikipedia.org/wiki/Longest_word_in_English)

**What we expect**
Long strings and spaced words will either be wrapped, or have a maximum displayed characters so as to not influence the placement/position of the dropdown menu size.
