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

* **Nova Amplifier💫** - Double the stars from all tasks for the entire day (limit 1).
* **Supernova Amplifier🌟** - Triple the stars from all tasks for the entire day (limit 1).
* **Healing Aura✨** - Only usable when a Negative Status Effect is active. All Self-Care tasks earn an extra +1 ⭐ (limit 1, expires after 7 days).
* **Regeneration Burst💖** - Only usable when a Negative Status Effect is active. All Self-Care tasks earn an extra +3 ⭐ (limit 1, expires after 7 days).

# Appendix E - Achievements
Achievements are awarded at the end of each day during the End of Day Procedure. An achievement can be awarded from combinations of tasks, consecutive conditions, and combinations of other achievements.  Achievements can award more stars, Items, or Loot Boxes. Some achievements do not have any immediate rewards, but are used as preconditions for other achievements.

* **Streak**: Complete all tasks for 3 consecutive days = +5 bonus stars
* **Mega Streak**: Complete all tasks for 5 consecutive days = Nova Amplifier💫
* **Super Streak**: Complete all tasks for 7 consecutive days = Supernova Amplifier🌟
* **Ultra Streak**: Complete all tasks for 14 consecutive days = Epic Loot Box
* **Early Riser**: Complete all Daily Maintenance tasks before 12 noon = ALL tasks completed that day each get +1 star
* **Constant Vigilance**: Earn the Early Riser achievement 5 days in a row = Small Loot Box
* **Clearly Consistent**: Complete all scheduled tasks for a day = Next day, 1 random task gets 2x stars during the End of Day Procedure
* **Category Mastery**: Complete 5 tasks in same category in the same day = +10 bonus stars for that day
* **Time Lord**: Complete 3 tasks in the Scheduling category in the same day = Receive bonus stars equal to the numerical value of the current day of the week (minimum 1)
* **Tireless**: Complete at least 10 tasks in the same day = +10 stars for that day
* **Draconic Might**: Complete 2 or more Dragon Tasks in the same day = +1 Bonus Dragon Token awarded
* **Silver Dragon Ward**: Go 3 consecutive days without creating any new Dragon Tasks = Earn +10 bonus stars for that day
* **Platinum Dragon Ward**: Go 7 consecutive days without creating any new Dragon Tasks = Earn +10 bonus stars for that day, and a 🐉 Dragon Token
* **Dragon Expert** : Earn 10 Dragon Tokens (lifetime)
* **Draconic Centurian** : Earn 100 Dragon Tokens (lifetime)
* **Dragon Slayer** : Complete any Dragon Task = Receive original stars plus applicable bonus (max +3) and earn a 🐉 Dragon Token
* **Proactive Maintenence** : Complete 2 or more Self-Care tasks when a Negative Status Effect is NOT active = **Healing Aura✨**
* **Rigorous Protection** : Complete at least 1 Self-Care task per day for 5 consecutive days when a Negative Status Effect is NOT active = **Regeneration Burst🛡️**
* **Tachyon Skip** : Complete any number of tasks after having no Quest Log for the previous day = Get +10 bonus stars for the day. Tomorrow get +10 stars ⭐ at the beginning of the day.
* **Second Wind** : Complete 3 tasks after 6pm = Start the next day with +5 stars
* **Iron Will** : Complete an unscheduled Dragon Task with a Negative Status Effect active
* **Self-Enlightenment** : Earn the **Proactive Maintenence** achievement 5 times in the same week = 1 🐉 Dragon Token
* **Phoenix Rising** - Complete all planned tasks after having an active Negative Status Effect the previous day = All tasks earn double stars
* **Solar Phoenix** - Earn the **Phoenix Rising** achievement 5 times
* **Phoenix Constellation** - Earn the **Phoenix Constellation** achievement 5 times
* **Galactic Phoenix** - Earn the **Phoenix Constellation** achievement 5 times
* **Steady Recovery** - Complete a Self-Care task every day for 3 days after a Negative Status Effect ends = 1 free Small Loot Box
* **Emotional Intelligence** - Go 7 consecutive days without declaring a Negative Status Effect.
* **Routine Builder** - Complete all Daily Maintenence tasks for 3 consecutive days.
* **Habit Former** - Earn the **Routine Builder** achievement 5 or more times in the same calendar month.
* **Lifestyle Integrator** - Earn the **Habit Former** achievement 3 months in a row.
* **Self-Disipline Master** - Ear the **Habit Former** achievement 6 months in a row.
* **Social Networker** - Complete 3 Socialization tasks in the same calendar week.
* **Social Connector** - Earn the **Social Networker** achievement 3 times.
* **Social Maestro** - Earn the **Social Connector* achievement 3 times.
* 
