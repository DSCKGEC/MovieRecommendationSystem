# Movie Recommendation System

[![Contributors](https://img.shields.io/github/contributors/dsckgec/project-template.svg)](https://github.com/dsckgec/project-template/graphs/contributors) [![Forks](https://img.shields.io/github/forks/dsckgec/project-template.svg)](https://github.com/dsckgec/project-template/network/members) [![Issues](https://img.shields.io/github/issues/dsckgec/project-template.svg)](https://github.com/dsckgec/project-template/issues) [![Pull Request](https://img.shields.io/github/issues-pr-closed-raw/dsckgec/project-template)](https://github.com/dsckgec/project-template/pulls)


A basic GitHub repository template for initializing open source projects on a single click.

## Contents

1. [Description](#description)
2. [Project structure](#project-structure)
3. [Datasets](#Datasets)
4. [Project roadmap](#project-roadmap)
5. [Getting started](#getting-started)
6. [Contributing](#contributing)
7. [Authors](#authors)
8. [License](#license)
9. [Acknowledgments](#acknowledgments)

## Description
Who does not love Movies? 
The DataSet was scraped from https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata and includes all the major Movies and the information relevent to it.

## Project structure

```
  ├── datasets/         Dataset of Movies.
  ├── notebooks/        Contains the jupyter notebook file of Movies.
```
## Datasets
  - `movies.csv` is the dataset for Data Cleaning and Preprocessing and Recommendation Systems Section of the notebook
  - `tmdb_5000_credits.csv` and `tmdb_5000_movies.csv` are the datasets for the notebook Data Visualization and Revenue Prediction Sections of the Notebook

## Project roadmap

The project currently does the following things.

- Cleans the Dataset `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv`
- Cosine Similarity Algorithm is used on that data to predict movie
- Data Visualization on Movies and their profit percent. 

See below for our future steps.

- Find other possible algorithms for Recommendtion System
- Make Revenue Prediction on movies whose Status!=released.
- Make more Productive Visualizations.
- Clean `movies.csv` and make Recommendation System based on that data.


## Getting started
### Prerequisites

#### Software Needed
 
  1. A web browser. 

         OR
         
  3. Anaconda software.

#### Knowledge Needed
- Very basic understanding of git and github:

    1.  What are repositories (local - remote - upstream), issues, pull requests
    2.   How to clone a repository, how to fork a repository, how to set upstreams
    3.   Adding, committing, pulling, pushing changes to remote repositories

- For EDA and Visualisation
 
    1. Basic syntax and working of ```python```.(This is a must)
    2. Basic knowledge of ```pandas``` library. [Reading this blog might help.](https://www.dataquest.io/blog/pandas-python-tutorial/)
    3. Basic knowledge of ```matplotlib``` library. [Reading this blog might help.](https://blog.quantinsti.com/python-matplotlib-tutorial/)
    4. Basic knowledge of ```seaborn``` library. [Reading this blog might help.](https://www.mygreatlearning.com/blog/seaborn-tutorial/)
    5. Basic knowledge of ```scikit learn``` library. [Reading this blog might help.](https://www.dataquest.io/blog/sci-kit-learn-tutorial/)

  However the code is well explained, so anyone knowing the basics of Python can get a idea of what's happenning and contribute to this.

### Installing

There are two ways of running the code.
  1. Running the code on web browser.(Google Colab) [Recommended]
      - Head on to [Google colab](https://colab.research.google.com/)
      - Then click on ```Upload Notebook``` Tab.
      - Upload the notebook that you got from this repo.
        ![Colab-1](https://res.cloudinary.com/codehackerone/image/upload/v1618463907/ML/colab-2_c14swf.png)
      - Connect with the runtime.
        ![Colab-2](https://res.cloudinary.com/codehackerone/image/upload/v1618464955/ML/Colab-3_da822c.png)
      - Upload your dataset.
        ![Colab-3](https://res.cloudinary.com/codehackerone/image/upload/v1618464958/ML/Colab-04_sxfyjx.png)
      - Then Click on ```Run All```.
        ![Colab-4](https://res.cloudinary.com/codehackerone/image/upload/v1618465413/ML/colab-5_i92bzp.png)
      - Start Editing.

  2. You can also run the code locally in your computer by installing Anaconda.
      - Install Anaconda. [Follow these steps to install Anaconda on your computer](https://www.edureka.co/blog/python-anaconda-tutorial/#:~:text=on%20our%20systems.-,Installation%20And%20Setup,the%20instructions%20in%20the%20setup.)
      - Install jupyter notebook using ```conda```. [Follow these steps to install jupyter notebook.](https://test-jupyter.readthedocs.io/en/latest/install.html)
      - Make sure to install ```pandas```,```matplotlib```,```seaborn``` and ```scikit-learn``` to run the notebook.
      - Start Editing.

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. 
Any contributions you make are **greatly appreciated**. 
Contributing is also a great way to learn more about social coding on Github, new technologies and and their ecosystems and how to make constructive, helpful bug reports, feature requests and the noblest of all contributions: a good, clean pull request.

### Guidelines

- Before starting to work on any issue or feature, open an issue explaining the changes you want to make and wait for any of the project maintainers to assign it to you.
- Use better commit messages that explain the changes you make. View the example below:
    - Bad commit message: `updated readme`
    - Good commit message: `updated contributors list in readme`
- You **should not**, in any case, use resources or code snippets from sources that do not allow their public use.

### Steps to follow for Pull Request

- For solving an issue/adding a feature, write the code ***after*** the original code finishes and do not forget to add the issue name and number as a heading in the notebook.
- Before Submitting the PR, make sure to have a link of colab notebook of the feature/issue solved so that we can check easily. This even applies to those who are doing on anaconda.

## Authors

<a href="https://github.com/DSCKGEC/project-template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=DSCKGEC/project-template" />
</a>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- 
