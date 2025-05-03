# Dragonstar AI
## Meta-commentary
Ok, so, it's just us humans now. 

## Project Overview
This project is an attempt to create a task-managment and motivation system for myself, using incentive-based motivation and positive reinforcement concepts. It is a system that is ment to be used as a collaboration between a user (me) and an LLM based AI system. The LLM ingests the system's rules and a list of tasks, and then responds to specific prompts (eg "I'm ready to start my day") to help me prioritize what I need to do each day. 

## Project Setup
Here's what you need to know to try and adapt Dragonstar to your own LLM based AI and your own needs. This was originally created using Anthropic’s Claude AI - v3.7 Sonnet.

### Prerequisites
* An LLM based AI (so far this has only be used with Claude 3.7 Sonnet)
* A "Project" or other method of telling the AI in advance to injest the documents in this repository every time you start a new chat
* Fork this repository

## Files
Here's a quick description of what's in this repository and what it's for. If it's marked with a ⭐, it should be included in the LLM's project. The rest are ment for you, the human. 
* **README.md** - this file 📖
* ⭐ **dragonstar-system.md** - The main rules of the system, how everything should work, what key phrases to watch for, etc.
* ⭐ **dragonstar-appendix.md** - The appendecies of the system, with information like loot tables.
* ⭐ **dragonstar-tasks-repeatable.md** - The list of tasks that are repeatable, eg things that you do daily or weekly (sometimes monthly?)
* ⭐ **dragonstar-tasks-singular.md** - "Singluar" task, or tasks that just need done once, like "repaint the bathroom"
* ⭐ **dragonstar-quest-log.md** - Your log of what you've done, and where your current inventory and score is recorded.

### Getting Started
First you will need to link the dragonstar-system, tasks, and appendicies to your LLM's project.

In your project, set the project's Special Instructions to something like:
```
This is a project to help me organize myself by surfacing and prioritizing tasks. I am using a gamification system to help me stay motivated through positive reinforcement. The rules of this gamified system are in the Dragonstar System Google Doc. All tasks are saved in the Dragonstar Task List Google Doc. Anytime I say "task", it means the same as "quest" for the purposes of this chat.

When asking questions of me, only ask 1-2 questions at a time to prevent overwhelming me. 

If I say I need encouragement or motivation, ask if I need help for a specific task and remind me of the motivations and reasons I described for doing that specific task.
```

Then you can the system's rules and tasks to match your thematic preferences. Since the LLM also has an understanding of the rules it can offer meta-commentary and advise about the system itself. Try asking the LLM to help you customize Dragonstar!

That should be all that's needed to get it working! Try starting a new chat in the project with the phrase “I'm ready to start my day” and seeing what happens.  You can even go through the whole process of checking off tasks, and ending your day with “I'm done with my day”. If you don't want to keep the result, just delete the chat. 

## Next Steps
Here's some next steps I recommend:
* Try simulating a day to see how the system works
* Update the tasks in Daily Maintenance and Weekly Maintenance to match your personal routine
* Don't try to update or add all the tasks you can think of all at once.  It can get overwhelming really easily. Try adding 1-3 new things each day as you remember them. 
* Change the loot table in Appendix C to suit you personally.  Try putting the list into a chat and asking the LLM to help you think of more personalized suggestions

## Daily Workflow
All of this is laid out in the Dragonstar System document, but it’s very verbose since it’s intended for the AI. Here’s a more brief human version:
1. Start a new chat in the project
2. Say “I’m ready to start my day”, and follow the prompts. Be sure to tell it about stuff like “i’m working from 9-5 today” or “I’m planning to spend my evening playing bar trivia”
3. Follow the prompts to confirm
4. Throughout the day tell it “I’ve completed ____” 
5. You can optionally tell it to collect your stray thoughts, eg “remind me to ___” or “note to self, ____”
6. At the end of the day, tell it “I’m done with my day”, and follow the prompts
7. Take the finalized Quest Log it generates, and copy-paste it into your personal Quest Log document, so that the chat that you start tomorrow is aware of it. 
(ChatGPT may not need this step, since it “remembers” things between chats. Claude’s chats are sandboxed and do not “remember” things from previous chats)

## General Notes
If you find yourself overwhelmed by a stack of things that can go together (like scheduling appointments, shopping for specific items, etc) try making a task that is timeboxed to the category rather than listing all of them individually. Then only spend a specific amount of time tackling that category instead of trying to do all of them. 

One of the parts I've enjoyed most about this system so far is that the LLM will of course help you organize and check off tasks, but it can also help you analyze the system itself, offer suggestions for changes to the rules, achievements, rewards, task formatting, what fields are in the templates, whatever!

Lastly, remember this system's rules are dictated only by a text document. Any part of it you don't like, you can change, easily and quickly. Want to inflate all the star values by 100? Do it.  Don't like the dragon theme and want sharks instead? Go for it🦈  Think you're earning stars too fast because you tend to create lots of tiny tasks instead of fewer larger ones? Go adjust the scale, stars per task, or the cost of loot boxes. There are a ton of ways to make this your own. 
