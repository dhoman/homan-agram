initial gibberish


This project doesn't work yet,

give me time. I'll keep y'all posted

but the idea is that you create posts in the posts folder
and the json data in each of the posts subfolder will be the metadata to make the post, albumn, etc, the only additional attribute will be a *post_at* attribute which will (when index.js is called (or might be moved into a separate post.js file)) will post any new items in the posts folder which haven't already been posted and the *post_at* has passed, (so you can schedule stuff in the future and be sure it won't be posted until the post_at time has passed) And allowing you to schedule this as a cron task (if that's your stick)