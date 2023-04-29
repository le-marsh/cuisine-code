# cuisine-code
This is my project to generalise cuisines using my favourite recipe site recipetineats.com.

The project is based around two steps - scraping all the recipes from the website, then perfoming association rule mining on the recipes. 

The scraping file is not included in the repo as I don’t really want to encourage people to scrape the website incase it gets overloaded with traffic.

I have done all the scraping anyway and saved the outputs in a series of csvs with are included - this way if anyone wants to expand on the association rule mining I’m doing they can do it without adding extra pressure on the site.

The association rule mining groups the recipes by cuisine (e.g. Chinese, Italian etc.) and then examines the likelihood of one ingredient existing, given the presence of another ingredient.

It outputs a csv with the top five or so flavours that are commonly combined in each cuisine, along with the ratios. This way you can make a generic {cuisine} tasting dish without using a recipe.
 