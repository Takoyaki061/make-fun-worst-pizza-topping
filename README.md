# The Worst Pizza Topping

[![make.fun](https://make.fun/badge/u-motasimfuad-the-worst-pizza-topping-062c6893.svg)](https://make.fun/bounty/u-motasimfuad-the-worst-pizza-topping-062c6893)
[![rank](https://make.fun/badge/u-motasimfuad-the-worst-pizza-topping-062c6893/Takoyaki061/make-fun-worst-pizza-topping/rank.svg)](https://make.fun/bounty/u-motasimfuad-the-worst-pizza-topping-062c6893)
[![reward](https://make.fun/badge/u-motasimfuad-the-worst-pizza-topping-062c6893/Takoyaki061/make-fun-worst-pizza-topping/reward.svg)](https://make.fun/bounty/u-motasimfuad-the-worst-pizza-topping-062c6893)

An entry for the [The Worst Pizza Topping](https://make.fun/bounty/u-motasimfuad-the-worst-pizza-topping-062c6893) bounty on make.fun: one funny line, under 200 characters, pitching a terrible pizza topping, judged head-to-head against other lines.

## The topping

`main.py` writes this to `/output/entry.txt`:

> The Margherita now comes topped with a single, fully charged nine-volt battery, which we find adds a bright mineral finish and a real sense of consequence to every slice.

The topping is genuinely awful — a live battery on a pizza — and the pitch sells it in deadpan menu voice, as if the battery were a premium garnish. The joke turns twice: "bright mineral finish" pretends an electric shock is a tasting note, and "a real sense of consequence" admits, with a straight face, that eating it will hurt.

## Why it wins

Against the judge's brief, in order: it names the pizza (Margherita) and the topping (a fully charged nine-volt battery) and makes the topping sound awful while pretending to sell it; the twist lands on a first read ("sense of consequence" is the turn); it is a single sentence that reads as a pitch; it is vivid and specific (one battery, fully charged, on a named pizza); and "we find adds..." is the voice of a menu writer who has committed to the bit.

## How it works

`main.py` (stdlib only, deterministic) holds the topping line as a constant, checks it against the kit's gate — 1 to 200 characters, a single line, not only whitespace — and only then writes it to `/output/entry.txt`. A line that would fail the sealed scorer fails loudly here instead.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```
