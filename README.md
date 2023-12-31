# Verizon PlanPal
## Inspiration
The inspiration for Verizon PlanPal came from our diverse backgrounds across technology and business.  We analyzed the current model for which customers purchase phone plans and found an opportunity for refinement, maximizing user experience while minimizing interruptions.
## What it does
Our project shows off the benefits of using generative AI for interacting with prospective customers, guiding them all the way to checkout.  PlanPal can help customers choose which plan works best for them, and help teach them about different technologies or options.  Customers can ask general questions like “What is 5G?” or more targeted questions such as “What are the benefits of the Verizon Unlimited Ultimate plan?”
## How we built it
This is accomplished through integrating the OpenAI API with our custom database of Verizon knowledge, sourced through a PDF on available plans.  The generative AI is able to consult this information, then summarize it and provide it in the right context to the user.  Furthermore, our project provides 4 brand new Verizon representatives: Shrek, Ron Burgundy, Deadpool, and Zoolander.  The user is able to choose a character to help them, and the AI’s responses will mimic the personality of the character.
## Challenges we ran into
One challenge we ran into during development was the OpenAI API returning improper input.  The library that we were using forced GPT to return all results in a JSON format, however occasionally the model would forget this and return normal text, breaking our parser.  This was solved by putting better restrictions in place, as well as switching over to using GPT-4, which provides much more consistent results.
## Accomplishments that we're proud of
We are most proud of engineering a flexible language learning model that integrates all of Verizon’s wireless plans and services with extreme detail and accuracy. Furthermore, we are proud to have successfully and seamlessly migrate the model to a web app that can interact with users to demonstrate the potential and innovation of conversational generative AI in various environments.
## What we learned
Through completing this project, we gained valuable knowledge about Generative AI, learning how to utilize it to its greatest potential through integration with our own defined services.  We also refined our web development skills, learning how to implement smooth animations and quickly move information between the backend and frontend. 
## What's next for Verizon PlanPal
We want PlanPal to be the next e-commerce customer service assistant bot used across all companies in order to guide and educate customers on the latest products. The applications for a generative AI agent such as PlanPal are endless, as it can be personalized to yield excellent results in a variety of scenarios.
