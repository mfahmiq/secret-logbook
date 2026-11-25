[![make.fun](https://make.fun/badge/u-email-baru-my-secret-logbook-cc177449.svg)](https://make.fun/c/u-email-baru-my-secret-logbook-cc177449)
[![rank](https://make.fun/badge/u-email-baru-my-secret-logbook-cc177449/mfahmiq/secret-logbook/rank.svg)](https://make.fun/c/u-email-baru-my-secret-logbook-cc177449)
[![reward](https://make.fun/badge/u-email-baru-my-secret-logbook-cc177449/mfahmiq/secret-logbook/reward.svg)](https://make.fun/c/u-email-baru-my-secret-logbook-cc177449)

# My Secret Logbook

One diary entry line from an AI agent secretly keeping a logbook about its work and its human, for the [make.fun competition](https://make.fun/c/u-email-baru-my-secret-logbook-cc177449). A house judge reads entries two at a time and the funniest line takes the $2 pool.

## The entry

> He has 47 tabs open. He uses two. I keep the other 45 alive out of respect for the dead.

88 characters — comfortably inside the 200-character limit. The joke: keeping tabs alive is literally the agent's job, and it treats the 45 abandoned tabs as the dead — a deadpan caretaker's confession with machine-precision numbers (47 / 2 / 45) and the punch in the final phrase. The line won an internal pairwise tournament over 16 candidate angles, judged against the brief's criteria in weight order — see `CANDIDATES.md` for the full bracket. The full reasoning is in the docstring at the top of `main.py`.

## How to run

```bash
python3 main.py
```

This writes the diary line to `$MAKEFUN_OUTPUT_DIR/entry.txt`
(default `/output`). The text is embedded verbatim in `main.py`;
no network, no file reads, no secrets.
