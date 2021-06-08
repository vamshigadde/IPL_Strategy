PROJECT NAME -: IPL TOURNAMENT ANALYSIS AND ITS STRATEGY

Table of Content-:
->Demo Overview
->Reason to Choose these Project
->Pandas Methods which are used in these project
->Graph which are used
->Workdone
->Conclusion 
->Result


1)Demo Overview-:
link-(https://drive.google.com/file/d/1S2GHGy_1Qv8PF8b8nCIboU-0DU--1bsZ/view?usp=sharing)


2)Reason to Choose these Project-:
->Firstly I'm huge fan of Cricket and when it comes IPL it is most interesting and Entertaining Tournament.
->Through this Dataset i want to conclude that the teams which are winning,
 after my analysis i want to come to a strategy that what we should with respect to 
 toss win,toss decision,venue/hometown and result through overall analysis of IPL history.

3)Pandas Methods which are used in these project-:
->info(),desribe(),isna(),sum()
->drop(),fillna()
->value_counts(),groupby()
->idxmax(),idxmin(),nlargest()
->unique()

4)Graph which are used-:
->For plotting i have used matplotlib.pyplot and seaborn
* Bar graph
* Pie chart 
* Countplot
* Heat map

5)Workdone-:
->By using fillna i have filled all the Nan values in the dataset
->By using value_counts i got a name and the count of players who got
player of the match ,same as teams also and i use it in Graphs also
->By using idxmax and idxmin i got the top and bottom i.e highest and lowest 
of the columns,were i have used it such has teams and players.
->I used nlargest because by dataset is very big to visualize the data 
properly on the following graph i have drawn the top (n) teams or players
using it.
->I used masking technique to know the information about tied matches.
->I used groupby where i need the reference of some other column.
->I have used unique method to neglect the copies
->I used countplot where the data is more and to visualize it properly.


6)Conclusion-:
->From above analysis i have concluded highest award of 'player of the game' is received by AB Devillers and J Theron.
->Mumbai Indians is the team,won maximum times in the Ipl History i.e almost 15% and least time chennai super kings ie.13.24%.
->Most of the teams won,when they won the toss and choice to field ->Match Result is declared mostly on the basis of runs ->less number of matches which are tied
->winning percentage with their venue/home town is less then 15%,the highest % of wins with respect to venue the team is Kolkata Knight Riders
->Outoff Total matches,these is the data on the basis of their result runs 366 tie 13 wickets 437 
->on the Toss decision bat 320 field 496

7)RESULT-:
->After my analysis the strategy of the team must be with respect to the toss,
if they win toss and in case if they choose to field the chances of winning the match is more(60-70)%.
->When they will come to bat they should try to hold the wickets. ->Chances of winning with respect venue is very low,we'll not consider it.
->In case if they losses toss,then at the time of batting make runs as much as possible by holding wickets also
