# Pokemon-Matchups
Data 601 Homework 1 
<h1>Summary</h1>
<p>
This is Repo includes an exploration of the Pokemon Matchup data from Kaggle. This dataset includes damage modifiers for each Pokemon and how effective types of moves would be catorgrized by each type. The types of Pokemon moves include Normal, Fire, Water, Grass, Flying, Fighting, Poison, Electric, Ground, Rock, Psychic, Ice, Bug, Ghost, Steel, Dragon, Dark and Fairy. If a move is above 1, that means the Pokemon is susitible to to the attack and it would effective. While if a move is below 1 it is ineffective and is not very useful against said Pokemon. From the Histograms of each type, it seems like the weakest Pokemon types are Ice, Fighting, Fire, when only the Type match up is considered. This is due to the alot of the damage modifiers for those types have the highest amount of Pokemon in the *2 category meaning that when matched against a random Pokemon they have a higher likely hood of facing off against a Pokemon that would be very effective against them. The Strongest being Bug, Ice, Grass type pokemon due to having *1/2 damage modifers, meaning in a matchup against any random Pokemon they would be well off since the moves would have a high likelyhood of not being effective against them. Also from the Boxplot a Fire type move/Pokemon would fair well with most opponents due to haveing a the most even spread when it comes to effectiveness. The images can be found in the images folder, the Python Report can be found  
</p>
<h2>Goals</h2>
<p>
  The goal of exploring this dataset is gain a better understanding of Pokemon moves. Also to find what is the most effective type of Pokemon move and what is the least effective type of Pokemon move.
 </p>
 <h3>Methods</h3>
 <p> The dataset was loaded into the Python notebook. By im[porting the Panda library, we were able to load the CSV file into the Notebook, and check for any missing values or outliers. Fortunately all of the data was there. Removing the astrick (*) was needed to manipulate and visualize the data and was done by using the replace function. Next, the to_numeric function from the Panads library was used that allows the numbers to be seen as numeric instead of a string. The data was than illustrated. First into a boxplot for each type, and than for histrograms.This was done by first importing the matplotlib library.</p>
 <h4>Source</h4>
 <p> The dataset was found on the website Kaggle and was from the user Luna McBride, found here.https://www.kaggle.com/lunamcbride24/pokemon-type-matchup-data . The CSV file was downloaded to my personal computer and the path or the exact location was written in the notebook in order for the notebook to load the dataset. </p>
 <h5>Advice</h5>
 <p>In order for someone to be successful repliacting what I just did. You would need to first download the dataset from Kaggle found under Source or in the data folder. Also before coding importing the Pandas,and Matplotlib is needed.</p>
