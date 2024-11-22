# Interest-based question banks for first-year programming students

The motivation for programming amongst first-year IT students varies
significantly, with some students very keen to pick up new skills, while
others need more inspiration. Performance of students in programming
has statistically been more "bimodal" than "normal". One of the
possible reasons is the dryness of problems students get in introductory
programming subjects.

Rather than asking them to

- *"add up items of an array"*

It might interest students if we ask them to:

- *"find the number of tickets Taylor Swift sold in her 2024 Eras Tour",
  or,*

- *"calculate the number of goals scored by Lionel Messi in the current
  season", or,*

- *"determine the total value of my stock portfolio"*

Some may enjoy the Taylor Swift example, some would relate to Messi, and
yet others will get excited by the shares context.

Anecdotal student feedback overwhelmingly favours problems with context
compared to *generic* problems.

# Proof-of-concept example

Example of a typical generic programming problem is:

*Define a function that when passed an array of integers,*

*returns the sum of all items in the array*

This question will be rephrased (as some examples), as,

- Sports 

  - *Define a function that, when given an array of integers where each
    number represents the goals scored by Messi over various matches,
    returns the **total number of goals** scored Messi.*

  - **Example:**

    - In a season, where the players scored the following goals: {1, 2,
      0, 3, 1}, your function should return 7 (1+2+0+3+1), which is the
      total number of goals scored by Messi across the 5 games.

- Music

  - *Define a function that, when given an array of integers where each
    number represents the duration of a song in minutes, returns
    the **total playtime** of the playlist.*

  - **Example:**

    - For a playlist with song durations (in seconds) {180,160, 240,
      140}, your function should return 720 (180+160+240+140), which is
      the total duration in seconds.

- Movies/TV

  - *Define a function that, when given an array of integers where each
    number represents the runtime of a movie in minutes, returns
    the **total duration** of your movie marathon.*

  - **Example:**

    - For a movie lineup with runtimes (in minutes) {120, 150, 95, 180},
      your function should return 545, which is the total time in
      minutes for the movie marathon.

- Video Games -- Sinan

- Business -- Combined

# Domains and topics

The domains in which we expect to write the questions are:

1.  Generic
2.  Entertainment (Music, Movies and other pop culture)
3.  Sports
4.  Gamers
5.  Science
6.  Business and finance (for example, stocks)

The sixth domain can be _mixed bag_.

The question bank can be developed simultaneously in several environments:

1.  CodeRunner: Current programming environment in Moodle.
2.  Visual Studio Code: For portability, reusability, and ease of
    dissemination.
3.  Codingbat.com: For wider adoption and equity.
4.  Ed Stem: Partner LMS being explored as an option due to its rich capabilities.

Our aim is to develop approximately multiple questions each for functions with:

|                             | **Python** | **Java** |
|-----------------------------|------------|----------|
| **Variables and operators** | Yes        | Yes      |
| **Conditions**              | Yes        | Yes      |
| **Loops**                   | Yes        | Yes      |
| **Arrays**                  |            | Yes      |
| **Lists**                   | Yes        |          |
| **Dictionary**              | Yes        |          |
| **ArrayLists**              |            | Yes      |
| **Strings**                 | Yes        | Yes      |

Possibly extra topics if our work is finished ahead of schedule:

|                                        |**Python**| **Java** |
|----------------------------------------|----------|----------|
| **Defining complete class**            | Yes      | Yes      |
| **Creating an ArrayList of objects**   | Yes      | Yes      |
| **Recursive Data Structures**          | Yes      | Yes      |

# Budget breakdown

6 domains

X 12 primary topics across the two languages

X 10 questions (on an average) each

X 4 platforms (CodeRunner, Codingbat, Visual Studio Code, Ed)

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--

2880 question instances

Assuming each question instance, on an average, takes 10 minutes to design and write,
this means approximately 480 hours of work. It is important to note that the first variation will take longer, and the subsequent ones will be much shorter, especially with CodeRunner "duplicate question" facility, and similar procedure with other platforms.

Also, we'll finish working with CodeRunner and Visual Studio Code, then move to Codingbat, and finally to Ed.

# Sample of deliverables

Some of the problems that we converted to "interesting domains" can be seen at:

- [https://codingbat.com/prob/p254748](https://codingbat.com/prob/p254748?parent=/home/gaurav.gupta@mq.edu.au/conditions)

- <https://codingbat.com/prob/p244597>

- <https://codingbat.com/prob/p294898>

- <https://codingbat.com/prob/p263710>

- <https://codingbat.com/prob/p266177>

- <https://codingbat.com/prob/p207720>

- <https://codingbat.com/prob/p221041>
