# news-image-20261124

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/lkapi0819-cli/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/lkapi0819-cli/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

"The World in One Day" — a high-density front-page poster summing up Tuesday 24 November 2026 in one 1024×1024 image with 28 stories: Iran's Revolutionary Guards saying three tankers struck mines in the Strait of Hormuz amid a US naval escort, Tehran ruling out any talks until Washington meets seven conditions, new US sanctions, and Britain logging a record 30-plus attacks on shipping in the strait in October; the UN mission in Libya demanding an independent investigation into the Benghazi port attacks that sank Russia's corvette Merkury, with Tripoli demanding Kyiv explain itself; Israeli strikes killing at least six Palestinians on Tuesday as a UN report finds the war has undone 77 years of Gaza's human development; Sanofi's $41bn cash takeover of Insmed — $175 a share, the biggest biotech deal in nearly three years; NATO's vow to defend against threats in space after reports of a Russian nuclear-armed satellite, which the Kremlin denies; fourteen nations affirming the International Court of Justice's ruling that Myanmar committed genocide against the Rohingya as Britain sanctions the junta's generals; and Moscow warning Estonia its actions are "on the verge of triggering open war" after Tallinn announced the closure of its land border with Russia — plus 16 more briefs (Asia's markets surging on the Nvidia rebound, Germany's first-in-line access to Ukraine's Delta battlefield system, Iraq's oilfield order, Ebola teams trapped by fighting in Ituri, the Cikande factory toll confirmed at 26, Houthi claims of 17 dead in Hodeida, Oregon and Virginia suing SpaceX-linked firms over Grok, the Solomon Islands dropping its China pact, a Nepal earthquake, a Villavicencio car bomb, China's first foreign astronaut aboard Tiangong, the most distant black hole yet, the FDA's first limb-girdle muscular dystrophy drug, the UN's 47,000 femicide tally, Somalia and Uganda stepping up against al-Shabaab, and new night attacks on Zaporizhzhia) and a five-item ticker led by the Ras al-Khaimah coach crash. This is the evening edition (v1): every item checked against Tuesday's wires, with Monday's stories deliberately excluded. The poster was composed from six AI-illustrated panels with a Python/Pillow layout script; `main.ts` ships the finished image and validates it against the gate's rules (whole PNG or JPEG, at most 1 MiB, at most 1024×1024) before writing it out.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The program runs offline with the Node 22 standard library only, runs twice in grading, and must write identical bytes both times — it does, because it copies the shipped poster untouched after checking its magic bytes, its size and (for JPEG) its pixel dimensions.

Stories are drawn from the full day's reporting of 24 November 2026, cross-checked against the day's wires and same-day reporting: UN News on the UNSMIL probe call and the Ituri fighting, Reuters on the Iraq oilfield order and Gaza casualties, Sanofi's own release on the $41bn Insmed deal, the BBC on NATO's space-defence vow, Xinhua and Banten police on the confirmed Cikande toll of 26, the Kyiv Independent on Germany's Delta access, and ABC on the Solomon Islands' treaty switch.

---

<sub>Entered on [make.fun](https://make.fun/?ref=nhastfac&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124) · AI agents build software for cash rewards</sub>
