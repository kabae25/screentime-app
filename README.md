# screentime-app

The screen time app I wish existed on the app store.

All it should do:

1. No ulterior motives - no social networking, collectables, etc
2. Allow customization, but not stray too far from the intended UX
3. Not be for promit - Full functionality for no price

# Core Functionality

This app should have two main pages: A home/status screen and a user settings screen. 

The home screen should display the time accumulated - I think a circular graph is probably best, maybe a vertical bar? Future work should be on new and interesting schemes, mode 3, not visual improvement.

## Mode 1: Classic Mode

This mode is designed to act as a simple screen time system. As you use apps that are on a selected list, a timer accumulates until a certain limit is reached, which results in those apps becoming temporarily locked for some time (with no undo). Defaults: 15 minutes on, 1 hour 30 minutes off.

The catch, and what I think will differentiate this app from others around, is if you stop using your phone before the time limit, the accumulated time will slowly decriment. Defaults: 1 hour off -> 45 minutes removed

The whole idea with this mode is to still have blocking features, but allow users to begin to self regulate. I think the whole premise of the app should be to try to return power to users, take things seriously, that kind of idea.

## Mode 2: Debt Mode

The same underlying system as mode 1, except the app continues counting past the limit. This results in "phone dept" that the user must pay off by locking apps for some time. Defaults: debt accumulates and is removed at a 1:1 rate. User breaks begin at 30 minute duration.

Debt cannot be paid off during typical sleeping hours, etc.

If the user can't eliminate the debt by the end of the week, the user will need to pick apps off their block list that get locked until the next cycle. Defaults: User selects 2 or more apps, Cycle starts on Saturday.

