# experiment-generation
This Python program generates names of experimental trials based on a letter code system and can be adapted to any experiment. Specifically, users can specify a two-letter naming system for trials where each letter represents a condition.
This program will randomly generate a set of trials, each with 2 conditions for each participant, "translate" the letter code system to the actual conditions by using a user-specified
dictionary, and will print the shuffled list of trials for the participant.

---

**Usage**\
Replace ``route`` and ``distractions`` to contain whatever conditions needed. Replace ``route_dict`` and ``distractions_dict`` to contain 
"translations" of letters. Change the 3 and 2 in samples to change how many trials are wanted for each participant. Specifically, with the current code,
for each participant, the program will generate a set of trials that combine any of two routes with any of three distractions (for a total of six trials.)
If the user wants just one trial per participant, change these numbers to 1 and 1. If the user wants all possible trials per participant, change
these numbers to represent the total number of route trials and total number of distractions trials.

**Requirements** \
``random``
