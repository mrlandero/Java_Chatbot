# Java_Chatbot
A chatbot is an application that talks to the user. We're going to build an app that carries a simple conversation.

![Image_One](image_one.png)

## 1. Store each answer.

After each question, add code that picks up the user's answer and stores it.

![Image_Two](image_two.png)

### Careful from the **nextLine()** trap

- **nextLine()** gets "skipped" if you put it ahead of **nextInt()** , **nextDouble()**, **nextLong()**. You can expect this behaviour when you try to pick up the user's favorite language.

- You will understand why this happens when we cover **Delimiters** in the next section (Booleans and Conditionals).

- The solution is to add a throwaway **scan.nextLine()** before the "real" **scan.nextLine().**