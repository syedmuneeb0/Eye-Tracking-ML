# Eye-Tracking-ML
Eye Tracking Dataset for Autism


Longitudinal eye tracking experiments to study Autism Spectrum Disorder (ASD).
This Dataset contains 25 CSV files and 1 metadata file

Autism Spectrum Disorder (ASD) is a condition that affects how a person communicates, interacts with others, and experiences the world. It is called a “spectrum” because different people experience it in different ways; some may have mild challenges, while others may need more support.

Now, about the eye-tracking dataset:
Metadata: This has 5 columns. Participant ID, Gender, Age, Class, CARS Score.
Class represents whether the child has the disorder or not by mentioning ASD or TD
CARS Score is a Childhood Autism Rating Scale (CARS) is a tool used to assess autism in children. It helps clinicians determine the severity of autism symptoms by evaluating behaviors across different categories.

How CARS Works
The scale consists of 15 behavioral areas, including social interactions, communication, emotional response, and sensory sensitivities.
Each category is rated on a scale from 1 to 4, with higher scores indicating more pronounced autism-related behaviors.
The total score determines whether a child falls into non-autistic, mildly autistic, moderately autistic, or severely autistic categories.
CARS Score Interpretation
Below 30 → Likely not autistic.
30-36.5 → Mild to moderate autism.
Above 36.5 → Severe autism.
Since you're working with eye-tracking datasets for ASD detection, CARS could be useful for validating behavioral metrics in your research.
 Foundational Eye-Tracking Concepts
Eye tracking captures visual attention patterns through metrics like:
Fixations: Pauses in eye movement (≥100 ms) indicating focused attention. Critical for studying ASD’s social attention deficits 15.
Saccades: Rapid eye movements between fixations. ASD individuals often show atypical saccadic patterns 7.
Pupil Dilation: Linked to cognitive load/arousal. ASD may exhibit abnormal pupillary responses to social stimuli 15.
Gaze Coordinates: Spatial attention (e.g., reduced eye-region focus in ASD) 7.


Category group has: Information and Eye rows
Category right and left group has :Separator, Fixation Saccade and Blink rows
There are 59 participants so they are designated a unique number each hence the column participants
Participants column also has Unidentified neg and Unidentified positive rows nearly 4k out of 37000 total rows
Colour indicates the color of the pupil
Index right and left has only one value i.e. "1"

Concatenating CSV files into one master file:
Why Do We Need to Concatenate Multiple CSV Files?
If you're working with datasets split into multiple CSV files—for example, monthly financial data, separate patient records, or logs from different sources—you need to combine them into one master dataset. Concatenation helps:
Standardize data processing by working on a single dataset.
Improve efficiency instead of managing multiple files separately.
Enhance analysis by having all records in one place for statistical modeling or machine learning.
