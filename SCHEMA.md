# 📊 Dataset Schema

This document describes the structure of each CSV file included in the Russian Games Dataset (IMDB + Steam).

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

## `info_imdb.csv`

| Column     | Description                                 |
|------------|---------------------------------------------|
| `name_imdb`| Game name as listed in IMDB                 |
| `year`     | Release year on IMDB                        |
| `country`  | Country listed (should include "Russia")    |
| `genre`    | Genre info from IMDB                        |

---

## `rare.csv`

> This is a raw, uncleaned dataset collected during the initial data gathering process. Use with caution; better cleaned data is available in `main_info.csv`.

---

## `nav.csv`

| Column            | Description                                 |
|-------------------|---------------------------------------------|
| `Название листа`  | Name of the dataset sheet/file              |
| `Описание`        | Description of the dataset's contents       |
