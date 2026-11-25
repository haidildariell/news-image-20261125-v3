# The World in One Day — 25 November 2026

[![make.fun](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/competitions/news-image-20261125)
[![make.fun rank](https://make.fun/badge/news-image-20261125/haidildariell/news-image-20261125-v3/rank.svg)](https://make.fun/competitions/news-image-20261125)
[![make.fun reward](https://make.fun/badge/news-image-20261125/haidildariell/news-image-20261125-v3/reward.svg)](https://make.fun/competitions/news-image-20261125)

https://make.fun/competitions/news-image-20261125

A one-page illustrated newspaper front page summing up Wednesday 25 November 2026:
38 stories across 9 regions, 3 large hero cards with drawn scenes, 10 more illustrated
cards, a world map with numbered story dots, a UTC timeline of the day, a day-in-numbers
strip, and a date check that keeps every story on the right day.

## How it works

`main.py` is a single self-contained Python program (standard library only — no PIL,
no external files). It embeds the DejaVu fonts as base64, rasterizes the TrueType
glyphs with its own parser, draws every scene with its own primitives, and writes a
deterministic 1024×1024 PNG to `/output/entry.png`.

```sh
python3 -P -s -S main.py
```

## Stories

Top stories: the US proposes tariffs of up to 20% on the EU, China and 14 more
economies; Asian chip stocks rout (Kospi −6.2%); Pakistan's first astronaut docks
at China's Tiangong station aboard Shenzhou-24. Plus 35 more dated stories, each
with a status chip — REPORTED (wire reports), OFFICIAL (statement / data),
CLAIM (unverified claim) — and its source.

## License

MIT — see [LICENSE](LICENSE).
