# Makerere-Passion-Fruit-Disease-Detection
Makerere Passion Fruit Disease Detection

escription
Passion fruit pests and diseases in Uganda lead to reduced yields and decreased investment in farming over time. Most Ugandan farmers (including passion fruit farmers) are smallholder farmers from low-income households, and do not have sufficient information and means to combat these challenges. Without the required knowledge about the health of their crops, farmers cannot intervene promptly to avoid devastating losses.

The Marconi Society Machine Learning Laboratory at Makerere University is addressing the lack of a reliable, timely diagnostic platform for passion fruit diseases by developing a low-cost hand-held diagnostic device (based on the Raspberry Pi) making use of state-of-the-art machine learning techniques.

In this challenge, you will classify the disease status of a plant given an image of a passion fruit. If successful, this model will be deployed as part of a device to aid smallholder farmers in making a prompt diagnosis in their passion fruit crops.

About The Marconi Society Machine Learning Laboratory (ml.netlabsug.org)


The Marconi Society Machine Learning Laboratory, Makerere University is a research initiative of netLabs! UG, Makerere University that focuses on machine learning research in diverse areas including Agriculture, Health and Natural Language Processing.

About Makerere University Research Innovations Fund (RIF) (rif.mak.ac.ug)


This work is supported by the Makerere University Research Innovations Fund (RIF),  a Microsoft AI 4 Earth Grant, and a Labelbox education license.

Rules
Teams and collaboration

You may participate in competitions as an individual or in a team of up to four people. When creating a team, the team must have a total submission count less than or equal to the maximum allowable submissions as of the formation date. A team will be allowed the maximum number of submissions for the competition, minus the total number of submissions among team members at team formation. Prizes are transferred only to the individual players or to the team leader.

Multiple accounts per user are not permitted, and neither is collaboration or membership across multiple teams. Individuals and their submissions originating from multiple accounts will be immediately disqualified from the platform.

Code must not be shared privately outside of a team. Any code that is shared, must be made available to all competition participants through the platform. (i.e. on the discussion boards).

The Zindi user who sets up a team is the default Team Leader. The Team Leader can invite other data scientists to their team. Invited data scientists can accept or reject invitations. Until a second data scientist accepts an invitation to join a team, the data scientist who initiated a team remains an individual on the leaderboard. No additional members may be added to teams within the final 5 days of the competition or the last hour of a hackathon, unless otherwise stated in the competition rules

A team can be disbanded if it has not yet made a submission. Once a submission is made individual members cannot leave the team.

All members in the team receive points associated with their ranking in the competition and there is no split or division of the points between team members.

Datasets and packages

The solution must use publicly-available, open-source packages only. Your models should not use any of the metadata provided.

You may use only the datasets provided for this competition. Automated machine learning tools such as automl are not permitted.

If the challenge is a computer vision challenge, image metadata (Image size, aspect ratio, pixel count, etc) may not be used in your submission.

You may use pretrained models as long as they are openly available to everyone.

The data used in this competition is the sole property of Zindi and the competition host. You may not transmit, duplicate, publish, redistribute or otherwise provide or make available any competition data to any party not participating in the Competition (this includes uploading the data to any public site such as Kaggle or GitHub). You may upload, store and work with the data on any cloud platform such as Google Colab, AWS or similar, as long as 1) the data remains private and 2) doing so does not contravene Zindi’s rules of use.

At the end of the competition the dataset will be publicly available.

You must notify Zindi immediately upon learning of any unauthorised transmission of or unauthorised access to the competition data, and work with Zindi to rectify any unauthorised transmission or access.

Your solution must not infringe the rights of any third party and you must be legally entitled to assign ownership of all rights of copyright in and to the winning solution code to Zindi.

**Submissions**

You may make a maximum of 10 submissions per day.

You may make a maximum of 300 submissions for this project.

Before the end of the project you need to choose 2 submissions to be judged on for the private leaderboard. If you do not make a selection your 2 best public leaderboard submissions will be used to score on the private leaderboard.

These models often need to be applied at scale, so large ensembles aren’t encouraged. To incentivise more lightweight solutions, we are adding an additional submission criteria: your submission should take a reasonable time to train and run inference. Specifically, we should be able to re-create your submission on a single-GPU machine (eg Nvidia P100) with less than 8 hours training and one hour inference.

Zindi maintains a public leaderboard and a private leaderboard for each competition. The Public Leaderboard includes approximately 30% of the test dataset. While the competition is open, the Public Leaderboard will rank the submitted solutions by the accuracy score they achieve. Upon close of the competition, the Private Leaderboard, which covers the other 70% of the test dataset, will be made public and will constitute the final ranking for the competition.

Note that to count, your submission must first pass processing. If your submission fails during the processing step, it will not be counted and not receive a score; nor will it count against your daily submission limit. If you encounter problems with your submission file, your best course of action is to ask for advice on the Competition’s discussion forum.

If you are in the top 20 at the time the leaderboard closes, we will email you to request your code. On receipt of email, you will have 48 hours to respond and submit your code following the submission guidelines detailed below. Failure to respond will result in disqualification.

If your solution places 1st, 2nd, or 3rd on the final leaderboard, you will be required to submit your winning solution code to us for verification, and you thereby agree to assign all worldwide rights of copyright in and to such winning solution to Zindi.

If two solutions earn identical scores on the leaderboard, the tiebreaker will be the date and time in which the submission was made (the earlier solution will win).

If the error metric requires probabilities to be submitted, do not set thresholds (or round your probabilities) to improve your place on the leaderboard. In order to ensure that the client receives the best solution Zindi will need the raw probabilities. This will allow the clients to set thresholds to their own needs.

The winners will be paid via bank transfer, PayPal, or other international money transfer platform. International transfer fees will be deducted from the total prize amount, unless the prize money is under $500, in which case the international transfer fees will be covered by Zindi. In all cases, the winners are responsible for any other fees applied by their own bank or other institution for receiving the prize money. All taxes imposed on prizes are the sole responsibility of the winners. The top 3 winners or team leaders will be required to present Zindi with proof of identification, proof of residence and a letter from your bank confirming your banking details.

Payment will be made after code review and an introductory call with the host.

You acknowledge and agree that Zindi may, without any obligation to do so, remove or disqualify an individual, team, or account if Zindi believes that such individual, team, or account is in violation of these rules. Entry into this competition constitutes your acceptance of these official competition rules.

Zindi is committed to providing solutions of value to our clients and partners. To this end, we reserve the right to disqualify your submission on the grounds of usability or value. This includes but is not limited to the use of data leaks or any other practices that we deem to compromise the inherent value of your solution.

Zindi also reserves the right to disqualify you and/or your submissions from any competition if we believe that you violated the rules or violated the spirit of the competition or the platform in any other way. The disqualifications are irrespective of your position on the leaderboard and completely at the discretion of Zindi.

Please refer to the FAQs and Terms of Use for additional rules that may apply to this competition. We reserve the right to update these rules at any time.

**Reproducibility of submitted code**
If your submitted code does not reproduce your score on the leaderboard, we reserve the right to adjust your rank to the score generated by the code you submitted.
If your code does not run you will be dropped from the top 10. Please make sure your code runs before submitting your solution.
Always set the seed. Rerunning your model should always place you at the same position on the leaderboard. When running your solution, if randomness shifts you down the leaderboard we reserve the right to adjust your rank to the closest score that your submission reproduces.
We expect full documentation. This includes:
All data used
Output data and where they are stored
**Explanation of features used**
A requirements file with all packages and versions used
Your solution must include the original data provided by Zindi and validated external data (if allowed)
All editing of data must be done in a notebook (i.e. not manually in Excel)
Environment code to be run. (e.g. Google Colab or the specifications of your local machine)
Expected run time for each notebook. This will be useful to the review team for time and resource allocation.
Data standards:

Your submitted code must run on the original train, test, and other datasets provided.
If external data is allowed, external data must be freely and publicly available, including pre-trained models with standard libraries. If external data is allowed, any data used should be shared with Zindi to be approved and then shared on the discussion forum. Zindi will also make note of the external data available on the data page.
Packages:
You must submit a requirements file with all packages and versions used.
If a requirements file is not provided, solutions will be run on the most recent packages available.
Custom packages in your submission notebook will not be accepted.
You may only use tools available to everyone i.e. no paid services or free trials that require a credit card.



**Evaluation**
The error metric for this competition is Mean Average Precision @ Intersection over Union(IoU) threshold -0.5.

**Your submission file should look like this:**

Image id     class             confidence  ymin  xmin  ymax  xmax
ID_2TZLLT80  fruit_woodiness        0.5     130   12    340   300
Image_Id: is the Id assigned to each image. Note, that each image can have more the one object , which translates to more than one bounding box.
Class: is the particular bounding box classification, i.e.,, fruit woodiness, fruit healthy or fruit woodiness.
Confidence score: each object detector model gives the confidence score of each bounding box predicted in an image; this value is used to sort the bounding boxes.
(ymin, xmin, ymax, xmax) (<left> <top> <right> <bottom> ): The values of the bounding box as per the PASCAL implementation. The train data has(xmin, ymin, width, height), incase your model does produce the same structure, you need to convert it the required format.
You may submit a maximum of 4 bounding boxes per image.

These models often need to be applied at scale, so large ensembles aren’t encouraged. To incentivise more lightweight solutions, we are adding an additional submission criteria: your submission should take a reasonable time to train and run inference. Specifically, we should be able to re-create your submission on a single-GPU machine (eg Nvidia P100) with less than 8 hours training and one hour inference.

Please note that we will not tell you if you are missing an image in your submission file. You will need to make sure you have submitted a prediction for each image.



**Timeline**
Submission closes on 21 November 2021.

Final submissions must be received by 11:59 PM GMT.

****Data****
**About**
The dataset contains about 4000 images resized to 512x512. There are ~5000 fruit in total. Some images contain more than one fruit and thus more than one bounding box. The images are annotated using bounding boxes defined in a COCO format and each bounding box is tagged to one of three classes: fruit_healthy, fruit_brownspot and fruit_woodiness.

The images were collected from the Eastern, Western and Central regions of Uganda. The image capturing process involved guidance from National Crop Resources Research Institute (NaCRRI) passion fruit disease experts, who identified the disease manifestation in the fruits of passion fruit plants.

The objective of this challenge is to classify the disease status of a plant given an image of a passion fruit. You need to classify each fruit individually and not assume that all the fruit in the same image have the same status.

**Files available for download:**

Train_Images.zip - contains the ~3000 resized (512x512) images.
Test_Images.zip - contains ~ 1000 images resized (512x512) images.
Train.csv - contains the image IDs that are in the train set and the label (fruit_healthy, fruit_brownspot or fruit_woodiness) target. You will use this dataset to select the images from Train_Images.zip to train your model on.
Test.csv- contains image IDs for the test set. You will use this dataset to select the images from Test_Images.zip to apply your model to.
SampleSubmission.csv - shows the submission format for this competition, with the ‘Image_ID’ column mirroring that of Test.csv. The order of the rows does not matter, but the names of the‘Image_ID’must be correct. You may submit a maximum of 4 bounding boxes per image.
Files
**DESCRIPTION**
**FILES**

Train.csv 191.8 KB

Test_Images.zip 36.4 MB

Train_Images.zip292.9 MB

Sample_submission.csv 16.4 KB
Test.csv 10.9 KB

PassionfruitStarterNotebook.ipynb 608.5 KB

https://zindi.africa/competitions/makerere-passion-fruit-disease-detection-challenge
