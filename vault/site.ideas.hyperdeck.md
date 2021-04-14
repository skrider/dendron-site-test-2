---
id: 545ac24d-faa9-4011-a522-b80af79d555f
title: Hyperdeck
desc: ''
updated: 1617696924068
created: 1617694947096
---

>Everyone wants to have a useful meeting, but no one wants to make the PowerPoint.

Working on [[Kalenda.io|site.projects.Kalenda]] was my first experience with frequent, remote meetings. While often short, our meetings rarely accomplished more than reasoning in circles while contributing to the ever-growing **information asymmetry** within our budding organization. As an organization building a product dedicated to making meetings more efficient and easier, I found this somewhat ironic.

I realized that meetings are these amorphous things that really do not want to take on structure. Giving meetings structure is like trying to mix oil and water. You can't do it without an emulsifier. And what is that emulsifier? Potentially hyperdeck.

What does "structure" mean when it comes to meetings? I see it as having three main parts, in line with the temporal flow of the meeting.

### 1. Before

Before the meeting, some kind of structure is necessary for determining when the meeting will be held, where, who will attend, and what will be discussed. The last fact is quite important. Knowing what should and shouldn't happen during a meeting is key to making it more efficient.

### 2. During

During the meeting, some kind of structure is needed in order to keep attendees on track with the previously stated meeting guidelines and record important information.

### 3. After

After the meeting is one of the most important and often-overlooked parts. Action items decided on during the meeting need to be kept track of and sent to their respective endpoints, whether that be a person's personal task management system or a project management tool such as Jira. Additionally, meeting notes need to be made available for reference, both by forgetful meeting attendees and the organization at large, in order to combat information asymetry.

## The Solution

Hyperdeck is basically an interactive, editable slideshow constructed from a Notion-style markdown-esque document, managing **all** information that has to do with one single meeting.
1. Before the meeting, the document can be sent out to all participating team members, who 
    1. specify meeting availability using a When2Meet (or, [[Kalenda|site.projects.Kalenda]]) style grid 
    2. edit the meeting agenda. 
2. From the agenda items, an *editable* slide presentation is created and presented during the meeting. 
    * (Ideally, this would be live-editable by all members at once, but initially the appointed "scribe" could just screen share it, or if in-person, project it.)
3. Some slides are entirely presentational in nature, containing videos, text, or images. Some are more for taking notes and driving / recording discussion.
4. Each slide has a timer showing how long it has been shown for, total.
5. Each slide can be edited to add notes and action items
6. Additional slides can be appended to the presentation
7. Once finished, the presentation is returned to markdown format, retaining all meeting notes. It can then be filtered, edited, etc, and sent out. Specific line items can be sent to specific endpoints, such as email, Jira, trello, a team wiki, etc.

## Core Features

* Timers - hold the group accountable
* Integrations - Most teams have defined pipelines already in place for storing info, managing tasks, communication, etc. Hyperdeck is the hub for all of these. As such, it is a kind of purgatory for information, not meant to store it long term, but to be an efficient pipeline.
* Pretty UI
* Template friendly - creating templates involves planning, which involves optimistically daydreaming about actually following through in the future, which is quite a fun and rewarding pastime.

## Rationale

Notion is one of my favorite products out there. It makes organizing my life - giving structure to something that really does not want it - actually fun. I think that this is a combination of its minimal but beautiful UI and overall modularity. Creating templates is a nice touch as well.

However, there is no product out there that does this with meetings. Meeting structure depends wholly on uncommon, unscaleable things like professionalism and organizational discipline. If planning meetings could be made fun, meetings could be made more efficient, and above all, less frequent.
