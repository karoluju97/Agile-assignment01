# Assignment 1 - Agile Software Practice.

Karol Uju Amajirionwu

## App Features.
 
+ Feature 1 - Continuous Integration - Integrated the project with both the Cypress Dashboard and Gitlab Pipeline.

![][cypressDashboard]
![][gitlabPipeline]

+ Feature 3 - Added new navigation testing and other testing files:

+ Navigation - Changed navigation tests to navigate via a dropdown menu. 

Tests: cypress/integration/navigation.spec.js 

![][navigation]

+ Home Page - Shows a list of movies to discover. Clicking the 'Add to Favorites' button will add it to the Favorite Movies page. Aside from the code from the labs, I added a test for adding movies to favorites.

Tests: cypress/integration/home-page.spec.js 

![][homepage]

+ Person Details Page - Shows detailed information on a TV Show.

Tests: cypress/integration/personDetails-page.spec.js 

![][personDetails]

+ Popular People Page - Shows a list of popular people. Clicking the 'Add to Favorites' button will add it to the Favorite Actors page.

Tests: cypress/integration/personPopular-page.spec.js 

![][personPopularList]

+ TV Airing Page - Shows a list of TV shows to be discovered. Clicking on any of the images will display a new page with TV show details. Clicking the 'Add to Watch List' button will add it to the TV watch list page.

Tests: cypress/integration/tvAiring-page.spec.js 

![][tvAiringList]

+ TV Details Page - Shows detailed information on a TV Show. Clicking the 'Show Reviews' button will display extracts from critic reviews.

Tests: cypress/integration/tvDetails-page.spec.js 

![][tvDetails]

+ TV Discover Page - Shows a list of TV shows to be discovered. Clicking on any of the images will display a new page with TV show details. Clicking the 'Add to Favorites' button will add it to the TV favorite's page.

Tests: cypress/integration/tvDiscover-page.spec.js 

![][tvDiscoverList]

+ TV Top Rated Page - Shows a list of Top Rated TV Shows. Clicking on any of the images will display a new page with TV show details. Clicking the 'Add to Watch List' button will not add it to the watch list page because of a bug.

Tests: cypress/integration/tvTopRated-page.spec.js 

![][tvTopRatedList]

+ Upcoming Page - Shows a list of upcoming movies. Clicking the 'Add to Watch List' button will add it to the watch list. 

Tests: cypress/integration/upcoming-page.spec.js 

![][upcomingMoviesList]

## Testing.

Cypress Dashboard URL: https://dashboard.cypress.io/projects/1z3idx/runs?branches=%5B%5D&committers=%5B%5D&flaky=%5B%5D&page=1&status=%5B%5D&tags=%5B%5D&timeRange=%7B%22startDate%22%3A%221970-01-01%22%2C%22endDate%22%3A%222038-01-19%22%7D

### Advanced Testing (If required).

+ None

## Independent learning (If relevant).

Implemented a react bootstrap dropdown menu to replace to default navbar menu. Added and implemented tests for it mainly in navigation.spec.js but it is also present in all test files. 

![][dropdownMenu]

https://react-bootstrap.github.io/components/dropdowns/

Github Link: https://github.com/karoluju97/Agile-assignment01/tree/master
GitLab Link: https://gitlab.com/KarolUju97/agile-assignment001

---------------------------------
[reviewLink]: ./public/rreview.png
[cardLink]: ./public/homepage.png
[upcomingMoviesList]: ./public/upcomingmovies.png
[moviesWatchList]: ./public/watchlist.png
[tvDiscoverList]: ./public/tvdiscover.png
[tvFavorites]: ./public/tvfavorites.png
[tvTopRatedList]: ./public/topratedtv.png
[tvAiringList]: ./public/tvairing.png
[tvWatchList]: ./public/watchlist.png
[tvDetails]: ./public/tvdetails.png
[tvReviews]: ./public/rrviews.png
[tvFullReview]: ./public/revviews.png
[personPopularList]: ./public/popularperson.png
[personFavorites]: ./public/favoriteperson.png
[personDetails]: ./public/persondetails.png
[dropdownMenu]: ./public/dropDown.png
[cypressDashboard]: ./public/cypressDashboard.png
[gitlabPipeline]: ./public/gitlab.png
[navigation]: ./public/navigation.png
[homepage]: ./public/homepage.png