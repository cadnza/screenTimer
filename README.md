# `screenTimer`

![](https://img.shields.io/github/v/release/cadnza/screenTimer)

Very (very) simple timer to remind you to look away from your Mac every 20 minutes. Saves me headaches.

## Installation

1. Clone the repo
2. Change the `Program` path in `com.jondayley.screenTimer.plist` to it's real path on your machine
3. Symlink `com.jondayley.screenTimer.plist` into `~/Library/LaunchAgents`
4. Start the job
    - Seriously—this project is so simple that I'm not even going to write up a tutorial on launch agents. [This one](https://developer.apple.com/library/archive/documentation/MacOSX/Conceptual/BPSystemStartup/Chapters/CreatingLaunchdJobs.html) should do.

## What it does

Thing shows a notification every 20 minutes so you can look at something 20 feet away for 20 seconds and not get a headache.

## Can I customize it?

Sure. There aren't any built-in options, but the entire repo's like 25 lines long.\* It's pretty straightforward.

## How do I change the icon?

🤷‍♂️

## Can I set the behavior of notifications?

Yes, it falls under _Script Editor_ in the Notifications pane (macOS Monterey). Could have its own application identifier, but then it wouldn't be very (very) simple.

## Is this even a project?

I mean, _I_ see it more as an off-brand Aspirin. This repo isn't going on my next resume, but I hope it'll keep me from getting headaches so often. If you stare at your Mac as much as I stare at mine, then maybe it'll help you out too.

**\*** _As of writing, this README is a couple hundred bytes heavier than the entire rest of the repo. So there you go._
