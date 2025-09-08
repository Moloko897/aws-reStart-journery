# Amazon Lex Chatbot
# Objective

The goal was to design a quiz chatbot in Amazon Lex for CloudLearners Inc. that:

-Tests learners’ knowledge of Amazon S3.

-Provides immediate feedback (correct/incorrect).

-Uses branching logic to guide the conversation.

-Creates an engaging and interactive learning experience.

# Steps Taken

Intent Creation - Built an intent called quiz with utterances such as “Start quiz”, “Hi, Tell me about S3”.

Question Setup - Added the first multiple-choice question with answer slots (A/B/C).

Branching Logic - Configured slot capture success to provide different responses for correct vs incorrect answers.

Additional Questions - Linked follow-up quiz questions with conditional branching.

Feedback & Flow - Ensured the bot gives feedback before moving to the next question.

Testing  - Build and Tested the bot in Lex console.

# Challenges

Answer Slot Handling – Making sure multiple-choice responses (A/B/C) were captured correctly instead of defaulting to Yes/No.

Conversation Flow Control – Ensuring branching logic delivered correct/incorrect feedback before moving on to the next question.

# Screenshot

# Successfully created an S3Bot

<img width="1891" height="897" alt="s3Bot" src="https://github.com/user-attachments/assets/f967c48b-425e-41fb-8992-3d567b3b12a0" />


# Error: Couldn’t build language English (South Africa) in bot: SSSBot

<img width="1907" height="878" alt="project error" src="https://github.com/user-attachments/assets/8f72d222-3eb0-4828-8e06-76a0cf91a474" />

# Solution
-Checked Sample Utterances

-I used “Generate utterances,” but did not have Bedrock permissions, so i then deleted those and Added valid sample utterance for the intent  manually.

-Saved  then Build the intent


# Successfully built language English (ZA) in bot: SSSBot

 Lex bot has been compiled (built) successfully.

<img width="1918" height="918" alt="Build successfully" src="https://github.com/user-attachments/assets/d6808209-5262-4fbc-99b1-f11ce6111ddc" />


  # Bot Testing
  
# initial interaction with the Bot

<img width="1918" height="927" alt="initial interaction" src="https://github.com/user-attachments/assets/57267323-1571-48e5-b9a4-0052ea896fa2" />


# Response for the correct answer

<img width="1906" height="882" alt="correct" src="https://github.com/user-attachments/assets/4f3297d6-fdf2-4b7c-98af-5ec68a7439a0" />


# response for incorrect answer

<img width="1918" height="883" alt="testing incorrect answer" src="https://github.com/user-attachments/assets/9bbea07e-fbfd-4623-bf1a-91490d5dd132" />


# Closing Responce 

<img width="1906" height="872" alt="closing" src="https://github.com/user-attachments/assets/594da873-87c6-4e2b-bce6-7f27b20f8046" />

