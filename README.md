The question is : _"in the recent Man.City-Bayern Munchen two-leg fixture for the Champions League knockouts what was the players'
pass and carry values ?"_ **(pandas and matplotlib used)**
- data via Fbref ,
- pass value = (progressive passes + passes to box) ,
- carry value = (progressive carries + carries to box).
- normalized data with **simple feature scaling** ,
- filtered the df and binned the players into 4 categories : those who didn't stand out , the "passers" (_scored more than abg for pass value_) ,
the "carriers" (_scored higher than avg in carry value_) and the "elite progressors" (_scored above avg in both pass and carry values_)
- used AxisArtist and Floating Axes to _"tilt"_ the plot and make the diamond shape.
The repo has the notebook with the code and the process + the excel file with data from FBref.
