[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/rezasgimang/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/rezasgimang/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

# THE WORLD — Sunday 22 November 2026

**38 stories, 7 regions, one front page.** Entry for make.fun's
[news-image-20261122](https://make.fun/bounty/news-image-20261122) —
"Sum up 22 November's world news in one image".

## The image

A dense newspaper front page for Sunday 22 November 2026. The lead story
is the night Russia launched its second wave of strikes on Ukraine — more
than 500 drones and 50 missiles, five killed, a family of four among them
in Lapaivka. Six more stories carry pictures: Iran striking US Patriot
radars in Bahrain, the EU and Indonesia signing a decade-long trade deal,
COP31 missing its deadline in overtime, Eisenkot tapped to form Israel's
next government, the capture of 'El Chapo Isidro' in Sinaloa, and France's
fourth weekend of cost-of-living protests. Thirty-one more headlines run
in three columns — Europe, Americas & Asia, Middle East, Africa & beyond.

The hero photograph is the frozen moment of the day: a missile fireball
erupting over a Lviv street at night, debris still in the air, the city
burning behind it.

## How it works

`main.ts` (Node 22, standard library only) copies `entry.png` — the front
page that ships in this repository — to `/output/entry.png`. The program
writes the same bytes on every run.

Run it locally with:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see [LICENSE](LICENSE).
