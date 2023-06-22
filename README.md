# automod-url-whitelist
A Discord Automod rule that prevents any links from being sent except those which you have specifically whitelisted.

# Guide:

- Go to Discord Server Settings and enable Community.
- Go back to Server Settings and scroll to the Moderation tab and click "Safety Setup"
- You will see the AutoMod section. Click on "Create Block Custom Words"
- Rename the rule to whatever you like. I usually put "URL Whitelist" or something similar.
- Under the "Choose your words" section, paste the word list. (You can get it from the <a href="./word-list.txt">word-list.txt</a> file in this repository)
- Scroll to the bottom of your rule and find the "Allow words and phrases (optional)" section and open it.
- Type in your whitelisted URLs in this format: ```*link.com*, *link2.net*, *link3.gg*```
- Configure anything else you want in your rule, such as mod logs, timeouts, etc.
- Click "Save Changes" at the bottom of the screen to save your AutoMod rule.
- All done!
