
# RVisuals

Welcome to RVisuals, a dedicated repository where I showcase a diverse
range of R visualizations that I have created. The primary focus of this
collection is on recreating and refining visuals that I find across the
internet or sharing inspiring visuals I created myself.

This not only presents me with engaging challenges but also provides a
valuable opportunity to learn and discover new R packages and coding
techniques. The idea for this repository came to me when i found a
reddit visual that sparked my interest.

## Reddit Cuisine Visual

The reddit visual that sparked my interest is what I call the ‘Reddit
Cuisine Visual’
<https://www.reddit.com/r/Infographics/comments/17houn9/chart_showing_how_much_or_how_little_a_country/>.
It shows the ranking of cuisines by people from countries. I first
wanted to see if i can recreate it all and then try to use other data to
make use the code I created for the visual. I did this by using data
from the European Championship.

You can find more on this topic in the markdown files within this
repository named Heatmap. See my final result below:

![](https://github.com/user-attachments/assets/ccf8db41-5d27-41cd-8833-a7f744bf119e)

## Leaflet Map with PDOK Package

I have been making maps with ggplot and ggiraph with cbs data for fun
but these maps are mainly summaries per region. I now wanted to also be
able to be more specific and showcase addresses and such. Therefore I
made a package around the PDOK geolocation service and cbs postal code
house number data. Check it out at:
<https://github.com/reijmerniek/PDOK/>. I used my package to find a
random address in amsterdam and find how many are within a 10km
distance. I then took 10 random addresses within this sphere and added
them to a leaflet map with distance calculations shown. See the picture
below as an example. Althought these examples are totally random you
could of course use this to a large extent to calculate real distances
for the whole Netherlands. You do have to note though that it does not
show apartment numbers etcetera, so in assuming population or such is
inaccurate without additional data.

![](https://github.com/user-attachments/assets/7c95c2b4-2a2f-4cf6-b02d-1dbc8bfe46a2)
