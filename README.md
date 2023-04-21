# Spontaneous and acquired spatial-numerical association in honeybees (Apis mellifera) reveals a rightward bias for the Mental Number Line 

Jung-Chun (Zaza) Kuo1, Leslie Ng1†, Devi Stuart-Fox1†, Adrian G Dyer2† & Scarlett R Howard3†* 

1School of BioSciences, University of Melbourne, Melbourne, Victoria, Australia. 

2Department of Physiology, Monash University, Clayton, Victoria, Australia. 

3School of Biological Sciences, Monash University, Clayton, Victoria, Australia. 

*Author for correspondence – Scarlett R Howard scarlett.howard@monash.edu 

† Equal contribution 

Jung-Chun (Zaza) Kuo - 0000-0002-6158-1561 

Leslie Ng - 0000-0001-5973-1367 

Devi Stuart-Fox - 0000-0003-3362-1412 

Adrian G Dyer - 0000-0002-2632-9061 

Scarlett R Howard - 0000-0002-1895-5409 

This readme file describes the data files accompanying the above publication. For any
further queries please contact scarlett.howard@monash.edu
The following files are included:

1) "1-42.csv"

This file contains the individual choices made by honeybees during the Experiment 1. The columns are
as follows:

* beeID: individual bee recruited from the hive 
* choicenum: choice number, bees made 10 choices in each test type (small number vs big number AND UD vs LR)
* number: "small" = small number test (2 elements on the stimuli); "big" = big number test (4 elements on the stimuli)
* choice: bees chose the stimulus on the left side or right side/ top or bottom. "0" = right and "1" = left in LR test. "0" = down and "1" = up in UD test
* test_type: the stimuli were present vertically or horizontally. "UD" = vertical presentation; "LR" = horizontal presentation 

2) "28-42 UD.csv"
This file contains individual choices made by bee no. 28 - 42  during the Experiment 1. The columns are
as follows:
* beeID: individual bee recruited from the hive 
* choicenum: choice number, bees made 10 choices in each test type (small number vs large number)
* number: "small" = small number test (2 elements on the stimuli); "large" = big number test (4 elements on the stimuli)
* choice: bees chose the stimulus on the top or bottom. "0" = down and "1" = up in UD test

3) "1-42 LR.csv"
* bee_id: individual bee recruited from the hive 
* trial: trial number, same as "choicenum" in previous files. Bees made 10 trials in each test type (small number vs large number)
* choice: bees chose the stimulus on the left side or right side. "0" = right and "1" = left in LR test.

4) "part 2_training.csv"
* bee_id: individual bee recruited from the hive 
* group: type of training the bee underwent. "LR" = the bee was trained to choose the small number on the left and the large number on the right; "RL" = the bee was trained to choose the small number on the right and the large number on the left
* trial: trial number. Each bee underwent 40 training.
* choice: "1" = correct choice; "0" = incorrect choice
* block: trials in grouped into block of 10

5) "part 2_testing.csv"
* bee_id: individual bee recruited from the hive 
* group: type of training the bee underwent. "LR" = the bee was trained to choose the small number on the left and the large number on the right; "RL" = the bee was trained to choose the small number on the right and the large number on the left
* test_type: what type of test did bees undergo. Learning test is we tested the bees with the same elements we used for training (2 elements for small number and 4 elements for large number). Transfer test is we tested the bees with novel elements (1 element for small number and 5 elements for large number) "LTS" = learning test with small number; "LTB" = learning test with large number; "TTS" = transfer test with small number; "TTB" = transfer test with large number
* trial: trial number. Each bee underwent 10 trial for each test type (LTS; LTB; TTS; TTB).
* choice: "1" = correct choice; "0" = incorrect choice
* test: test type. "LT" = learning test; "TT" = transfer test
