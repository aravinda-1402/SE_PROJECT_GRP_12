# <i>Movie Recommendation System🎥 </i>
![Python](https://img.shields.io/badge/Python-3.6.13-blueviolet)
![Framework](https://img.shields.io/badge/Framework-Flask-red)
![Frontend](https://img.shields.io/badge/Frontend-HTML/CSS/JS-green)
![API](https://img.shields.io/badge/API-TMDB-fcba03)
![Coverage](https://img.shields.io/badge/coverage-97%25-brightgreen)

[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)
[![Build Status](https://app.travis-ci.com/prathyu99/CSC510_Group25_Project1.svg?branch=main)](https://app.travis-ci.com/prathyu99/CSC510_Group25_Project1)
[![PEP8](https://img.shields.io/badge/code%20style-pep8-orange.svg)](https://www.python.org/dev/peps/pep-0008/)
[![Issues](https://img.shields.io/github/issues/SurajRKU/SE_PROJECT_GRP_12)](https://GitHub.com/SurajRKU/SE_PROJECT_GRP_12/)
[![Issues Closed](https://img.shields.io/github/issues-closed/SurajRKU/SE_PROJECT_GRP_12)](https://GitHub.com/SurajRKU/SE_PROJECT_GRP_12/)
![last commit](https://img.shields.io/github/last-commit/SurajRKU/SE_PROJECT_GRP_12)
![total lines](https://img.shields.io/tokei/lines/github/SurajRKU/SE_PROJECT_GRP_12)
![GitHub branch checks state](https://img.shields.io/github/checks-status/prathyu99/CSC510_Group25_Project1/main)[![Repo-size](https://img.shields.io/github/repo-size/prathyu99/CSC510_Group25_Project1)](https://GitHub.com/prathyu99/CSC510_Group25_Project1/)
[![file_count](https://img.shields.io/github/directory-file-count/prathyu99/CSC510_Group25_Project1)](https://GitHub.com/prathyu99/CSC510_Group25_Project1/)
[![language_count](https://img.shields.io/github/languages/count/prathyu99/CSC510_Group25_Project1)](https://GitHub.com/prathyu99/CSC510_Group25_Project1/)
![GitHub all releases](https://img.shields.io/github/downloads/prathyu99/CSC510_Group25_Project1/total)
[![Top Language](https://img.shields.io/github/languages/top/prathyu99/CSC510_Group25_Project1)](https://GitHub.com/prathyu99/CSC510_Group25_Project1/)
[![Version](https://img.shields.io/github/package-json/v/prathyu99/CSC510_Group25_Project1)](https://GitHub.com/prathyu99/CSC510_Group25_Project1/)
[![Release](https://img.shields.io/github/v/release/prathyu99/wolfjobs)](https://GitHub.com/prathyu99/CSC510_Group25_Project1/)
![codecov](https://img.shields.io/badge/coverage-97%25-brightgreen)
[![unit_tests](https://github.com/ashakhatri007/CSC510_Group25_Project1/actions/workflows/QtyCalcTests.yml/badge.svg)](https://github.com/SurajRKU/SE_PROJECT_GRP_12/actions/workflows/QtyCalcTests.yml)
[![Repo Size](https://img.shields.io/github/repo-size/SurajRKU/SE_PROJECT_GRP_12?color=brightgreen)](https://github.com/SurajRKU/SE_PROJECT_GRP_12.git)
[![contributors](https://img.shields.io/github/contributors/SurajRKU/SE_PROJECT_GRP_12)](https://github.com/SurajRKU/SE_PROJECT_GRP_12/graphs/contributors)

This Movie Recommender System is like having a movie buddy who knows your taste super well. It looks at movie info from TMDB and even checks out what people say on IMDB. Then, it uses something called cosine similarity along with the sentiment analysis to match you with movies you'll love.

Imagine each movie is a star, and cosine similarity is like a cool trick to see which stars go together in the movie universe. You just type in a movie you like, and boom! It suggests other movies you'll probably dig. Setting it up is a breeze—just follow the steps. It's like having your own movie sidekick, making sure every suggestion is spot-on for your movie mood!

## 🎬✨Unlocking Movie Magic: A Glimpse into Our Enhanced Recommendation System ✨🎥

Let us say you're browsing through our updated system. You select a recent movie you loved, and instantly, the system not only suggests similar movies based on your taste but also factors in how others felt about those movies. Click on a poster, and a trailer pops up, engaging you even more. Dive deeper, and you'll discover captivating details about the actors—when they were born, where they're from, and their remarkable journey in the film industry. It's a journey, not just through movies, but through emotions and experiences.    


### Architecture of the Recommendation System 🏗️
![Alt Text](Recommendation_Architecture.png)


### What's New? 🤔
**🔄 Evolution Snapshot: Old vs. New**
- **Static to Dynamic Magic:** Old system had static movie details - a fixed menu with limited movie details. But now, with dynamic web scraping, we're serving real-time details like titles, cast details, genres, and eye-catching posters. So even the latest movies released are incorporated into the recommendation model. It's not just a movie; it's a dynamic experience! 🍿✨

- **Predictable to Feel-Good Feels:** Before, our system only understood your movie preferences. Now, we don't just understand them; we feel them too! Through sentiment analysis, we decode the essence of movie reviews, translating them into a mix of positive and negative vibes. Instead of merely suggesting similar movies based on your selection, we curate recommendations that resonate with your preferences and how others feel about them. It's not just a movie night; it's an emotionally resonant experience! 🎭👍

- **Interface Glow-Up:** Say goodbye to the old look; we've given it a complete makeover! The user interface is now a captivating wonderland of movie details, cast revelations, and user reviews. One can even get details of the cast like when their birthday and place of birth is, if you are curious, and also a biography explaining their jouney in the movie industry. It's not just watching; it's a visual feast! 🎨👀

- **Poster Pretty to Interactive Play:** Posters were just pretty faces. Now, click on them, and it's a gateway to excitement! Experience the thrill with interactive movie trailers. This transcends the passive observation of movie materials and shift towards active participation and engagement.  It's not just lights, camera, action; it's lights, camera, interaction! 🎬🔗



### Video ▶️ 
Please find our Youtube video [here](https://youtu.be/dPXN1Eo9zPE)




### How to run the project? ⚙️

1. Create an account on [TMDB](https://www.themoviedb.org/).

2. Obtain your API key by clicking on the API link in your account settings.

3. Copy or download this repository to your local machine.

4. Create a new conda environment using the command:

    ```bash
    conda create --name YOUR_ENV_NAME python=3.6.13
    ```

5. Activate the conda environment:

    ```bash
    conda activate YOUR_ENV_NAME
    ```

6. Install all required Python packages using:

    ```bash
    pip install -r requirements.txt
    ```

7. Replace `YOUR_API_KEY` in both instances (line no. 15 and 29) within the `static/recommend.js` file and save the changes.

8. Launch your terminal or command prompt from the project directory and execute `main.py` using the command `python main.py`.

9. Access [http://127.0.0.1:5000/](http://127.0.0.1:5000/) in your web browser.






### Rubric 📝
Refer to Rubric.md file [here](https://github.com/SurajRKU/SE_PROJECT_GRP_12/blob/main/project3/README.md)

### Documentation 📚
Refer to Wiki page [here](https://github.com/SurajRKU/SE_PROJECT_GRP_12/blob/main/API_Documentation.md)



### Similarity Score 📏
The recommender system employs a similarity score to quantify the likeness between two items, providing a numerical measure on a scale from zero to one. This score is derived through the application of cosine similarity, a method that assesses the resemblance between the textual details of the two items. The resulting numerical value encapsulates the degree of similarity, with zero indicating dissimilarity and one signifying identical text details. In essence, the similarity score serves as a crucial metric for the system to gauge and rank the similarity between items based on their textual characteristics.

### How Cosine Similarity Works 🔍

Cosine similarity is a measure used to evaluate the similarity between two vectors by calculating the cosine of the angle between them in a multi-dimensional space. In the context of the recommender system, these vectors represent the textual details of different movies. The method is particularly useful when dealing with high-dimensional data, as it captures the similarity between items irrespective of their overall size. A smaller angle between vectors indicates higher similarity, making cosine similarity a valuable tool for comparing and ranking items based on their textual characteristics.

For a deeper dive into the mathematical aspects of cosine similarity, refer to the [Cosine Similarity Wikipedia page](https://en.wikipedia.org/wiki/Cosine_similarity).

## Datasets 📊

The project utilizes data from the following sources:

1. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
2. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
3. [Movie List - 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)
4. [Movie List - 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [Movie List - 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)

## To run test cases enter below commands
- python -m pip install -r requirements.txt
- python -m coverage run -m unittest discover

## To test Code Coverage
- python -m coverage report
- python -m coverage html

## Funding 💰
The project is not currently funded

## Future Roadmap 🌠

See RoadMap [here](https://github.com/users/SurajRKU/projects/1/views/2)

*For a detailed description of the same, please refer to the comment for each item*

### Bug? 🐛
[Raise an issue](https://github.com/SurajRKU/SE_PROJECT_GRP_12/issues/new) on this repository, we would love to look at it ❤️

# Contributors 👥
  <table>
  <tr>
    <td align="center"><a href="https://github.com/prathyu99"><img src="https://avatars.githubusercontent.com/u/33190791?v=4" width="100px;" alt=""/><br /><sub><b>Prathyusha Kodali</b></sub></a></td>
    <td align="center"><a href="https://github.com/aravinda-1402"><img src="https://avatars.githubusercontent.com/u/71303848?v=4" width="100px;" alt=""/><br /><sub><b>Aravinda Raman Jatavallabha</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/SurajRKU"><img src="https://avatars.githubusercontent.com/u/53537228?v=4" width="100px;" alt=""/><br /><sub><b>Suraj Raghu Kumar</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/yuktasree"><img src="https://avatars.githubusercontent.com/u/64723066?v=4" width="100px;" alt=""/><br /><sub><b>Yuktasree Muppala</b></sub></a><br /></td>
  </tr>
</table>

**For any further support please email us:** segrp12fall2023@gmail.com 




