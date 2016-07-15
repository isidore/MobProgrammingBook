# Setting Up the Space

For your first time doing mob programming, you do not need to worry too much about the space. We're going to lay out just the most critical things that are helpful.

Note: If you are doing this with more than ten people, please check out the chapter *mobbing with an audience*.

## Basic Setup

![Mob Programming Setup](images/MobProgrammingSetup.png)

## The Screen

The screen, projector or TV should be visible and clear to everybody in the mob. The chairs should be facing forward towards the screen as much as possible. People will need to stand up and move around frequently, so there should be enough room to do so comfortably. It is not helpful to have backpacks and laptops during this. Usually we put bags in the corner of the room. However, if people are uncomfortable with this, it's not a big deal.

It is also important to have a whiteboard where the navigator can express ideas.

## The Facilitator

As you are reading this book, you will most likely be the facilitator. The important part to know is that mob programming works much better in the beginning when there is a facilitator. As a facilitator, your job is to ensure that all the steps of mob programming are being carried out appropriately. Most of the time, you will not be doing the programming yourself. The exception being if you need to pause the mob to introduce a new idea by temporarily stepping into the navigator role. You do not need to be a good programmer or even a programmer at all to be a good facilitator. This is not a team lead position. When everything is going well, you will be doing nothing at all.

## The Work

The first question is always: "What are we going to work on?" While there are many answers to this question, whatever you decide to work on, it should be simple. You are going to learn a lot working together as a mob. Don't try to do that while adding the extra complexity of a super-hard task. After you've learned to work together, it's a good time to tackle the hard tasks.

There are three common items to work on as your first task.

1. **Simple work task**

   If you have a simple task to do, this can  be a perfect place to start. Just do it as a mob.

2. **Refactoring large methods**

   Many teams have code that is hard to read and understand. A refactoring for readability exercise makes a great first experience in mobbing. Simply choose a method that everyone agrees is troublesome and you are going to work with soon anyways. When you do this exercise, we suggest starting with the simple extraction of paragraphs of code and giving them better names. The only two refactorings we suggest are extract method and rename. We also suggest that you commit frequently, usually after each paragraph.

3. **Programming Katas**

   Katas are simple exercises that are used to practice programming. The more common ones include FizzBuzz, Roman Numerals, and Tic-Tac-Toe. For more Katas, check the reference in the back. However, any problem usually makes a good Kata. These are often done in test-first style of programming.

## The Computer

While you can get away with just about anything for your first mob, here are some tips to make things easier.

1. **Keyboard and mouse**

   Having an external keyboard and mouse just makes everything simpler for the driver. An external keyboard and mouse can also allow you to close the laptop, which is even better because then everybody is looking at the same the screen. This allows the driver to cue off of people pointing to the screen.

2. **Screen**

   While you usually have little control over the screen or projector, when you have a choice, try to get a bigger screen and a high-resolution projector. Remember that the code often has many more details than a regular slide presentation.

3. **Simple editor with line numbers**

   Line numbers make it easy to talk about where your focus is at. Editors that allow for simple typing and scrolling make it easier for everybody to track what is going on. In particular, editors like vi and Emacs add to the cognitive load if not configured in the way each individual member of the team normally uses them. Finally, make sure the font size is big enough so that everyone can easily read it.

## Seating and roles

### The Driver

The driver is the typist. There should be "no thinking" going on by the driver. This means that for anything to happen, there will need to be talking involved. It is important that the driver trusts the navigator and does their best to listen and do what is asked.

### The Navigator

The navigator is the main person programming. While they will take insight and help from the mob, they are the person who has to make the final decision on what to do. They should be talking in the highest level of abstraction possible. However, in the beginning, this is often at the level of keystrokes and simple programming structures.

We will go into this more in the chapter on **Strong-Style Pairing**.

### The Mob

The mob is checking the navigator and contributing insights when appropriate. Remember that you will be rotating fast and soon a new person will be navigating. This forces the other people in the mob to pay attention.

### The Facilitator

The facilitator sits in the back and does not rotate with the rest of the mob. If it is necessary for them to step in, they can pause the mob and assume whatever role is needed, except that of the driver.

## The Rotation

In the beginning, you will be using a 4-minute timer. This is usually your phone. It should have an audible (but pleasant) sound at the end of each turn. At the end of each turn, everybody stands up and rotates to the next seat. The navigator should become the driver. The driver should join the mob.

Note: Experienced mobs will use a special software instead of phones as their timer. We recommend not using this the first time people are mobbing.

> **&nbsp; *Congratulations!  
> &nbsp; You are now ready to start your first mob programming session!* &nbsp;**  
