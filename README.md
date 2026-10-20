# AI coding plans: prices and usage limits (open dataset)

Verified list prices for 57 AI tools for builders, and 5-hour, weekly and monthly usage caps for 28 plans of 8 AI coding tools (Claude Code, Cursor, OpenAI Codex, GitHub Copilot, Windsurf, Google Antigravity, Replit, Lovable).

Every figure is copied by hand from the vendor's own pricing or docs page and carries the URL and the date it was checked. Nothing is estimated: when a vendor doesn't publish a cap's size, the data says so.

Maintained by [AIBuildersUse](https://aibuildersuse.com). Browse it at [aibuildersuse.com/limits](https://aibuildersuse.com/limits/) and [aibuildersuse.com/prices](https://aibuildersuse.com/prices), or embed the live table: [aibuildersuse.com/embed](https://aibuildersuse.com/embed).

## Files

| File | What |
|---|---|
| `prices.json` / `prices.csv` | One entry per tool: `free` (free tier?), `entry` (cheapest paid plan, USD/month), `entryLabel`, `verified` (plans we checked), `source`, `checked` (YYYY-MM-DD). |
| `limits.json` / `limits.csv` | Per tool and plan: price, and for each window (`short` = 5-hour/daily, `week`, `month`) a kind, an optional value and a text. Kinds: `rel` = multiple relative to another plan of the same tool, `amt` = published amount, `np` = a cap exists but its size isn't published, `none` = no cap of this kind published, `nolimit` = vendor says there's no limit. `value` only scales plans within one tool. `limits.json` also has a dated `changes` log. |

Live JSON (CORS enabled): `https://aibuildersuse.com/embed/data.json`.

Prices are USD list prices, excluding tax, seats and usage. They change often: check the vendor before you buy.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Use it anywhere, including commercially. Please credit **"Data: AIBuildersUse"** with a link to https://aibuildersuse.com/limits/ (or the matching page).

## Corrections

Spotted an outdated figure? Open an issue with the vendor link.
