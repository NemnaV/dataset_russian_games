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
| `website`                   | URL to game website                                                |
| `support_url`               | Contact info                                                       |
| `support_email`             | Contact info                             |
| `windows`                   | Platform support                          |
| `mac`                       | Platform support                            |
| `linux`                     | Platform support                            |
| `metacritic_score`          | Scores from Metacritic                            |
| `metacritic_url`            | URL to game's page on Metacritic                                   |
| `achievements`              | Number of Steam achievements available                             |
| `recommendations`           | Number of Steam user recommendations                               |
| `notes`                     | Internal notes or flags (may be empty or used for filtering)       |
| `supported_languages`       | List of supported interface languages                              |
| `full_audio_languages`      | Languages with full audio support                                  |
| `packages`                  | Steam packages the game is part of                                 |
| `developers`                | Developers of the game                                             |
| `publishers`                | Publishers of the game                                             |
| `categories`                | Indicate technical features or game modes                          |
| `genres`                    | Official game genres chosen by the developer                       |
| `screenshots`               | List of URLs to game screenshots                                   |
| `movies`                    | List of URLs to trailers or gameplay videos                        |
| `user_score`                | user_score = positive / (positive + negative)                      |
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
| `tags`                      | These reflect how users perceive the game (assigned by players)    |
															
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
