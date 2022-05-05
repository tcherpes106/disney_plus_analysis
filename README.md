# disney_plus_analysis

Project Name: disney_plus_analysis

------------------------------

Project Objective: See what type of content could be added to the Disney+ catalog to see an uptick in subscriptions to the site.

What problem are you solving? - Disney+, while a big player in the streaming space, has seen less growth recently in terms of 
  subscriptions - I wanted to see what type of content could be added to the site to rope in new customers.
  
How are you solving this problem? - By using the IMDb Top 250 movies list and Rotten Tomatoes Top 100 movies list as my reference,
  I looked to see what type of content was highly rated to see if Disney+ had the same type of content within the site.
  
------------------------------
  
Job Description: I selected a Data Analyst position withhin the Disney company that was geared towards the 
  Disney Streaming Engagement & Retention Analytics team. This role supports Disney’s streaming services
  through measurement, analysis, and insight generation. These analysts focus on helping our
  subscribers get the most value out of our services, and improving business results through the
  combination of statistical rigor, data analysis, and fast paced execution with an emphasis on driving
  actionable business recommendations.
   
  This project allowed me to provide business recommendations by seeing the areas where the Disney+ catalog was lacking.
  
------------------------------

Data: I pulled my data from 3 main web scrapes

  Disney: 'https://www.cordcuttersnews.com/disney-plus-movies-and-shows-list/'
    This source, while not completely up to date, had the data I needed from the Disney+ catalog - Since the Disney+ site
    makes it very hard to gather data, I had to look to other sources.
    
  IMDb: 'https://www.imdb.com/chart/top/?ref_=nv_mv_250'
    A list of the top 250 rated movies on IMDb.
    
  Rotten Tomatoes: 'https://www.rottentomatoes.com/top/bestofrt/'
    A list of the top 100 rated movies on Rotten Tomatoes.
    
------------------------------

Notebooks:
data_collection.ipynb - https://github.com/tcherpes106/disney_plus_analysis/blob/main/data_collection.ipynb
This notebook was used to gather the data necessary for the project and add it to a database.

sql_analysis.ipynb - https://github.com/tcherpes106/disney_plus_analysis/blob/main/sql_analysis.ipynb
This notebook was used to run analysis on the data using sql queries.

presentation.ipynb - https://github.com/tcherpes106/disney_plus_analysis/blob/main/presentation.ipynb
This notebook is a combined version of the previous two with the addition of the recording link.

------------------------------

Future Improvements:
1. If I had more time, I would have liked to add more data such as directors, actors, and movie runtime to do
  further analysis.
2. I would have also liked to find cleaner sources to gather my data from, there was a lot of extra cleaning and 
  and adding to do. For the ratings and genres, I couldn't reliably find a source, so I had to manually input those.

