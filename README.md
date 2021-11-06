# needadog
a gift for my partner. a web app that gets you the precise amount of dogs that you need to see right now. 

# Structure & Drafting 
will utilize Dog API to browse by different dog breeds and then prompt user to select the number of dogs that they wish to see 
  - there will be a few different ways to structure the display of the API response data. 
    - some of it can be used for the menu structure of the site to find the KIND of dogs that should be displayed 
    - a secondary API call may be needed to get back to specific amount of dogs. This can be done once the user is on the viewing page

### Landing Page 
  - header 
    - nav links 
    - tip jar 
    - maybe leads to the site map since we won't want one at the bottom?
  - welcome message 
  - what it is 
  - get started prompt 

### Breed selection 
  - pop up prompted at arrival of URL 
  - breed list based on API hit to get back breeds 
     - will pass URL modifier based on the link selection (onCLick formula) 
 
 ### view page 
  - pop up asking how many dogs they need to see 
  - second API hit to the URL to get back that many dogs 
  - scrollable list of images (and other information that may be included in photo meta data) 
