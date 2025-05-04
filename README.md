# 🇷🇺 Russian Games Dataset (IMDB + Steam)

This repository contains a structured dataset from Steam about Russian video games listed in the IMDB video game listing.

## Dataset Contents

| File | Description |
|------|-------------|
| `info_imdb.csv` | IMDB data on Russian games |
| `info_steam_rare.csv` | Raw uncleaned dataset obtained from Steam parsing |
| `info_steam_main.csv` | Cleaned dataset with core game information from Steam |
| `categories.csv` | Steam categories per game |
| `genres.csv` | Steam genres per game |
| `tags.csv` | Steam tags per game |
| `estimates.csv` | User estimates and ratings from Steam per game |

## Dataset Structure

Each file represents a different aspect of the dataset. The main dataset is `info_steam_main.csv`, which includes core game data. Other files such as `categories.csv`, `genres.csv`, and `tags.csv` can be linked using shared identifiers (e.g., `id_steam`).

## Article and Research Background

This dataset was created as part of a master's's thesis (ВКР) at the Higher School of Economics (HSE).  
The research explored the characteristics of Russian video games on IMDB using Steam data.

A data-journalism article was also developed based on this dataset, highlighting trends, genres, and user perceptions of Russian games.

📄 [Read the article](./article.md) (in Russian)  
🎓 [View the diploma project on HSE portal](https://www.hse.ru/edu/vkr/?supervisor=%D0%9D%D0%BE%D0%B2%D0%B8%D1%87%D0%BA%D0%BE%D0%B2%20%D0%90%D0%BB%D0%B5%D0%BA%D1%81%D0%B5%D0%B9%20%D0%92%D0%BB%D0%B0%D0%B4%D0%B8%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B8%D1%87&author=%D0%9D%D0%B5%D0%BC%D0%BD%D0%B0%20%D0%92%D0%B0%D0%BB%D0%B5%D1%80%D0%B8%D1%8F%20%D0%90%D0%BB%D0%B5%D0%BA%D1%81%D0%B0%D0%BD%D0%B4%D1%80%D0%BE%D0%B2%D0%BD%D0%B0)

## Usage

1. Download the CSV files from this repository.
2. Load the data using your preferred data analysis tool (e.g., Python, R, Excel).
3. Start with `info_steam_main.csv` and join other tables as needed to enrich your analysis.

## Data Sources

- **IMDB**: Extracted metadata about Russian games.
- **Steam**: Scraped game information including categories, genres, tags, user ratings and etc.

## License & Terms
This dataset is released under the [MIT License](LICENSE).  
Please credit **Valeria Nemna** as the original author when using this dataset in any publication or derivative work.

This dataset is compiled from publicly available sources and is intended strictly for research and educational use. Always check the terms of service for IMDB and Steam when using their data.


## Author

This dataset was created by **Valeria Nemna** as part of a diploma research project.

---
