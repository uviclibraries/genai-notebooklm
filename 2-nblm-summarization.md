---
layout: default
title: 2 - NotebookLM Summarization Use Cases
nav_order: 7
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
--- 
# Summarizing Text, Audio, & Video 
<img src="images/nblm-summarize-text2.gif" style="float:right;width:400px;padding:10px;" alt="GenAI summarizing text abstract Logo">
In this workshop, we'll explore how GenAI can help you quickly summarize meeting notes, including action items. We'll also discover how to customize these summaries by adjusting the tone, style, and language level. Have you ever needed to create a summary in a different language for a colleague or student? We'll show you how AI can translate your text with ease. 

> NOTE: Like all other Generative AI tools, NotebookLM will sometimes make mistakes, although because you are providing it with training data, it will likely make fewer mistakes than general purpose Generative AI tools. Always research any factual claims it makes if you are not a subject area expert. 

If you have any questions or get stuck as you work through this exercise, please ask the instructor for assistance.

## Summarize a Single Journal Article with a Purpose in Mind
Instead of summarizing all three journal articles we're going to direct NoteBookLM to summarize just one of the articles and then give it a specific focus for the summary to assist us in drafting promotional materials for a University Library Makerspace (or Library Digital Scholarship Commons).
1. De-select articles 2 and 3 in the Sources area on the left side of the web page.
<img src="images/nblm-deselect-articles.png" style="width:500px;padding:10px;border: 1px solid #555;" alt="NotebookLM deselect articles"><br>
2. In the chat area type: ```Create a promotional message to parents explaining how the University Makerspace (or Library Digital Scholarship Commons) can help their children with job searches for co-op positions and for their post-graduation job search.```
   - Does the text NoteBookLM response look helpful?
   - Are there any inaccuracies?
   - Feel free to give it follow-up prompts if you notice anything you'd like changed (or you could manually change the message yourself of course in your favourite document editor.
3. Let's assume that the message is accurate and the tone is appropriate but is too long. Let's ask NotebookLM to make it shorter:
   - In the chat area type: ```Shorten the promotional message to 100 words.```
   - How does that look? Maybe too short?
   - Let's try again and make it a little bit longer: ```Shorten the promotional message to 150 words.```
   - How does it look now? Better? Worse? Feel free to play around with this giving NotebookLM additional instructions on length, tone, and audience (maybe have it craft a message for students duing their first week of classes?)
4. Can you think of any other ways you could summarize the journal article for a specific purpose?
   - How about summarizing it for 5 key points for an academic poster you need to create based on an article you wrote: ```Provide me with 5 one-sentence bullet points to help me create an academic poster for a Makerspace conference poster session.``
   - Does the text NoteBookLM response look helpful?
   - Are there any inaccuracies?
   - Feel free to give it follow-up prompts of course
5. You have been invited to speak to a group of grade 5 students about the research you did on Makerspace badging (assuming you wrote the article that is selected in NotebookLM).
   - In the chat area type: ```Summarize the article into a 10-minute speech for a group of grade 5 students. Make the speech upbeat and engaging. Include a short story to illustrate how fun makerspaces are and how badges are cool and helpful.```
   - Does the text NoteBookLM response look helpful?
   - Are there any inaccuracies?
   - Feel free to give it follow-up prompts if you notice anything you'd like changed (or you could manually change the message

## Summarize Meeting Notes & Create Action Items
We're going to summarize a transcription of a meeting held via Zoom for a fictitious "Makerspace Executive Weekly Meeting" in a new notebook:
1. Create a new notebook:
   - Click on the **NotebookLM logo** on the top right of the screen, which will take you out of the current notebook and to the main NotebookLM screen.
   - Click on the blue **Create new** button on the left side of the screen. You're in a new notebook now.
<img src="images/nblm-new-notebook3.gif" style="width:800px;padding:10px;border: 1px solid #555;" alt="Try NotebookLM button"><br>
2. Add the PDF of the meeting notes:
   - Download the meeting transcription document to use as training data for your notebook in this activity, and please make note of where your web browser is saving them (usually in your Downloads or Desktop folders): [Meeting Transcription](images/nblm-meeting-notes.pdf){:target="_blank"}
   - Upload the Meeting document you downloaded by clicking on the blue **choose file** link in the middle of the page, then **navigate** to where you just downloaded the document, **select the document** and **open it**.
3. Ask NotebookLM for a summary:
   - In the chat area type: ```Summarize the meeting transcript into a summary in bullet point form.```
     - How do the meeting notes look? Do they look like an accurate summary of the meeting?
   - Maybe you want more details, so type this in the chat: ```Give me more details.```
5. Lastly let's generate a list of action items to be completed by individuals as well as unassigned action items:
   - Type in the chat area: ```Create a detailed bullet point action item list of action items to be completed by individuals as well as unassigned action items.```
   - How do the action items look for completeness?
   - Any missed assigned action items?

> NOTE: Always ask someone who attended the meeting (and was paying attention) to double-check the meeting notes and action items. 
   
## Translated Summaries & Action Items
1. Let's translate the meeting summary into Portuguese:
   - In the chat area type: ```Create a detailed meeting summary in Portuguese.```
     - Unless you speak Portuguese you'll have a hard time evaluating the results, but in my experience, the translation was quite accurate in this case.
   - In the chat area type: ```Create a detailed bullet point action item list of action items to be completed by individuals as well as unassigned action items in Portuguese.```
   - Now try to translate the meeting notes into a different language, if possible a language that you speak.
     - How did it do? Was the translation accurate?

## Try Summarizing Your Own Class Notes or Lecture Presentations
1. Why don't you try summarizing your own class lecture notes:
   - Start by creating a new notebook and importing notes from one lecture or multiple lectures.
   - You can also add Lecture Presentation slide decks to notebooks, but they have to be in either PDF or Google Slides format for NotebookLM to "read" them NOTE: You can easly convert PowerPoint Presentations into Google Slides format (just google it and you'll find a number of how-to guides).

## Summarize YouTube Videos
   - NoteBook LM will also summarize one YouTube video, or multiple YouTube videos... Give it a try in a new notebook!

[NEXT STEP: Brainstorming Stragegies](3-nblm-brainstorming.html){: .btn .btn-blue }
