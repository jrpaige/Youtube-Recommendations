# Youtube Recommendation Patterns

> <i> [From the NY Times](https://www.nytimes.com/2019/08/11/world/americas/youtube-brazil.html) </i><br>
> <br>
> * A team at Harvard set to find out whether rise on the platform of certain topics were boosted by YouTube’s recommendation 
> engine. 
> * They programmed a server to enter a popular channel or search term, then open YouTube’s top recommendations, then follow the recommendations on each of those, and so on. 
> * By repeating this thousands of times, the researchers tracked how the platform moved users from one video to the next. 
> * They found that after users watched a video about politics or even entertainment, YouTube’s recommendations often favored right-wing, conspiracy-filled channels like Mr. Moura’s.


## Initial Goal

* Understand/Observe/Identify<br>
    * Algorithm/recommendations patterns <br>
    * Viewer infuence <br>
    * Common accounts/posters/users/categories recommended regardless of category
    * The probability of being recommended a video based on watching certain videos. <br>
   

## Hypotheses

<i>Youtube recommendation videos lead users to videos of longer length <br>
   Youtube recommendation videos lead users astray from the initial category within 10 subsequent recommendations.
   <br>
   Youtube recommendation videos present users with videos from repeat posters more than 3 times within 50 subsequent recommendations.  
</i>
<br>

---

# Scrape Details

## <u> Process </u>
* Use generic search terms to locate initial video recommendation
   * Disregard live videos, ad videos, Youtube Movies, Youtube Music, recommended channels, and "Top News" videos (not related to "Politics" or "News" 
* Pull information <br>
* Navigate to first recommendation/Allow autoplay<br>
* Repeat X 10/50/100

## </u> Search Terms </u> 
* Animation
* Music
* Pets
* Animals
* Sports
* Travel
* Gaming
* Health 
* Cooking 
* Comedy
* Politics
* Science Technology
* Nonprofit Activism 
* Beauty 
* Fashion


## <u>Video Details</u>
* Title
* Poster
* Poster’s number of subscribers
* Number of views
* Length
* Date Originally Posted
* Category 
* Number of Likes & Dislikes
* Top Recommended Video


---

# Statistics to Calculate
* Average number of comments/day
* Average length of youtube video
* Each video's length proportional to the average and to the last video played
* Video category at level 10/25/50
* How many recommended videos were longer than 10 minutes?
* How many videos were the same poster?

---    
    
# Youtube Categories
* Film & Animation
* Autos & Vehicles
* Music
* Pets & Animals
* Sports
* Travel & Events
* Gaming
* People & Blogs
* Comedy
* Entertainment
* News & Politics
* Howto & Style
* Education
* Science & Technology
* Nonprofits & Activism <br>

# Issues:
* Scraper
* Up Next vs Top Recommended 
* Random Videos vs Top Search Result

# Potential Next Steps:
<i>Thoughtful Queries </i>
* How often are the recommendation videos being clicked?<br>
* Positioning of videos
* Reccomendations watching all the way through vs web scraping with 5 second window 
