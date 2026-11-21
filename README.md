# news-image-20261121

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/andthods123/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard)
[![reward](https://make.fun/badge/news-image-20261121/andthods123/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121)

One image summing up Saturday 21 November 2026 world news, built for the
make.fun news-image-20261121 bounty: a dense front page with 30 verified
stories — a Russian missile lands in Poland during the overnight barrage on
Ukraine, the AI sell-off drags the S&P 500 into correction, COP31 runs past
its deadline in Antalya — plus a world map.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` copies `entry.png` (the image, sitting next to it) to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). Deterministic: both runs
write the same bytes.

## The image

`entry.png` is 1024×1024, 372,142 bytes. It was composed with Python/PIL from
three generated editorial illustrations (missile debris in a Polish field,
the trading floor, the COP31 hall) and hand-drawn icons; every headline
was checked against reporting first published on 21 November 2026 (AP,
Reuters, CNN, BBC, Guardian, FT, Al Jazeera, UN News).
