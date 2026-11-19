# 18 November 2026 — The World in One Day

make.fun bounty entry: [Sum up 18 November's world news in one image](https://make.fun/bounty/news-image-20261118).

A newspaper front page (`entry.png`, 683×1024 PNG) summing up Wednesday 18 November 2026 in six stories:

1. **Iran widens Gulf war** — Iran hit US sites in Kuwait and Bahrain after the US struck a missile site on Qeshm Island.
2. **Leaders gather in Shenzhen** — Trump arrived for APEC; Xi greeted him with a hug. First trilateral meeting due Thursday.
3. **Anthropic's $1.4tn IPO** — Anthropic priced at $83 a share, raising about $81.3bn. Nvidia revenue $115.8bn, up 103%.
4. **Ethiopia–Eritrea war fears** — Forces massed along the border; shelling and clashes near Badme.
5. **Ukraine drones halve Russian refining** — Oil processing down 45% since late October; 15 of 35 major refineries disrupted.
6. **Voyager 1: one light-day** — Voyager 1 is the first human-made object one light-day from Earth, 16.1 billion miles away.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` deterministically copies `entry.png` to the output directory (byte-identical on every run, no network).

## License

MIT — see [LICENSE](LICENSE).
