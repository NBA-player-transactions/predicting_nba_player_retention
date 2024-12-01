# Helper Files

In this folder, we store some auxiliary files to assist in the data cleaning
process. Namely, we have the following:

- Since we are pulling data from different sources and different sources
have different ways of attaching unique IDs to players, we need to choose a
convention for assigning IDs. Then, we need to translate all IDs to this
convention. The convention we will use is the NBA API ID. The below files
provide assistance in this process.
    - `nba_player_id_helper.ipynb`
    - `player_id_name.csv`
    - `player_id_season_name.csv`
    - `nonunique_player_names.csv`
    - `nonunique_player_id_season_pairs.csv`
    - `NBA_PLAYER_IDs.csv`

- To correctly place transactions in the correct timeframe (e.g. Regular
Season, Postseason, etc.), we need to know some basic information about
the NBA schedule for each season. The below file contains that.
    - `nba_key_datas.csv`
