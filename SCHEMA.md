# 📊 Dataset Schema

This document describes the structure of each CSV file included in the Russian Games Dataset (IMDB + Steam).

---
## `info_imdb.csv`

| Column        | Description                                                        |
|---------------|--------------------------------------------------------------------|
| `name_imdb`   | Game name as listed in IMDB                                        |
| `release_year`| Release year of game                                               |
| `imdb_score`  | IMDB rating (can be empty)                                         |
| `rew_amount`  | Number of reviews (user votes) on IMDB                             |

---

## `info_steam_rare.csv`

| Column                      | Description                                                        |
|-----------------------------|--------------------------------------------------------------------|
| `id_steam`                  | Steam game ID                                                      |
| `name_imdb`                 | Game titles from IMDB                                              |
| `name_steam`                | Game titles from Steam                                             |
| `required_age`              | Minimum age requirement                                            |
| `price`                     | Current price of game on Steam, USD                                |
| `dlc_count`                 | Number of DLCs (Downloadable Content) available                    |
| `detailed_description`      | Long-form marketing text from Steam                                |
| `about_the_game`            | Game desription text                                               |
| `short_description`         | Short marketing texts                                              |
| `reviews`                   | One of the user's reviews                                          |
| `header_image`              | URL to header image                                                |
| `website`                   | Number of reviews (user votes) on IMDB                             |
| `support_url`               | Number of reviews (user votes) on IMDB                             |
| `support_email`             | Number of reviews (user votes) on IMDB                             |
| `windows`                   | Number of reviews (user votes) on IMDB                             |
| `mac`                       | Number of reviews (user votes) on IMDB                             |
| `linux`                     | Number of reviews (user votes) on IMDB                             |
| `metacritic_score`          | Number of reviews (user votes) on IMDB                             |
| `metacritic_url`            | Number of reviews (user votes) on IMDB                             |
| `achievements`              | Number of reviews (user votes) on IMDB                             |
| `recommendations`           | Number of reviews (user votes) on IMDB                             |
| `notes`                     | Number of reviews (user votes) on IMDB                             |
| `supported_languages`       | Number of reviews (user votes) on IMDB                             |
| `full_audio_languages`      | Number of reviews (user votes) on IMDB                             |
| `packages`                  | Number of reviews (user votes) on IMDB                             |
| `developers`                | Number of reviews (user votes) on IMDB                             |
| `publishers`                | Number of reviews (user votes) on IMDB                             |
| `categories`                | Number of reviews (user votes) on IMDB                             |
| `genres`                    | Number of reviews (user votes) on IMDB                             |
| `screenshots`               | Number of reviews (user votes) on IMDB                             |
| `movies`                    | Number of reviews (user votes) on IMDB                             |
| `user_score`                | Number of reviews (user votes) on IMDB                             |
| `score_rank`                | Number of reviews (user votes) on IMDB                             |
| `positive`                  | Number of reviews (user votes) on IMDB                             |
| `negative`                  | Number of reviews (user votes) on IMDB                             |
| `estimated_owners`          | Number of reviews (user votes) on IMDB                             |
| `average_playtime_forever`  | Number of reviews (user votes) on IMDB                             |
| `average_playtime_2weeks`   | Number of reviews (user votes) on IMDB                             |
| `median_playtime_forever`   | Number of reviews (user votes) on IMDB                             |
| `median_playtime_2weeks`    | Number of reviews (user votes) on IMDB                             |
| `discount`                  | Number of reviews (user votes) on IMDB                             |
| `peak_ccu`                  | Number of reviews (user votes) on IMDB                             |
| `tags`                      | Number of reviews (user votes) on IMDB                             |
															
---


## `main_info.csv`

| Column         | Description                              |
|----------------|------------------------------------------|
| `id_steam`     | Unique Steam app ID                      |
| `name_imdb`    | Game title as found in IMDB              |
| `name_steam`   | Game title on Steam                      |
| `release_date` | Steam release date (DD.MM.YYYY)          |
| `price`        | Price in USD (as listed on Steam)        |
| `developers`   | Developers of the game                   |
| `publishers`   | Publishers of the game                   |

---

## `genres.csv`

| Column     | Description                    |
|------------|--------------------------------|
| `id_steam` | Steam game ID                  |
| `genre`    | Genre assigned to the game     |

---

## `tags.csv`

| Column     | Description                    |
|------------|--------------------------------|
| `id_steam` | Steam game ID                  |
| `tag`      | Tag from user-generated list   |

---

## `categories.csv`

| Column     | Description                         |
|------------|-------------------------------------|
| `id_steam` | Steam game ID                       |
| `category` | Steam category (e.g., Single-player, VR support) |

---

## `estimates.csv`

| Column     | Description                                 |
|------------|---------------------------------------------|
| `id_steam` | Steam game ID                               |
| `positive` | Number of positive user reviews             |
| `negative` | Number of negative user reviews             |
| `score`    | Overall score or rating (if available)      |

---
