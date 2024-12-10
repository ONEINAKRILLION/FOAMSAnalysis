# FOAMSAnalysis
### Files Used
1) Sub01-Sub21 contain raw data from each experimental trial, description below<br />
2) MisoAssessment contains data from misophonia assessments S5 and DMQ, as well as self-diagnosis of misophonia, gender, and age for each participant<br />
##2) Description of all variables in the datasets included from FOAMS Website (https://zenodo.org/records/7922615), with the ones kept after cleaning in bold and italics<br />
### Packages used<br />
tidyverse, afex, rstatix, emmeans, effsize, car, lsr<br />
### Subject Files<br />
***1. Sub: participant number***<br />
2. Block: block number<br />
	- first two trials were practice<br />
	- participants took a short break between blocks<br />
3. Trial: trial number<br />
***4. SoundCategory: broader sound taxonomy (for use in unrelated experiment)<br />
	- Oral_nasal: breathing, chewing gum, clearing throat, swallowing<br />
	- Non_oral_nasal: cutting food, flipping paper, dribbling ball, typing<br />
	- White_noise: pink noise (note: "white noise" was used for participant familiarity)<br />
	- Quiet: no sound***<br />
5. DistractorSound: sound stimulus presented, as found in Pilot_sound_stimuli folder<br />
6. SoundLabel: Correct answer to sound identification, as shown to participants<br />
7. SoundID: What participant identified the sound to be (given 10 options)<br />
8. SoundAccuracy: Whether or not participant's sound ID matched the correct label<br />
9. soundRT: Time on response screen before clicking Continue <br />
	- Includes response time to both sound ID + discomfort rating<br />
***10. AversiveRating: Rating of anxiety/discomfort felt during the sound<br />
	- Ranges from 0 (no discomfort) to 5 (max discomfort)***<br />
### MisoAssessment File Variables pulled from original MisoAssessment Data<br />
***1. SelfAssess: self-diagnosis of misophonia from original MisoAssessment csv (1=yes, 3=no)***<br />
***2. S5Sum: total of all S5 measures from original MisoAssessment csv***<br />
***3. SelfMiso: whether or not participant identified as having misophonia coded from SelfAssess (0=no, 1=yes)***<br />
***4. MisoStatus: whether or not the particpant has a S5 score of more than 87, coded by 1(more than 87) or 0(less than 87) from S5Sum***<br />
