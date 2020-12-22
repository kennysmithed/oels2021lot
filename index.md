This is the webpage for the Netherlands Graduate School of Linguistics course Online Experiments for Language Scientists, running in January 2021.

## Course summary

Many areas in the language sciences rely on collecting data from human participants, from grammaticality judgments to behavioural responses (key presses, mouse clicks, spoken responses). While data collection traditionally takes place face-to-face, recent years have seen an explosion in the use of online data collection: participants take part remotely, providing responses through a survey tool or custom experimental software running in their web browser, with surveys or experiments often being advertised on crowdsourcing websites like Amazon Mechanical Turk (MTurk) or Prolific. Online methods potentially allow rapid and low-effort collection of large samples, and are particularly useful in situations where face-to-face data collection is not possible (e.g. during a pandemic); however, building and running these experiments poses challenges that differ from lab-based methods.

This course will provide a rapid tour of online experimental methods in the language sciences, covering a range of paradigms, from survey-like responses (e.g. as required for grammaticality judgments) through more standard psycholinguistic methods (button presses, mouse clicks) up to more ambitious and challenging techniques (e.g. voice recording, real-time interaction through text and/or streaming audio, iterated learning). Each day we will read a paper detailing a study using online methods, and look at code (written in javascript using jsPsych) to implement a similar experiment – the examples will skew towards the topics I am interested in (language learning, communication, language evolution), but we’ll cover more standard paradigms too (grammaticality judgments, self-paced reading) and the techniques are fairly general anyway. We’ll also look at the main platforms for reaching paid participants, e.g. MTurk and Prolific, and discuss some of the challenges around data quality and the ethics of running on those platforms.

No prior experience in coding is assumed, but you have to be prepared to dive in and try things out!

## Staffing

[Kenny Smith](http://www.lel.ed.ac.uk/~kenny/) (that's me) is the 'lecturer' (I won't be lecturing). Best way to get in touch with me is in one of the live sessions, via Slack (I'll send details of the course Slack group), or by email to [kenny.smith@ed.ac.uk](mailto:kenny.smith@ed.ac.uk).

## Class times

We will meet 11:15 - 13:15 CET, Monday 18th-Friday 22nd January, on Zoom.

## Course Materials

Course content will appear here - I'll get everything up as early as possible to allow you to work through the materials before the course starts.

For each day I will provide a set reading and programming assignment(s). The reading involves a blog post introducing a published paper, you read both the blog and the paper. The programming assignments involve working through a section of the [Online Experiments with jsPsych](https://softdev.ppls.ed.ac.uk/online_experiments/index.html) tutorial and/or looking at code implementing a language-related experiment. We can discuss this in the first class, but my plan is that we will use part of the Zoom sessions for a short discussion of the set readings, focussing on any bits you didn't understand or wanted clarification on, but use the majority of the time to work on the practical assignments - I can help you work through problems you have running the code, difficulties you encounter in editing the code, etc. The idea is that this course will set you up to build and run your own experiments, so I am keen that we focus on the practical content.

### Preparatory materials

I'd encourage you to work through as much of the material as you can before the course starts - if you can attempt some of the practical exercises (certainly the Monday practical) before we start it'll mean you can identify problems and get my help on them in the limited time we have available. But at a minimum, work through the following preparatory materials.

- *Scientific content:* lab vs online data collection
- *Technical content:* jspsych basics, intro to crowdsourcing platforms
- [Reading](oels_reading_pre.md)
- [Programming task](oels_practical_pre.md)


### Monday: Grammaticality judgments and self-paced reading

Slightly ambitiously the plan is to cram a couple of basic experimental paradigms into the first day - hopefully the paradigms and the code are simple enough that we can manage this, but remember you have all week to make use of me in drop-in labs so if you don't get through this on the Monday you can get help with it later in the week.

- *Scientific content:* lab vs online grammaticality judgments; syntactic processing and acceptability; processing costs of syntactic dependencies
- *Technical content:* simple key- and button-press responses; collecting reaction time data; more complex nested trials


### Tuesday: Word learning / frequency learning

- *Scientific content:* probability matching and regularisation
- *Technical content:* using trial data for contingent trials; filtering and saving data

### Wednesday: Audio stimuli

- *Scientific content:* speech perception, social influences on phonetic adaptation
- *Technical content:* Audio, trial data again, saving data trial by trial

### Thursday: Confederate priming

- *Scientific content:* syntactic priming and alignment
- *Technical content:*  Audio recording, more randomisation stuff, custom preload lists, reading trial lists from CSV

### Friday: Participant-to-participant interaction or Iterated Learning

Pick one of the two topics and do the associated reading / practical.

Participant-to-participant interaction:
- *Scientific content:* least effort and Zipf's Law of Abbreviation
- *Technical content:* web sockets, python servers, incrementally building a timeline

Iterated Learning:
- *Scientific content:* iterated learning and the evolution of compositional structure
- *Technical content:* reading trial lists from CSVs again, PHP scripts for iteration

## Re-use

All aspects of this work are licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
