---
title: 'Definition of Encoding in Computing'
description: 'In this article, we will learn what programming is so you can have a solid foundation to build upon.'
pubDate: '2024-11-25T06:39:32.971Z'
heroImage: '/computer-80s.jpg'
categories: ['Coding']
tags: ['binary', 'software']
author: '["ghxstloner"]'
lang: 'en'
---

*It happened to me: when starting our journey as programmers, one of the most exciting and overwhelming things is the sheer amount of information we need to learn.*

You'll learn a wide variety of languages, frameworks, libraries, inventions, and conventions.

Often, one technology requires knowledge of another, and everything seems interconnected or interwoven.

With new technologies frequently emerging in such a fast-paced and ever-changing industry, it can quickly become confusing for beginner programmers.

When learning to program, instead of focusing solely on a specific technology, it can also be helpful to understand the fundamentals, the foundations, and to unravel the layers of abstraction to know the underlying principles that all these technologies have in common.

Understanding programming at a fundamental level will make problem-solving easier and give you a better understanding of how these technologies work under the hood.

In this article, we will learn what programming is so you can have a solid foundation to build upon.

# How Do Computers Work?

When turned off, computers are just expensive electronic machines. They are objects made of metals, plastics, and other materials.

However, once you press the power button and they go through their startup process, called booting, they come to life.

<p align="center">
  <img src="/computador-viejo1.jpg" alt="Old Computer"/>
</p>

Your computer becomes this extremely powerful electronic machine. It’s a device capable of performing complex tasks at incredible speeds that would be difficult, if not impossible, for humans.

Its screens are vibrant and active, and there are a variety of buttons and icons ready to be clicked.

## Computers' Relationship with Electricity

---

Computers operate and are powered with the help of electricity.

Electricity only has two states: **it can be on or off**.

Electricity being on and flowing represents a boolean value of "true" (True), having the state of on. Conversely, when it's off and not flowing, this represents the boolean value "false" (False) and the off state.

It can only have one state at any given time.

These two states of electricity are called Binary states, the prefix bi- meaning two. And this brings us to the next question…

## What is Binary Code?

---

This concept of electric charges and the existence of only two possible states ties well with the numbering system that computers use in their hardware. They use it to complete every task they are assigned. It’s called binary code and consists of sequences of *0*s and *1*s.

Binary code, by design, directly corresponds to specific machine instructions, commands, and locations in the computer's memory. The computer then reads and interprets these instructions and performs particular tasks.

Computers are made up of thousands of tiny physical devices that act as electrical switches, called **transistors**.

<p align="center">
  <img width="400" height="300" src="/primer-transistor.jpg" >
</p>

<p align="center"><em>The first transistor in history <strong>(1950)</strong></em></p>

These small electrical hardware components, transistors, enable or disable the flow of electricity.

They can have a positive or negative electrical charge depending on their state—whether they conduct electricity or not. These thousands of tiny switches can be either on or off.

## How Does the Binary System Work?

---

We just mentioned—and you may have heard before—that **computers work with 0s and 1s**, but… what does that actually mean? We may no longer work directly with binary code, but it’s the only thing a computer's CPU (processor) understands.

Are there literally *0*s and *1*s stored in our physical devices, flowing and moving? Not exactly.

However, our CPUs are made of countless microscopic digital circuits that carry information.

With the help of transistors, which come together to form these circuits, and their small sequences of electrical signals that turn on (1) or off (0), there can only be two types of voltages: high and low. This results in the representation of different values, i.e., different instructions or calculations being performed.

When these electrical signals from transistor circuits and other electrical components are linked, combined, or modified in a certain way, they can create a wide range of possible tasks and operations that the computer can perform and oversee.

## The Relationship Between Computers and Humans

---

Machine-level programming language is the only language that computers can directly understand and are capable of comprehending.

Binary code may vary from one computer to another and from one machine to another. At this level of programming, there is no portability. This means programs and software cannot be transferred to different systems.

## Limitations of "Machine Languages"

---

Machine languages may vary depending on the operating system where they are implemented.

This, of course, is very limiting.

Machine code or binary code can execute very quickly. It may be the computer’s native language and extremely efficient because instructions are executed directly by the CPU. But it’s a very boring, monotonous, and, not to mention, highly error-prone way of using a computer.

Trying to use a computer by manually writing binary codes for each transistor is a cumbersome process.

Making a mistake while directly managing the computer's data storage and operations is very difficult to troubleshoot.

Machine-level languages are hard to read, write, learn, and understand for humans. So, programmers and computer scientists found a better, arguably easier, way to solve these problems.

The tasks that a computer can perform on its own are at a very primitive level and are limited in scope.

An example of this is that they are good at performing arithmetic calculations like adding numbers or checking if a number equals zero.

## The Human Element in Computing

---

Humans created these machines that have revolutionized our way of life, but when it comes down to it, computers really aren’t that smart and are limited in their capabilities on their own.

They only do exactly what they’re told to do. They don’t make assumptions or have common sense as humans do.

At their core, computers are machines that perform mathematical operations. But they’re also good at displaying text on the screen or repeating a task over and over again.

These operations are basic and don’t go far beyond that—they’re known as the computer's instruction set.

Although, at their core, computers can only perform very basic tasks, they can perform extremely complex actions and follow and execute program instructions given to them. This is due to the many layers of abstraction they have.

However, the real power lies in human hands. Everything we want to achieve and everything we imagine—we can use this machine as a tool to perform complicated calculations, conduct research to find and extract a document among billions of others, or stay in touch with friends and family who are far away.

Everything we can imagine, we can now create by programming a program.

Computers and programs can improve our collective lives worldwide. But how do we make them do what we want?

## What is Computer Programming?

---

Coding and programming are terms often used interchangeably. However, they have some differences.

### Programming vs. Coding

Programming means telling a computer what to do and how to do that thing you told it to do.

It involves providing well-thought-out and methodical instructions for your computer to read and execute.

You need to break down large tasks into smaller tasks. And you keep repeating this process of breaking something down into smaller tasks until you reach a point where you don’t need to tell the computer what to do anymore—it already knows how to do that task.

The essence of programming is the process of problem-solving, complex thinking, attention to detail, and reasoning, all using a computer.

Programming involves thinking about all the different steps a user might take, and we must also consider all the things that could go wrong. Once you’ve thought about all the potential problems a user may encounter, you need to find solutions before writing the code.

We can think of problem-solving as taking an input (the information and details about our problem we want to solve) and producing an output (the end goal or solution to our problem).

The outputs can be complicated—very complicated.

## Problem-Solving with Algorithms

---

When solving problems using a computer, you need to express the solution to that problem in accordance with the computer’s instruction set.

For that purpose, we use algorithms—a systematic approach to solving problems.

Algorithms are an idea or method expressed in a very concise and precise set of step-by-step rules and instructions. The computer needs to follow these instructions to solve the problem.

When we think of algorithms, they don’t just apply to computers. They are also machine-independent.

Humans, too, follow algorithms—sets of instructions to complete tasks in our daily lives.

Some examples might be:

- Counting people in a room
- Performing arithmetic calculations
- Figuring out the right route to reach a particular destination
- Following a cooking recipe

In the last example, we can think of the recipe as the instructions we use, and we compare ourselves to the computers that have to read those instructions and execute them correctly.

An algorithm is a plan that outlines the steps you need to follow to achieve a desired result.

## How Computers Use Algorithms

---

When it comes to computers, algorithms must be precise because computers take everything literally. They don’t read between the lines or make assumptions.

There’s no room for ambiguity, so algorithms must not only be precise but also organized, correct, error-free, efficient, and well-designed. All this helps minimize the time and effort the computer needs to complete a task.

Computers execute algorithms mechanically without thinking much about each step. And they should work exactly as we intended them to.

A computer program is a collection of those instructions or algorithms—it’s a text file that serves as a manual of instructions.

It describes a very precise sequence of steps for the computer to follow. The computer performs a specific task, its hard drive executes the instructions, and you get the expected result (if it’s free of semantic errors) in the end.

Aside from thinking, researching, detailed design, and planning, programming also involves testing, debugging, deploying, and maintaining the final result.

When you’re developing a program to solve a particular problem, you typically express the idea of the solution using an algorithm. Then, developers code the program by implementing that algorithm. You use a language with a particular syntax that both humans and computers can understand.

This is where the actual coding comes into play.

## What is Computer Coding? The Simple Definition

---

Coding is the process of transforming ideas, solutions, and instructions into a language the computer can understand—specifically, machine binary code.

Coding is how humans can communicate with computers.

Coding involves communicating and giving instructions for various actions we want our computers to perform using a programming language.

Programming languages like JavaScript, Java (my favorite), C/C++, or Python act as the translator between humans and machines.

These languages bridge the communication gap between computers and humans by representing, expressing, and implementing algorithms. They do this using a specific sequence of statements that machines can understand and follow.

**Programming languages** are similar to human languages in that they consist of basic syntactic elements like nouns, verbs, and phrases. You group these elements to form something that resembles a sentence and creates meaning.

In most cases, programming languages are very close to the English language. But they provide a shorter, more precise, and less verbose way of creating instructions that a computer can understand.

A spoken or natural language like English, on the other hand, leaves much room for ambiguity and different interpretations by many people.

Programming languages are a set of rules that define how to write computer code.

We use computer code to create all the web applications, websites, games, operating systems, and all other software programs and technologies we use daily.

You can see the code that makes up your favorite websites by right-clicking and selecting "Inspect" (or also View Page Source) as shown below:

<p align="center">
  <img src="/ver-codigo-fuente.png">
</p>

After selecting either option, you’ll be able to view the HTML, CSS, and JavaScript code that makes up the website’s Frontend, which would look something like this:

<p align="center">
  <img src="/codigo-fuente.png">
</p>

With all this, we can better understand that programming is the act of translating problems that are first in a natural human language into a machine-readable language. This translation happens thanks to programming languages and coding.

Coding requires you to understand the intricacies, specific syntax, and keywords that make up a programming language. Once you know these features of a language, you can start developing applications.

# Conclusion

If you’ve made it this far, it means you’ve learned how computers work at a high level. We then defined what programming is, the meaning of coding, and some key differences between them.

It’s important to remember that **_coding_** is simply the process of writing code to develop programs and applications. Using a metaphor, it’s like the tools for a carpenter.

Coding is a subset of programming, which involves logical reasoning, analysis, and planning of a sequence of instructions for a computer program or application before writing any code.

Programming is the bigger picture of the process. Coding is part of that process but should always come after programming or the planning and problem-solving stage.

I hope that through this article, you’ve been able to understand the basic concepts of programming and coding. Thank you for reading! :D


Aside from thinking, researching, detailed design, and planning, programming also involves testing, debugging, deploying, and maintaining the final result.

When you’re developing a program to solve a particular problem, you typically express the idea of the solution using an algorithm. Then, developers code the program by implementing that algorithm. You use a language with a particular syntax that both humans and computers can understand.

This is where the actual coding comes into play.

## What is Computer Coding? The Simple Definition

---

Coding is the process of transforming ideas, solutions, and instructions into a language the computer can understand—specifically, machine binary code.

Coding is how humans can communicate with computers.

Coding involves communicating and giving instructions for various actions we want our computers to perform using a programming language.

Programming languages like JavaScript, Java (my favorite), C/C++, or Python act as the translator between humans and machines.

These languages bridge the communication gap between computers and humans by representing, expressing, and implementing algorithms. They do this using a specific sequence of statements that machines can understand and follow.

**Programming languages** are similar to human languages in that they consist of basic syntactic elements like nouns, verbs, and phrases. You group these elements to form something that resembles a sentence and creates meaning.

In most cases, programming languages are very close to the English language. But they provide a shorter, more precise, and less verbose way of creating instructions that a computer can understand.

A spoken or natural language like English, on the other hand, leaves much room for ambiguity and different interpretations by many people.

Programming languages are a set of rules that define how to write computer code.

We use computer code to create all the web applications, websites, games, operating systems, and all other software programs and technologies we use daily.

You can see the code that makes up your favorite websites by right-clicking and selecting "Inspect" (or also View Page Source) as shown below:

<p align="center">
  <img src="/ver-codigo-fuente.png">
</p>

After selecting either option, you’ll be able to view the HTML, CSS, and JavaScript code that makes up the website’s Frontend, which would look something like this:

<p align="center">
  <img src="/codigo-fuente.png">
</p>

With all this, we can better understand that programming is the act of translating problems that are first in a natural human language into a machine-readable language. This translation happens thanks to programming languages and coding.

Coding requires you to understand the intricacies, specific syntax, and keywords that make up a programming language. Once you know these features of a language, you can start developing applications.

# Conclusion

If you’ve made it this far, it means you’ve learned how computers work at a high level. We then defined what programming is, the meaning of coding, and some key differences between them.

It’s important to remember that **_coding_** is simply the process of writing code to develop programs and applications. Using a metaphor, it’s like the tools for a carpenter.

Coding is a subset of programming, which involves logical reasoning, analysis, and planning of a sequence of instructions for a computer program or application before writing any code.

Programming is the bigger picture of the process. Coding is part of that process but should always come after programming or the planning and problem-solving stage.

I hope that through this article, you’ve been able to understand the basic concepts of programming and coding. Thank you for reading! :D
