---
layout: answer
title: Importing Aiken Formatted Questions
topic: moodle
question: How can I import quiz questions from a file?
---
<!-- this explanation isn't very good but it's taken from the official moodle docs -->
# Importing Aiken Formatted Questions

Rather than creating individual questions in Moodle you can have multiple questions constructed in a text document that you can then import into Moodle. The Aiken Format provides you with an easy way to import multiple choice questions into Moodle.

First, open the document that contains your multiple choice questions. Then, format your document in the Aiken Format. The Aiken format is a very simple way of creating multiple choice questions using a clear human-readable format. The question must be all on one line. Each answer must start with a capitalized single-letter character, followed by a period '.' or a bracket ')', then a space. Whichever you choose to use, it must be consistent thoughout the document. The answer line must immediately follow, starting with "ANSWER: " (NOTE: space after: the colon, and all capitalized letters) and then provide the correct answer letter. To separate each question, place only one line space between each new question. Here is an example of the format:

```
What is the correct answer to this question?
A. Is it this one?
B. Maybe this answer?
C. Possibly this one?
D. Must be this one!
ANSWER: D

Which LMS has the most quiz import formats?
A) Moodle
B) ATutor
C) Claroline
D) Blackboard
E) WebCT
F) Ilias
ANSWER: A
```

Notes:
 - The answer letters (A,B,C etc.) and the word "ANSWER" must be capitalized as shown otherwise the import will fail. 
 - There must be a space between the lettering and "." and the answer as shown otherwise the import will fail.
 - Use Notepad to edit your Aiken document. MS Word and other rich text editors add formatting that will interfere.

[More information about the Aiken format can be found on the Moodle Docs.](https://docs.moodle.org/39/en/Aiken_format)
