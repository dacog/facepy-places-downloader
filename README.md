# facepy-places-downloader

Playing with facepy + Facebook Graph API + other modules to get a list of places and save them to a csv file.

You can get your token at [https://developers.facebook.com/tools/explorer/2401807843381964?method=GET&path=type%3Dplaces%3Ffields%3Did%2Cname&version=v3.2]() after you create an app at [https://developers.facebook.com]()

**Disclaimer: use it under your own risk**

The code pauses to prevent limit error from facebook. AFAIK 600 queries per 600 seconds.