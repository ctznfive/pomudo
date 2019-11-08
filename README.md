# pomudo



## Simple timer for Pomodoro Technique written in Bash with minimal dependencies

The Pomodoro Technique is a time management method developed by Francesco Cirillo in the late 1980s. The technique uses a timer to break down work into intervals, traditionally 25 minutes in length, separated by short breaks. 

There are six steps in the original technique:

    - Decide on the task to be done.
    - Set the pomodoro timer (traditionally to 25 minutes).
    - Work on the task.
    - End work when the timer rings and take a short break (5 minutes), then go to step 2.
    - After four pomodoros, take a longer break (30 minutes), then go to step 1.
    
    
## Installation
Simply place "pomudo"-file on your $PATH or run it by specifying the full path


## How to use
pomudo [-w m] [-b m] [-l m] [-h]
			-w m / --work m : time for work (default: 25 min)
			-r m / --rest m : time to rest (default: 5 min)
			-l m / --longrest m : time for longer break (default: 30 min)
			-h: print this help message
      
## Dependencies

bash, coreutils, paplay and notify-send (for notifications)
      

