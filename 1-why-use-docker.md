#Why use docker

I want to start to tackle one very important question:

`why do we use Docker?`

We're going to first tackle why we use Docker by going through a quick little flow diagram.

![installing program flow](./installing-program-flow.svg)

And this is a flow of probably a process you've gone through at least once in your life before.

It's a flow of installing software on your personal computer.

And I bet at least once for you this is what has happened.

Maybe you have downloaded some installer, you run that installer, and then inevitably at some point

in time you end up getting an error message during installation.

So what do you do?

Well, you probably troubleshoot the issue by looking on Google.

You try to find a solution.

You eventually solve that issue.

You then rerun the installer only to find, Hey, today you have some other error appearing and then

you have to go through this entire troubleshooting process again.

So this is at its core what Docker is trying to fix.

Docker wants to make it really easy and really straightforward for you to install and run software on

any given computer, not just your computer, not just your personal laptop or your personal desktop,

but on web servers as well or any cloud based computing platform.

I want to give you a very quick demonstration of this flow right here in action and then show you how

quickly I can solve installing a problem or installing a piece of software by making use of Docker.

So I'm going to very quickly go through the flow of installing a piece of software called Redis.

Redis is an in-memory data store.

We're going to be using it quite a bit throughout this course.

But right now, I just want to give you a quick demo of how it can be a little bit challenging to get

installed on your own computer.

So I'm just going to go through the installation steps here very quickly.

So this is the red zone page.

This is the official download page.

In theory, I could use the documentation here to install Redis on my local machine.

I'm going to go down to the installation section and it very proudly says, Oh yeah, just run these

four commands right here and boom, that's pretty much it.

You can then then run Redis.

So I'm going to grab the first command right here.

I'm going to copy it and then I'm going to run it inside of my terminal.

So.

Paste There is the same exact command.

I'm going to run it and sure enough, yep, I get an error message.

Now in this case, the error message is a little bit predictable.

It's complaining about a program that is just not installed on my local machine.

Now, I could definitely go and troubleshoot this, install that program, and then try installing Redis

again.

But that's the whole point.

You kind of get into this endless cycle of trying to do all this troubleshooting as you are installing

and running software.

So let me now show you how easy it is to run Redis.

If you are making use of Docker instead, I'm going to go back over to my command line and I'm going

to run one single command.

I'll say Docker, run, dash it, read like, so I'll hit enter.

And then after a very brief pause, almost instantaneously, I have an instance of Redis up and running

on my computer, and that's pretty much it.

That is Docker in a nutshell.

That is how easy it is to run software when you're making use of Docker.

So to answer the question very directly of why we use Docker, well, we make use of it because it makes

life really easy for installing and running software without having to go through a whole bunch of setup

or installation of dependencies.

Now we're going to learn many more reasons throughout this course of why we use Docker.

But I want to give you a very quick demo and show you how easy it can be to get up and running with

some new piece of software when you are using Docker.

Let's take a quick pause right here.

We're going to come back to the next section and start trying to the answer of answer the question of

what Docker is.