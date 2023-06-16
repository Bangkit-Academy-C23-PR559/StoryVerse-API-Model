# StoryVerse-API-Model
An API for Recommend Titles by Category Features using Flask Python

## Prerequisite
- Python 3.9
- Flask
- Tensorflow

## Setup
- Clone API Model
  ```
  https://github.com/Bangkit-Academy-C23-PR559/StoryVerse-API-Model.git
  ```
- Test the API locally
  ```
  python index.py
  ```
- Deploy App Engine (app.yaml)
  ```
  gcloud app deploy
  ```


## Recommend Titles by Category 
- base url : ```https://storyverse-app.et.r.appspot.com/recommend```
- Method : ```POST```
- Data Params :
  ```
  categories = ["Profesi", "Pengalaman Pribadi", "Kesehatan Mental", "Mistis", "Percintaan"] 
  ```
  **1-5 categories, case-sensitive**
- Response :
```
{
    {
    "recommended_titles": [
        "Mengapa Saya Meninggalkan Go-Jek, Unicorn Start up Indonesia",
        "Bagaimana Memulai Startup di Indonesia?",
        "Designer *katanya",
        "Berapa Gaji Yoel?",
        "How to Find Confidence in Your Career Path",
        "How to Become an Employee Benefits Professional",
        "The Secrets of a Successful Internship",
        "Menjadi Penulis Mobile"
    ]
}
}
```
