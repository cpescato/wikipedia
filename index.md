### YO BANANABOY
Faites vous plaise à écrire dans ce fichier
html syntax, markdown syntax 

# WIKIPEDIA 
What can we learn from Wikipedia adminship elections ? 
How social network structure potentially infkuence voting in a time-dependent manner: analysis of a signed social network. 

Politics are everywhere. 
From seeking to be the class representative of your 5th grade class, to announcing you will be running for president (never say never, sometimes dreams DO come true), you are most likely to be involved in some kind of election throughout your life. 
We yet do not have the magic trick that will ensure you to be elected next time you run, but we are working hard on it. And for that, we chose to analyse past elections, exactly like football players review past games for improving their strategy. 
We chose to look back on Wikipedia Adminship elections that happened between 2004 and 2008. 
For some context : Wikipedia is the free online encyclopedia that we all know and love. Its articles are written by volunteers, amongst whom can be distinguished Administrators. In addition of being able to write articles, those people also have access to technical features of the website, especially giving the ability to help with its maintenance. But not anyone can become an admin that easily ! Adminship seekers have go through a public election process at the end of which the vote count determines whether or not they are promoted.

And now we ask : Tell us what you got Wikipedia ! 

# TEMPORAL ANALYSIS 
## DATE
If you could choose the time of year your election will be held, would a move be more strategic than the other ? We definitly know people are cheerier when, for example, Santa's coming to town, but is it to the point where it could influence a vote they would cast at this time ? 

Let's take a look. Its is important for further analysis to firstly know how the number of elections evolved over time, when grouped by year.

include time_plot1.html %}

We can notice an important increase (actually, even an exponential-like increase) in the number of elections between 2004, 2005, 2006 and 2007.  
In the perspective of refining our analysis, let's see what this evolution would look like if we group the number of elections by day. 

include time_plot2.html %}  

The first thing that pops out is the peak on May 3, 2007, during which more than 300 elections were opened. One could of course suppose that the death of Warja Honegger-Lavater, the famous Swiss Illustrator, might have caused several patriots to realise that Swiss artists are poorly recognized on Wikipedia, which might have inspired them to seek adminship in order to try and make up for this.  (Yes, this is quite unlikely... but he was REALLY talented).  

Anyway, what about the number of votes ? We could easily suppose that they tend to follow a similar trend than the number of elections, but let's actually verify it. 

include time_plot2.html %}  

So we have seen that the number of elections and votes have increased between 2004 and 2008. but what about the election outcomes? 

Add plots 


XXX

include data_with_size.html %}

## DURATION 
O.K., so now you have chosen the perfect date for your election to be held. But it is not the only parameter to take into account if you want to maximize your chances of being elected. Another important point is the duration of the election. As Wikipedia elections are public and a discussion between voters happens whithin the duration of the election, we can identify the duration of the election with the length of time during which you should campaign. 

We analyse a large variety of durations, so we have a good grasp on the infuence of this parameter. 

include histogram_durations1 %}

Most of the elections lasted less than 250 hours, meaning less than 2 weeks. 

include scatterplot_duration2 %}
There is definitely 2 clusters. ELections that lasted close to 250 hours are more likely to have an positive outcome. On top of that, elections that lasted very little time, meaning less than 50hours, are way more likely to end with a negative outcome. 
This repartition seems coherent with the fact that shorter elections are rather unsuccessful. This also can be explained by the fact that Wikipedia bureaucrats tend to close elections that cumulate almost only negative votes from the beginning, resulting in short, failed elections.

Conclusion: Give people time to know you, to hear your opinions, and discuss about your program! 

## TIME 

# ANALYSIS OF NEUTRAL VOTES 

# ELECTION DUPLICATES 


{% include average_over_time.html %}

notes 
- if people have more time to vote, might be most likely to be elected, so campaign for longer. 