[home](/README.md)

# Government Debt Bar Chart (Part 1)
![2015](/images/2008debt.png)
Source: [https://www.oecd.org/en/data/indicators/general-government-debt.html?oecdcontrol-3122613a85-var3=2008](https://www.oecd.org/en/data/indicators/general-government-debt.html?oecdcontrol-3122613a85-var3=2008)


# Government Debt Heat Map (Part 2)
<div class='tableauPlaceholder' id='viz1730773258069' style='position: relative'><noscript><a href='#'><img alt='General Government Debt ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;bf&#47;bfarrah_dataviz2&#47;GeneralGovernmentDebt&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='bfarrah_dataviz2&#47;GeneralGovernmentDebt' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;bf&#47;bfarrah_dataviz2&#47;GeneralGovernmentDebt&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1730773258069');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
Source: DP_LIVE_05112020192340808.csv


# Government Debt Line Graph (Part 3)
<div class='tableauPlaceholder' id='viz1730777034880' style='position: relative'><noscript><a href='#'><img alt='U.S.A. and Canada Debt ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;bf&#47;bfarrah_dataviz2_2&#47;U_S_A_andCanadaDebt&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='bfarrah_dataviz2_2&#47;U_S_A_andCanadaDebt' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;bf&#47;bfarrah_dataviz2_2&#47;U_S_A_andCanadaDebt&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1730777034880');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
Source: DP_LIVE_05112020192340808.csv

This is a line graph showing the changes debt-GDP ratios for the US and Canada from 1995 to 2019. The influence of the 2008 recession (aka The Great Recession) is also likely depicted in this graph.

# Writeup
For the third data visualization, the graph visualizes a subset of the original data, looking only at the debt percentages for the U.S.A. and Canada. It shows that at the earliest point of the dataset, the US debt-GDP ratio (appx. 93.72) is far lower than the Canadian debt ratio (123.96). It also shows that, at the end of the dataset, the US debt ratio (135.69) has gotten much higher than the Canadian debt-ratio (108.20). This graph simultaneously compares the changes in debt for both countries and shows each country's own journey.

I picked these countries because the US and Canada are geographically close and culturally similar. It's no surprise, then, that both countries were heavily impacted by the 2008 recession. This point on the graph shows a large spike in debt for both countries, but it was much worse for the US. The debt for both countries started to plateau around 2013, though there seems to have been more frequent changes for Canada in that time. It's also interesting that the US and Canada seem to have traded places. They begin with Canadian debt being about 30 points higher than the US, and they end with the US being about 27 points higher than Canada.

My use of color here wasn't very innovative, but I believe it was adequate for the graph. Since I chose to use a line graph, I couldn't show any gradual changes in color to represent changes in the data. I instead decided to pick blue (Canada) and red (US) from Tableau's colorblind pallete, since these colors are visually striking, distinct from one another, and colorblind-friendly.

The second visualization is a heatmap showing the debt for all countries included in the dataset and aims to use color to symbolize the debt, with blue acting as cool/low debt and orange being hot/high debt. It uses shape to show a grouping of countries that all follow similar patterns. The third visualization is a line graph which focuses only on the US and Canada. It primarily uses shape to show the difference in debt trends for the countries, illustrating how the US began with lower debt than Canada and ended with much higher debt. It also may give more context to the 2008 recession, since that was a major point of change within the graph.


