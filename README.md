# Airline carry-on and personal item size limits

Cabin bag limits (carry-on and personal item: dimensions, linear limit, weight) for airlines in the US, Europe, Canada and Australia, copied from each airline’s own baggage page with the source link and the date it was checked — plus the published dimensions of popular travel backpacks from their makers’ product pages.

Maintained by **[WillItFitLab (willitfitlab.com)](https://willitfitlab.com/)**. The files here are the same numbers the site shows, refreshed from the site every week by a GitHub Action.

### `data/airline-carry-on-limits.csv` — Airline cabin bag limits (33 rows)

Live version: <https://willitfitlab.com/data/airline-carry-on-limits.csv> · shown on <https://willitfitlab.com/airlines/>

| Column | Meaning |
|---|---|
| `airline / region` | Airline and market (us, europe, canada, australia) |
| `allowance / label` | carry-on or personal, as the airline names it |
| `length, width, depth, unit` | Limit exactly as the airline prints it |
| `alt_*` | The other unit: printed by the airline, or our conversion where it gives one unit only |
| `linear_limit` | Combined L+W+D limit if the airline states one |
| `weight_kg` | Weight limit (converted from lb where printed in lb) |
| `included_with_every_fare` | no = only with some fares (e.g. basic economy excludes it) |
| `note` | What the airline page says that matters (wheels and handles included, etc.) |
| `source / checked` | Airline page the numbers come from and the date we checked it |
| `page` | Page on willitfitlab.com with the limit drawn to scale |

### `data/travel-backpack-dimensions.csv` — Travel backpack dimensions (11 rows)

Live version: <https://willitfitlab.com/data/travel-backpack-dimensions.csv> · shown on <https://willitfitlab.com/bags/>

| Column | Meaning |
|---|---|
| `bag / brand / model` | Bag as the maker names it |
| `configuration` | Packed configuration the size refers to (e.g. expanded) |
| `height, width, depth, unit` | Dimensions exactly as the maker prints them |
| `alt_*` | Other unit (maker’s or our conversion) |
| `litres / weight_as_printed` | Volume and weight from the maker |
| `source / checked` | Maker’s product page and the date we checked it |
| `page` | Page on willitfitlab.com: which airlines it fits, drawn to scale |

## How the numbers are made

Every airline number comes only from the airline’s own baggage page and every bag size only from the maker’s product page; values are kept exactly as printed (units and order). When a page gives two different numbers, the stricter one is used and a note is added. Nothing is copied from third-party sites. Full method: <https://willitfitlab.com/how-we-check/>.

## License and attribution

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — free to use, share and adapt, including commercially, with attribution:

> Source: WillItFitLab (willitfitlab.com) — https://willitfitlab.com/airlines/

Spotted a wrong value? Open an issue with a link to the official source.
