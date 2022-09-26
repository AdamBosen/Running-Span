# Running-Span
Website built in javascript using the jsPsych library to test memory in a running span task. A running example of the most recent version of this script can be found here: https://jatos.boystown.org/publix/jVa581wM7W6

This script was developed in jsPsych 7.2.1, which can be downloaded here: https://github.com/jspsych/jsPsych/releases/tag/jspsych%407.2.1 . It probably works with newer versions of jsPsych, but I haven't tested it.

If you want to run this program locally you will need to run a local web server so the GET request for the sequence file is not blocked. I use the Web Server For Chrome app for debugging purposes, but you may want to do some research and decide what works best for you. When testing participants, we use a version of this program hosted on cognition.run

Once you have downloaded jsPsych, the VisualRunningSpan.html file, and the Demo.txt expeirmental sequence, you can open the website in a web browser through your server and it should bring up the task instructions.

This script implements a visual numerical running span task based on a blend of Cowan et al. (2006, J Mem Lang) and Broadway and Engle (2010, Behavior Research Methods). Each trial shows on screen a rapid sequence of between 12 - 21 digits (300 ms per digit, 200 ms between digits), one at a time. The goal is to remember as many numbers from the end of the list as possible, and type them in the text box in order. Each trial is defined by a single line in the experimental sequence file, and each character will be shown on screen in sequence. We will share the full experimental sequence and scripts for scoring data on request (adam.bosen@boystown.org).
