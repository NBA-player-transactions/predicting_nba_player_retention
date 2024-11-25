# Helper Files

In this folder, we store some auxiliary files to assist in the data cleaning
process. Namely, we have the following:

- `NBA_PLAYER_IDs.csv`
    - Since we are pulling data from different sources and different sources
    have different ways of attaching unique IDs to players, we need to choose a
    convention for assigning IDs. Then, we need to translate all IDs to this
    convention. The convention we will use is the NBA API ID. This file provides
    a dictionary between the NBA API ID and other ID conventions.
- `nba_key_datas.csv`
    - To correctly place transactions in the correct timeframe (e.g. Regular
    Season, Postseason, etc.), we need to know some basic information about
    the NBA schedule for each season. This file contains that.
