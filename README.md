# Glacier shrinkage in the Alps

This is my entry to the **Little Pictures of climate competition 2023**, organized
by ESA at https://climate.esa.int/en/littlepicturescompetition/.

## Source paper

> "Glacier shrinkage in the Alps continues unabated as revealed by a new glacier inventory from Sentinel-2"  
> https://essd.copernicus.org/articles/12/1805/2020/  
> https://doi.org/10.5194/essd-12-1805-2020

## Source dataset

> https://doi.pangaea.de/10.1594/PANGAEA.909133

## How I made it

The 2019 paper by Paul et al. is a detailed inventory of all glaciers in the
Alps.
I initially experimented with various visualizations of all 4395 glacier
footprints but this amount of information proved difficult to work with and not
really compatible with the minimalistic style of little pictures.

I quickly realized that the massive scale of glacier shrinkage could simply be 
represented with just two shapes with areas proportional to the glacier surface
area remaining today, and the surface area lost since 2003.

Between the two surveys of the paper, 15% of total surface area has been lost.
This means that the melted area is equal to (1/0.85 - 1)  = 18% of the
remaining surface area.

I drew by hand through trial and error a vector shape representing abstractly
the Alps mountain range, and a droplet.
I then adjusted the relative size of the two shapes until the droplet area was
18% of the Alps area.

Choosing the date to display in the subtitle was difficult because the team used
several data sources around 2015/2016.
In the end I decided to pick 2003 - 2016 as the date range, but I have to admit
this is not as precise as it looks due to the reality of the time it takes to
process such dataset.

I choose the colors using color palette tools and my own judgment after a lot of
subtles changes and attempts.  I added a small linear gradient to both shapes to
give some depth and some
illusion of a small lighting effect.

I played with the positioning of both shapes for a while, and ended up with this
final position once I accidentally noticed it looked kinda like a human face wearing a hat.

I wrote the footer by reading the original paper, paraphrasing, simplifying the
words and trying to say as much as possible as simply as possible.

Finally I exported the vector shapes to svg and used html and css to add the
footer with a pleasing typographic design.

## HTML rendering

* [glacier shrinkage in the Alps](index.html)

## PNG exports

* [800x1032](esalp-glacier-shrinkage-alps-800x1032.png)
* [1000x1290](esalp-glacier-shrinkage-alps-1000x1290.png)
* [1200x1548](esalp-glacier-shrinkage-alps-1200x1548.png)
* [1600x2064](esalp-glacier-shrinkage-alps-1600x2064.png)
