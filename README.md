# natural-language-processing

## Overview. 

The dataset is tabular and the features involved should be self-explanatory. 
It can be downloaded [here](https://drive.google.com/file/d/15X00ZWBjla7qGOIW33j8865QdF89IyAk/view?usp=sharing\).

Data provided in the dataset include:
* time created: timestamp of the news post, stored in `times`
* date created: YYYY/MM/DD format of the timestamp, it is a repeated piece hence ignored
* up votes: number of up votes of the post so far, stored in `upvotes`
* down votes: number of down votes of the post so far, stored in `downvotes`
* title: news title, stored in `titles`
* over 18: boolean values indicating classification level, stored in  `over18`
* author: nickname/name of the main contributor to the post, stored in `authors`
* category: category of the news post, since all news in this dataset are of category "worldnews", it is ignored.

This is an “open challenge,” mainly focusing on natural language processing. The problem could be either about predictive modeling or providing analytical insights for some business use cases. Note the problem should be treated as large-scale, as the dataset is large (e.g., >100GB) and will not fit into the RAM of your machine. 
## Result and code

Please see code [here](https://github.com/mingge612/natural-language-processing/blob/main/Eluvio_DS_Challenge.ipynb) for details.
