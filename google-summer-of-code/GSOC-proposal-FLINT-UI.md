# Moja global project proposal template for GSoC

## GCBM Simulation Editor for FLINT-UI

### Applicant information
Name: Abel Serrano Juste
github account: Akronix
Location (country or state): Spain
Mentors: @aornugent and @HarshCasper

### Abstract

Currently, there's an user interface to launch [The Full Lands Integration Tool (FLINT)](https://moja.global/flint/), called FLINT-UI. However, this interface lacks a way to modify the configuration parameters for the underneath model, [the Generic Carbon Budget Model (GCBM)](https://community.moja.global/docs/GCBM/GCBM), which is capable to moderate the carbon flow of a given area. This project implements that missing interface for the user to visually configure the input parameters for the model, prior to run any simulation with the aforementioned model.

### Motivation

I want to contribute in a project related to environment management and climate change awareness, that is why I see the moja global project matching exactly with my interests and motivations. Personally, I've developed some user interfaces in the past for web applications and I think I'm skilled enough to help to fill the gap missing in FLINT-UI.

### Project plan

* Make an user story of an user intending to do a simulation with FLINT.(*)
* Study current workflow to create and run a simulation.
* Improve current UI based on previous studies.
* Design the layout for configuration of parameters window.
* Implement the above layout
* Implement widgets
* Create configuration from widgets and test the workflow.

(*): Potentially, It could be required to make many user stories for different personas or user cases.

### Schedule of Deliverables


| Days/Dates         | Deliverable      |
|--------------------|------------------|
| May 20 - Jun 12 | Community Bonding Period. Participate in UI meetings, get to know mentors and other members of the organization.|
| May 20 - Jun 12 | Learn Vue.JS. Get familar with current codebase.|
| Jun 13 - Jun 19 | Create first user story|
| Jun 20 - Jul 3 | Study current workflow & improve current UI  |
| Jul 4 - Jul 10 | Design layout for new window   |
| Jul 11 - Jul 29 | Implement new layout & widgets |
| Jul 29 | _Evaluation Phase 1_ |
| Aug 1 - Aug 14 | Add functionality to widgets and layout|
| Aug 15 - Aug 28| Last refinements: Document whatever is not documented, code tests, clean-up code, etc.
| Aug 29 - Sept 4| Bonus week: To use in case some things need to be finished and there was not time before.
| Sept 5 - Sept 12| _Prepare and submit final work. Evaluation phase 2_

### Past contributions

Issue: https://github.com/moja-global/FLINT-UI/issues/235


### Past experience

In my first job, I was working as a full-stack developer of a webapplication fully in Javascript. I coded mostly in ReactJS, although I had to do a bit of nodeJS and mongo for the backend.
Later on I was working in the university as an asistant researcher. There I was downloading, processing and analyzing
big ammounts of data. I also developed [WikiChron](https://wikichron.science/), a web app to visualize metrics and
networks upon wiki communities from their historical data.
I have also done some small contributions to other open source projects from time to time (you can
see some of my contributions in my github profile).

### About me
I graduated in 2015 of my Bachelor's in Computer Science in the Universidad Complutense de
Madrid (UCM). During my time in the university, I founded a student association to support free &
open-source software called LibreLabUCM. I also did one academic year abroad in Cyprus underthe Erasmus program. After university, I was working for a bit doing tutoring, web development, IT
support and system administration.
From March 2017 to Spring 2019 I got a position as an assistant researcher in the university to
support the research around online collaborative communities, in particular wikis. During this time I
wrote some research papers doing data analysis regarding these communities and developed a visualization tool of the collaboration and productivity within a wiki using the community history.
In 2020 I finished my Master's in Data Science in an online university of Spain.
I heard about Google Summer of Code while I was studying in the university and I found it as a
very good opportunity to get started with real open-source projects, to develop computer skills (like
remote working, good coding practices) and get precious knowledge and experience.
This project gives me the opportunity to do something with real impact and useful for the society by
extension.
