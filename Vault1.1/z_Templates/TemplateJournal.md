---
NoteIcon: journal
aat-render-enabled: true
fc-category: 
fc-display-name: 
sessionstatus: 
type: Session Journal
sessionDate: 2000-01-01
players: 
Status: 
OneLiner: 
timelines: []
tags:
  - journal
banner: [[MapBanner.jpg]]
banner-y: 60
content-start: 175
banner-display: cover
banner-repeat: false
banner-height: 250
banner-fade: -75
banner-radius: 0
banner-title-color: "#FF5733"
banner-x: 100
---

<% await tp.file.move("/4-Session Journals/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewJournal");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Date (yyyy-mm-dd)");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

# Roster 

%% Keep track of who turned up. %%

### DM:
- 

### Players Present:  
- 

### Absent:
- 

# Session Overview

%% I like to keep a quick summary of sessions here. %%

## Synopsis



## Important notes:

- 

## To Do:

1. 