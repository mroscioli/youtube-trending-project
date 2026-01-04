# Dataset folder

This folder documents the expected location and structure of the dataset used in the project.

Due to file size and licensing considerations, the dataset files are **not included**
in this GitHub repository.

---

##  Recommended structure

The notebook assumes that dataset files are placed in the following folder:
data/trendingYT/

This is a **conventional project structure** adopted to improve clarity and
reproducibility.  
Users may place the dataset files in a different location and update the file paths
inside the notebook accordingly.

##  Expected files

The dataset consists of two types of files for each country:

### CSV files (trending videos data)

- `CAvideos.csv.zst`
- `DEvideos.csv.zst`
- `FRvideos.csv.zst`
- `GBvideos.csv.zst`
- `INvideos.csv.zst`
- `JPvideos.csv.zst`
- `KRvideos.csv.zst`
- `MXvideos.csv.zst`
- `RUvideos.csv.zst`
- `USvideos.csv.zst`

### JSON files (video category mappings)

- `CA_category_id.json`
- `DE_category_id.json`
- `FR_category_id.json`
- `GB_category_id.json`
- `IN_category_id.json`
- `JP_category_id.json`
- `KR_category_id.json`
- `MX_category_id.json`
- `RU_category_id.json`
- `US_category_id.json`

---

##  Notes

- Each CSV file contains the trending videos for a specific country.
- Each JSON file provides the mapping between `category_id` and category names
  for that country.
- Category mappings are country-specific and should not be mixed across countries.

---

##  Usage

1. Download the YouTube Trending Videos dataset from its original source.
2. Place the dataset files in a local folder.
3. If the files are placed in `data/trendingYT/`, the notebook can be executed
   without modifying file paths.
4. Otherwise, update the dataset paths inside the notebook accordingly.
