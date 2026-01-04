# Dataset folder

This folder documents the expected location and structure of the dataset used in the project.

##  Dataset download

The dataset files are available for download at the following link:

https://drive.google.com/file/d/1VuI1NnPzYlhHIMBy-2nBegFoQTATbf8K/view?usp=sharing

After downloading, extract the files and place them in a local folder.
Update the paths in the notebookaccordingly.

---

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
3. Update the dataset paths inside the notebook accordingly.
4. Run
