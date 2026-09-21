# Timesheet Activity Tracker

The Activity Tracker records the apps and documents you work in, groups your day into work
blocks, and turns them into Timesheet tasks. Everything stays on your Mac until you book it.

This repository publishes the signed macOS builds. The source lives in Timesheet's own
repository.

## Download

The current version is on the [releases page](../../releases/latest), and
[timesheet.io/en/activity-tracker](https://timesheet.io/en/activity-tracker) explains what the
app does.

Each release is one universal disk image that runs on Apple Silicon and Intel. It is signed
with our Developer ID and notarised by Apple, so it opens without a Gatekeeper warning.

## Before you install

- macOS 10.15 or newer.
- A Timesheet account on the Pro, Business or Enterprise plan, or a trial. Every new account
  starts with a 30 day trial.
- macOS asks for Screen Recording permission the first time. Without it the tracker still
  records which apps you use, but window titles stay empty and no screenshots are taken.

## What leaves your computer

Nothing, until you turn recorded time into a task. Window titles and screenshots each have
their own switch, and the project suggestion runs on your own machine with a language model
you download once. It never uploads what it reads.

## Help

Documentation is at [docs.timesheet.io](https://docs.timesheet.io/). Please report problems
through the support channels on [timesheet.io](https://timesheet.io), not as issues here:
this repository only carries the builds.
