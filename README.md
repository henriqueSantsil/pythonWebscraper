# Python WebScraper NBA

A simple WebScraper with python that save some statistics of NBA season in JSON archive

## Libraries

To run this project, you will need to download the following libraries 

`Pandas`
`requests`
`bs4`
`selenium`


## Lessons learned and comments

While building this project, i ran against a lot of versioning problems, mainly because of the date that the tutorial i was following was published (https://www.youtube.com/watch?v=Vxl5jUltHBo&t=352s&ab_channel=C%C3%B3digoFonteTV), for example my python version was a bit ahead and some functions like "find_element" from selenium got updated and i had to check some stackoverflow comments. Luckly, jupyter notebook (at least the web version), made my jorney easier due to the libs like pandas that already has in it (but if you're trying to run this project in another environment you might give a check on your python and libs versions). 

Another issue i had to deal with, was the "accept or reject cookies" pop-up which the tutorial didn't predict, but that one was quite simple with the "find_element" from selenium (you might want to check this part too, specifically on the "time.sleep()" amount of time, depending on your internet connection, the time you will need to run the steps can be longer or shorter).


