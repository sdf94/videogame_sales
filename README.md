# How Many Videogames Will You Sell?

## Summary
<br>
This project investigates the correlation between publisher continent, number of tweets to sales, and ultimately be able to predict the weekly sales for the following week. Publishers usually were located on USA and Europe. Using the best machine learning method, AdaBoostRegressor with a RandomForestRegressor as a base estimator, I was able to predict the unit sales of videogames by name and console for the next four weeks with a 0.375 accuracy. 

## Files 
<br>
twitter_videogame.ipynb <br>
twitter_videogame.pdf <br>
README.md <br>
License <br>
videogames-slack-deck.pdf <br>
videogame_slide_deck.json <br>

Data <br>
----- example_location.csv	<br>
----- game_sales.csv - data for weekly sales	<br>
----- genre.csv	Added - data for genres needed for total sales <br>
----- joblib_model.pkl - saves machine learning model	<br>
----- machine_learning_data.csv - Cleaned data for machine learning model	<br>
----- objs.pkl - Picke file that saves tweets	<br>
----- objs_loc.pkl - Picke file that saves locations of publications 	<br>
----- publisher_location.csv - locations of publications; result of Location Look up function	<br>
----- publisher_location_saved.csv - smaller set of publisher_location.csv	<br> 
----- sales_tweets_saved.csv - smaller version of sales_tweets for total sales (actual sales_tweets too large for Github)	<br>
----- tweets.csv.zip - all of the tweets for weekly sales	<br>
----- vgsales.csv	- data for all sales<br>
----- videogames.csv - print out of small set of videogames for tweets <br>

## License 

The MIT License

Copyright (c) 2010-2018 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
