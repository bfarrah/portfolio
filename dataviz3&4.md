[home](/README.md)

# Original Data Visualization
![original visualization](/images/original_ceo.png)

Source: [https://www.epi.org/publication/ceo-compensation-surged-14-in-2019-to-21-3-million-ceos-now-earn-320-times-as-much-as-a-typical-worker/](https://www.epi.org/publication/ceo-compensation-surged-14-in-2019-to-21-3-million-ceos-now-earn-320-times-as-much-as-a-typical-worker/)

I chose this visualization because it seemed like it had a strong foundation and potential to show something important, but relied too much on jargon and became unclear. Specifically, the big block of text underneath the chart caught my attention. I became even more confused after reading it, and I only understood the difference between "realized" and "granted" compensation after some Googling. It also seemed a bit bland or boring to look at. This graph definitely seemed like it had a story to tell (CEO's having much more compensation than average workers) but wasn't easy enough to read so as to share that story beyond business-oriented individuals.

# Critiquing the Visualization
I used Stephen Few's Data Visualization Effectiveness Profile to critique the visualization. This method helped me think about the audience of the visualization. I realized that while it likely does effectively reach the intended audience, it doesn't do enough to reach people beyond that. It also helped me organize my thoughts of when I first saw the visualization, which helps shed light on what other people are likely going to pick up on when looking at it initially.

# Sketching out a Solution
![sketch1](/images/ceo_sketch.jpg)

For this sketch, I decided to keep the core aspects of the visualization the same, but make minor adjustments to help with readability and accessibility. I reworded the title to be "CEO-Worker Compensation Ratio" rather than "CEO-to-worker compensation ratio, 1965–2019". The new title is shorter and less clunky, since I removed the "to" which should be read implicitly with the "-". I also removed the date range, since that can be easily found out by reading the x-axis labels. I also made the buckets smaller for each axis. Originally, the bucket sizes were 10 years (x-axis) and 100 points (y-axis). I changed this to be 5 years and 50 points, which makes it easier for the reader to identify the year and ratio-value associated with whatever point they're looking at. Finally, I greatly reduced the length of the note, which may be the most important change. I removed everything from it except for the definitions of "granted" and "realized" since these would likely not be understood by anyone except those working in or studying business. 

# Testing the Solution
## Interview 1: Adult, late 50s
- Can you tell me what you think this is?
	-  It's a graph showing the difference between what a CEO thinks their salary is (realized) compared to what they're actually getting (granted).

- Can you describe to me what this is telling you?
	- The amount a CEO believes they are being paid is way higher than what they are actually being paid.

- Is there anything you find surprising or confusing?
	- It's surprising that the realized compensation is so much higher than the granted. Also, what is meant by worker's 			compensation? I thought worker's compensation is what you get when you're injured and can't go into work. Is that what 		this is talking about?

- Who do you think is the intended audience for this?
	- People who work for this company, probably meant for the CEO or another higher-up employee.

- Is this easy to read/understand?
	- Yeah, because the blue line is what they think they're getting, and the turquoise line is what they're actually getting, which is much lower. It's not a great graph, but you can see there's a clear difference between the two.

- Is there anything you would change or do differently?
	- I don't know that the numbers on y-axis mean. Are they a salary or some other kind of number? Is it a percent change? I would make that more clear. I also don't get the point of the labels on some points but not on others. Are these supposed to be important?

## Interview 2: Student, early 20s
- Can you tell me what you think this is?	
	- It's a graph of data from 1965 to 2019 that shows how much a CEO worker is compensated compared to the compensation of other employees.

- Can you describe to me what this is telling you?
	- The realized compensation is the potential of what they could have made. The granted is what the value actually was. 

- Is there anything you find surprising or confusing?
	- Well, I just feel as though it is confusing because it isn't clear as to what "realized" means and what "granted" means. It seems like the potential value for the compensation versus what the compensation actually was.

- Who do you think is the intended audience for this?
	- Whoever would technically be in charge of paying a salary. Maybe it's for HR or whoever determines salary and compensation. This could also be for CEO's and workers, you know, people that it applies to.

- Is this easy to read/understand?
	- Partially. I get what it's saying, but it's just kind of a lot to look at.

- Is there anything you would change or do differently?
	- I would give more explanation as to what it's depicting. Maybe the caption could be better, or it could just do something to be simpler. Also, it's hard to tell the difference between the two lines. I would use a more different color for one of them.

## Summary
Essentially, it seemed like I didn't do enough to make the graph more readable for non-business people. The biggest gripes the interviewees had were releated to still not understanding the difference between "granted" and "realized." It seemed like they both understood the difference the graph was trying to showcase, but not actually realizing what value the graph was depicting. They thought the point of the graph was to show the difference between granted and realized compensations rather than showing how how much more CEOs make than typical workers. It's also possible that I've been misunderstanding the purpose of the chart. The section of the article the chart is from was titled "CEOs make 320 times as much as typical workers" so I assumed that was the main idea it was trying to show. Maybe this is only a secondary idea of the chart, though. From here on out, I'm going to focus on the difference between granted and realized, while still paying attention to CEOs making more than average workers. One of the interviewees also pointed out poor choice of color, since it was hard to tell the difference between blue and turquoise.


# Building the Solution
<div class='tableauPlaceholder' id='viz1731646165459' style='position: relative'><noscript><a href='#'><img alt='Ratio of CEO Compensation to Worker Compensation ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ce&#47;ceo1&#47;RatioofCEOCompensationtoWorkerCompensation&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='ceo1&#47;RatioofCEOCompensationtoWorkerCompensation' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ce&#47;ceo1&#47;RatioofCEOCompensationtoWorkerCompensation&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    
  var divElement = document.getElementById('viz1731646165459');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

This is my final redesign. I changed the color of the granted compensation line so that it could stick out more and be harder to confuse with the other line. It's also now colorblind-friendly. I couldn't figure out how to add a caption to a Tableau chart, however, so the note would read: "'Granted' refers to a compensation package including the value of stocks at the time they were offered. 'Realized' refers to a compensation package including the value of the stock after they were granted." I also removed the individual data labels, and I changed the title of the y-axis to be just "compensation ratio." This makes it simpler since "CEO-Worker" is already in the title and is redundant. I also changed the title of the graph to be "Ratio of CEO Compensation to Worker Compensation" to call more attention to the fact that it is showing a ratio, since the interviewees seemed to have trouble with that.

### Note
The data for these visualizations can be found in the file [ceo.csv](/ceo.csv)
