---
layout: post
title:  How to prototype a Messenger bot.
date:   2016-07-28 14:13:00 +0100
excerpt: What text editor to use? Sass or plain old CSS? What on earth is Compass? Command line? I'm not touching that. Sound like you? Welcome, I was once like you and this is the guide I wish someone had given me.
categories: work
tags: facebook, messenger, prototype, sketch, keynote
---
Let's look at how we can prototype an iOS Facebook Messenger flow, using Sketch and Keynote.

Recently, I was asked by my pals at TalkBe to help them prototype an example of how a bot could work for a brand they work with in Facebook Messenger. There's a few UI kits kicking around, and so they thought I'd be able to use one to showcase a conversation a typical user could have with the bot, and specific commercial actions that could be taken.

Here's the problem; How can we showcase this conversation in the most easy to understand way? As this was essentially a pitch piece, how could we impress the client, while getting around the typical build time issues, and then onward distribution so the client could see the idea we've had?

The conversation is the experience

This wasn't a typical prototype or UX piece. The task here was to establish a conversational flow, and then bring it to life using many pieces of the preset UI Messenger already employs. Yes, we could attempt to own some visual flair with the content we would be presenting, but the main parts of the overall experience is how the user can develop a relationship with the bot, and deal with many of their common interactions with the brand through the interface.

Copy is often the most important part of both UX and digital service design, as it's the persuasive element which can convince a user to transact, or signpost their way to another area of service. For IM, copy is the only thing you have in converting a user to your goals.

Step One - Design the conversation

This might be easy for some of you, but the essential bit is to put yourself into both the shoes of the user, and the brand that the bot is representing. Then, have a conversation with yourself! To get the best out of the feature set that Messenger has, you'll also need to familiarize yourself with the differing types of interface language available.

Let's break it down:

- *Comments* behave just as you think they will, because they're the speech bubbles you see between yourself and the bot. They display simple content, without any embellishments, save for URLs. Be aware of their spacing, and how they change when comments are delivered in fast succession.
- *Structured Messages* can contain an image, title, description and calls to action. They might also contain a URL, but the key utility of this message type is to give call backs (CTA buttons) that the user can select to change the onward journey of the experience. They can also be used in a carousel.
- *Quick replies* appear above the message input, and are designed to be fast answers a user can select without having to type. While these can be generated through machine learning and be relevant to content, they can also be hard curated based on the expected reply instance.
- *Persistent menu* appears when the burger icon is tapped at the side of the chat input, and gives the option to launch a different function of the bot, so for instance, users can select "help" or "top sellers" as a fast action.
<!-- - *Account linking* enables a user to jump into a webview, which allowing them to log into their account. So if this was Amazon, and you had clicked "buy" on an item in a structured message carousel, you would then be jumped into a login interface to enable your account. In many cases, this only needs to be done once, and isn't the only way a user can connect their account to Messenger. -->

Of course, there are many other features you can design for in Messenger, but we'll be focussing on the above for now. You can see more [here](http://messengerblog.com/bots/messenger-platform-1-1-ratings-quick-replies-account-linking-and-more/).

STUFF ABOUT DESIGNING THE CONVERSATION GOES HERE.

Step Two - Prepare the assets

As mentioned before, there's a few different Messenger UI kits out there for Sketch. I used these three when putting the prototype together:

- [*Bots*](https://bots.mockuuups.com) came out not long after Facebook announced the new APIs for Messenger. In the world of mockups, it's a little old, but at the time of writing, most was relevant.
- [*Sketch App Sources*](http://www.sketchappsources.com/free-source/1952-facebook-messenger-ui-kit-chatbots-sketch-freebie-resource.html) has this rather good mockup which has some good UI examples and demonstration of how the flow can work.
- [*Facebook*](http://facebook.design/ios9) have this rather excellent iOS9 UI kit, which contains some bits you might find useful later on. And if you're reading this in a post iOS10 world, they've probably got a kit for that too.

1. Create a new Sketch document, and use a preset to give yourself an iPhone 6 artboard. Give it a lot of height so you can fit in the entire conversation, and leave enough space to accommodate the header elements and the keyboard at the bottom.

2. Open both Bots, and the Sketch App Sources templates. From there, copy and paste in the header elements and keyboard. Now, start to create your conversation by copying and pasting the different message types from Bots.

3. Group together the message and avatar, so you can copy and paste later on.

Step Three - Build the prototype

It's not big secret that aside from being a brilliant free alternative to Powerpoint, Keynote is also a super good prototyping tool for displaying interactions for mobile and web. The secret? Magic move. Set any slide to transition with Magic move applied, and you'll be able to do some amazing transitions between elements.

1. Open Keynote, and launch a new document with a white theme.
* Go to the inspector, and select "Document". From here, go to Slide Size, and select "Custom Slide Size" from the dropdown. Set the dimensions to that of the iPhone 6, so if working at 2x, 750x1334.

2. From Sketch, copy in your header elements. Sketch will paste them in as PDFs (if you're worried about file size). Paste in the keyboard, but position it off the bottom, so only the chat input shows. Now, paste in your first message, so there's a starting point

3. With the slide highlighted, click "Animate", then "Add an effect". Select Magic Move from the dropdown list. Make sure "Fade Unmatched Objects" is selected, and adjust the duration to 0.3 s.

4. Duplicate the slide, now paste in the next conversation element. Press play, and see what you get!

You should see that the reply has faded in as the slides transitioned. This is because Magic Move didn't see this element in the previous slide, so faded it into view. And this is how Magic Move works: It looks at what was in position in the previous slide that it was copied from, and moves the element to their new position.

Let's keep going.

5. Duplicate each slide whenever you need to implement a new item, and paste in each conversation element, until you have filled the slide.
* From here, space will need to be created at the bottom to facilitate the next conversation item. Duplicate the slide, then select all the previous conversation elements, and move them upward with the arrow keys (or shift+arrow up to move 10px at a time).

6. Paste in the new conversation item. Now press play.

What you should now see, is the screen fill with comments, and then shift up and fade in a new one. Try pasting in a carousel, and then animating between the first and last card in two slides.

7. And that's it! Keep going until all your conversation points are in, and that the presentation flows as you've designed it.   
