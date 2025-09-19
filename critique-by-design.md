| [home page](https://sachi1406.github.io/sachi-shah-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# What Does 1GB of Mobile Data Cost in Every Country?

## Step one: the visualization
_Original Visualization:_ Visual Capitalist’s “Cost of Mobile Data Worldwide.” (https://www.visualcapitalist.com/cost-of-mobile-data-worldwide/)

I selected this visualization because while it is visually engaging and artistic, it prioritizes aesthetics over clarity. The circular, map-like structure looks appealing, but it makes it difficult to directly compare costs between countries or regions. The reliance on vibrant design elements distracts from the data itself, and the variation across countries becomes harder to interpret. Since the data is important (global equity in digital access), I wanted to reimagine a design that emphasizes readability and fair comparisons.


## Step two: the critique
I completed Stephen Few’s **Data Visualization Effectiveness Profile** via the Google form provided.  
Key takeaways:  
- **Strengths**: eye-catching, designed to spark interest, global scope covered.  
- **Weaknesses**:  
  - Difficult to compare values between countries because of the circular radial design.  
  - Color scale is not intuitive, making it harder to read differences at a glance.  
  - Small text and layout cause accessibility issues.  
- **Audience fit**: Good for a general audience interested in eye-candy visuals, but less effective for policymakers, researchers, or people wanting to understand the disparities precisely.  

Compared to the **Good Charts method**, Few’s framework felt more systematic and diagnostic. Good Charts emphasizes storytelling and the "why", while Stephen Few provides clearer heuristics for diagnosing readability and design flaws. Together, they complement each other.

## Step three: Sketch a solution
Here’s my rough sketch of a redesign:
<img width="1098" height="726" alt="image" src="https://github.com/user-attachments/assets/f7a50505-df58-4676-a3fe-6095719b5246" />

<img width="1082" height="670" alt="image" src="https://github.com/user-attachments/assets/4d79347d-eb06-443d-b2a0-94b6dbb10433" />

Design idea:  
- **Choropleth map** using a sequential color ramp to show cost per GB across countries.  
- **Bar chart** highlighting the **top 10 most expensive** and **bottom 10 cheapest** countries for easy side-by-side comparisons.  

This redesign focuses on clarity and easy cross-country comparison without sacrificing context.


## Step four: Test the solution

The main pattern in the feedback was that users found the **map more interesting than the bar chart** for direct comparisons. The map provided good global context, while bar chart gave precise takeaways. Based on this, my redesign kept **both map and bar chart**, with a focus on simplifying the color scheme and adding clearer labeling.

## Step five: build the solution

Here is my final redesign (built in Tableau):  

<div class='tableauPlaceholder' id='viz1758253972830' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;Dataviz_Redesign&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Dataviz_Redesign&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;Dataviz_Redesign&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1758253972830');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1366px';vizElement.style.height='795px';} else if ( divElement.offsetWidth > 500 ) 
  { vizElement.style.width='1366px';vizElement.style.height='795px';} else { vizElement.style.width='100%';vizElement.style.height='877px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

## References
- Visual Capitalist. (2023). *Cost of Mobile Data Worldwide*. [Link](https://www.visualcapitalist.com/cost-of-mobile-data-worldwide/)  
- Few, S. *Data Visualization Effectiveness Profile*.  
- MakeoverMonday. [https://makeovermonday.co.uk](https://makeovermonday.co.uk)

## AI acknowledgements
AI tools (ChatGPT) were used to help phrase my critique ideas, polish written explanations and tableau steps for some conditions
