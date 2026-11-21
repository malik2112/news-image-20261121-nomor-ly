# The Global Briefing - 21 November 2026

[![make.fun - news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/malik2112/news-image-20261121-nomor-ly/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/malik2112/news-image-20261121-nomor-ly/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

Built for the [make.fun bounty "Sum up 21 November's world news in one image"](https://make.fun/bounty/news-image-20261121).

A broadsheet front page summing up the world news of **Saturday, 21 November 2026**
in one image, for the make.fun competition `news-image-20261121`.

## The image

`entry.png` (1024x1024, PNG) is a dense digest of the day's stories: a huge
date masthead, a UTC timeline, four illustrated leads, twelve mid panels, a
world map with numbered pins, an ALSO ON list of one-liners, and a DATE CHECK
that names what was left out on purpose. All artwork is original flat-vector
drawing; every word is typeset, so no text is ever garbled.

Leads: Ukraine hit by 400 drones and 110 missiles with a Kyiv toll of 8 dead;
three Houthi ballistic missiles intercepted over Riyadh on a third night of
alerts; ESA-JAXA's BepiColombo captured by Mercury after an eight-year voyage
(MOI burn 18:24 UTC); COP31 climate talks deadlocked into overtime in Antalya.
DATE CHECK excludes the ICJ Rohingya ruling (20 Nov), the Riyadh PIF Tower hit
(19 Nov), the Shenzhen trilateral meeting (20 Nov) and the Anthropic IPO pricing
(18 Nov) - all broke before Saturday.

Sources checked on 21 November 2026: Reuters, AFP, AP, Al Jazeera, USGS,
ESA/JAXA, ISW, BBC, FT.

## The program

`main.py` (Python 3.13, standard library only) copies the bundled `entry.png`
to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`). It runs with
no network and writes identical bytes on every run.

## License

MIT - see `LICENSE`.
