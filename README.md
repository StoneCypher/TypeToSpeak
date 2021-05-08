# TypeToSpeak

A redditor wanted a simple type-to-speak app for their kid.  Let's help



<br/><br/>

## What is this?

[A redditor wanted an app to help their kid, who is low-verbal, learn to read](https://www.reddit.com/r/learnjavascript/comments/n7mpsb/need_guidance_for_developing_a_simple_literacy/).

They're trying to make it themselves.  Apparently this doesn't exist.

I'm trying to pitch in, because aw, the feels.




<br/><br/>

## How does this work?

In my mind, this repo is just as much about teaching that person to program.

What we're doing here is:

1. Making a webpage that represents this "app"
    1. If it actually has to be an app we can do a browser embedding, but, I doubt that'll be needed, and on the web, it's more available
1. The app is two-pane
    1. Bottom area is a wide, low-height `<textarea>` for the child to type in
    1. Top area is a video panel, to show the child content
1. App carries a whitelist of content
    1. This way we won't accidentally get Apple Computer to show an apple, or politicians when they type boobs
    1. Also it won't respond to "fuck" at all
1. Apparently we're going to use the Speech Synthesis API for words
    1. It's way less awful than it used to be
    1. It sort of sounds acceptable now?  I guess
1. Throwing it on Github Pages
    1. Absolutely, *definitely* not having a database
