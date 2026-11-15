# Offensive Security Intro

**Path:** Pre Security > Introduction to Cyber Security
**Platform:** TryHackMe

## Goal
Find a weakness in a fake banking website (FakeBank) in a safe, legal lab.

## What I did
1. Launched the terminal in the lab machine.
2. Used the tool **dirbuster** to search the site for hidden pages:
   `dirb http://fakebank.thm`
3. Found a hidden admin page that was not linked anywhere on the site.
4. Opened the page and used it to transfer money into an account.

## What I learned
- Websites often have pages that are not visible but are still reachable.
- Tools like dirb guess page names to find them.
- An admin page that anyone can open is a serious security mistake.

## How to prevent it
- Protect admin pages with a login and proper permissions.
- Don't rely on a page being "hidden" for security.
