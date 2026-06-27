# baseballStatArb
ml project: uses pybaseball to calculate odds for games, connects to kalshi api and scans for pricing differences


# baseballStatArb
ml project: uses pybaseball to calculate odds for games, connects to kalshi api and scans for pricing differences.

plan:

1. download fat csv of games from the past 5 seasons
2. clean using pandas, postgres
3. analyze using some ml library to create prediction output
5. use openclaw instance to scan kalshi using kalshi api
6. have openclaw check game odds once a morning to find pricing irregularities
