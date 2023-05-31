# Twitter Reply Bot
Hey! Welcome to the Twitter Reply Bot repo where we go over how [@SiliconOracle](https://twitter.com/SiliconOracle) was made.

Check out the [video tutorial](https://youtu.be/yLWLDjT01q8)

This project was made for fun by [@GregKamradt](https://twitter.com/GregKamradt) to demonstrate the impact of Language Models

See jupyter notebook of prompt walkthrough [here](https://github.com/gkamradt/langchain-tutorials/blob/main/bots/Twitter_Reply_Bot/Twitter%20Reply%20Bot%20Notebook.ipynb)

## Deployment Steps
1. Create new Twitter Account for your bot (Note: You should set your bot account as [managed](https://help.twitter.com/en/using-twitter/automated-account-labels) by your company or personal account)
2. Get Twitter Developer API keys from https://developer.twitter.com/en/portal/dashboard (Note: Unfortunately you'll need the basic/paid tier for this bot to work)
3. [Optional] Create an Airtable account and create a personal access token - If you don't want to use airtable you can comment out references to it in the code.
4. [Airtable] If you choose to do logging (the default option) then you'll need to create an airtable table with the [columns here](https://github.com/gkamradt/twitter-reply-bot/blob/a8854dc96539c81a6e41d88990dea2030c081ac8/twitter-reply-bot.py#LL100C4-L100C4).
5. Close this github repo
6. Create railway account to host your code (or host whereever you want)
7. Add your [environment variables](https://github.com/gkamradt/twitter-reply-bot/blob/a8854dc96539c81a6e41d88990dea2030c081ac8/twitter-reply-bot.py#L15) to a .env file, your railway app, or whereever you host your app
8. Deploy and run!

The MIT License (MIT)
=====================

Copyright © `2023` `Greg Kamradt`

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the “Software”), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.