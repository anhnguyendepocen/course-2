# MACS 40700 - Data Visualization (Spring 2018)

|  | [Dr. Benjamin Soltoff](http://www.bensoltoff.com/) | Emma Peterson (TA) |
|--------------|----------------------------------------------------|-------------------------------------------------------------|
| Email | soltoffbc@uchicago.edu | ecpeterson@uchicago.edu |
| Office | 209 McGiffert House | MACSS Office Suite, McGiffert House |
| Office Hours | Th 1-3pm | Tu 2-4pm |
| GitHub | [bensoltoff](https://github.com/bensoltoff) | [emmacooperpeterson](https://github.com/emmacooperpeterson) |

* **Meeting day/time**: Tu 11:00-1:50pm, Saieh Hall, Room 247
* Office hours also available by appointment

## Course description

Social scientists frequently wish to convey information to a broader audience in a cohesive and interpretable manner. Visualizations are an excellent method to summarize information and report analysis and conclusions in a compelling format. This course introduces the theory and applications of data visualization. Students will learn about theory of cognition and perception in order to understand how humans process and synthesize information in a visual medium, while also developing techniques and methods for generating rich, informative, and interactive visualizations for both data exploration and explanation. These techniques will be developed using software implementations in [R](https://www.r-project.org/).

### Prerequisites

Students are expected to have prior programming experience; this is not an introductory programming course and students without this experience will have significant difficulties keeping up with the material. Experience could come from completion of [MACS 30500 - Computing for the Social Sciences](http://cfss.uchicago.edu/), an alternative course on programming at UChicago or undergrad, or self-taught experience using R. Students should also be familiar with the [Git version tracking system](https://git-scm.com/) and be comfortable with the Git workflow (commit, push, pull, merge, etc.). Finally, some basic experience with probability/statistical theory (especially regression analysis) will be helpful, though not required.

## Grades

| Assignment | Points |
|------------------|--------|
| Visualization critique | 10 |
| Visualization experiment | 20 |
| Interactive visualization | 20 |
| Geospatial/network/text visualization | 10 |
| Final project | 30 |
| Participation | 10 |
| **Total Points** | 100 |

## Disability services

If you need any special accommodations, please provide us with a copy of your Accommodation Determination Letter (provided to you by the Student Disability Services office) as soon as possible so that you may discuss with me how your accommodations may be implemented in this course.

## Readings

Readings for the course will come primarily from the following books, as well as an assortment of journal articles:

* **TA** - [Cairo, Alberto. *The Truthful Art: Data, charts, and maps for communication*. New Riders, 2016.](http://proquestcombo.safaribooksonline.com.proxy.uchicago.edu/book/databases-and-reporting-tools/9780133440492)
* **FA** - [Cairo, Alberto. *The Functional Art: An introduction to information graphics and visualization*. New Riders, 2012.](http://proquestcombo.safaribooksonline.com.proxy.uchicago.edu/book/graphic-design/9780133041187)
* **Munzer** - Munzner, Tamara. *Visualization analysis and design*. CRC Press, 2014.
* **R4DS** - [Wickham, Hadley and Garrett Grolemund. *R for Data Science*. O'Rielly Media, Inc., 2017.](http://r4ds.had.co.nz/)

> I recommend you purchase a copy of TA. R4DS is available for free online, however you can also purchase a hard-copy if you prefer that medium. TA and FA are also available as ebooks through the UChicago library (follow the links above, authentication required).

## Course schedule

| # | Date | Topic A | Topic B | Due dates |
|-----|---------|-------------------------------------------------------|-----------------------------------|------------------------------------------------------|
| 1. | Mar. 27 | Introduction to data visualization | Principles of data visualization |  |
| 2. | Apr. 3 | Design and evaluation | Grammar of graphics and `ggplot2` |  |
| 3. | Apr. 10 | Science, art, or somewhere inbetween | More `ggplot2` | [Viz critique](assignments/critique-grammar.md) |
| 4. | Apr. 17 | Graphical perception and cognition | Design a visualization experiment |  |
| 5. | Apr. 24 | Rules of thumb | Visualizing scientific results |  |
| 6. | May 1 | Interactivity | And more interactivity | [Viz experiment](assignments/experiment.md) |
| 7. | May 8 | ~~And even more interactivity~~ | ~~Information dashboards~~ |  |
| 8. | May 15 | And even more interactivity | Network visualization |  |
| 9. | May 22 | Geospatial visualization | Text visualization | [Interactive graphics](assignments/interactivity.md) |
| 10. | May 29 | Present [final project](assignments/final-project.md) |  | [Geospatial/network/text viz](assignments/geowxt.md) |
|  | June 3 |  |  | Submit [final project](assignments/final-project.md) |

## References and Readings

All readings are required unless otherwise noted. Adjustments can be made throughout the quarter; be sure to check this repository frequently to make sure you know all the assigned readings.

1. Introduction to data visualization/Principles of data visualization
    * TA Ch 1, 2, 5
1. Design and evaluation/Grammar of graphics and `ggplot2`
    * TA 2-4
    * Visualizations to critique in-class on Tuesday
        * [Earth Temperature Timeline](https://xkcd.com/1732/)
        * [Gun Deaths in America](https://fivethirtyeight.com/features/gun-deaths/)
        * [Marriage](https://xkcd.com/1431/)
        * [The Paper Mountain](http://www.nature.com/news/the-top-100-papers-1.16224)
        * [Trump popularity](https://projects.fivethirtyeight.com/trump-approval-ratings/)
    * [Wickham, Hadley. "A layered grammar of graphics." *Journal of Computational and Graphical Statistics* 19.1 (2010): 3-28.](http://www-tandfonline-com.proxy.uchicago.edu/doi/abs/10.1198/jcgs.2009.07098)
    * [R4DS Ch 1-3](http://r4ds.had.co.nz/)
1. Science, art, or somewhere inbetween/Exploratory data analysis
    * [Ch 4-5 in *The Visual Display of Quantitative Information* by Edward Tufte.](https://canvas.uchicago.edu/courses/15305/files?preview=1426507)
    * FA Ch 3 - focus on pg. 61-72
    * [Gelman, Andrew, and Antony Unwin. "Infovis and statistical graphics: different goals, different looks." *Journal of Computational and Graphical Statistics* 22.1 (2013): 2-28.](http://www-tandfonline-com.proxy.uchicago.edu/doi/full/10.1080/10618600.2012.761137)
    * [Wickham, Hadley. "Graphical criticism: some historical notes." *Journal of Computational and Graphical Statistics* 22.1 (2013): 38-44.](http://www-tandfonline-com.proxy.uchicago.edu/doi/full/10.1080/10618600.2012.761140?src=recsys)
    * [Bateman, Scott, et al. "Useful junk?: the effects of visual embellishment on comprehension and memorability of charts." *Proceedings of the SIGCHI Conference on Human Factors in Computing Systems*. ACM, 2010.](http://www.cedma-europe.org/newsletter%20articles/misc/The%20Effects%20of%20Visual%20Embellishment%20on%20Comprehension%20and%20Memorability%20of%20Charts.pdf)
    * TA Ch 6-7
    * [R4DS Ch 5, 7](http://r4ds.had.co.nz/exploratory-data-analysis.html)
1. Graphical perception and cognition
    * FA Ch 5-7
    * [Cleveland, William S., and Robert McGill. "Graphical perception: Theory, experimentation, and application to the development of graphical methods." *Journal of the American statistical association* 79.387 (1984): 531-554.](http://www.jstor.org.proxy.uchicago.edu/stable/2288400)
    * [Heer, Jeffrey, and Michael Bostock. "Crowdsourcing graphical perception: using mechanical turk to assess visualization design." *Proceedings of the SIGCHI Conference on Human Factors in Computing Systems*. ACM, 2010.](http://dl.acm.org.proxy.uchicago.edu/citation.cfm?id=1753357&CFID=745610279&CFTOKEN=53601915)
    * [Spence, Ian, and Stephan Lewandowsky. "Displaying proportions and percentages." *Applied Cognitive Psychology* 5.1 (1991): 61-77.](http://onlinelibrary.wiley.com.proxy.uchicago.edu/doi/10.1002/acp.2350050106/abstract;jsessionid=E21007114F95498B3EA95F35DD6A21BF.f03t04)
1. Rules of thumb/Visualizing scientific results
    * TA Ch 8-9
    * [Using Graphs Instead of Tables in Political Science](http://www.jstor.org.proxy.uchicago.edu/stable/20446574?seq=1#page_scan_tab_contents)
    * [visual battle: table vs graph](http://www.storytellingwithdata.com/blog/2011/11/visual-battle-table-vs-graph)
    * [Why tables are really much better than graphs](http://andrewgelman.com/2009/04/01/why_tables_are/)
    * [Siegrist, Michael. "The use or misuse of three-dimensional graphs to represent lower-dimensional data." *Behaviour & Information Technology* 15.2 (1996): 96-100.](http://proxy.uchicago.edu/login?url=http://search.ebscohost.com/login.aspx?direct=true&db=iih&AN=7613951&site=ehost-live&scope=site)
1. Interactivity
    * [Plotly R library](https://plot.ly/r/)
    * [`htmlwidgets`](http://www.htmlwidgets.org/)
    * [Shiny by RStudio](https://shiny.rstudio.com/)
    * [Building Shiny Apps](http://cfss.uchicago.edu/shiny001_abc.html)
1. ~~Interactivity/information dashboards~~
1. Information dashboards/Network visualization
    * [`flexdashboard`](http://rmarkdown.rstudio.com/flexdashboard/)
    * Munzner ch 9
    * [Andris, Clio, et al. "The rise of partisanship and super-cooperators in the US House of Representatives." *PloS one* 10.4 (2015): e0123507.](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0123507)
1. Geospatial visualization/text visualization
    * TA Ch 10
    * [Cartographers for social equality](https://www.youtube.com/watch?v=vVX-PrBRtTY)
1. Final project presentations
