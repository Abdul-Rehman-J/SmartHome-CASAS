Activities of Daily Living and Memory in Older Adulthood and Dementia

-> The sensors can be categorized by:

   Mxx:       motion sensor
   Ixx:       item sensor for selected items in the kitchen
   Dxx:       door sensor
   AD1-A:     burner sensor
   AD1-B:     hot water sensor
   AD1-C:     cold water sensor
   Txx:       temperature sensors
   P001:      whole-apartment electricity usage

-> The dataset contains passive and automatic sensing
data collected from 400 participants. Participant’s interaction
with the smart home is recorded with the help of a number of binary, digital, and
analog sensors like the motion sensor, door sensor, light sensor, temperature sensor,
burner sensor etc. The dataset contains instances of both simple and complex daily life
activities. 
-> Simple activities are defined as those that are performed in daily routine and
are not interwoven.
Number of Participants: 79
Mean Age: 66
Total Healthy: 65
Total Dementia: 14
Total Activities: 8
1: Sweeping the kitchen and dusting the living room.
2: Obtaining medicine containers and a weekly medicine dispenser, filling the dispenser according to the directions.
3: Writing a birthday card, enclosing a check and writing the address on an envelope.
4: Finding the appropriate DVD and watching the corresponding news clip.
5: Obtaining a watering can and watering all plants in the living space.
6: Answering the phone and responding to questions.
7: Preparing a cup of soup using the microwave.
8: Picking a complete outfit for an interview from a selection of clothing.


-> While complex activities represents interwoven activities like examine a bus schedule, plan a picnic etc.

Number of Participants: 179
Total Healthy: 145
Total Mild Cognitive Impaired: 32
Total Dementia: 2
Total Activities: 8
1: Magazine: Choose a magazine from the coffee table to read on the bus ride.
2: Heating pad: Microwave for 3 minutes a heating pad located in the kitchen cupboard to take on the bus.
3: Medication: Right before leaving, take motion sickness medicine found in the kitchen cabinet.
4: Complex Interwoven Activities of Daily Life Bus map: Plan a bus route using a provided map, 
determine the time that will be needed for the trip and calculate when to leave the house to make the bus.
5: Change: Gather correct change for the bus.
6: Recipe: Find a recipe for spaghetti sauce in the recipe book and collect ingredients to make the sauce with
your friend.
7: Picnic basket: Pack all of the items in a picnic basket located in the closet.
8: Exit: When all the preparations are made, take the picnic basket to the front door.

Our dataset contains 24 daily life activities, where first 8 activities represent the simple
daily life tasks, and the last 8 activities represent the complex daily life interwoven
tasks. Activities from 9 - 16 are also daily life activities but without a label, since
our focus is on classification, therefore these activities are not considered in the current
study. 

Both Code file are placed in simple and complex activities folder.
All the code is well commented and easy to read.

-> Evaluation and Discussion
We evaluate the performance of five learning models NB, J48, MLP, SMO, Adaboost
on smart home dataset. We choose four evaluation measure for performance
analysis: Area Under Curve (ACU), F-Score, Recall, and Accuracy.

We got the better accuracy from state of the art using Information Gain feature selection,
SMOTE, Ensemble method and Adaboost classifier.