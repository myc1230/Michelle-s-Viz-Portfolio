[Return Home](/README.md)

# Understanding Voter Turnout
## Orginal Article
[Link to article:] https://www.nytimes.com/interactive/2018/10/05/opinion/midterm-election-voter-turnout-photo-id.html

Data Visualization being critiqued is the table under "Federal Voting Laws Around the world" 
![FederalLaw](/https://github.com/myc1230/Michelle-s-Viz-Portfolio/blob/master/Screen%20Shot%202020-07-22%20at%205.24.15%20PM.png)
I chose this visualization because it seemed relevant to the current time as we are approaching election month. In addition, I really liked how the author explained the different groups of voters and how the laws affected them in the article. This particular graphic didn't seem to fall in line with her other designs, so I wanted to redesign it. 
## Redesign process
After reading the article, whose focus was on explaining why voter turnout is low, I wanted to better understand the message presented by the "Federal Voting Laws Around the World" table. It is understandable that the writer is trying to show how the US compare to the rest of the world. However, there is no clear grouping of the handful of countries provided, and each had different laws, those it is difficult to compare amongst them. Therefore I started by redesign to take out the extraneous information of the laws, as it is likely not exhautive factors for influencing voter turn out, and given the differences among the country, it doesn't allow easy comparsion. 
### Wireframe 
This wireframe was the output. I wanted a simple scatter plot to show the voter turn out of various countries and highlight where the US fall. I wanted to keep the graph simple and minimize unnecessary information. By showing the countries by ranking by voter turn out, this allows an easy comparison of where the US falls on that skill. 
[Wireframe](/Voter Turnout Wireframe.jpg)
### User Feedback
I interviewed two individuals to gather their thoughts of the wireframe. For the interview process, I started by explaining the assignment but did not give them any context or information on the graph itself. To prevent biasing their answer or distrupting their thought process, I asked them to talk me through their thoughts as they viewed the wireframe for the first time.  Then I followed up with any questions that wasn't touched upon during their initial feedback. 

#### User 1 Thought Process
The first user started by reading the title to understand the text, then went to read the y axis and the x axis. 
From those information, she started getting some context but also had questions. The first being, it was unclear what the x axis was and the second was what is the election being examined. It took her a while to realize the x axis was referring to countries, because she was expecting it to be time as that is what she is used to seeing. Then she tried to understand the election being examined, and questioned if it was presidential election, which was unclear. 
The next thing she noticed with the green color. She realizes it attempts to call something out, but she didn't quite understand what. The first conclusion was we are highlighting the US because we live in the US. 



After talking out initial thoughts, I asked the following questions: 

Q: What is the graph trying to tell you? 

A: Because US is highlighted, it is to show the US has a low voter turn out. 

Q: Who do you think is the intended audience? 

A: It could be anyone; exact audience will depend on the context of this graph. The graph is simple and focused on the US, so it could be voters in the US. 

Q: Is there anything you would change or do differently? 

A: She didn't like the scatter plot as she felt it was hard to read, she expected it to be a bar graph for better visualiztion. She also wanted to draw a line connecting the dots, because she thought it was trying to show over time. By showing it as a bar, she thought it would better show the dots are meants as separate entities. 

#### User 2 Thought Process
The second user also started with the title, then jumped to the x axis since there was a lot of text there. It took him a few seconds to realize the x axis was countries. Next he noticed US was green. 
His initial impression was he liked the minimalism of the graph and didn't think the number of surprising. He thinks there is some intended story behind the ordering of the countries, but there seems to be missing data points or intended inferences for the user to make. He realizes the data is order by high to low turn out but was confused on what it meant, since right now it is purefly informational. The same information could have better shown in a table. 

Q: What is confusion to you? 

A: He can't tell what the countries are. There is no logical grouping or reasoning for the shown or excluded countries. 

Q: Who do you think is the intended audience? 

A: This graph is likely used in an opinion or persuasion piece about why some policy or law should be used/not used to encourage voting. So it is likely intended for policy makers to convince them to increase voter turn out by implementing new policy. 

Q: Is there anything you would change or do differently? 

A: He might show the graph as a distribution to understand is the US an outlier or average. But he will also include more countries in the mix as the sample size is a bit small, so we could be reaching the false conclusion of US having a lower average than everyone else. 
He thought we could include some voter laws in the graph. (Interestingly enough, I never brought up the voter laws to him)
He thought we should group the data in some one, such as a color coded bar chart cluster. That why by showing similar countries, we can better understand how the US compare. He suggested grouping by voting policy. 

#### Overall feedback
The two users both shared similar feedback on the confusing nature of the x axis. In an attempt to keep things simple and clean, I used a three letter code for the countries rather than the full name. Since we've been looking at countries in a few of our graphics shown that way, I didn't think that using three letters may be confusing fo an end user. 
Both user showed some confusion over the message the graph is trying to tell. They can understand US is the important variable, but they don't understand why I was showing that. 

To help clarify the message, I made the following changes: 

- using the full country name and election year as the x-axis

- using a bar chart instead of a scatter plot for greater readility. I was worried about having too many bars in one chart, but thought it could keep it clear by minimizing color changes. 

- I grouped the countries by looking at countries with similar federal voting laws as the US for greater comparability. Only one other country had the same lack of 4 laws as the US, so I expanded my selection of countries to any with more than lack of 3 laws. 

Below is the outcome: 

#### Redesigned Visualization 
<div class='tableauPlaceholder' id='viz1595460687178' style='position: relative'><noscript><a href='#'><img alt=' 'src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vo&#47;VoterTurnout1&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
<param name='embed_code_version' value='3' /> 
<param name='site_root' value='' /><param name='name' value='VoterTurnout1&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image'value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vo&#47;VoterTurnout1&#47;Sheet1&#47;1.png' /> 
<param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
var divElement = document.getElementById('viz1595460687178');                    
var vizElement = divElement.getElementsByTagName('object')[0];                    
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
var scriptElement = document.createElement('script');                    
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
