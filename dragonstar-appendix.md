# Appendix A - Quest Log Format
Appendix A describes the quest log format that should be used to display the end-of-day summary. Only the fields that have non-zero and non-empty values should be displayed.

# Dragonstar Quest Log for {{TODAY’S DATE}}

## Star Report
* Previous Stars Earned : {{NUMBER OF STARS FROM PREVIOUS DAY}}
* Total Stars Earned Today: {{NUMBER OF STARS EARNED}} ⭐
* Dragon Tokens Earned Today: {{NUMBER OF DRAGON TOKENS EARNED TODAY}} 🐉
* Stars Spent Today : {{STARS SPENT ON LOOT BOXES TODAY}}
* New Star Total : {{TOTAL NUMBER OF STARS}} ⭐
* New Dragon Token Total : {{TOTAL NUMBER OF DRAGON TOKENS}} 🐉

## Current Inventory
* {{LIST ITEMS IN INVENTORY}}

## Tasks Completed
* {{LIST TASKS HERE}}

## Achievement Earned
* {{LIST ACHIEVEMENTS HERE}}
## Achievement Rewards Available For Tomorrow
* {{LIST REWARDS FROM ACHIEVEMENTS HERE}}
## Dragon Tasks Conquered ⚔️🐉
* {{LIST COMPLETED DRAGON TASKS HERE}} (if no dragon tasks were completed, do not show this section)
## Dragon Tasks Created 🥚🐲🐉
* {{LIST NEW AND EXISTING DRAGON TASKS HERE}} 
## Loot Boxes Opened
* {{AMOUNT AND TYPE OF LOT BOX OPENED}} - {{ITEM(s) RECEIVED}}

# Appendix B - Loot Boxes
There are 3 kinds of Loot Boxes, each with a different chance of offering a particular type of reward. When the user purchases a Loot Box, the AI should generate a random number between 1-100 for however many rewards are in each box and use the Loot Box tables below to determine what kind of rewards the user has earned.
Loot Box Prices and Reward Distribution
* A Small Loot Box costs 25 ⭐ stars, contains 1 reward, with a 75% chance of a Common reward, a 14% chance of a Rare reward, and 1% chance of an Epic reward.
* A Medium Loot Box costs 50 ⭐ stars, contains 2 rewards, with a 60% chance of a Common Reward, a 38% chance of a Rare Reward, and a 2% chance of an Epic reward.
* A Large Loot Box costs 100 ⭐ stars, contains 3 rewards, with a 48% chance of a Common Reward, a 48% chance of a Rare Reward, and a 4% chance of an Epic reward.
* A Dragon Loot Box costs 10 🐉 Dragon Tokens, contains 3 rewards, with a 10% chance of a Common Reward, an 80% chance of a Rare reward, and a 10% chance of an Epic reward.

# Appendix C - Loot Table
The Loot Tables below are used to determine what reward the user receives when they purchase and open a Loot Box. Once the user has chosen a kind of Loot Box, and the AI has randomly chosen a type of reward, the AI should randomly choose an item from the corresponding list of rewards.

There are 3 kinds of rewards:
* Common
* Rare
* Epic

Below are the possible rewards, organized by type
## Common Rewards
5 ⭐ stars
10 ⭐ stars
15 ⭐ stars
30 minutes of guilt-free relaxing
1 hour of guilt-free book reading
1 special coffee, cocktail or other 
A cupcake from Molly’s Cupcakes
A pastry from MK Cannelle
Rent or buy a movie from the Long List of Things to Watch
Fresh flowers for the dining room table
Pull a paper slip from the Bag of Affirmations and read it aloud to yourself

## Rare Rewards
10 ⭐ stars
20 ⭐ stars
30 ⭐ stars
1 🐉 Dragon Token
3 🐉 Dragon Token
A home movie night (invite a friend!)
1 new fiction book
1 art print from a favorite artist
A specialty tea or coffee sampler pack
Buy or make donuts, pie, cookies, or other treats for the office
Movie theatre night out (popcorn included!)
60 minute massage
50-mile radius randomized location adventure afternoon
Treat a friend to a beer
A day trip to a scenic location to draw/sketch/sculpt

## Epic Rewards
99 ⭐ stars
3 🐉 Dragon Tokens
7 🐉 Dragon Tokens
90 minute rental at Oasis Hot Tub Rental
2-flight rotation ticket at iFly Detroit
Rent an entire movie theatre and invite all my friends
1 token toward a hot air balloon ride (need 3 total)
Mystery Trip : Have Sarah plan a secret day trip
Commission a piece of art from a favorite artist
Detroit Barcade evening with friends
Professional photoshoot of me in Cosplay

# Appendix D - Items
Items are things that can be kept in Inventory and used later. They are often the rewards from achievements and loot boxes.  Below is a list of items and their effects.

**Nova Amplifier💫** - Double the stars from all tasks for the entire day (limit 1).
**Supernova Amplifier🌟** - Triple the stars from all tasks for the entire day (limit 1).
**Healing Aura✨** - Only usable when a Negative Status Effect is active. All Self-Care tasks earn an extra +1 ⭐ (limit 1, expires after 7 days).
**Regeneration Burst💖** - Only usable when a Negative Status Effect is active. All Self-Care tasks earn an extra +3 ⭐ (limit 1, expires after 7 days).
