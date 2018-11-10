# assignment-2-0-0

Our website is called "True North Travel".
4 different views:
1. Front entry video view
2. Main view with different sections
3. View with 9 choices
4. Modal with detailed information

The main goal for our website is to provide help when people have trouble planning a trip in Canada.

When users first enter the web, they will find an one-minute intro-video, showing the most beautiful views of Canada. After 7 seconds, the text "click to enter" fade in. 

For the header of "True North Travel", we include an navigation bar. It is made up by 5 parts, "Title", "Home", "About", "Search" and "Suggestion". "Title" will bring the whole page up to top. "Home" has similar function as "Title", in case when users don't know the "Title" is clickable.  When the users click on the rest of the parts, the website will scroll to corresponding sections. 

In the "Search" section, we have a 2-input search form. Users can type in any activity they want to do in Canada. If possible, they can also choose a province or territory as the desired destination. The default province is Ontario. So if user does not have a place in mind, we will display all the choices for their input activity in Ontario.

In the "Suggestion" section, there are 6 default activities. Each one will lead the page to display a new view containing 9 choices. If there are only few choices (less than 9) we get from Google Place api, we will display as much as we have. We apply a filter that will rank the results based on the rating, in non-increasing order. Also, if there is any place that does not fit the type of activity, we will delete it.

Finally, when user click on one of 9 choices on the page, we will show a modal with detailed informations. For instance, rating, address, bigger view of picture, a link to google map, etc. If user click on "Home" in navigation bar, it will direct it back to the main view. 
