# Gunners

**Gunners** is a website dedicated to Arsenal Football Club. It is essentially a hub for the r/gunners [subreddit](https://reddit.com/r/gunners).


## UX

As I mentioned, I designed this site to be a hub for r/gunners. 

Reddit can be confusing if you're not a regular user- it can be hard to find the type of content that interests you. I've recommended certain subreddits to my friends, but they have struggled with the navigation of the website. 

The goal of this project is to bridge the gap between the subreddit's community and the wider *Arsenal-supporting* community by showcasing some of it's top content and providing links to certain parts of reddit which user's may be interested in.

This website isn't exclusively a hub for r/gunners however, as there are a number of other pages which provide information about various aspects around the club.


### User Stories:

* As an Arsenal fan, I want to have everything I need to know about the club all in the same place.
* I'd like a browser homepage that relates to my interest in Arsenal and gives me a shortcut to useful info such as upcoming fixtures.
* I'm not necessarily a reddit user, however I enjoy some content especially in regards to Arsenal; I'd like to have a streamlined version of r/gunners with which I can easily find some of the more significant posts.
* I **am** a reddit user, and also an Arsenal fan. Reddit can be overwhelming & distracting sometimes; I'd like a shortcut to my favorite subreddit so I don't end up spending more time on the site/app than I plan to.



This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

## Features

### Existing Features:

1. **Homepage** - Acts as a streamlined [r/gunners](https://reddit.com/r/gunners). Contains embedded posts from reddit and an embedded widget with the entire subreddit.
2. **Homepage links** - Contains non-embedded links to other subreddits, and a link for non-users to sign up and join reddit.
3. **Fixtures page** - Contains a list of upcoming fixtures for the 20/21 season.
4. **Squad page** - Contains a list of players in the current squad.
5. **Official Footer** - Contains links to the clubs official channels (Website, Social media), as well as links to official merchandising.
6. **Our Friends page** - Contains links to other Arsenal fan projects, such as *AFTV* and *Arseblog*.

### Scrapped Features:

1. **Official page** - Contains links to the clubs official channels (Website, Social media), as well as links to official merchandising. Felt archaic; decided to replace it with a footer on every page which serves the same purpose.

### Features Left to Implement

* **News / Transfers** - In the future i'd like to implement a regularly updated news / transfers page.

## Technologies Used

* **HTML** - Used to structure my website
* **CSS** - Used to style/design my website

I used code from the following websites:

* **Reddit.com** - I embedded 6 posts directly from reddit.com/r/gunners
* **Redditjs.com** - I embedded a widget from Redditjs in order to have a mini version of r/gunners on my homepage.





### Testing

#### Validator issues

* I learned that <h(1-6)> & <ul> elements cannot exist inside span elements because they are block-level & inline element respectively. To fix this, I changed <span> elements to <div>.


#### Manual tests

* All external links are working as expected; all direct to a new tab, no broken links.

* Navigation bar is fully functional- Hover & Active work fine.

* All images are available from their URL sources, all contain alt attribute.

* Responsive; every page is compatible with both Mobile & Tablet screens.

* Embedded content; all embedded content on index.html works as expected.


#### Issues

* Embedded files on index.html take a while to load; not too long but noticable.

* *Top posts of the month* section on index.html has to be manually updated with new embeds every month / as often as needed (whenever there are more highly rated posts within that timeframe)


#### User stories / Evidence

![Screenshot 1](https://ibb.co/Z82MDfr "streamlined version of reddit")
![Screenshot 2](https://ibb.co/4JVKztw "info about the club; fixtures")
![Screenshot 3](https://ibb.co/t3wfmX3 "info about the club; squad")
![Screenshot 4](https://ibb.co/mNd2pvs "info about the club; related sources")
![Screenshot 5](https://ibb.co/sFHY9fK "mobile compatible")
![Screenshot 6](https://ibb.co/yNqZnjS "tablet compatible")


### Deployment
I deployed this website through the Github repository by going to settings and selecting the *master* branch for Github Pages.
The deployed version of my website seems to be fully functional; there are no differences between deployed page and development page.

### Credits

#### Images used in my website were obtained from:

* Logo - r/gunners logo obtained from https://twitter.com/rslashgunners

* Hero image - obtained from https://thefa.com

* Squad images - obtained from https://www.premierleague.com/clubs/1/Arsenal/squad

* AFTV logo - obtained from https://aftvstore.com

* Arseblog logo - obtained from https://podcasts.apple.com

* Handbrake off logo - obtained from https://theathletic.com

* Pain in the arsenal logo - obtained from https://paininthearsenal.com

#### Content

The embedded content on index.html are from https://reddit/r/gunners (Top posts of the months) and from https://redditjs.com (Reddit widget which has a more robust version of r/gunners)

#### Acknowledgement

This project was directly inspired by r/gunners and by Arsenal Football Club in general.

