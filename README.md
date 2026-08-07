AEC — Educational Platform (Aide École Canada)

A desktop learning application for elementary students (Grades 1–6), built in Python with Tkinter. Teachers create and assign exercises; students complete them and see their progress over time.

This is version 1. A rewritten, object-oriented version lives in aec-educational-platform-oop.

What it does
Two roles. Students and teachers log in to different views of the same app.
Exercises by grade level. Content is organised for Grades 1 through 6.
Score tracking. Every attempt is recorded so a student can see whether they are improving.
Session history. Past sessions are stored and can be reviewed later.
Why I built it

I teach robotics and programming to children, and I tutored a Grade 9 student for a full school year. The recurring problem was the same: a student practises, gets a mark, and has no idea whether anything actually changed since last week. I wanted a tool where the progress is visible to the student, not just to the adult.

Tech
	
Language	Python 3
GUI	Tkinter
Data storage	[FILL: JSON files? SQLite? CSV? — say exactly which]
Interface language	French
Running it
bash
git clone https://github.com/angelb-47/aec-educational-platform.git
cd aec-educational-platform
python [FILL: exact entry-point file, e.g. main.py]

Requires Python 3.[FILL] or newer. [FILL: "No external dependencies." — or list them.]

Screenshots

[FILL: 2 screenshots — the login screen and the student view. Drag the images directly into this file while editing on github.com; GitHub uploads them for you.]

What I would change
[FILL: one honest limitation. Example: "State is passed around through global variables — this is exactly what pushed me to rewrite the project using classes."]
[FILL: a second one.]
Status

Built as a Grade 12 Computer Science summative project (ICS4U), [FILL: month/year]. Not actively maintained — kept public as a reference point for the rewrite.
