# Side Quest: How Phones Leak Data

**Path:** Pre Security
**Platform:** TryHackMe

## Goal
See how an attacker can collect information from a phone, use it against the owner, and send it back without ever touching the phone.

## What I did
1. Chose the Red team (attacker) side.
2. Found 5 out of 5 signals the phone was giving away.
3. Spotted 3 out of 3 red flags in a fake message.

## What I learned
- Phones leak information by default. Mine shared its device type, browser, language, timezone, and location without asking.
- A message that knows your name and device can still be fake. Check the domain, not the details.
- Urgency is bait. Lines like "act within 30 minutes" are meant to stop you from pausing and checking.

## Key idea
Attackers use small pieces of information to make a fake message look real. Slowing down and checking the domain is the best defence.
