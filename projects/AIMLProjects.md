
---
layout: project
type: project
image: img/AIMLProjects/customGPT1.png
title: "Custom GPTs 2025"
date: 2025
published: false
labels:
  - Javascript
  - Meteor
  - GitHub
summary: "Custom GPTs- Used Car Matchmaker || Marshall Islands Text Corrections."
---

<img class="img-fluid" src="../img/customGPT/customGPT1.png">

header - Custom GPT #1 Marshall Islands Text Editor

In this project, the team was tasked with finding and implementing a system that takes handwritten letters, scans (OCRs) them and returns the contents of the letters in a searchable format.  One of the major difficulties with implementing one of the many already-existing programs was in the lack of accuracy with the scanning process.  Our team experienced about 50-60% accuracy, which was worsened by the fact that many proper nouns and writing style nuances were missed given the vernacular and the source of the letters.  

To solve this I implemented a custom-GPT model through openAI.  The GPT would take the raw OCR'd contents of a letter.  As reference, the GPT was provided a database of words that pertain to the time / place of these letters.  This included various nicknames/translations of places, islands that compiled into a very narrow-scope vernacular database.  The GPT would utilize the database to compare misspellings, as well as the context and sentence structure to provide corrections.  

As output, the GPT is not allowed to correct grammar or sentence structure, only misspelled words.  Furthermore, the GPT would maintain any and all line breaks in order to facilitate returning the corrected data over to the initial scanning program.  Lastly, there was a summary of the corrections conducted.  This made it so that a person could quickly validate the quality of corrections and drastically saved time in overall process.  

Overall, this resulted in a jump from about 50-60% to >90% accuracy of the letter transcriptions.  The GPT is still in use at the University of Hawai'i at Manoa by the Anthropology department.


header - Used Car Matchmaker

In the US alone, there are over 1000 car models to choose from.  The search for a used car usually requires a person to know what they're looking for so they do not simply fall prey to their closest car dealer or the most sponsored search result.  This, coupled with the fact that there is a wide spectrum of consumers' "car knowledge," I sought out to create an easier way to find a used car.

My implemented GPT model provides recommendations based on a simple premise:  What are you driving now, and what do/don't you like about it.  

The recommendations are designed to be scaled and reasonable.  For example, if someone has a hatchback, and wants more space, the recommendation may be a mid-size or full size sedan, and won't immediately suggest buying an Econoline.  If the user wants more speed, a 4 cylinder becomes a 6 cylinder not a V12.  The outputted recommendations are in a tabular form, allowing the user to see 3 recommendations and how they align with what improvements they'll see in their future car.  


The GPT model is for public use (with access to openAI).  
