# Resources

A collection of general interview prep guides, study materials, useful tools, and helpful advice for developers. Check out the [main interview guide](./README.md).

Click on the hamburger menu (icon with 3 horizontal stripes) at the top left corner of the README to jump to a topic.

:sparkles: = great content to review!

## General Guides (Overview)

- :sparkles: [How to Break Into the Tech Industry—a Guide to Job Hunting and Tech Interviews](https://haseebq.com/how-to-break-into-tech-job-hunting-and-interviews/)

  - written in May 2016 by Haseeb Qureshi

  <details><summary>More about Haseeb Qureshi</summary>

  - at the time of writing: former pro poker player, Director of Product at App Academy
  - currently: "Managing Partner at Dragonfly Capital. Effective Altruist. Airbnb, Earn.com (acquired by Coinbase) alum. Instructor @ Bradfield. Writer. Former poker pro. Donate 33% of my income to charity."

  </details>

- :sparkles: [The Interview Study Guide for Software Engineers](https://dev.to/seattledataguy/the-interview-study-guide-for-software-engineers-764)

  - a list of video lectures covering CS fundamentals in [Python](#python) and [SQL](#sql)
  - written by Ben Rogojan and last updated in December 2019

- [How to pass a programming interview](https://triplebyte.com/blog/how-to-pass-a-programming-interview) from Triplebyte

  - a short article, written in April 2020
  - :sparkles: a [longer article](https://triplebyte.com/blog/triplebyte-s-way-too-long-technical-interview-prep-guide) with more technical details

_[Click here](#resources) to go back to the top._

## CS Fundamentals

- Learn one language inside and out for interviews (eg: Python).
- Stick to learning the basics and skip on the fancy stuff (like list comprehensions) until you feel 100% comfortable with everything else.

**Topics:**

- data structures
- algorithms
- big O notation
- dynamic programming
- string manipulation
- object oriented programming (OOP)
- recursion
- tree traversal
- breadth-first search vs depth-first search

**Possibly optional stuff:**

- graph theory
- design patterns
- combinatorial problems

**Algorithms:**

- [The Tech Interview Handbook](https://techinterviewhandbook.org/algorithms/introduction/): [Algorithm tips](https://techinterviewhandbook.org/algorithms/introduction/#general-tips)

**Big O Notation:**

- freeCodeCamp.org's free 2 hr lecture video: https://www.youtube.com/watch?v=Mo4vesaut8g

## Object-Oriented Programming (OOP)

**What is it?**

- encapsulation

- [design patterns](https://en.wikipedia.org/wiki/Object-oriented_programming#Design_patterns)

More will be added soon.

## Code Quality

- [When to check your code quality](https://realpython.com/python-code-quality/#when-can-i-check-my-code-quality)
    <details><summary>Characteristics of high-quality code</summary>

  _Originally written for Python, but the general tips are true for most or all other languages._

  - It does what it is supposed to do.
  - It does not contain defects or problems.
  - It is easy to read, maintain, and extend.

  _Quoted from Real Python's [article about code quality](https://realpython.com/python-code-quality/#what-is-code-quality)._
    </details>

- keep your code [DRY (don't repeat yourself)](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)

### Anti-Patterns

**What is it?**
"a common response to a recurring problem that is usually ineffective and risks being highly counterproductive" ([Wikipedia](https://en.wikipedia.org/wiki/Anti-pattern))

watch out for [antipatterns](https://sourcemaking.com/antipatterns) in [the code](https://sourcemaking.com/antipatterns/software-development-antipatterns)

### Code Review

<details><summary>What qualities do code reviewers look for?</summary>

- **Design**: Is the code well-designed and appropriate for your system?

- **Functionality**: Does the code behave as the author likely intended? Is the way the code behaves good for its users?
- **Complexity**: Could the code be made simpler? Would another developer be able to easily understand and use this code when they come across it in the future?
- **Tests**: Does the code have correct and well-designed automated tests?
- **Naming**: Did the developer choose clear names for variables, classes, methods, etc.?
- **Comments**: Are the comments clear and useful?
- **Style**: Does the code follow our style guides?
- **Documentation**: Did the developer also update relevant documentation?

_Quoted from Google's [Code Review Developer Guide](https://google.github.io/eng-practices/review/)._

</details>

**Resources:**

- :sparkles: Google's [Code Review Developer Guide](https://google.github.io/eng-practices/review/)
  - [The Code Reviewer's Guide](https://google.github.io/eng-practices/review/reviewer/)
  - [The Change Author's Guide](https://google.github.io/eng-practices/review/developer/)
    - how to get your code through a code review
    - CL = changelist (aka "change", "patch", "pull request")

_[Click here](#resources) to go back to the top._
## Design Patterns

**What are they?**

- **creational patterns** provide the capability to create objects based on a required criterion and in a controlled way

<details><summary>Examples of creational design patterns</summary>

<details><summary>from Wikipedia</summary>

- Abstract Factory pattern: a class requests the objects it requires from a factory object instead of creating the objects directly

- Factory method pattern: centralize creation of an object of a specific type choosing one of several implementations
- Builder pattern: separate the construction of a complex object from its representation so that the same construction process can create different representations
- Dependency Injection pattern: a class accepts the objects it requires from an injector - instead of creating the objects directly
- Lazy initialization pattern: tactic of delaying the creation of an object, the calculation of a value, or some other expensive process until the first time it is needed
- Object pool pattern: avoid expensive acquisition and release of resources by recycling objects that are no longer in use
- Prototype pattern: used when the type of objects to create is determined by a prototypical instance, which is cloned to produce new objects
- Singleton pattern: restrict instantiation of a class to one object

</details>

<details><summary>from The Interview Study Guide for Software Engineers</summary>

- Factory Design Pattern
- Observer Design Pattern
- Adapter Design Pattern
- Facade Design Pattern
- Chain of Responsibility Design Pattern
- Interpreter Design Pattern
- Singleton Design Pattern
- Head First Design Patterns

his recommended resources:

- [video snippet from Dr. Timothy Lethbridge's SEG 2100 course](https://www.youtube.com/watch?v=LAP2A80Ajrg&list=PLJ9pm_Rc9HesnkwKlal_buSIHA-jTZMpO&t=3350s) (20 min) - recorded in 2002
- [video lectures for each (creational) design pattern](https://dev.to/seattledataguy/the-interview-study-guide-for-software-engineers-764/#design-patterns)

_Quoted from [The Interview Study Guide for Software Engineers](https://dev.to/seattledataguy/the-interview-study-guide-for-software-engineers-764/#design-patterns)._

</details>
</details>

- **structural patterns** are about organizing different classes and objects to form larger structures and provide new functionality

- **behavioral patterns** are about identifying common communication patterns between objects and realizing these patterns

- **concurrency patterns** deal with the multi-threaded programming paradigm

**Resources:**

- [list of creational/structural/behavioral/concurrency design patterns](https://en.wikipedia.org/wiki/Software_design_pattern#Classification_and_list) from Wikipedia
- [examples of structural patterns](https://en.wikipedia.org/wiki/Structural_pattern) from Wikipedia
- [video lectures for each (creational) design pattern](https://dev.to/seattledataguy/the-interview-study-guide-for-software-engineers-764/#design-patterns)

_[Click here](#resources) to go back to the top._

## System Design

**General:**

- :sparkles: [System Design Primer](https://github.com/donnemartin/system-design-primer): learn how to design scalable systems
- Entity Relationship Diagrams (ERD): [quick reference for relationship symbols](https://www.vivekmchawla.com/erd-crows-foot-relationship-symbols-cheat-sheet/)

_[Click here](#resources) to go back to the top._

## Databases

**Topics:**

- SQL vs NoSQL databases
- ACID compliance (atomicity, consistency, isolation, and durability)
- normalization
- data warehousing
- sanitizing user input (beware of SQL injection attacks!)

**General:**

- DB structure & design tutorial: https://www.lucidchart.com/pages/database-diagram/database-design
- MySQL vs PostgreSQL: https://towardsdatascience.com/mysql-vs-postgresql-3d48891452a


**Diagram Drawing Tools:**

1. https://www.diagrams.net/

   - This is the tool we used for systems design diagrams yesterday.

2. https://dbdiagram.io/home

   - Very similar to option #3. Use this if you prefer typing up your db schema. Allows you to import/export SQL.

3. https://drawsql.app/home
   - Very similar to option #2. Nice UI and UX, but not easy to type out schema and relationships. Allows you to import/export SQL. Better relationship arrows with directionality.

_[Click here](#resources) to go back to the top._

## Data Engineering

- [Extract Transform Load (ETL)](https://databricks.com/glossary/extract-transform-load)
- :sparkles: [Designing an ETL pipeline (video)](http://www.acheronanalytics.com/acheron-blog/sql-best-practices-designing-an-etl-video)
  - from an operational database to a data warehouse

## Data Science

Quick reference: [How do you decide whether to use Python or R?](https://s3.amazonaws.com/assets.datacamp.com/email/other/Python+vs+R.pdf)

_Would data visualization also go here?_

**Topics:**

- [SQL](#sql) & data analysis
- [Data structures & algorithms](#cs-fundamentals)
- [Machine learning theory](#machine-learning)
- Modeling case studies
- [Database](#databases) & [system design](#system-design)
- Product & business intuition
- Statistics & probability
- [Python scripting](#python)
- Experimentation & A/B testing

**Optional Topics:**

_These might fit better under [data engineering](#data-engineering)..._

- data warehousing
- data cleanup

**Resources:**

- https://www.theseattledataguy.com/4-skills-data-scientist-must-have/

**Helpful Libraries:**

- pandas: [10 minutes to pandas](https://pandas.pydata.org/docs/user_guide/10min.html)
- [D3.js](https://d3js.org): examples [here](https://observablehq.com/@d3/gallery) and [there](https://www.d3-graph-gallery.com), tutorials on [their wiki](https://github.com/d3/d3/wiki/Tutorials) or [Observable](https://observablehq.com/@d3/learn-d3)

**Problem Sets:**

- https://www.interviewquery.com/blog-python-data-science-interview-questions

**Services:**

- https://www.interviewquery.com
  - paid service to "focus your studying and practice only the most relevant questions for your dream role and company"

_[Click here](#resources) to go back to the top._

## Front-End

**Types of Front-End Roles:**

1. Functional JavaScript-related work
   - middleware
   - handling APIs
   - building APIs
2. Visual work
   - DOM structure/optimization
   - CSS & JS interactions
   - may blend with UX/UI design a bit...

**Watch:**

- A Beginner's Guide to React: https://egghead.io/lessons/react-a-beginners-guide-to-react-introduction

**Quick Reads:**

- [20 inspiring web & mobile wireframe examples](https://www.justinmind.com/blog/20-inspiring-web-and-mobile-wireframe-and-prototype-examples/)
- [Helpful tips and best practices for jQuery](https://code.tutsplus.com/tutorials/14-helpful-jquery-tricks-notes-and-best-practices--net-14405) (written 9/11/2010): but to be more marketable, learn React instead :)

**Longer Reads:**

- :sparkles: Front-End Developer Handbook by Cody Lindley:
  - 2018: https://frontendmasters.com/guides/front-end-handbook/2018/
  - 2019: https://frontendmasters.com/guides/front-end-handbook/2019/
  - There are no 2020 or 2021 versions.
- :sparkles: MDN's front-end web developer guide: https://developer.mozilla.org/en-US/docs/Learn/Front-end_web_developer
  - a structured course with exercises and assessments for each section

<details><summary>The subjects covered are:</summary>

- Basic setup and learning how to learn
- Web standards and best practices (such as accessibility and cross-browser compatibility)
- HTML, the language that gives web content structure and meaning
- CSS, the language used to style web pages
- JavaScript, the scripting language used to create dynamic functionality on the web
- Tooling that is used to facilitate modern client-side web development.

_Quoted from the link above._

</details>

## Back-End

**General:**

1. [CS fundamentals](#cs-fundamentals)
2. Data structures
3. Algorithms
4. [System design](#system-design)
5. Data models
6. [Data science](#data-science) - optional

### Problem Sets

- [andrewblum's recommended leetcode problems](https://github.com/andrewblum/recommended-problems):
  Recommended by Hackbright Academy instructor and UC Berkeley alum Andrew Blum:

_[Click here](#resources) to go back to the top._

# Language-Specific Resources

## Python

**Official Documentation:**

- [The Python Tutorial](https://docs.python.org/3/tutorial/index.html#tutorial-index)
- [Glossary](https://docs.python.org/3/glossary.html#glossary)
- [The Python Standard Library](https://docs.python.org/3/library/index.html)
- [The Python Language Reference](https://docs.python.org/3/reference/index.html#reference-index)
- [PEP 8](https://www.python.org/dev/peps/pep-0008/): style guide

**General:**

- :sparkles:[Jupyter notebooks to learn Python 3.5+](https://jerry-git.github.io/learn-python3/), including the following topics:
  - [Idiomatic Python](https://jerry-git.github.io/learn-python3/notebooks/intermediate/html/idiomatic_misc2.html#Properties-instead-of-getter/setter-methods): some do's and don'ts at an intermediate level
  - :sparkles: [Best practices](https://jerry-git.github.io/learn-python3/notebooks/intermediate/html/best_practices.html): includes why + how
  - [goodies of the standard Python libarary](https://jerry-git.github.io/learn-python3/notebooks/intermediate/html/std_lib2.html): encoding/decoding JSON, mock tests, etc.
- :sparkles: Python cheatsheet (basics to more fancy stuff): https://www.pythoncheatsheet.org
  - Python comprehensions: [a step-by-step guide](https://www.pythoncheatsheet.org/blog/python-comprehensions-step-by-step/)
- :sparkles: [Big O notation](https://wiki.python.org/moin/TimeComplexity): more about time complexity
- Algorithm implementations: https://www.algorist.com/languages/Python.html

**Tools:**

- Python Package Index (PyPI): https://pypi.org
- [Jupyter notebooks](https://jupyter.org)
- :sparkles:[Formatting strings](https://pyformat.info): comparing new vs old styles

<details><summary>Extra resources</summary>

- [Dive Into Python 3](https://diveintopython3.net): differences between Python 2 and 3 in textbook form, for free

</details>

_[Click here](#resources) to go back to the top._

## JavaScript

**Getting Started:**

- [MDN's JavaScript Tutorials for Complete Beginners](https://developer.mozilla.org/en-US/docs/Web/JavaScript#for_complete_beginners)
- Language basics crash course from MDN: [here](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics#language_basics_crash_course)
- Airbnb's JavaScript Style Guide: https://github.com/airbnb/javascript

**Official Documentation:**

- [JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide): overview of the language
- [JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference): exhaustive information about a language feature
  - official repository of facts about JS


_[Click here](#resources) to go back to the top._

## SQL

- [Writing more legible SQL](https://www.craigkerstiens.com/2016/01/08/writing-more-legible-sql/): tips written in 2016
- Hackbright Lecture on SQLAlchemy (day 1): https://fellowship.hackbrightacademy.com/materials/serft8/lectures/sql-alchemy-1/
- [60+ SQL questions to prepare for interviews](https://www.interviewbit.com/sql-interview-questions/) from InterviewBit
- [Interview questions](https://www.geeksforgeeks.org/sql-interview-questions/) from GeeksforGeeks

<details><summary>Extra resources</summary>

- [The best Postgres feature you're not using – CTEs aka WITH clauses](https://www.craigkerstiens.com/2013/11/18/best-postgres-feature-youre-not-using/) (Craig Kerstiens, 11/18/2013)

</details>

_[Click here](#resources) to go back to the top._

# Extra Material

- [How does the internet work?](https://www.youtube.com/watch?v=zN8YNNHcaZc) - a nearly 2 hr lecture video from freeCodeCamp.org (on Youtube)

**Git & GitHub:**

- How to write a good Git commit message: https://cbea.ms/git-commit/
- How to collaborate on a project with GitHub: https://medium.com/@jonathanmines/the-ultimate-github-collaboration-guide-df816e98fb67
  - setup git flow with a new team

**Regular Expressions:**

<details><summary>More info here</summary>

- :sparkles: Python Cheatsheet's [quick tutorial](https://www.pythoncheatsheet.org/#Regular-Expressions)
- :sparkles: HackerRank's [list of practice problems](https://www.hackerrank.com/domains/regex) (in order of difficulty)
- Tools: quick ways to test regex
  - https://pythex.org - in Python
  - https://regex101.com - in PHP, JS, Python, Golang, and Java
  - https://www.debuggex.com

</details>

_[Click here](#resources) to go back to the top._

# How to Stand Out

## Resume & CV

- Canva: [free resume templates](https://www.canva.com/templates/?query=resumes)
- :sparkles: Indeed's list of [transferrable skills to highlight](https://www.indeed.com/career-advice/resumes-cover-letters/transferable-skills) - helpful for career transition
- [How your resume is screened & 10 ways to improve your resume](https://techinterviewhandbook.org/resume/) - The Tech Interview Handbook

## Coding Challenges

- [The 10 Most Popular Coding Challenge Websites](https://www.freecodecamp.org/news/the-10-most-popular-coding-challenge-websites-of-2016-fb8a5672d22f/) - freeCodeCamp, updated in 2021
- https://www.aicrowd.com

## Project Portfolio

- [Using GitHub to build a portfolio](https://yourbrainoncomputers.com/using-github-to-build-a-portfolio-ultimate-guide/) - updated in 2020
- :sparkles: [The Ultimate Guide To Building A Personal Website](https://collegeinfogeek.com/personal-website/)
  - by Thomas Frank (College Info Geek), written in 2012, updated in January 2022
  - covers how to [get a domain name](https://collegeinfogeek.com/personal-website/#step-get-a-domain-name-and-hosting), [setup WordPress](https://collegeinfogeek.com/personal-website/#step-install-wordpress-and-set-up-your-site) (easy enough for people with no coding background), [improve search engine optimization](https://collegeinfogeek.com/personal-website/#step-optional-make-your-website-even-better), etc.

_[Click here](#resources) to go back to the top._

# The Job Hunt

- [How to find a remote job](https://www.glassdoor.com/blog/guide/how-to-find-a-remote-job/) - Glassdoor, updated 6/29/2021
- Indeed's [guide to maintaining mental health during the job search](https://www.indeed.com/career-advice/finding-a-job/college-graduate-job-search-anxiety) - Jane Kellogg Murray, 5/13/2021

_[Click here](#resources) to go back to the top._
