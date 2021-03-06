# Update
You may be wondering about the seemingly-stagnant codebase of DrillBook over the past months. Don't fear -- this project is not dead. On the contrary, it's going through a glorious rebirth. We are recreating DrillBook using Electron instead of Java Swing. This will give the project a much (MUCH!) cleaner, more intuitive, and more flexible UI. It will also ease the cross-platform installation process. These benefits, plus the "now we know better" changes we're implementing in the new design means that DrillBook will be back and better than ever.

### TL;DR: This repo hasn't been active because we're revamping the technology behind the scenes. Please be patient; you won't regret it!

# DrillBook
DrillBook is a marching band drill creation software. It is designed to help drill writers and band directors create, edit, and print drill pages with ease and control.

## Features
- Pages saved in JSON format in .drill files
- Application state saved
- Simple click to add a dot
- Click and drag dot to move
- Right-click dot to remove
- Simple shift-click, control-click, and alt-click functions to select multiple dots
- Toggle showing grid lines
- Page information such as page number, song title, beginning and ending measures, counts, and notes controlled with ease and displayed in a (movable) text box on the page itself.
- Dot information such as instrument label, number, and position fine-tunable and reflected immediately.
- Dot position text shown in English:

    > Horizontal - Side 1: 1.5 inside of 10

    > Vertical - 4.0 in front of Back Hash
- Toggle displaying dot names (C1, A4, etc.)
- Easily print an individual page or the whole show
- Print dot sheets for every player with one click
- Play the move from the previous to current pages. Get automatically notified about extremely far moves and possible collisions
- Supports both High School and College hashes

## [Usage](../master/DrillBook/src/main/resources/Usage.md)

## Samples
### UI Sample:
![UI Sample](../master/ui-sample.png "UI Sample")

### Page Sample:
![Page Sample](../master/page-sample.png "Page Sample")

### Dot Sheet Sample:
![Dot Sheet Sample](../master/dotsheet-sample.png "Dot Sheet Sample")

### DrillBook was written by [Evan Belcher](http://evanbelcher.com) starting in 2016. [Isaac Shiekh](http://www.isaacsheikh.com) was brought on to the project in mid-2017.
