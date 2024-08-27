# **Spotify-Music-Analysis**
Analysis of different audio attributes for Drake, Britney Spears, and Led Zeppelin

The investigative goal of this project was to determine the audio features that distiguish these three artists from one another, create a model that could predict eh artist based on the audio features as well as determine the importance each feature has on the popularity of a song.

**Dataset**:

The data was obtained from Kaggle. It includes details such as the release date, song name, artists name, popularity, danceability, instrumentalness, energy, loudness and key. 

I filtered the data to include songs from Drake, Britney Spears or Led Zeppelin because they represent different genres and eras, and each of these artists dominated their respective periods and genres.

*Drake: Primarily Hip-Hop/Rap, with influences from R&B, pop, and dancehall. Drake began his career around 2009 and continues to be active.

*Britney Spears: Pop, with influences from dance-pop, teen pop, and occasionally R&B. Period: Britney Spears' career began in the late 1990s and continues to the present, though her most influential work was from the late 1990s to the early 2000s.

*Led Zeppelin: Hard Rock, with elements of blues, folk, and heavy metal. Led Zeppelin was active primarily in the late 1960s and 1970s, with their career spanning from 1968 to 1980.

**Tools and Technologies:**

Python was used for data analysis. Libraries such as pandas, seaborn, numpy, matplotlib, sklearn.linear_model, sklearn.ensemble, and sklearn.model_selection were utilized for data manipulation, analysis, and visualization, and machine larning.

**Findings:**

Drake’s music is characterized with high danceability, key complexity, and loudness, along with greater popularity and speechiness.

Britney Spears' songs typically have a lower tempo and consistent time signature.

In contrast, Led Zeppelin’s tracks are marked by high energy, greater instrumental complexity, lower danceability, and longer duration.

Overall, the values for Britney are more consistent or concentrated around a particular range, whereas those for Drake and Zeppelin are more varied. This could mean that her songs tend to have similar audio features.

Danceability plays a big role in a song's popularity, meaning tracks that are easier to dance to are more likely to succeed. Artists and producers might want to focus on creating more danceable music to boost their chances of of achieving popularity and perhaps hitting the charts.


**Note:** These results are specific to the dataset and the model used. Different datasets or models with other artists and songs might yield different results, so these findings should be considered in context.
