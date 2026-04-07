<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Build a Chatbot with Amazon Lex

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-ai-lex1)

**Author:** Afolabi Ayomide  
**Email:** afoayo1@gmail.com

---

## Build a Chatbot with Amazon Lex

![Image](http://learn.nextwork.org/joyful_turquoise_calm_mule/uploads/aws-ai-lex1_505be5b8)

---

## Introducing Today's Project!

### Project overview

In this project, I will demonstrate how to use Amazon Lex to build a banking bot  for an imaginary banking service .I'm doing this project to learn about AI bots, Natural Language processing and much more.

### What is Amazon Lex?

Amazon Lex is an AWS service that is used to build and intelligent banking bot.

### Key tools and concepts

Services I used were LEX, Intent and much more.

### Personal reflections

One thing I didn't expect in this project was how simple it is to build a fully functional and intelligent Bot without the need to write extensive code. It is amazing

### Project timeline

This project took me approximately 40 minutes, and it was very rewarding and interesting.

---

## Setting up a Lex chatbot

### Approach to chatbot setup

In this step, I will create a new bot from scratch on Amazon Lex.

### Chatbot creation process

I created my chatbot from scratch with Amazon Lex. Setting it up took me 2 minutes

### IAM role configuration

While creating my chatbot, I also created a role with basic permissions because it needs permisiion to call other AWS services.

### Intent classification confidence score

In terms of the intent classification confidence score, I kept the default value of 0.40. This means that my bot must br 40% confidence that it understands what the user is saying.

![Image](http://learn.nextwork.org/joyful_turquoise_calm_mule/uploads/aws-ai-lex1_97dc2351)

---

## Intents

In this step, I will be training BankerBot to greet the users.

### Creating my first intent

An Intent is what the user is trying to achieve with the bot.

I created my first intent, WelcomeIntent, to welcome all users when they say hello.

### Testing chatbot responses

I launched and tested my chatbot, which could respond successfully if I enter responses like
Hi
Hello
I need your help

---

## Handling unrecognized inputs

My chatbot returned the error message 'Intent FallbackIntent is fulfilled' when I entered "How are you" This error message occurred because Amazon Lex doesn't quite recognize your utterance. 

![Image](http://learn.nextwork.org/joyful_turquoise_calm_mule/uploads/aws-ai-lex1_505be5b8)

---

## Configuring FallbackIntent

In this step, I will be Customizing FallbackIntent to send user-friendly messages because  "Intent FallbackIntent is not fulfilled" is what is sent by the bot when it doesn't understand the user.

### When FallbackIntent triggers

FallbackIntent is a default intent in every chatbot that gets triggered when the Bot does not understand what the user said.

I wanted to configure FallbackIntent because users would not understand this error message.

### My FallbackIntent configuration

To configure FallbackIntent, I changed the closing response 

I also added variations! What this means for an end user is that there would be different error messages when the bot does not understand the user.

---

## FallbackIntent with Variations

![Image](http://learn.nextwork.org/joyful_turquoise_calm_mule/uploads/aws-ai-lex1_c4fc89af)

---

## Initial Responses

### Setting up initial responses

### Initial response implementation

---

---
