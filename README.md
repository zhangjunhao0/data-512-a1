# The project
The purpose of this project is to process and analyze Wikipedia traffic dataset and practice reproducibility of research. We use the following articles as guidelines of reproducibility.

## Data Source
For this project we use Wikipedia flow traffic data using API from the Wikimedia REST API, Wikimedia Foundation, 2017. CC-BY-SA 3.0. Terms and conditions can be found here: https://www.mediawiki.org/wiki/Wikimedia_REST_API#Terms_and_conditions.
Pagecounts API: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts
Pageviews API: https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews

Note that for PageCounts API, web crawler and spiders cannot be filtered out as it is older. However, they are filtered out for Pageviews API.

## Data Description
Column
year: the year of counting Wikipedia page views, aggregated together with month. In format YYYY.
month: the month of counting Wikipedia page views, aggregated together with month. In format MM.
pagecount_all_views: total views (desktop and mobile) returned by the pagecount API
pagecount_desktop_views: total views accessed by desktop returned by the pagecount API
pagecount_mobile_views: total views accessed by mobile returned by the pagecount API
pageview_all_views: total views (desktop and mobile) returned by the pageview API
pageview_desktop_views: total views accessed by desktop returned by the pageview API
pageview_mobile_views:  total views accessed by mobile (including mobile web and mobile app) returned by the pageview API

## Visualization
We only perform a visualization as data analysis. It plots the traffic over time. For code see A1.ipynb, and for final visualization, see analysis.png.
