# Java_Chatbot
A chatbot is an application that talks to the user. We're going to build an app that carries a simple conversation.

![Image_One](images/image_one.png)

## 1. Store each answer.

After each question, add code that picks up the user's answer and stores it.

![Image_Two](images/image_two.png)

### Careful from the **nextLine()** trap

- **nextLine()** gets "skipped" if you put it ahead of **nextInt()** , **nextDouble()**, **nextLong()**. You can expect this behaviour when you try to pick up the user's favorite language.

- You will understand why this happens when we cover **Delimiters** in the next section (Booleans and Conditionals).

- The solution is to add a throwaway **scan.nextLine()** before the "real" **scan.nextLine().**

## 2. Update each reply.

Update each reply with the user's answer.

![Image_Three](images/image_three.png)

## 3. Run your code.

![Image_Four](images/image_four.png)

Why is the cat scared?

The screaming cat appears when something's wrong or looks bad. In this case, the output is very messy. There should be a line of spacing between each answer and reply (see arrows).

## 4. Add a new line

Before every reply, add a **new line.**

![Image_Five](images/image_five.png)

Follow the comments to guide your code.

![Image_Six](images/image_six.png)

## Final output:

![Image_One](images/image_one.png)