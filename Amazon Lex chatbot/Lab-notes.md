# Amazon Lex Chatbot
# Objective

The goal was to design a quiz chatbot in Amazon Lex for CloudLearners Inc. that:

-Tests learners’ knowledge of Amazon S3.

-Provides immediate feedback (correct/incorrect).

-Uses branching logic to guide the conversation.

-Creates an engaging and interactive learning experience.

# Steps Taken

Intent Creation - Built an intent called S3Quiz with utterances such as “Start quiz”, “Quiz me on S3”.

Question Setup - Added the first multiple-choice question with answer slots (A/B/C).

Branching Logic - Configured slot capture success to provide different responses for correct vs incorrect answers.

Additional Questions - Linked follow-up quiz questions with conditional branching.

Feedback & Flow - Ensured the bot gives feedback before moving to the next question.

Testing  - Build and Tested the bot in Lex console.

# Challenges

Slot Handling – Ensuring answer slots (A/B/C) captured user responses correctly instead of defaulting to Yes/No.

Branching Logic – Configuring conditional responses so the chatbot didn’t skip straight to the next question.

# Screenshot

# Successfullu created an S3Bot

<img width="1891" height="897" alt="s3Bot" src="https://github.com/user-attachments/assets/f967c48b-425e-41fb-8992-3d567b3b12a0" />


# Error: Couldn’t build language English (South Africa) in bot: SSSBot

<img width="1907" height="878" alt="project error" src="https://github.com/user-attachments/assets/8f72d222-3eb0-4828-8e06-76a0cf91a474" />

# Solution

-Checked Sample Utterances
-I used “Generate utterances,” but did not have Bedrock permissions, so i then deleted those and Added valid sample utterance for the intent  manually.
-Saved  then Build the intent


# Successfully built language English (ZA) in bot: SSSBot

 Lex bot has been compiled (built) successfully.

<img width="1890" height="895" alt="testing2" src="https://github.com/user-attachments/assets/c5155b03-2147-413f-a7d0-bd88df881d2f" />


  # Bot Testing
  
# initial interaction with the Bot

<img width="1912" height="831" alt="testing 1" src="https://github.com/user-attachments/assets/148e640f-0f6d-4cca-899f-da0a3f8f54d3" />


# Begin Quiz

<img width="1890" height="895" alt="testing2" src="https://github.com/user-attachments/assets/a6e83453-8480-4e79-8696-d8eb7a4742b5" />


# Response for the correct answer

<img width="1915" height="921" alt="correct answer" src="https://github.com/user-attachments/assets/5747c2a0-51e3-401d-8181-2134b53fa684" />


# response for incorrect answer

<img width="1918" height="883" alt="testing incorrect answer" src="https://github.com/user-attachments/assets/9bbea07e-fbfd-4623-bf1a-91490d5dd132" />


# Closing Responce 

<img width="1906" height="872" alt="closing" src="https://github.com/user-attachments/assets/594da873-87c6-4e2b-bce6-7f27b20f8046" />

