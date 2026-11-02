# Tally: case study

Tally is an interactive demo of a gym membership and loyalty app. The gym, its members and all its figures are invented. It is live at https://joshterblanche18-cmd.github.io/tally-gym-app/

## The brief

Gyms lose members quietly. I wanted to show a gym owner what an app could do about it: give members a reason to keep showing up, and show the owner who is drifting away before they leave.

I am not a developer. I led the project and made the product, design and business decisions.

## What I built

A phone app for members and a full-screen dashboard for the owner, in one web page. Members check in, book classes, log lifts and climb ranks. Owners see attendance, money, classes and members who have stopped coming.

## Decisions that mattered

**Rank people against others their size.** Leagues are split by gender and weight class, so a newcomer has someone realistic to beat.

**Reward showing up.** Weekly streaks and points come from attendance, not just strength, so members who are not the strongest still have something to win.

**Coaches verify personal bests.** A new best only earns points once a coach confirms it, which keeps the league honest.

**Fits different gyms.** The owner's Set up screen picks the type of gym and which parts of the app members see.

**Messages only with permission.** The app drafts a message to a member who is drifting away, and the gym sends it itself, only to members who said yes to messages.

**One file, no server.** A single web page keeps the demo free to host and safe for anyone to explore. Nothing is saved.

## Results

Measured 2 November 2026 in Chromium, at laptop and phone sizes. All 15 screens opened, and all 82 buttons on them were pressed at each size, with no page errors. Logging a new best and verifying it as the owner passed at both sizes. The full results and limits are in the README.

## What I would do next

Try it with a real gym. It has not been used with real members, and nothing here measures whether it keeps people coming back.
