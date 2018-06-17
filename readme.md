# Election Bot
## An Automated Tool & Public Information Campaign
### Overview
*Election Bot* (final name TBD) exists as a static website and a social media
tool intended to inform people about the characteristics of computer-generated
social media posts and fake news perpetuated by foreign governments or
organizations.

### Website
The website will provide examples and guidance on identifying fake posts
perpetuated by foreign governments or interests. It will also educate users on
how to use the social media tools to evaluate the likelihood a particular post
is robotically generated or amplified.

[Plain language](https://en.wikipedia.org/wiki/Plain_language) will be used
throughout the single-page website which makes visitors feel welcome and safe
with a sincere and serious, yet non-judgmental tone.

### Bot
- Users will `@mention` the bot on a post they wish to check for human authenticity.
- The **bot** will connect to [BotOMeter](https://botometer.iuni.iu.edu/#!/), a
collaborative project between IU and USC.
- Using the [BotOMeter API](https://github.com/IUNetSci/botometer-python),
The **bot** evaluate the score returned by `BotOMeter` against a heuristic
algorithm developed by our team to determine if the post is or is not robotically
generated.

### Partnerships
We will look to partner with commonly used social media platforms including:
- Twitter
- Facebook / Instagram
- Pinterest

Partnerships will give credibility to the project as well as potential technical
support, insight, and amplification to their respective users.

### Background Reading
-
### Tools
**Back End**
- Python 3.6
- Requests
- Tweepy
- BotOMeter

**Front End**
- Ruby on Rails
- Jekyll

### Marketing, Amplification, Communications
- *see* [comms.md](https://github.com/csethna/electionbot/blob/master/comms.md)

### Roles Needed
- SWE (front end)
- SWE (back end)
- SRE (deployment)
- UX
- UI
- Product Manager
- Marketing / Comms
