| [home page](https://myrashen.github.io/Shihan-Shen-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique by Design on Demographics of Social Media Users  

## Step one: the visualization

The initial data visualization link: [Demographics of Social Media Users](https://www.pewresearch.org/internet/fact-sheet/social-media/?tabItem=3345cffa-94a6-4e74-9272-70dee1e0e213#who-uses-each-social-media-platform)

Before looking further on the data visualization, I think this topic is very useful because many Americans use social media to connect with one another, engage with news content, share information and entertain themselves. Among the widespread social media landscape, there exits long-enduring development regarding the social media users, from where we can come up with some insights on social media trends.

The primary audience, I suppose, are mainly the policy makers and analysts those studying the impact of social media. Besides, I thought it was also useful for business leaders and strategists. Through the demographic analysis of social media users, policy analysts can analyze the public opinions and propoganda. Companies can decide where to allocate marketing budgets and resources, such as  advertising. 

However, I think this visualization is not effective for reaching those audiences. The visuals are static and lack storytelling. It merely displayed the data collection, with no further explanation or any narratives related to meaningful storytelling.

## Step two: the critique

I began the critique by design on demographics of social media users by critically evaluating the initial data visualization using Stephen Few's Data Visualization Effectiveness Profile. The seven dimensions of criteria Stephen lists are instructive. Based on this Data Visualization Effectiveness Profile, I found both advantages and shortcomings with the demographics of social media users.

This data visualization did well in credibility and clarity. I can approach to its data source on the URL. It has several notes explaining some specific data point, such as the vertical line in the chart, indicating a change in survey mode. On this web page, there is a board, "HOW WE DID THIS", explaining its methodology, purpose and survey questions as supplemental information. It did well in trustfulness, intuitiveness, and completeness.

However, this data visualization were really bad in the aesthetics and engagement. It solely uses charts and tables to visualize the percentage of social media users in demographic perspectives. Besides, the visuals are purely functional, with no interactivity, designs, or storytelling elements. Users can’t filter, compare, or explore the data beyond what is given. A key realization was that while the original visualization presented interesting data points, it lacked a clear narrative, making it difficult for viewers to extract meaningful conclusions at a glance. Additionally, the color scheme and labeling needed improvement for better readability.

I would at least change the form of charts, making it more visible and showing more on social media trends. Besides, I would add an interactive function, such as filters.

## Step three: Sketch a solution

![line charts of overall proportion](WechatIMG2.jpg)

Explanations:
With the critique in mind, I moved to sketching potential redesigns. I explored different visual formats, including line charts to depict trends over time, scatter plots to show correlations, and bar charts to highlight the most engaged users. In my initial design, instead of overwhelming and colorful lines, I decided to divide the twelve lines into three groups:
1) Dominant platforms with over 50% engagement now.
2) Emerging and prospect platforms with rapid growth in engagement.
3) Shrinking platforms with slowly growing user engagement.

![charts of demographics analysis](WechatIMG3.jpg)

Explanations:
From a demographics perspective, I planned to apply stacked bar charts to show the composition of gender and age and to facilitate comparisons between various platforms. For ethnicity and education data, I opted for area charts to illustrate both the composition and trends in social media engagement across different racial and educational backgrounds. 

## Step four: Test the solution

| Question | Interview 1: Student, MISM Program | Interview 2: Student, Mid 20' |
|----------|-------------|-------------|
|Can you tell me what you think this is?|The heatmap shows the engagement level of users on different platforms|The heatmap shows the comparison between platform popularity|
|Is there anything you find surprising or confusing?|The effort on dividing the overwhelming line chart into three charts|The stacked bar chart clearly represents the composition of demographic elements|
|Is there anything you would change or do differently?|Add some cross-platform analyses|Improve color designs for clearity|

Synthesis: 
I think my solution is clear for the audience to have a glance at. Based on the feedback, I should improve the color scheme to ensure perceptibility, using contrasting but visually cohesive palettes. Besides, adding a brief summary text below the visualization helps to guide the audience on how to interpret key patterns. I might use a filter function for better clarity and customization, allowing users to focus on specific demographics or trends.

## Step five: build the solution

**1) Overview of social media platforms:**

![social media users](socialmediaheatmap.png)
The graph is a treemap visualization that illustrates the percentage of U.S. adults who report using various social media platforms as of June 10, 2024. The purpose of the graph is to provide a comparative overview of social media platform usage among U.S. adults, emphasizing the relative popularity of different platforms.

**2) Line charts of grouped platforms:**
<div class='tableauPlaceholder' id='viz1739411300305' style='position: relative'>
   <noscript><a href='#'><img alt='% of U.S. adults who say they ever use …(dominant platforms) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;so&#47;socialmediausers&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript>
   <object class='tableauViz'  style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
      <param name='embed_code_version' value='3' />
      <param name='site_root' value='' />
      <param name='name' value='socialmediausers&#47;Sheet1' />
      <param name='tabs' value='no' />
      <param name='toolbar' value='yes' />
      <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;so&#47;socialmediausers&#47;Sheet1&#47;1.png' />
      <param name='animate_transition' value='yes' />
      <param name='display_static_image' value='yes' />
      <param name='display_spinner' value='yes' />
      <param name='display_overlay' value='yes' />
      <param name='display_count' value='yes' />
      <param name='language' value='zh-CN' />
   </object>
</div>
<script type='text/javascript'>                    var divElement = document.getElementById('viz1739411300305');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

<div class='tableauPlaceholder' id='viz1739411548994' style='position: relative'>
   <noscript><a href='#'><img alt='% of U.S. adults who say they ever use …(emerging platforms) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;so&#47;socialmediausers&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript>
   <object class='tableauViz'  style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
      <param name='embed_code_version' value='3' />
      <param name='site_root' value='' />
      <param name='name' value='socialmediausers&#47;Sheet2' />
      <param name='tabs' value='no' />
      <param name='toolbar' value='yes' />
      <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;so&#47;socialmediausers&#47;Sheet2&#47;1.png' />
      <param name='animate_transition' value='yes' />
      <param name='display_static_image' value='yes' />
      <param name='display_spinner' value='yes' />
      <param name='display_overlay' value='yes' />
      <param name='display_count' value='yes' />
      <param name='language' value='zh-CN' />
      <param name='filter' value='publish=yes' />
   </object>
</div>
<script type='text/javascript'>                    var divElement = document.getElementById('viz1739411548994');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

<div class='tableauPlaceholder' id='viz1739412057523' style='position: relative'>
   <noscript><a href='#'><img alt='% of U.S. adults who say they ever use …(kind of shrinking platforms with slow growth) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;so&#47;socialmediausers&#47;Sheet3&#47;1_rss.png' style='border: none' /></a></noscript>
   <object class='tableauViz'  style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
      <param name='embed_code_version' value='3' />
      <param name='site_root' value='' />
      <param name='name' value='socialmediausers&#47;Sheet3' />
      <param name='tabs' value='no' />
      <param name='toolbar' value='yes' />
      <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;so&#47;socialmediausers&#47;Sheet3&#47;1.png' />
      <param name='animate_transition' value='yes' />
      <param name='display_static_image' value='yes' />
      <param name='display_spinner' value='yes' />
      <param name='display_overlay' value='yes' />
      <param name='display_count' value='yes' />
      <param name='language' value='zh-CN' />
   </object>
</div>
<script type='text/javascript'>                    var divElement = document.getElementById('viz1739412057523');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>


These graphs are line and area visualization that illustrates the percentage of U.S. adults who report using various social media platforms as time goes. The purpose of these graphs is to provide a clear overview of three groups of social media platform usage among U.S. adults, representing the rise and fall.

**3) One of the demographics stacked bar chart:**
<div class='tableauPlaceholder' id='viz1739418968371' style='position: relative'>
   <noscript><a href='#'><img alt='% of U.S. adults who say they ever use __ by Age ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_17394189575970&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript>
   <object class='tableauViz'  style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
      <param name='embed_code_version' value='3' />
      <param name='site_root' value='' />
      <param name='name' value='Book1_17394189575970&#47;Sheet1' />
      <param name='tabs' value='no' />
      <param name='toolbar' value='yes' />
      <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_17394189575970&#47;Sheet1&#47;1.png' />
      <param name='animate_transition' value='yes' />
      <param name='display_static_image' value='yes' />
      <param name='display_spinner' value='yes' />
      <param name='display_overlay' value='yes' />
      <param name='display_count' value='yes' />
      <param name='language' value='zh-CN' />
      <param name='filter' value='publish=yes' />
   </object>
</div>
<script type='text/javascript'>                    var divElement = document.getElementById('viz1739418968371');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>


The graph is a stacked bar chart that illustrates the percentage of U.S. adults who report using various social media platforms by age groups. The purpose of the graph is to provide a comparative overview of social media platform usage among U.S. adults, emphasizing the relative age groups composed.

## References
"Data Visualization Effectiveness Profile", Stephen Few,*Perceptual Edge*, *Visual Business Intelligence Newsletter*, 2017.
