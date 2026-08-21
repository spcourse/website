# Syllabus Scientific Programming / Data Processing {#overview}

- [General info](#general-info)
  - [Schedule](#schedule)
  - [Attendance](#attendance)
- [Programming modules](#programming-modules)
- [Grading](#grading)
- [Prerequisites](#prerequisites)
- [Learning goals](#learning-goals)
- [Course materials](#materials)
- [Doing your own work](#plagiarism)
- [Acknowledgements](#acknowledgements)

## General info {#general-info}

Welcome to this programming track! Here, you’ll use the Python programming language while learning to solve scientific problems from several fields of science. This track is intended for students who have no experience in programming at all. The Scientific Programming track consists of three courses:

- Scientific Programming 1 (SP1) — 3 EC, not graded but pass/fail.
- Scientific Programming 2 (SP2) — 3 EC, not graded but pass/fail.
- Data Processing (DP) — 6 EC, graded.

You learn about the Python language by working on programming problems from several scientific areas. The three courses from this track are designed to be taken together, but you can choose to only follow one or two of the courses.

### Schedule {#schedule}

You can follow each course at different paces to fit your schedule. This means you could do all three courses in a single semester, or you could do them spread out over several semesters. 

These are the most common schedules:

<style>
.tracks { width: 100%; border-collapse: collapse; margin-bottom: 1.5em; font-size: 0.9em; }
.tracks th, .tracks td {
  border: 1px solid #d8d2c4; padding: 0.35em 0.5em; text-align: center; border-radius: 3px; border-spacing: 5px;
}
.tracks thead th { background: #f0ede6; }
.tracks tbody th { text-align: left; white-space: nowrap; background: #f7f5f0; }
.tracks .sp1 { background: #dbe3d1; color: #39492a; }
.tracks .sp2 { background: #f0e2be; color: #5d4713; }
.tracks .dp  { background: #d3e0dc; color: #2d4a43; }
.tracks .next { text-align: left; font-style: italic; color: #6b6455; white-space: nowrap; }
</style>

<table class="tracks">
  <thead>
    <tr>
      <th>Schedule</th>
      <th>Sep</th><th>Oct</th><th>Nov</th><th>Dec</th><th>Jan</th>
      <th>Feb</th><th>Mar</th><th>Apr</th><th>May</th><th>Jun</th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Fast</th>
      <td class="sp1">SP1</td>
      <td class="sp2">SP2</td>
      <td class="dp" colspan="2">DP</td>
      <td colspan="6"></td>
      <td></td>
    </tr>
    <tr>
      <th>Standard</th>
      <td class="sp1" colspan="2">SP1</td>
      <td class="sp2" colspan="2">SP2</td>
      <td></td>
      <td class="dp" colspan="4">DP</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Relaxed</th>
      <td class="sp1" colspan="4">SP1</td>
      <td></td>
      <td class="sp2" colspan="4">SP2</td>
      <td></td>
      <td class="next">DP next year</td>
    </tr>
    <tr>
      <th>Fast (starting Feb)</th>
      <td colspan="5"></td>
      <td class="sp1">SP1</td>
      <td class="sp2">SP2</td>
      <td class="dp" colspan="2">DP</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Standard (starting Feb)</th>
      <td colspan="5"></td>
      <td class="sp1" colspan="2">SP1</td>
      <td class="sp2" colspan="2">SP2</td>
      <td></td>
      <td class="next">DP next year</td>
    </tr>
    <tr>
      <th>Relaxed (starting Feb)</th>
      <td colspan="5"></td>
      <td class="sp1" colspan="4">SP1</td>
      <td></td>
      <td class="next">SP2 and DP next year</td>
    </tr>
  </tbody>
</table>

You don't have to follow the entire Scientific Programming track, **you can also follow a single course**. 

### Attendance {#attendance}

There are no lectures (except for a non-compulsory kick-off meeting at the start of Scientific Programming 1) and the tutorials are flexible. 

The fact that the track offers a lot of flexibility doesn't mean you are on your own. In the tutorials, we do provide a lot of help with the programming assignments. You'll work on campus (together with other students) in a classroom. You can ask us questions while you're working on your assignments.

- You can find the times and locations here: [Tutorial and exam schedules](/datanose)
- **We expect all students to join at least one tutorial a week.** You can pick which one you prefer yourself.
- This is the main place where you talk with us and meet other students.


## Programming modules {#programming-modules}

You're going to learn programming through a number of programming modules. 
The modules are grouped into levels, you have to make one module per level. 
For some levels you have the choice between two different modules. 
When there is such a choice, you will learn the same programming concepts, but often in different thematic context (i.e. different scientific fields).

Each module consists of:

- **Theory** — explanations, both written and in the form of videos.
- **Pair assignments** — assignments you are encouraged to do together with other students.
- **Individual assignments** — assignments you make on your own (with our help, of course).
- **Challenges** — optional, more difficult assignments.

Here below is an overview of all modules for all courses. Click a module title to read what it is about.

<style>
.modules { width: 100%; border-collapse: collapse; margin-bottom: 1.5em; }
.modules th {
  text-align: left; padding: 0.4em 0.6em; font-size: 0.9em;
  background: #f0ede6; border: 1px solid #d8d2c4;
}
.modules td { vertical-align: top; padding: 0.5em 0.6em; border: 1px solid #d8d2c4; }
.modules td.mid { vertical-align: middle; }
.modules summary { cursor: pointer; font-weight: bold; }
.modules details p { margin: 0.6em 0 0; font-size: 0.9em; line-height: 1.4; }
.modules .or { margin: 0.5em 0; font-style: italic; }
.modules .todo { color: #8a6d3b; font-style: italic; }
</style>

### Scientific Programming 1 (Level 1 - Level 3) {#sp1-modules}

<table class="modules">
  <tr>
    <th>Level 0</th>
    <th>Level 1 (choose one)</th>
    <th>Level 2 (choose one)</th>
    <th>Level 3</th>
  </tr>
  <tr>
    <td class="mid">
      <details><summary>INSTALL</summary>
        <p>Before you can start programming you set up your own machine: learn to use the command line, install Python together with uv and checkpy, and install the Zed editor. Work through these steps before Level 1.</p>
      </details>
    </td>
    <td>
      <details><summary>ALGORITHMS</summary>
        <p>Learn to think like a computer. Things that we intuitively know how to do, like drawing a pyramid or computing change for a payment, is hard to get a computer to do right. In this module you’ll learn how to break down such intuitive problems into steps that even a computer can understand.</p>
      </details>
      <p class="or">or</p>
      <details><summary>NUMBERS</summary>
        <p>How do you know if a number is a prime number? Number theory is the science about properties of numbers. In this mathematically oriented module you create a series of programs that compute this and other properties of numbers. No math knowledge required for this module. (You will learn some, though.)</p>
      </details>
    </td>
    <td>
      <details><summary>INTEGRATION</summary>
        <p>In many scientific fields you need to determine the surface area under a function. Integration is a mathematical tool for doing so. However this tool doesn't always work and in such cases we can use numerical integration techniques to let the computer do the work for us. You will learn two important techniques for numerical integration.</p>
      </details>
      <p class="or">or</p>
      <details><summary>TEXT</summary>
        <p>Natural language processing is the science of making a computer understand (something about) natural human language. You will learn how you can get a computer to understand the sentiment of tweets. Is the tone of the tweet positive or negative?</p>
      </details>
    </td>
    <td class="mid">
      <details><summary>BIG DATA</summary>
        <p>In this module you will learn to work with data. You will, for example, analyze weather from the Netherlands and answer questions like: When was the first heat-wave? What was the longest freezing period?</p>
      </details>
    </td>
  </tr>
</table>

### Scientific Programming 2 (Level 4 - Level 6) {#sp2-modules}

<table class="modules">
  <tr>
    <th>Level 4</th>
    <th>Level 5</th>
    <th>Level 6</th>
  </tr>
  <tr>
    <td>
      <details><summary>MONOPOLY</summary>
        <p>When playing Monopoly, a starting player's advantage seems unfair. To verify, you could play many (millions) real games, but this would take way too much time. Instead, you'll write a computer simulation. This also allows you to experiment with game adjustments to make it fair. You're doing all this for a board game, but this simulation principle applies to various scientific fields (economy, chemistry, biology...).</p>
      </details>
    </td>
    <td>
      <details><summary>MONOPOLY 2</summary>
        <p>This is a continuation of MONOPOLY. You’re going to improve the design of your Monopoly simulation. You will learn about more advanced data structures that can help you improve the design of your code dramatically, making it easier to debug, maintain and extend. You will also learn about computational complexity, which gives you a way to reason about the efficiency of your algorithms and shows why picking the right data structure can mean the difference between a run time of a couple of minutes and one of weeks. Redesigning code that you already wrote using more advanced concepts might seem redundant, but it can be one of the most valuable learning experiences on the way to becoming a good programmer.</p>
      </details>
    </td>
    <td>
      <details><summary>POPULATIONS</summary>
        <p>Predator-prey simulations are models used in ecology and computer science to study the dynamics between populations of predators and their prey within an ecosystem. What's particularly interesting about these simulations is how they can reveal emergent patterns and complex behaviors that arise from relatively simple rules. To make it easier to program such a simulation you will learn a programming technique called object oriented programming (OOP).</p>
      </details>
    </td>
  </tr>
</table>

### Data Processing (Level 7 - Level 10 + final project) {#dp-modules}

<table class="modules">
  <tr>
    <th>Level 7</th>
    <th>Level 8</th>
    <th>Level 9</th>
    <th>Level 10</th>
    <th width="32%">Final project</th>
  </tr>
  <tr>
    <td>
      <details><summary>PANDAS</summary>
        <p>Data processing is the art of reading and transforming data so that it can be easily analyzed, visualized and used in machine learning. You could do all of that with the for-loops and file I/O you already know, but it gets cumbersome very quickly, which is why Python has packages built for the job. In this and the next module we focus on the most widely used one, Pandas, though the principles carry over to most data-oriented packages and programming languages, such as SQL or R. Some subjects you will see in this module are: reading, selecting and grouping data, and dealing with missing values. In the end you will see how some of the *Weather* assignments from Scientific Programming 1 become considerably easier with Pandas.</p>
      </details>
    </td>
    <td>
      <details><summary>XKCD</summary>
        <p>This is a continuation of PANDAS. Some subjects you will see in this module are: data quality, combining data sets with concatenation and joins, reshaping data between long and wide form, and rolling windows. You finish with an assignment in which you have to combine data from wildly different sources, from biology, physics and astronomy, to reproduce an <a href="https://xkcd.com/3283/">XKCD comic</a>.</p>
      </details>
    </td>
    <td>
      <details><summary>DATABASES</summary>
        <p>When working with really large amounts of data, you typically won't store it in simple (text) files on your computer. You'd use something like a relational database. To get information from a database you'll need a specific language called Structured Query Language (SQL). You're going to practice SQL by solving a mystery...</p>
      </details>
    </td>
    <td>
      <details><summary>WIKIPEDIA</summary>
        <p>When you’re working with data, it does not always come packaged in a nice “machine readable” way, like a CSV file or a database. Sometimes the information we have is embedded in the HTML of a website. Knowing how to access, transform and visualize that information can be an extremely useful tool in many real-world data projects. In this module you will learn how to use BeautifulSoup, a Python package that allows you to extract data from websites, on a copy of Wikipedia that we host ourselves.</p>
      </details>
    </td>
    <td>
      <details><summary>FINAL PROJECT</summary>
        <p>Do you have data from your own studies or research that you would like to analyze? Do this with our help for the final project of this course. The goal here is to work on something that you find interesting and care about.</p>
      </details>
    </td>
  </tr>
</table>

## Grading {#grading}

**Scientific Programming 1 and 2** are pass/fail. You pass a course by completing all of its
modules and passing an on-campus programming exam of about three hours.

**Data Processing** is graded (1-10) and has no exam. Your grade comes from two of the modules
and the final project:

Once you are enrolled, the syllabus for your own schedule has the full rules and the deadlines.

## Prerequisites {#prerequisites}

Scientific Programming 1 assumes no prior programming experience. If you have already done a course in Python, or if you have extensive experience in another programming language, this course might not be your best starting point.

Other than that, some modules assume high school mathematics or physics, but in those cases you can choose an alternative module that doesn't. 

Scientific Programming 2 and Data Processing only assume the preceding course as prior knowledge.

## Learning goals {#learning-goals}

**Scientific Programming 1** is a beginner's course. You will learn the basics of Python programming as well as several different ways of solving computational problems. After this course, we envision that you:

- can transform the description of a simple algorithm into working code by combining basic program elements;
- can apply several scientific programming techniques from different areas of study;
- can use a couple of libraries in your program and know how to find and read documentation on other libraries;
- can make your programs simpler and easier to read by employing a few standard tactics;
- can trace and fix several common programming errors.

After **Scientific Programming 2** you should be able to independently tackle typical programming challenges that you might encounter in your field of studies/research. We will teach you more intermediate Python concepts. And some more advanced concepts pertaining to data analysis. After this course, we envision that you:

- can use native python data structures (like sets, dictionaries, and tuples);
- analyze the complexity of an algorithm;
- quickly learn to use new python packages and know how to find documentation for them;
- import and analyze data;
- create advanced plots.

For **Data Processing** you'll learn how to read, transform and analyze data that you might find in various scientific areas. After this course we envision that you:

- can read data into your programs from several structured standard formats;
- can transform data into a form suitable for further analysis by combining basic operators;
- can build meaningful visualizations of your data;
- understand how to write programs that are easy to understand for yourself and other programmers;
- are capable of using advanced programming concepts (like object oriented programming).

## Course materials {#materials}

All the reading and video material is available on this website. You do not need to purchase any books or software. Every module consists of short explanations (written and in the form of videos) and assignments. _You do need to bring your own laptop._

## Doing your own work {#plagiarism}

This course's philosophy on academic honesty is best stated as "be reasonable". Discussing the
material with other students helps you learn, and pair assignments are meant to be done
together. But the essence of all work you submit must be your own.

Handing in someone else's solution is not acceptable, and neither is handing in work produced
by an AI assistant such as ChatGPT or Copilot.

In all cases we follow the directives regarding fraud and plagiarism of the University of
Amsterdam and of the Computer Science BSc programme. Find them here in [English] and [Dutch].
Once you are enrolled, the syllabus for your own schedule sets out in detail which acts the
course considers reasonable and which it does not.

[Dutch]: http://uva.nl/plagiaat
[English]: https://student.uva.nl/en/content/az/plagiarism-and-fraud/plagiarism-and-fraud.html

## Acknowledgements {#acknowledgements}
This course has been designed by Simon Pauw, Martijn Stegeman, Wouter Vrielink, Tim Doolan and Ivo van Vulpen.

It is partially based on many great programming resources that have been published as Open Courseware under a Creative Commons license. The resulting work itself is also published under the Creative Commons License Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License. 

We have had lots of help from students as well as teaching assistants who tried the course or added ideas of their own. We especially thank:

- Jelle van Assema (assignments and checkpy)
- Puck te Rietmolen (revisions)
- Roan van Blanken (checkpy tests)
- Amir Sahrani (assignments)
- Natasja Wezel (videos, revisions)
- Iris Luden (video)
- Marianne de Heer Kloots (revisions and testing)
- Maarten Inja (DNA assignment)
- Quinten Post (translations)
- Marleen Rijksen (revisions)
- Huub Rutjes (films)
- Vera Schild (checkpy tests)
- Luca Verhees (artwork “semester of code”)

We have used many programming recourses for inspiration:

- 6.189 A Gentle Introduction to Programming Using Python by Sarina Canelake at MIT http://ocw.mit.edu
- 6.00 Introduction to Computer Science and Programming, Fall 2008 by Eric Grimson and John Guttag at MIT http://ocw.mit.edu
- CS50 Introduction to Computer Science I by David Malan at Harvard http://cs50.tv/
- 6.0001 Introduction to Computer Science and Programming in Python by Ana Bell, Eric Grimson and John Guttag at MIT http://ocw.mit.edu
- Think Python by Allen B. Downey http://greenteapress.com/wp/think-python/
