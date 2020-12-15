### YO BANANABOY

# WIKIPEDIA 
What can we learn from Wikipedia adminship elections ? 
How social network structure potentially influences voting in a time-dependent manner: analysis of a signed social network. 

Politics are everywhere. 
From seeking to be the class representative of your 5th grade class, to announcing you will be running for president (never say never, sometimes dreams DO come true), you are most likely to be involved in some kind of election throughout your life. 
We do not yet have the magic trick that will ensure you to be elected next time you run, but we are working hard on it. And for that, we chose to analyse past elections, exactly like football players review past games to improve their strategy. 
To this end, we chose to look back on Wikipedia Adminship elections that happened between 2004 and 2008. 
For some context : Wikipedia is the free online encyclopedia that we all know and love. Its articles are written by volunteers, amongst whom we can distinguish Administrators. In addition of being able to write articles, those people also have access to technical features of the website, especially the ability to help with its maintenance. But not anyone can become an admin that easily ! Adminship seekers have to go through a public election process at the end of which the vote count XXnot only vote count determines outcomeXX determines whether or not they are promoted.

**And now we ask : Tell us what you got Wikipedia !**

### TEMPORAL ANALYSIS 
## DATE
If you could choose the time of year your election will be held, would a certain move be more strategic than another ? We definitely know that people are cheerier when, for example, Santa's coming to town, but is it to the point where it could influence a vote they would cast at this time of year? XXOr do people that cast their votes around this period of the year that you usually spend with your loved ones, far away from your screen, tend to somewhat adopt the mind set of the Grinch? XX
Let's take a look. Its is important for further analysis to firstly take a look at how the number of elections evolved over time, when grouped by year.

*include time_plot1.html %}*

We can notice an important increase (actually, even an exponential-like increase) in the number of elections between 2004, 2005, 2006 and 2007.  In the perspective of refining our analysis, let's see what this evolution looks like if we group the number of elections by day. 

*include time_plot2.html %}*

The first thing that pops out is the peak on May 3, 2007, during which more than 300 elections were XXopened-->closed?XX. One could of course suppose that the death of Warja Honegger-Lavater, the famous Swiss Illustrator, might have caused several patriots to realise that Swiss artists are poorly recognized on Wikipedia, which might have inspired them to seek adminship in order to try and make up for this.  (Yes, this is quite unlikely... but she was REALLY talented).  
Anyway, what about the number of votes ? We could easily suppose that they tend to follow a similar trend than the number of elections, but let's actually verify it. 

*include time_plot2.html %}*  

So we have seen that the number of elections and votes have increased between 2004 and 2008. But what about the election outcomes? 

Add plots 


XXX

*include data_with_size.html %}*

## DURATION 
O.K., so now you have chosen the perfect date for your election to be held. But it is not the only parameter to take into account if you want to maximize your chances of being elected. Another important point is the duration of the election. As Wikipedia elections are public and a discussion between voters happens during the election duration, we can identify the duration of the election with the optimal length of time during which you should campaign.XXand hope that after this time your election gets closedXX
We analyse a large variety of durations to get a good grasp on the infuence of this parameter. 

*include histogram_durations1 %}*

Most of the elections lasted less than 250 hours, meaning less than 2 weeks. 

*include scatterplot_duration2 %}*

We can clearly see 2 clusters. ELections that lasted close to 250 hours are more likely to have a positive outcome. On top of that, elections that only lasted a very brief amount of time, meaning less than 50 hours, are way more likely to end with a negative outcome. 
This repartition seems coherent with the fact that shorter elections are rather unsuccessful. This can also be explained by the fact that Wikipedia bureaucrats tend to close elections that cumulate almost only negative votes from the beginning, resulting in short, failed elections. XXis that a fact or do we assume it?XX 

**Conclusion: Give people time to know you, to hear your opinions, and discuss about your program!**

## TIME 

*need to find a story angle for this one* 


## ELECTION DUPLICATES 

*need to find a story angle for this one* 


## ANALYSIS OF NEUTRAL VOTES 
Let's say your election is closed, and votes have been counted, and you did not get elected. But sticks and stones won't break your bones, and you decide to analyse the election process in order to learn from your mistakes and maybe take another chance later. 
What do neutral votes say about your election ? What do neutral votes say about the electors's opinions ? 
First, we have found that if there were no neutral votes casted for one election, there is a 53% chance of being elected. Meaning that maybe, no one casted a neutral vote and you have been rejected anyway, and this next part won't serve you.. 
But anyway, we dove into the elections where at least one neutral vote was casted per election. We have investigated whether or not neutral votes can correlate with the outcome of the election. There is a potential relationship between the fraction of neutral votes over the total number of votes, and the outcome of the election. 

*include scatterplot_plot_neutral_votes1 %}*

We can see that a high fraction of neutral votes is correlated with a negative outcome of the election. This could be interpreted in several ways, since we have not much additional information XXon how these votes are casted and interpretedXX. 
One could suppose that voters did not have a set opinion on you, the adminship seeker, and thus they voted neutral. This could be explained by the fact that your campaign was not strong enough to turn the opinions of people that did not know you before. They were not convinced, but not disappointed either, hence they voted neutral. XXThis seems rather unlikely to us as no one is forced to cast their vote for every election so why would they make the effort to cast a neutral vote?XX
Another explanation is that people were really not convinced that you would be a good Wikipedia administrator, but they actually knew you as a person, and as the elections are public, they did not want to hurt any feelings. Hence they chose to cast a neutral vote rather than a negative vote. 
Let's be honest, in both cases, your feelings might have been spared, but one could say you missed your shot.
XXoption that they firstly voted positive or negative and then decided to change their vote lateron (if that's allowed for Wikipedia elections), as Francis Picabia stated, "Notre tête est ronde pour permettre à la pensée de changer de direction", i.e. our heads are round so that our thinking can change directionXX

Another correlation that can be investigated is the one between the proportion of neutral votes and the duration of the elections. If a larger fraction of neutral votes are casted, one could suppose that more people are perplew XX?XX about you candidacy, and that overall it would take more time to settle the decision. This could mean that next time, you should campaign better and for longer in order to turn more's people opinion. 

*include scatterplot_neutral_votes2 %}*

We can see that most of the unsuccessful elections counted a higher fraction of neutral votes compared to the successful ones. We could infer that over a threshold of neutral votes, you will have very little chance of being elected, namely over 20% of neutral votes. Also, with a same ratio final ratio of neutral votes, an election is more likely to be successful if it lasted for a longer period of time. 


### CONCLUSION


{% include average_over_time.html %}

notes 
- if people have more time to vote, might be most likely to be elected, so campaign for longer. 
