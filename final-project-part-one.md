| [home page](https://sachi1406.github.io/sachi-shah-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# The Price of Fun: Why Entertainment is Becoming a Luxury

# Outline
## High-Level Summary  

Entertainment has always been a reflection of culture, joy, and togetherness. From school picnics at theme parks to family movie nights and concerts with friends, “fun” is deeply embedded in our memories. Yet in recent decades, the cost of this fun has skyrocketed. A movie ticket that cost around $5 in 1980 now averages close to $15, while the price of attending a Taylor Swift concert can match a week’s groceries, and a Disney World trip can rival a month’s rent.  

This project, The Price of Fun, explores how the cost of leisure activities – movies, concerts, and theme parks – has changed over time. We ask: *“Why does it cost so much more to have fun now?”*  

Using public data sources, we will track changes in ticket prices (adjusted for inflation and wages), uncover which form of fun has risen the fastest, why, and explore what these trends reveal about cultural priorities. We will contextualize the data with personal anecdotes and cultural shifts: from streaming’s rise to the “experience economy,” to show how fun has moved from being a regular activity to a luxury.  

Our story arc begins with nostalgia (the affordable fun of the past), moves through data-driven analysis (visualizing rising costs across decades), and ends with reflection (is fun now a luxury?).  

 

## Project Structure (Story Arc)  

<img width="500" height="403" alt="image" src="https://github.com/user-attachments/assets/9400b99f-f2f9-414d-a227-b2a24b4e493a" />

1. *Nostalgia + Relatability*  
   The story begins on a joyful note, recalling childhood memories of affordable fun: school picnics, family movie nights, first concerts. This sets the emotional hook: fun once felt accessible to everyone.  

2. *Rising Prices*  
   As we introduce data, the line dips: movie tickets, concerts, and theme parks have steadily risen in cost. What was once a few dollars now feels like a serious purchase, and the audience begins to feel the weight of change.  

3. *Cultural Shift*  
   The curve rises slightly as we zoom out: entertainment itself has evolved. Streaming replaces theaters, and Disney mega-resorts overshadow local fairs. This neutral zone explains that rising costs aren’t just about inflation — they’re tied to how culture values “bigger” experiences.  

4. *Affordability*  
   The emotional low point comes when we compare prices to wages. Hours of work are needed for a single ticket, especially for concerts and parks. Here, fun becomes less a regular habit and more a luxury item.  

5. *Fun Budget / Reflection*  
   The curve lifts again as the story closes with reflection and interactivity. Readers are asked: How would you spend $100 on fun today? The resolution is not a return to full happiness, but a thoughtful acknowledgment that choices about fun are more constrained than ever.  



## Initial sketches
- *Timeline Line Graphs (1980–2025):* ticket (total of all 3 categories) price trends
  <img width="1171" height="499" alt="image" src="https://github.com/user-attachments/assets/586e3fa6-0bf1-4eb0-808c-2345e16d7033" />

- *Inflation Prices vs Actual Prices:* how actual price is higher than the inflation-adjusted price
  <img width="798" height="420" alt="image" src="https://github.com/user-attachments/assets/a3071214-b372-47df-9c73-6b02f8af26c2" />

- *Affordability Index Bar Chart:* hours of minimum wage required per ticket  
  Which form of fun has become least affordable? (e.g., concerts skyrocketing faster than inflation)
  <img width="1153" height="593" alt="image" src="https://github.com/user-attachments/assets/a649b49a-c20a-47a2-bb4f-18f54fa7bfaa" />

- *Disparity Slope Graph:* % increase since 1980 by category
  <img width="514" height="433" alt="image" src="https://github.com/user-attachments/assets/41a96090-cdca-4665-8af6-a4b808e95c85" />

- *Share of Household Spending:* how much does a household spend in each category
  <img width="855" height="481" alt="image" src="https://github.com/user-attachments/assets/c6107af8-8e50-4fba-8c18-80ac7dfcf2e0" />
 
- *Calculator Visualization (Interactive):* user birth year → then vs now ticket prices, current wage → number of tickets affordable per category
  <img width="874" height="558" alt="image" src="https://github.com/user-attachments/assets/d7f1918b-a271-4b33-98ee-c40c6974d879" />


# The data
> A couple of paragraphs that document your data source(s), and an explanation of how you plan on using your data. 

Text here...

> A link to the publicly-accessible datasets you plan on using, or a link to a copy of the data you've uploaded to your Github repository, Box account or other publicly-accessible location. Using a datasource that is already publicly accessible is highly encouraged.  If you anticipate using a data source other than something that would be publicly available please talk to me first. 

| Name | URL | Description |
|------|-----|-------------|
|      |     |             |
|      |     |             |
|      |     |             |

For this project, I will use publicly accessible datasets that track ticket prices for movies, concerts, and theme parks over time, alongside wage and inflation data for affordability analysis. These datasets are drawn from reliable and recognized sources such as UNESCO, OECD, the World Bank, and the U.S. Bureau of Labor Statistics. Together, they provide both global and U.S.-specific coverage going back several decades.  

The movie ticket datasets (UNESCO, NATO/The Numbers, and Kaggle) will help illustrate how cinema costs have changed over time, while concert ticket price data from Pollstar and CPI indices will highlight the sharp growth in live music costs. For theme parks, Disney’s historical ticket price archives and the BLS Producer Price Index will provide benchmarks for long-term changes. To calculate affordability, I will combine these entertainment cost datasets with OECD wage data and World Bank/BLS inflation indices to create metrics such as “hours of minimum wage per ticket.”  

These combined sources will allow me to compare real versus inflation-adjusted costs, highlight which category of fun has become least affordable, and tie those trends into larger cultural shifts. All datasets are publicly accessible and can be exported in formats compatible with Tableau for visualization.  

| Name | URL | Description |  
|------|-----|-------------|  
| UNESCO Institute for Statistics – Feature Films Dataset | [Link](https://datafinder.qog.gu.se/dataset/une4#) | Global cinema dataset including admissions, box office, and average ticket prices (1970s–present). |  
| NATO (Cinema United) / The Numbers – U.S. Movie Ticket Prices | [Link](https://www.the-numbers.com/market/) | Historical U.S. average ticket prices; widely cited industry data. |  
| Kaggle – Hollywood Theatrical Market Synopsis | [Link](https://www.kaggle.com/datasets/johnharshith/hollywood-theatrical-market-synopsis-1995-to-2021) | U.S. market dataset (1995–2021) including average ticket prices. |  
| Pollstar – Concert Ticket Price Index (coverage example) | [Link](https://www.alternativenation.net/metallica-u2-ticket-prices-are-unaffordable/) | Annual average prices for Top 100 worldwide tours, as summarized in industry reports. |  
| BLS Producer Price Index – Amusement & Theme Parks | [Link](https://www.bls.gov/ppi/factsheets/producer-price-index-introduced-for-amusement-and-theme-parks-naics-713110.htm) | Tracks changes in theme park admission charges (2006–present). |  
| AllEars.net – Walt Disney World Ticket Price History | [Link](https://allears.net/walt-disney-world/wdw-planning/walt-disney-world-ticket-price-increase-history/) | Chronology of Disney World ticket price increases, freely accessible. |  
| OECD – Average Annual Wages by Country | [Link](https://data.oecd.org/earnwage/average-wages.htm) | Wage data by country in constant USD PPP, used for affordability comparisons. |  
| World Bank – Consumer Price Index (2010=100) | [Link](https://data.worldbank.org/indicator/FP.CPI.TOTL.ZG) | Global CPI data for converting nominal ticket prices to real prices. |  
| U.S. BLS CPI Sub-Index – Admissions to Movies, Theaters, Concerts | [Link](https://www.bls.gov/cpi/) | U.S. inflation index specific to entertainment admissions. |

# Method and medium
- *Medium:* A full interactive website published on GitHub Pages  
- *Tools:* Tableau (interactive charts), Shorthand or custom HTML for narrative flow, optional Python for calculator widget  
- *Structure:* Linear story with embedded visuals, personal callouts, and interactive elements  
- *Output:* A polished, public-facing project titled: “The Price of Fun: Why Entertainment is Becoming a Luxury”  

## References
The following sources were reviewed during the project for context, background information, and supplementary insights. While they were not used directly in the final dataset table, they informed framing, historical context, and validation of the trends presented.  

- American TV. Cost of a Movie Ticket in Each State.  
  [https://www.americantv.com/cost-of-a-movie-ticket-in-each-state.php](https://www.americantv.com/cost-of-a-movie-ticket-in-each-state.php)  

- MickeyVisit. Disneyland Ticket Price Increases (2014–2024).  
  [https://mickeyvisit.com/disneyland-price-increases/](https://mickeyvisit.com/disneyland-price-increases/)  

- Alternative Nation. Average Concert Ticket Price in 2024 ($135.92, +41% since 2019).  
  [https://www.alternativenation.net/metallica-u2-ticket-prices-are-unaffordable/](https://www.alternativenation.net/metallica-u2-ticket-prices-are-unaffordable/)  

- Statista. Average Ticket Price for Concerts in the U.S. since 1990.  
  [https://www.statista.com/statistics/190140/average-us-ticket-price-for-concerts-since-1990/](https://www.statista.com/statistics/190140/average-us-ticket-price-for-concerts-since-1990/)  

- The Numbers. Historical Market Data for the U.S. Movie Industry.  
  [https://www.the-numbers.com/market/](https://www.the-numbers.com/market/)  

- Box Office Mojo. Movie Ticket Pricing Reports.  
  [https://www.boxofficemojo.com/about/](https://www.boxofficemojo.com/about/)  

These references are useful for validation, anecdotal context, and potential case studies (e.g., Taylor Swift resale markets, Disneyland pricing trends), though they were not treated as primary structured datasets for analysis.  


## AI acknowledgements
I used AI (ChatGPT) as a *writing and structuring assistant* for this assignment within the permitted course guidelines. Specifically, AI was used to:  
- Help brainstorm the *story arc structure* and align it with visual storytelling.  
- Reformat and *beautify Markdown sections* (Data tables, project summary, references) for readability and professionalism.  
