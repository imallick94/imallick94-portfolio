
This is Ipsita Mallick's public portfolio for Telling Stories with Data, Fall 2020 class at Carnegie Mellon University.

# About me
Hello! I’m Ipsita (she/her) and I’m a graduate student at the Integrated Innovation Institute, currently in my last semester of pursuing my masters in innovation for products and services (MIIPS Program) at Carnegie Mellon University. Over the summer I worked with a startup based in Berkeley, Climate Action Guide and with CMU’s Open Learning Initiative as a product design intern. Before joining grad school, I worked as an architect in Mumbai, India for the construction of two hospitality projects. I am now in the process of pivoting my career towards product design and UX. After graduating this December, I want to work on designing useful, usable and desirable products with a focus on inclusive user experiences for interactive/responsive environments, XR and IoT product-service ecosystems. 

# What I hope to learn
Over the course of this class, I want to learn to better visualize and communicate information revealed by data to ensure that decisions made in the process of product development and design are guided by an informed narrative which can have a powerful impact and solve challenges or problems for users in an informed and equitable manner. By understanding and communicating the story that historic or past data tells us, we can better identify the points of intervention for design and gain insights to drive us towards a more human-centred approach in thinking about better possible futures.

Quotes that inspire me:

“The goal is to turn data into information, and information into insight.” – Carly Fiorina, former executive, president, and chair of Hewlett-Packard Co.

"Data is the kind of ubiquitous resource that we can shape to provide new innovations and new insights." - David McCandless, author of book Information is Beautiful.



# Portfolio


## Assignment 2 (09/16/20): OECD Government Debts

### Chart 0: Original Visualization

<iframe src="https://data.oecd.org/chart/65K0" width="950" height="713" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/65K0" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2016</a></iframe>

### Chart 1: Using Flourish to visualize the data

<div class="flourish-embed flourish-chart" data-src="visualisation/3758496" data-url="https://flo.uri.sh/visualisation/3758496/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Chart 2: Using Flourish to visualize the same data in an alternate way

<div class="flourish-embed flourish-hierarchy" data-src="visualisation/3758613" data-url="https://flo.uri.sh/visualisation/3758613/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Comparing Charts 1 & 2
Chart 1 and chart 2, when visualized as above tell different stories while using the same dataset. While Chart 1 shows the timeline of government debts for OECD countries over time, chart 2 tells the story of government debts for OECD countries where only a handful of countries form the majority of government debts in total. Chart 1 is better if we want to tell the story of the trajectories of the government debts by country, and though one can see the countries with the highest levels of debts, it is made clearer through the treemap chart 2 through the hierarchy of the area of occupied by each country which can be seen all at one or by year using the filter function of chart 2.




## Assignment 3 & 4 (09/23/20): Gender Wage Gap
Critique and suggested redesign of chart type to show a decline in gender wage gap for countries, in 2000 versus in 2015. 


### The Original Visualisation 
<iframe src="https://ourworldindata.org/grapher/gender-gap-in-average-wages-2000-vs-2015" loading="lazy" style="width: 100%; height: 600px; border: 0px none;"></iframe>

This chart is presented in support of the story that:
[In most countries the gender pay gap has decreased in the last couple of decades](https://ourworldindata.org/economic-inequality-by-gender#in-most-countries-the-gender-pay-gap-has-decreased-in-the-last-couple-of-decades "In most countries the gender pay gap has decreased in the last couple of decades").


### Critique of Original Visualization
The scatter plot chart here does a good job of showing an overall picture of how gender inequality in wages is reducing by showing most countries below the 45° line, indicating that the wage gap in the countries has been closing from 2000 to 2015. But it took me almost 15 minutes to reach this conclusion when I did not read the article it is associated with. It helped that the chart was interactive, so I could read the exact percentage changes of gender wages gap in 2000 and 2015 by country to come to this conclusion.

However, the visualisation is still very confusing for anyone looking at it at glance and does not tell the story of a decline in gender wage gap in most countries clearly for several reasons:

1. The size of the dots in the scatter plot shows the proportional size of population of the countries, but in a chart that is trying to communicate decline in gender wage gap, the size of the dots can be misinterpreted as the country showing the most change in gender wage gap from 2000 to 2015.
  
2. The axes and the chart type is problematic. This chart is showing the ratio of gender wage gap of 2015 to 2000 (y-axis:x-axis). In my opinion reading such a chart is difficult and not relevant to the overarching narrative that needs to communicate a decline in gender wage gap for majority of the countries.There is too much information - there are 4 quadrants for measuring % change in gender wage gap and a line of correlation between the years. The axes measure % in one year vs another, which according to me is not an effective way to show the trend over time in a clear and effective manner.

3. The headline of the visualization is factual rather than a statement of what the chart means to represent, i.e., a reduction in gender wage gap over time.

4. Further, it not not evident at a glance whether the overall trend amongst the countries here has been +ve or -ve. The audience needs time to read and understand the chart which is currently not intuitive.


### Wireframing solutions



### User testing (round 1) on wireframe sketches
Participant Name: Mahima Sharma (HR manager at ITC, India)

- Can you tell me what you think this is?
"

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?
*"This data is for anybody who wants to see how the pay gap between men and women has changed in the last 2 decades."*

- Is there anything you would change or do differently?


### Redesign of Chart: Pre-final Version
<div class="flourish-embed flourish-slope" data-src="visualisation/3830697" data-url="https://flo.uri.sh/visualisation/3830697/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>


### User testing (round 2)
Participant Name: Rahul Sridhar (CMU graduate student)

- Can you tell me what you think this is?
"It's a visualisation of gender 

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?


### Redesign of Chart: Version
<div class="flourish-embed flourish-scatter" data-src="visualisation/3830089" data-url="https://flo.uri.sh/visualisation/3830089/embed" aria-label=""><script src="https://public.flourish.studio/resources/embed.js"></script></div>
