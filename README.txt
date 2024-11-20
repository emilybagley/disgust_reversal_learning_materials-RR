Materials made available with the stage 1 Registered Report
This repository contains the code for the video rating, reversal learning and digit span tasks.
Additionally, we include details of how the videos used in the video rating and reversal learning tasks are selected.


List of files
digit_span_task.html: creates a digit-span working memory test - adapted from this repository: https://github.com/mahiluthra/working_memory_tests/tree/master 
index.html: contains code for the video rating task, personalised stimulus selection and the reversal learning task
stimulus_selection.ipynb: outlines how the 5 fear- and 5 disgust-inducing videos were chosen from the Cowen and Keltner (2017) database


Stimuli
The 5 fear and 5 disgust inducing videos used in the video ratings and reversal learning task are not shared here as they were ascertained from the Cowen and Keltner database.
This data-based and the videos are accessible via this online form: https://docs.google.com/forms/d/e/1FAIpQLScf9XVemSUWz6kUWySUdaQ5pxwqs8mugngrkBoLmX-3DMX1KA/viewform .
The videos we are using are (as named in the Cowen and Keltner database): 
    0046.mp4, 0374.mp4, 0548.mp4, 0877.mp4, 1202.mp4 (5 fear-inducing videos) 
    0888.mp4, 1414.mp4, 1765.mp4, 1987.mp4, 2106.mp4 (5-disgust inducing videos) 
    1686.mp4 (neutral/'safe' video used in all three blocks of the reversal learning task)
  

 All other stimuli necessary for the task are found in this repository - in the reversal_learning_stim folder(e.g., audios for the videos, yellow and blue background colours, fractals used in the reversal learning task).
  

Running the task: 
    digit_span_task.html and index.html files both run the tasks using jsPsych. The digit_span_task uses jspsych version 6.0.4 which can be downloaded from the jspsych website (https://github.com/jspsych/jsPsych/releases/download/v6.0.4/jspsych-6.0.4.zip), whilst index.html uses jspsych version 7.3.3 which requires no download. 
    Both tasks are hosted by jatos - so uploading the files to a jatos surver (see https://www.jatos.org/Whats-JATOS.html) is necessary to allow them to run. However, a minor modification of the code (namely, removing the lines of code that reference jatos - and adding back the commented-out code marked 'add in if not running using jatos') can allow both tasks to run as standalone html files.

 