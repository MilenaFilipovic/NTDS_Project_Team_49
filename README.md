# A Network Tour of Millenial Movies
## Project for the course A Network Tour of Data Science
Github repository of the project done by a team of four students for *A Network Tour of Data Science* course (EE=558) given at *École polytechnique fédérale de Lausanne*. This readme contains the project abstract, list of required libraries for the correct execution, datasets that were used for project implementation and the different research questions and products that were analyzed. The code can be found in the Jupyter Notebooks of this repository, and the report is given in the *Project report.pdf*.

## Libraries used
We used the following libraries for this project, with Python 3.6.6


 Computational:

    numpy (as np)
    pandas (pd)
    networkx (nx)
	scipy
	sklearn
	surprise
	operator
	collections
	pandas_profiling

 Graphical:

    seaborn (as sns)
    matplotlib (as plt)
	IPython
	
 Textual:

    json
    base64
	codecs
	re
	io
    


## Abstract

As Walt Disney once said: "Movies can and do have tremendous influence in shaping young lives in the realm of entertainment towards the ideals and objectives of normal adulthood." But what do viewers really know about movies and what makes them successful? This project, based on the TMDb dataset, offers some interesting insights into movies from the past several decades. It shows how some of the movie features are correlated, explores how movies can be classified into genres using spectral graph analysis and CNNs, and gives a simple demo of a recommender system.

## Datasets

- The TMDb credits [dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata#tmdb_5000_credits.csv)

- The TMDb movies [dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata#tmdb_5000_movies.csv)

The `data` folder contains the subsampled data that was used for the implementation.

## Research Questions

-

## Structure of repo

The notebooks of the repository should be read in the following order:

- `Data Cleaning and Subsampling` [notebook](https://github.com/MilenaFilipovic/NTDS_Project_Team_49/blob/master/Data%20Cleaning%20and%20Subsampling.ipynb)

- `Data Exploration` [notebook](https://github.com/MilenaFilipovic/NTDS_Project_Team_49/blob/master/Data%20Exploration.ipynb)

- `Data Exploitation - Spectral Graph Theory (Cast and Crew)` [notebook](https://github.com/MilenaFilipovic/NTDS_Project_Team_49/blob/master/Data%20Exploitation%20-%20Spectral%20Graph%20Theory%20(Cast%20and%20Crew).ipynb)

- `Data Exploitation - Keyword co-occurrence graph` [notebook](https://github.com/MilenaFilipovic/NTDS_Project_Team_49/blob/master/Data%20Explotitation%20-%20Keyword%20co-occurrence%20graph.ipynb)

- `Data Exploitation - Recommender Systems` [notebook](https://github.com/MilenaFilipovic/NTDS_Project_Team_49/blob/master/Data%20Exploitation%20-%20Recommender%20Systems.ipynb)

Additionally, there is a `Gephi graph visualization` [notebook](https://github.com/MilenaFilipovic/NTDS_Project_Team_49/blob/master/Gephi%20graph%20visualization.ipynb) that was only used for visualization. 


## Authors

* *Milena Filipović*
* *Kristijan Lopatički*
* *Jelena Malić*
* *Davor Todorovski*


## License

Copyright 2019 Milena Filipović, Kristijan Lopatički, Jelena Malić and Davor Todorovski

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License.

You may obtain a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and limitations under the License.