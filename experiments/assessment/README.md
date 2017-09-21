### experiments/assessment

This folder holds all code for the quality assessment experiment, 
which has been repeted after the first round of reviews.

* [`create_attentional_videos.py`](`create_attentional_videos.py`)
is a script to pre-evaluate videos for the quelity assessment.
Also saves the parameters of each video in a single txt file.
* [`questions.py`](`compute_metrics.py`)
contains code to ask questions to the user.
* [`show_attentional_video.py`](`show_attentional_video.py`)
is the script to call when a new subject partecipates. 
Shows a video and asks questions.


### TODOS:
* **IMPORTANT:** validate video creation (plz, frs, smn).
Redo until perfection.
* blur with different levels (and log blur).
* make sure that areas are the same across different map
types.
* check for any other request of reviewer 1.