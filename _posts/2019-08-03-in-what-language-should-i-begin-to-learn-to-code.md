---
layout: post
title: "In what language should I begin to learn to code?"
date: 2019-08-03
---

Short answer: I don't know.

Long answer: I don't *know*, but I do have some ideas, and some experiences with this. I've been a student of programming for about five years now, which feels absolutely wild to say. I took the non-Advanced Placement computer science course as a senior at New Trier High School in 2014-2015. Then, after a year in Israel, I took Introduction to Computer Science/Programming in Java at Columbia in Spring 2017. I've heard of some other strategies for teaching coding, and I'm interested in some of their benefits and drawbacks.

*New Trier High School*

New Trier taught three programming languages in the less advanced computer science course, which is the one I took (and which I believe has been revised since then). I don't recall a whole lot technically about them. One was an animation langauge, and we used it because it introduced the idea of [Object Oriented Programming (OOP)](https://www.scaler.com/topics/what-is-object-oriented-programming-oop/). Actions were performed on objects in the animation, and that was how we were meant to appreciate the idea that functions in OOP are always associated with objects. We also learned about control flow through [RAPTOR](https://raptor.martincarlisle.com/), which did a good job visualizing the different kinds of control flow, but didn't ever feel like it was programming, because users interacted with it via a GUI. The last language we learned was Visual Basic, which I think was supposed to integrate these different skills in a way that is actually usable to create meaningful code. Coding and lectures both happened in-class.

The course gave an effective overview of what it means to code using OOP, but a poor perspective on the technologies that enable effective programming. Since the vast majority of the course was spent in learning languages, I didn't end the course with a sense of accomplishment, like "I now have skills x, y, and z that I can use to do projects like a, b, or c." I also didn't feel like I'd gained an understanding of the technologies that I would use to program after graduating high school. Since I'd spent a little time on three languages, I didn't feel like I had a good grasp of the fundamentals of any programming. It was a good introduction course in that it was very accessible to students with no programming experience and limited math experience, but I didn't feel like it effectively prepared me for programming after the course's conclusion. This methodology did not work for me.



*Columbia University*

Columbia's first required programming course for students who intend to major in Computer Science is COMS W1004: Introduction to Computer Science & Programming in Java. It is exactly what the name indicates - and you can take a look at [the syllabus](http://www.cs.columbia.edu/~cannon/1004/syllabus.html) to see what I mean. There were several programming projects in Java, which increased in complexity as the semester went on. They were real applications of programming principles - even if I would never myself use the products I had to create for the course, they were real beginner-level projects created using the infrastructure used by real-world programmers. I used Eclipse, though I heard that the professor now requires students to use an internet-based Comand Line Interface (CLI). We built our way up to using OOP to simulate a game using a command-line interface. There were also a number of problem sets, all of which were introductory-level, and each of which dealt with a different non-programming aspect of computer science. 

The course effectively taught me all the Java I needed to be successful in the next course, which taught data structures and algorithms. Spending all my time in one language made me feel like I had a good beginner-level understanding of what it was, and how to use it in programming projects. Java is a good first language to learn, because it shares some traits with C, but is higher-level. I didn't feel like I had any breadth in other programming languages besides Java, or paradigms besides OOP, but if that's the price to pay for a more thorough understanding of one language and paradigm, I'm happy to have paid it. For people who enjoy it, this is just the first coding experience of many! 



*Other Methods*

The first, and probably the most obvious, alternative methodology to teaching new coders Java is teaching them Python. There are many strong [advocates for this approach](https://www.geeksforgeeks.org/is-it-snakepython-or-coffeejava-wholl-win/), though the argument is clearly not [over](https://www.educba.com/java-vs-python/), or even necessarily [decideable](https://medium.com/@dev.n/the-beginners-dilemma-should-i-learn-java-or-python-7efed89dc5b1) on a broad level. I did not go through this approach, so I can't really speak to its effectiveness. I know that Columbia offers a couple courses in Python that are meant to be taken before (for students intending to major in Computer Science) or instead of (for non-Computer Science majors) COMS W1004, but because of my degree program requirements, and because the course was not mandatory for my major, I did not take it.

I heard from a friend who went to Harvard about [CS50](https://cs50.harvard.edu/college/2019/fall/), their introductory coding course. They apply an interesting approach where they learn a little bit of a [lot of languages](https://cs50.harvard.edu/college/2019/fall/faqs/#curriculum), including C and SQL, but not Java. My friend did not go on to study computer science, and I have not spoken in-depth with anybody who did go on in the field after taking it, so I have no stories of its effectiveness. 

There are other approaches that I am not discussing because I do not know about them.



*My Ideas*

Peoople teach programming as an integral part of computer science. It is, but I am not convinced that this is the right way to introduce it it - especially to somebody who does not intend to study computer science in some depth. As somebody who likes computer science and coding, but is much more passionate about space, I view software development as a tool, as a means to an end. Code is a very helpful tool, because coding can be applied to solve so many different kinds of problems. So my take on it is that the language to use to begin to learn coding is the one that will most immediately solve problems in ways that improve your quality of life. I don't actually think this is Python or Java in many cases. 

I think the most common answer, which is probably just true for a plurality of cases, is the CLI on whatever computer you happen to be using. If your computer uses a UNIX-based operating system (Mac and Linux users), that's going to be some sort of shell scripting language; if you use Windows, that'll likely be PowerShell. Right now, I'm using a Windows computer, so that's what I'll be discussing in a bit more detail. Shell scripting is simple, and it has the ability to immediately improve the way in which you use your computer. 

CLI scripting is simple to install on your computer, because it comes pre-installed. There's no frustration with Integrated Development Environments, or issues downloading languages, or confusion with compilers and interpreters. Just find the program on your machine, open it up, and get to work! Furthermore, CLI scripting languages tend to have more simple syntaxes that emphasize the functionality of the code over its structure. The best way to observe this is to look at languages' "Hello, World" statements, which are traditionally the first programs written in a new language. [Java](https://introcs.cs.princeton.edu/java/11hello/HelloWorld.java.html)'s statement can exist only in a kind of object, inside a main method, by calling a function (println) that doesn't actually live inside the object or method.

	public class HelloWorld {
  		public static void main(String[] args) {
        	// Prints "Hello, World" to the terminal window.
        	System.out.println("Hello, World");
  		}
	}
	
Python also requires a function call with a defined structure, though it dispenses with the need for a class or main method. Deviation from the method's structure in either Python or Java will produce an error, and the code will not work.

	print("Hello, World")
	
PowerShell's equivalent command is 

	echo "Hello, World"
	
It produces

	Hello, World
	
However, 
	
	echo Hello World
	
is also legal syntax, which produces the output

	Hello
	World

CLI scripting languages, in my experience, emphasize function over form, and I really think that matters for first-time programmers. While the error-finding and error-correcting tools are not nearly as well-developed for this sort of scripting as they are in Java or Python Integrated Development Environments, simple beginner programs that do not use much code from other sources should not cause the kinds of errors that those tools really help to solve. 

The other advantage of CLI scripting is how immediately you can improve your own experience. CLI scripting provides an alternative to using the Graphical User Interface (GUI) (File Explorer or Finder) to look through and manage files on your computer. It can be significantly faster than the GUI for certain operations, and the instructions are *always* less ambiguous. 
