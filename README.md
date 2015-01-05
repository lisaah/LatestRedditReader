Latest Reddit Reader
====================

Show the best of the latest posts in a reddit thread.

A Javascript implementation based off of <a href="https://github.com/NosajGithub/game_comment_scraper">game_comment_scraper</a> (Python). Uses <a href="https://github.com/sahilm/reddit.js">reddit.js</a> as the Reddit API wrapper.

Displays the top 5 (best) of the latest 200 (new) posts. Caches comments so you don't see the same post twice.

Should work out of the box, but your mileage may vary.

Usage
====================

The reader needs to the know the subreddit you're in and the thread you're on. You can supply this manually and select "Update". Or, put the entire thread link and select "Parse" and that should hopefully populate the necessary fields. Then you can click "Update" as per usual to get updates.