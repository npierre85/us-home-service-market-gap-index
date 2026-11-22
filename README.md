# US Home-Service Market Gap Index (November 2026)

Which local service businesses are under-supplied in 386 US towns: how many people search Google for each of 71 home services every month, how many companies already compete for those customers, and where demand clearly outruns supply.

Built by [Town Demand](https://www.towndemand.com/) from its November 2026 scan (run 28, 27,406 town and business pairs). Free to use under CC BY 4.0: please credit **Town Demand** with a link to https://www.towndemand.com/.

## What is in it

| File | Rows | One row per |
|---|---|---|
| [`data/towns.csv`](data/towns.csv) | 386 | town: total monthly searches across 71 services, how many have an opening, the top 3 openings, median competitors on the Google map |
| [`data/businesses.csv`](data/businesses.csv) | 71 | service: in how many towns it has an opening, total searches, median cost per click, median competitors, best 3 towns |
| [`data/states.csv`](data/states.csv) | 47 | state: towns tracked, total searches, the most common top opening, the town with the strongest opening |

Every row links to its page on towndemand.com, which shows the full ranking for that town, service or state.

## Headline findings

- **6.75 million searches a month.** That is how often people in these 386 towns search Google for one of the 71 services.
- **Garage door repair is the most common gap.** It is the #1 opening in 119 of 386 towns and has an opening in 374. Roof repair (#1 in 59 towns) and AC repair (49) follow.
- **The most open services overall:** garage door repair (374 towns), AC repair (370), pressure washing (343), roof repair (337), water heater installation (330), countertop installation (328), tree removal (324) and dumpster rental (303).
- **The most expensive clicks:** whole house repipe ($51 median cost per click), water damage restoration ($46), AC repair ($45), foundation repair ($41) and garage door repair ($40). High cost per click means each customer is worth a lot to the businesses competing for them.
- **Smaller towns with the most openings** (under 15,000 tracked searches a month): Columbia SC (36 services with an opening), Fishers IN (35), Manchester NH (35), Albany NY (35) and Little Rock AR (34).
- **The most crowded towns:** Waterbury CT and Rocky Mount NC have no clear opening in any of the 71 services.

## How it is measured

For each town and service Town Demand pulls:

1. **Demand:** monthly Google searches for the service and its common variations in that town (Google Ads keyword data).
2. **Competition:** the businesses Google shows on the map and in the top results for those searches, their review counts and ratings, and how many results are directories instead of real local companies.
3. **Value:** the cost per click advertisers pay for those searches.

An **opening** means demand is high enough to support a new business and the companies Google shows are beatable: few of them, thin review counts, or results filled with directories instead of local firms. The **score** ranks openings within the scan; higher is a clearer gap. Towns and services too small to judge are left out of the opening counts. Full method: https://www.towndemand.com/methodology/

The data is a snapshot of November 2026. Town Demand rescans every month; the live numbers, the competitor lists behind each score and town-level reports are at https://www.towndemand.com/.

## Uses

- **Journalists:** "{Town} is short on {service}" stories, with the numbers behind them.
- **Economic development and chambers:** which services residents search for that too few local companies provide.
- **Lenders and business counselors:** a starting point for the market section of a business plan.
- **Researchers:** local service supply and demand across US metros.

## Citation

> Town Demand. *US Home-Service Market Gap Index, November 2026.* https://www.towndemand.com/

See [`CITATION.cff`](CITATION.cff). Questions or a custom cut of the data for your town: npierre@synergeticv.com

## License

[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). Share and adapt for any purpose, including commercial, with credit to Town Demand and a link to https://www.towndemand.com/.
