# EduAI

##  🤔 Problem Statement

Many people experience the excitement of delving into a new subject but may feel discouraged by a high entry threshold or an unhealthy learning environment. eduAI addresses these issues, catering to users of all ages and backgrounds, whether it's a 10-year-old curious about giraffes' brown spots or an elderly person seeking advice to keep up with the modern world. To sum it up, EduAI is a platform where people can freely learn about several sub-topics of a given topic and test their depth in learning.

## 💡 Inspiration

When someone is looking for articles to read, they may find some articles either too hard to understand or too easy. The goal of this project was to build an educational platform where the user would enter a topic and a difficulty level, then AI would generate them an article about that topic with that difficulty level and also take their age and occupation into consideration.

## 🤖 What it does

EduAI is a full-stack web application that empowers users to explore any topic they are interested in, fostering a love for learning. Many people experience the excitement of delving into a new subject but may feel discouraged by a high entry threshold or an unhealthy learning environment. EduAI addresses these issues, catering to users of all ages and backgrounds, whether it's a 10-year-old curious about giraffes' brown spots or an elderly person seeking advice to keep up with the modern world.

## 🧠 How we built it

We built eduAI using ReactJS for the front-end, the Flask framework for the back-end in Python, and MongoDB for the database. Users sign up by creating a username and password and providing their age and occupation. Upon login, they can enter a topic of interest and the desired difficulty level. Follow-up questions help provide additional context for the content. We utilized the "command-light" language model to generate these questions and trained a custom language model using the user-generated dataset. This achieved an accuracy of 72% and a loss of 0.92, which we believe can be improved by increasing the training set size.

## 🧩 Challenges we ran into

We encountered challenges connecting to MongoDB, as our primary experience was with SQL databases. However, with some study and mentor support, we successfully connected our web application to MongoDB. Another challenge was the time-consuming process of training the cohere API due to the need for a large dataset.

## 🏆 Accomplishments that we're proud of

We take pride in our web app's user interface, dedicating extra time to ensure a visually pleasing and user-friendly experience. Additionally, we successfully trained our custom language model to generate unique and engaging content based on minimal context.

## 💻 What we learned

This project allowed us to explore new technologies and enhance our skills in full-stack web development. We gained experience in ReactJS for the front-end and honed our skills in Python, Flask, and MongoDB for the back-end.

## 🚀 What's next for EduAI

We plan to expand EduAI by gathering user feedback through surveys regarding their experience with the generated content. This will enable us to refine our model by leveraging cohere's capabilities in summarization and sentiment recognition. Additionally, implementing the embed use case could provide valuable insights by comparing user feedback, allowing us to focus on areas requiring improvement.
