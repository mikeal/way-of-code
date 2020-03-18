# The Way of Code

To me, programming is not a science but a practice. The
more I write code the less I believe that there are unified **correct** ways of doing
and that the end result is limited not by methods of engineering but by the skill
of a programmer to express their desired form.

Programming happens in the mind. There is a disparity between what can be *proven*, what 
can be *imagined* and what can be *expressed*, and that distance is the experience and
art of the programmer.

As I try to be a better programmer I've turned toward debugging my mind. Considering the
different states I'm in as I program and being mindful to do each as well as I can. This
has required a lot of experimentation with different tools and techniques from editors
to various forms of meditation.

I've been programming for about 20 years but have only settled in to this method of iteration
recently. After doing this for about a year I've become a little more confident in my assessments and
am going to start writing them up in this repo. These begin with what I belive are 3
distinct states of mind you must shift between while programming.

# States of Mind

I find that I have 3 distinctly separate states of mind that must be engaged when programming.

* **Vision** - in which I assemble the code in my mind until it is clear enough to express.
* **Expression** - in which I commit what’s in my mind to text as well as I can.
* **Reflection** - in which I look back on the expression in order to understand it in the context of 
what now exists in text rather than what had been in my mind.

Each state naturally flows into the next and these states are cyclical as reflection often uncovers a
new problem, then I think of a solution, then I express it and reflect upon the newly “fixed” state.

Sometimes these states are long running and sometimes they are incredibly short. During some furious debugging
I might cycle through them all a few times a minute. While other problems I may think about for years before
I have enough in my mind to express.

## Vision

Since this state is entirely mental many of the best tools are away from the keyboard.

If I have a specific problem I need to work on today it’s best to clear the mind first, meditation
works quite well. Clearing away all the thoughts and anxieties you might be carrying with you means
you have more room to envision the code you’re about to write.

For longer projects that I think about for months or years, having conversations with friends and
colleagues, reading other people’s code and libraries on GitHub, researching and learning all play a
role in building the vision I want to eventually express.

While I do not believe programming to *be* a science, science has a strong role to play. Learning through
books and academic papers shape what can be envisioned. For instance, without understanding how certain
cryptographic techniques work you wouldn't know how to apply them to solving a particular problem. Part of
my practice is continually learning about these things but I might also dive in to specific areas of research
in order to build the vision for a specific problem, or I might have a problem in mind for years and only
recognize the missing piece when reading something new in white paper.

One thing I’ve learned not to do is try to write before I have a clear vision for what I want to express.
The process is frustrating and ends in very poor code if I’m thinking of the expression as I write it. The
best way to write code is often to stop typing and fully consider what needs to be typed before moving on.

Coding is not an "act" it is a process and the most important part of that process does not include typing
and might be happening while walking or making tea.

## Expression

As I've gotten better at acknowledging and separating these states of mind the tools I use during expression
have changed the most. Since I'm not learning as I type, since I'm not imagining what I want to type as I type,
since I'm not correcting errors as type, the tools that help in those tasks have had to be thrown away.

An editor I can write fast in is a must. Anything I see visually as I type other than the code will draw my
attention away from the expression and interrupt my flow.

All the features people add to editors in order to reduce errors need to be turned off. I want errors to go un-noticed
while I'm expressing what is in my mind. I’m often writing code for variables and functions that do not exist yet.
I even turned off syntax highlighting, as I can’t help but look to the highlighter as a sort of error check. Anything
that draws my attention interrupts the flow of expression. Most programmers have had sessions or at least moments of
intense flow and we often are trying to re-produce those flow states, but it's not until I started removing all the
tools we use to "help" us program that I realized how much they interrupt that flow.

It is not necessary in this state of mind to build confidence in the accuracy or runability of the expression.
The primary purpose is to move code from your mind to text. Build confidence in the expression
once it’s out of your mind.

## Reflection

It starts with just reading what you’ve written. Correct all the tiny and obvious mistakes first.

Now lint the code, run the code, run any tests, build confidence in the expression.

If there’s a big problem, shift to envision the solution. If it works, envision the tests or documentation.

# Tooling Theories

Different states of mind lend themselves to very different tools.

While I've turned off syntax highlighting in my editor in order to improve my ability to express it makes the editor
a poor place to center learning and debugging. I mostly read code on GitHub where there is excellent highlighting and
other tools. For debugging I now rely on a variety of command line tools to point out where the issues are rather
than integrating them into my editor.

Now that the editor/IDE isn't the central dumping ground for all tooling I'm much less dependent on a specific
device or environment. I do all of my development in a remote docker container. As I take on different tasks
I can spin up different machines or tmux sessions suited to the task. 
