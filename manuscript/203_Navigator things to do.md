# Navigator: Things to Do

As navigator, you are in responsible for caring for your driver. If the driver is the intelligent input device, for them to operate properly, you need to care for the conditions of work. Being the navigator, you need to pay attention to your driver, to constantly know where they are going. And you need to enable them to go as fast as possible.

As a navigator, you have three main tasks you’re paying attention to:

## Feed driver the next thing to do.

You’re creating the driver the box they work in on as high abstraction level as your driver can handle.

## Mine the to-do-list.

Create an idea on where to go next. You might be just one step ahead, but being that one step ahead is important. Where to go to get your thing done?

## Observe your driver.

See where they are and where they are going, and correct if the direction does not match what you had in mind. Pay attention on how they are doing, and help them whenever they need it.

Three main tasks might sound simple, but there’s a bundle of advice to do them slightly better.

## Programming style matters

The style of programming matters. Pair programming would seem to work a lot more fluently if the programming style is consume-first. With this the idea is that you start with an end result at first and then one by one build the things you wish you had in order to have the end result. Consume-first enables the navigator to go immediately, coming up with things to do while figuring things out themselves. And the end result and it’s division keep a visible checklist of what there is to do to get to the end result.

Some navigators prefer to work with bottom-up programming style. They build the image of the end result in their head, and feed the smallest possible pieces to the driver, one at a time. In this style, the navigator has a lot more of the information about what we’re trying to achieve, leaving the driver to interpret more of why the navigator is having them do things.

The third style is hardest, when there’s no ability to work in small pieces. If the navigator has to figure out the whole thing before feeding driver work, most of the time the driver is paused or participating in design discussions over taking the implementation forward. As a navigator, you’re supposed to care for your driver, not just having them type for you. Keeping driver waiting while navigator figures things out by themselves isn’t exactly the optimal way of caring. Working with partial information is essential.

## The abstraction level dilemma

As the navigator feeding the driver the next thing to do, finding the right abstraction level to communicate with them is relevant, even key to making progress. For driver to go forward, you need to find the right level on which to talk. If you are using an abstraction level too high, you will see nothing happening at the keyboard. If you are using an abstraction level too low, you’re not harnessing the powers of your driver by keeping them on too short a leash.

The core of going as fast as possible is navigating on the highest level of abstraction. Talking in keystrokes when talking in concepts would suffice can feel insulting. So pay attention to raising the level of abstraction.

  * **Intent**. What is the thing we want to accomplish now?
  * **Location**. Where does doing that start? Is the cursor in the right place or moving to the right place so that what we want done could be done?
  * **Details**. What exactly to do or type so that the intent is fulfilled, allowing for the drivers contribution while avoiding mistakes?

You notice if the level of abstraction is too high with the puzzled look on their face and the lack of action you expect to see. Drill in if needed.

I was particularly puzzled with the idea of using highest abstraction level possible, until I realised finding the level is really a listening and observation exercise. If you give instructions and following them is hard, you’re probably working on a too high abstraction level. Drilling down can be instant, just be more specific. If you’re not noticing the need to change level, you’re perhaps risking an experience of failing with tasks that lowers motivation in pairing, so it’s good to keep your eyes and ears open. If you start from a very low abstraction level, the driver can always correct you by telling you the level they are comfortable with. But if they have not yet learned how to, they might get a feeling of being talked down. And I found I am particularly sensitive to that, being the only woman and paying attention to being treated differently.

## Mining the to-do-list

There needs to be an idea of where we’re heading. But the road ahead might be only clear for the next few steps, instead of all the way. An important thing for a driver is keeping track of the work ahead. There’s three main things to consider on this:

### Timing

Find the right time to use an item on the list. What should be done first, what would make a coherent shared story in your pairing. What choices would enable you as the navigator to care for your driver in the best possible way?

### Backlog

What is there on the list of things to do? Your backlog is best if it can somehow be part of the code and become a shared view — with consume-first style. But you can also make notes by scribbling on a piece of paper of a whiteboard. Whatever you need to keep track of things. Notes are disposable, code (including test code) is what remains when you’re done.

### Prioritisation

Deciding what comes next and in what order to do things. It’s not just about the right time in long term, but the right thing right now. And it keeps changing as you learn.

## Express a in-a-nutshell idea of what you’re doing

As a navigator in strong-style, you are not supposed to have to justify all your chosen actions to your driver. Sometimes the driver has little clue on where you’re about to be heading, and a great practice in these cases seems is to invite temporary trust saying you’d like to just go to this direction for like 10 minutes, and if they are still unsure about doing this, you can change then. The argument of what is right thing to do takes easily more time than that. And nothing stops the pair of you implementing both of your ideas and then deciding that a third, completely different option is what you should go for. With programming in particular, there’s a lot of uncertainty that unfolds only through implementation and experimentation.
If you need to express what you’re doing, you should learn to express that in a very concise format. Instead of all the rationale, pick only the part of the message that is absolutely relevant to care for your driver.

## Immediate feedback

When you navigate, keep an eye on your driver. Double-check with questions what the driver does. And if the driver does something you consider a problem, help them correct it right away. Feedback belongs with the action the feedback relates to.
