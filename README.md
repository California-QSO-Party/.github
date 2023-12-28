# California QSO Party Software
## What is the California QSO Party
The [California QSO Party](https://cqp.org) (CQP) is amateur (ham) radio contest held every year on the first weekend of October.  The first CQP took place in 1966. Since 1974, the [Northern California Contest Club](https://nccc.cc/) (NCCC) has sponsored CQP.  CQP has traditionally opened the annual contest season by providing an opportunity for contesters to prepare for the ARRL November Sweepstakes since the format is similar.

Stations outside of California, worldwide, work stations in California only. The 58 counties of CA are the multipliers. California stations work all stations in or out of CA. The 50 US states and 13 Canadian provinces/territories are the multipliers. California stations multipliers are capped at 58 to maintain consistency with historical scores and non-CA stations.  Stations outside of Canada and the US add to one's QSO total but do not count as multipliers. See the [CQP website](https://cqp.org/) for more rules and more information about the contest.

## What's the purpose of this GitHub Organization?
The organizers of the CQP have put together a suite of software to manage the organization, log retrieval, scoring, and analysis for the contest. The GitHub organization is an attempt to enable Open Source support and development of these tools. At the time the organization was set up the main pieces are:
* a webserver for receiving Cabrillo logs from participants
* a web interface to view the incoming logs, potentially missing logs, and various aggregate visualizations of the incoming logs
* programs to perform log triage (i.e,. the process of getting logs into the required Cabrillo format)
* a program crossmatch QSOs in the submitted logs to determine which QSOs are confirmed, confirmed with mistakes, not in log (NIL), or byes (QSOs with stations who didn't submit a log)
