[Main Page](README.md)

## Part 1: Working with web-based visualization tools and data
### General Government Debt as % of GDP, 2020
<iframe src="https://data.oecd.org/chart/6O4k" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6O4k" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2020</a></iframe>

## Part 2: Working with Flourish
Below, we have sparklines of debt to GDP ratio brooken down by country. The data comes from [OCED](https://data.oecd.org/gga/general-government-debt.htm) and is from 1995 to 2021. I decided to go with a teal-ish green color, as I find it easier on the eyes. There are a few problems with this chart. Notably, I wish I were able to order the countries in someway, perhaps alphabetically. Additionally, it is hard to tell which country is which by just the three letter code.
<div class="flourish-embed flourish-chart" data-src="visualisation/11123039"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Reworked Flourish Visualizsation
<div class="flourish-embed flourish-chart" data-src="visualisation/11123409"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Summary
The original OCED chart is a simple bar chart representing all of the countries GDP to Debt ratio for 2020. I think this is a good overall design for this purpose. This chart does not do anything to highlight an individual country, but presents the information nicely. The sorting makes it easy to pick out which country has the highest ratio (Japan). Next, the sparkline chart takes the same information but presents each country as its own mini timeline. This is a nice way to visualize trends over time for multiple countries. This would be very hard to do in a bar graph without overwhelming the audience. The sparklines allow this data to be visualized without displaying too much on one particular chart. The drawback to this method, however, is it is hard to see small changes in the trend since the individual graphs are so small.

My goal in the third graph was to reimagine the first two, and tell a story that focuses on the United States and its ratio in relation to the other countries on the graph. To acheive this, I placed all the countries' lines on one graph. I then greyed out the background countries and highlighted the United States in a greenish color, and the average in black. In order to *craft for clarity*, I got rid of the legend and instead added it as color elements to the title. I found that there are some drawbacks to the Flourish platform. I was looking for a way to make the green and black lines bolder, but could not find a way to bold individual lines.

## Tableau
<div class='tableauPlaceholder' id='viz1662651611096' style='position: relative'><noscript><a href='#'><img alt='GDP to Debt Ratio1995 - 2021OCED, 2021 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;GD&#47;GDPtoDebtRatio&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GDPtoDebtRatio&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;GD&#47;GDPtoDebtRatio&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>'
  var divElement = document.getElementById('viz1662651611096');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
