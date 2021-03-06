# Magic Conch Public Privacy Statement
This Discord Bot collects and logs messages only that activate a response. Messages that activate logging are those that begin with the bot's mention.

For example, the following messages will be logged:
 * @Magic Conch#7782
 * @Magic Conch#7782 Is this a question?
 * @Magic Conch#7782 help

The following messages will **not** be logged:
 * I think @Magic Conch#7782 is a great bot
 * Magic Conch#7782 is a public bot!
 * This is a random message

For each logged message, the following information is collected and logged:
 * The message author's ID
 * The message author's current username
 * The message content

No other information is collected (for example, pfp, presence, about me, message metadata [such as date, ID, guild, channel], etc). 
All logged author ID's, usernames, and trigged message contents are also deleted on a 15 day rotation period. 

Should you wish to have your data deleted faster than the 15 day period, contact @dovedevic#0522 on Discord or raise an issue in this repository.

# Data Use

Logged information is only used for debugging purposes when the bot encounters an error due to user input. ID's/usernames are saved to blacklist offending users who abuse the bot and it's commands. Message content is used to test the bot further. **No selling, trading, or transfer of your data or its derivatives are made.**
s