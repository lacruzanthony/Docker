# What is Docker?

In the last section, we tried to answer the question of why use Docker?

And we eventually said that we use Docker because it makes it really easy to install and run new software on our computer.

We're not going to try to answer the other big question here, which is what is Docker?

Well, this question is a lot more challenging to answer.

Any time you see someone refer to Docker in a blog post or an article or a forum or wherever it might be, they're kind of making reference to an entire ecosystem of different projects, tools and pieces of software.

So if someone says, Oh yeah, I use Docker on my project, they might be referring to Docker client

or Docker server.

They might be referring to Docker Hub or Docker Compose.

Again, these are all projects, tools, pieces of software that come together to form a platform or

ecosystem around creating and running something called containers.

And so your immediate question might be OC, well, what's a container?

That's a good question, and that's a question that we're going to be trying to answer throughout this

entire course.

Just a moment ago, when I ran that command at my terminal of Docker run Redis, it went through a little

series of actions behind the scenes, and we're going to examine that entire series of actions very

closely over time.

But right now, let me give you two important pieces of terminology.

When I ran that command, something called the Docker CLI reached out to something called the Docker

Hub, and it downloaded a single file called An Image.

An image is a single file containing all the dependencies and all the configuration required to run

a very specific program.

For example, Redis, which is what the image that I just downloaded was supposed to run.

This is a single file that gets stored on your hard drive, and at some point in time you can use this

image to create something called a container.

A container is an instance of an image, and you can kind of think of it as being like a running program.

We're going to go into great detail over time, over behind her to learn exactly how a container works.

Exactly.

But right now, all we really need to understand is that a container is a program with its own isolated

set of hardware resources.

So it kind of has its own little set or its own little space of memory as its own little space of networking

technology and its own little space of hard drive space as well.

So I didn't really answer the question here of what Docker is, but we did learn at least that a reference

to Docker is really talking about a whole collection of different projects and tools.

And we also picked up two important pieces of terminology a Docker image and a container.

Now these images and containers are the absolute backbone of what you and I are going to be working

with throughout the rest of this course.

So let's take a quick pause right now.

We're going to come back the next section, and we're going to start talking a little bit more about

how we work with images and containers.

So a quick break and I'll see you in just a minute.

