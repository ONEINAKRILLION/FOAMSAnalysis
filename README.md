# FOAMSAnalysis
##1) Description of files
1) Sub01-Sub21 contain raw data from each experimental trial, description below
2) MisoAssessment contains data from misophonia assessments S5 and DMQ, as well as self-diagnosis of misophonia, gender, and age for each participant
##2) Description of all variables in the datasets included from FOAMS Website (https://zenodo.org/records/7922615), with the ones kept after cleaning in bold and italics
### Packages used
tidyverse, afex, rstatix, emmeans, effsize, car, lsr
### Subject Files
***1. Sub: participant number***
2. Block: block number
	- first two trials were practice
	- participants took a short break between blocks
3. Trial: trial number
***4. SoundCategory: broader sound taxonomy (for use in unrelated experiment)
	- Oral_nasal: breathing, chewing gum, clearing throat, swallowing
	- Non_oral_nasal: cutting food, flipping paper, dribbling ball, typing
	- White_noise: pink noise (note: "white noise" was used for participant familiarity)
	- Quiet: no sound***
5. DistractorSound: sound stimulus presented, as found in Pilot_sound_stimuli folder
6. SoundLabel: Correct answer to sound identification, as shown to participants
7. SoundID: What participant identified the sound to be (given 10 options)
8. SoundAccuracy: Whether or not participant's sound ID matched the correct label
9. soundRT: Time on response screen before clicking Continue 
	- Includes response time to both sound ID + discomfort rating
***10. AversiveRating: Rating of anxiety/discomfort felt during the sound
	- Ranges from 0 (no discomfort) to 5 (max discomfort)***
### MisoAssessment File Variables pulled from original MisoAssessment Data
***1. SelfAssess: self-diagnosis of misophonia from original MisoAssessment csv (1=yes, 3=no)***
***2. S5Sum: total of all S5 measures from original MisoAssessment csv***
***3. SelfMiso: whether or not participant identified as having misophonia coded from SelfAssess (0=no, 1=yes)***
***4. MisoStatus: whether or not the particpant has a S5 score of more than 87, coded by 1(more than 87) or 0(less than 87) from S5Sum***
