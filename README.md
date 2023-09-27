# ViSATUI

Welcome to the repository for the Visual Semantic Association Task (ViSAT).

## Task description

ViSAT is an image-based task that tests the ability to associate the content between images based on factual/general long-term knowledge about them. The ViSAT task specifically targets non-verbal semantic memory. There are no requirements of sound, speech, reading, or writing to perform the task. 

As an example, one might associate an image of a squirrel would be most-associated with an image of a nut compared to images of a potato, corn, or a carrot. In this example, the squirrel image would be called the "stimulus" and the other 4 images are called the "answer" images.

![Example of a trial using a squirrel as the stimulus.](assets/squirrel.png)

## Task development

The task was adapted from concepts and similar stimuli as the Pyramids and Palm Trees (PPT) and Camels and Cactus (CCT) tasks, yet with a variety of features changed:
1. We used new color and picture images from royalty-free stock photo repositories online (pexels.com, pixabay.com, and unsplash.com).
2. To increase the potential generalizability of ViSAT across participants of all backgrounds (age, language, education, literacy levels, and socioeconomic status), we avoided religious, generation-specific, culture-specific, outdated, and potentially offensive references. 
3. To decrease the confounding influences from visuospatial processing, we strived to avoid consistencies in color, size, and shape between stimuli and answers.
4. Since semantic associations can vary between participants based on factors such as personal experiences and backgrounds. Instead of deciding amongst ourselves which answer was "correct") we obtained normative data and quantified the proportion of responses for each choice, convening on a “consensus” (top) answer as the “accurate” response.
5. The percent consensus (PCons) of the top answer can therefore be used as a difficulty metric for statistical modeling if desired.

## User interface

The ViSAT task is delivered by a computer interface, and the software and all stimuli are included in this public repository. 

![Picture of the user interface used to administer the task.](assets/user_interface.png)

There are three phases for each trial:
1. A fixation dot is displayed in the center of the screen for 2 to 3 seconds (duration randomly jittered).
2. The stimulus image is displayed, and the subject is required to click on it
3. The four answer choices are displayed, and the subject is required to click on the image that is most associated with the stimulus image

![Picture displaying the task workflow, including the fixation point, the stimulus and the answers.](assets/workflow.png)

There are four blocks of 25 trials each, for a total of 100 trials. 
Each block begins with the same three "practice trials" (not scored) to allow acclimation prior to the actual set of 25 trials. 
Blocks are balanced in terms of difficulty (similar average trial PCons), and thus can be done at different timepoint for longitudinal comparison.

## Behavioral metrics

Behavioral metrics provided by the user interface:
1. Response time for clicking the stimulus (no semantic processing requirement)
2. Response time for clicking the answer (semantic processing required)
3. Accuracy (whether consensus/most common answer was chosen)

## Tips

Here are a few tips to make the administration of the task as easy as possible: 
- Emphasize to the the subject beforehand that they must pick the answr that is most associated using their general knowledge about those objects, not the color, shape, texture, or other visual feature. 
- Behavioral timelocking with neural data amplifiers (for example, EEG experiments) can be done using a photodiode analog input. A photodiode option is available on the UI (checkbox at lower left) which enables grey-scale light transitions at top left that can be tracked with a screen-mounted photodiode.

## Cite

The scientific manuscript describing the ViSAT task is currently submitted; upon publication the direct citation will be listed here.
