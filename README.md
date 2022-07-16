# sharedAppartmentManager
Telegram bot to add to your appartment group to help manage shared tasks and turns. 

# Features 
Lists of tasks with a queu of people assigned to each of them. The assignment can be stopped and started so someone can leave the flat for a while without affecting the flow. The assignment has a person that it notifies. When that person says that it's done, the assigned person rotates. Each task sends notifications programmed or wait for input (a flatmate has to say that it need to be done). 

Examples: 
- Clean the kitchen (programmed each thursday) 
- Buy toilet paper (wait for input) 
- Take out the trash (wait for input) 

- Languages are Spanish and Ennglish 
- You can create interconnected task such that the number of people in the flat is the same to the number of interconnected tasks, they are programmable and they notify at the same time. In that case, each person is always assigned to one of those and only one of those. When someone is logged out, it says "blank".  
- People have to be assigned manually to each tasks that they have to do. 
- When someone that left is back, they are randomly placed in the not interconnected tasks queues
