# How to effectively interview prep

**Important note:** The degree to which companies test for algorithms knowledge varies widely. If possible, look into what kinds of questions the company tends to ask (Glassdoor or Leetcode are places to start, but worth searching online for more resources). Generally speaking, startups are more likely to ask questions more related to everyday work, whereas larger companies are more likely to ask CS/algorithms questions. **[Check out this guide for some tips on startup-specific interview prep](startup_interview_prep.md)**.

This guide is focused on a typical CS/algorithms-based interview. A plan of attack to prepare:

- Work through good interview prep resources
- Learn essential data structures and algorithms
- Solve problems
- Practice whiteboarding
- Know your language in and out
- Do your research on companies
- Prep for behavioral questions
- Prep questions to ask interviewers
- Have a good side project

## Work through good interview prep resources

Find good resources to work through. There's a lot of good material out there so don't limit yourself to these, but some good ones I've used are:

- [**Leetcode**](https://leetcode.com/) ($0 to $35/mo) - a site with a huge number of real interview problems from software companies, where you can submit your solutions to the "online judge" which runs it against a suite of test cases. There's a guide on what problems to work through in [Tech Interview Handbook](https://yangshun.github.io/tech-interview-handbook/best-practice-questions/). Recommended.
- [**Cracking the Coding Interview**](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850) ($35) - a book that covers CS concepts well, along with problems and solutions with explanations. Recommended.
- [Interview Cake](https://www.interviewcake.com/) ($0 to $249) - problems with high-quality explanations, and other reference material.
- [Tech Interview Handbook](https://yangshun.github.io/tech-interview-handbook) (free) - a comprehensive guide to the technical interview.

## Learn essential data structures and algorithms

We'll cover this in more detail in the [data structures and algorithms](data_structures_and_algorithms.md) doc.

## Solve problems

If you expect your interview to have algorithms questions, the best way to prepare for them is to solve a lot of problems. Leetcode is a great place to find real problems that people get in tech interviews. When working on a problem, try to:

- Think out loud, like you would in an interview
- Ask clarifying questions early before diving into the code.
  - One common clarifying question is what you should optimize for - generally, time or space.
- Outline your approach before diving in
- Try a few concrete examples
- If applicable, describe a naive, brute force solution first (along with big-O runtime). You may not necessarily implement it, though - the interviewer may ask you for a more efficient solution. [[1]](https://medium.com/@yashgirdhar/11-companies-55-interviews-9-offers-including-google-and-amazon-heres-what-i-have-to-share-293852c1c98f) [[2]](https://yangshun.github.io/tech-interview-handbook/during-coding-interview)
- When you're done, carefully review your solution. Look it over line-by-line, and test it with example inputs. [[1]](https://yangshun.github.io/tech-interview-handbook/during-coding-interview#after-coding). It can be a bonus if you add good test cases without prompting.
- Evaluate the runtime/space of your solution in big O
- [Other tips from Tech Interview Handbook](https://yangshun.github.io/tech-interview-handbook/algorithms/algorithms-introduction)

As you solve problems, you'll find common problem-solving patterns [[1]](https://medium.com/@yashgirdhar/11-companies-55-interviews-9-offers-including-google-and-amazon-heres-what-i-have-to-share-293852c1c98f). Take notes on these patterns! It'll help you re-apply them to new problems.

After you solve a problem, or if you're having trouble after an hour or two, read the solution carefully and make sure you fully understand it. On Leetcode, there are often good solutions in the language of your choice in the "Discuss" tab. If you didn't get the solution, try implementing the solution without looking at it.

Doing a lot of problems will also help you get fast at [common programming patterns](./common_programming_patterns.md). Make sure you know how to do these quickly and without errors in your preferred language.


## Know your language in and out

You'll want to use the language you're most comfortable with for interviews, and know it intimately. Here are some important javascript concepts:

* Event loop
  * [The Javascript Event Loop](https://flaviocopes.com/javascript-event-loop/)
  * [Concurrency model and the event loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop)
* Closures
  * [What is a closure?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-closure-b2f0d2152b36)
* `this` - refers to the object which is executing the current function
  * [JavaScript — all about “this” keyword](https://codeburst.io/all-about-this-and-new-keywords-in-javascript-38039f71780c)
  * [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this)
  * Related: `.bind()`, `.call()`, and `.apply()`
* Prototypal inheritance


## Practice whiteboarding

Whiteboarding is nervewracking! For technical problems, interviewers generally like to see a candidate explain their thought process as they're solving a problem. I know this can be really hard; I struggle with this part. It's useful to practice this upfront! Practicing whiteboarding with a friend is highly recommended in order to get you more comfortable and used to thinking out loud [[1]](https://blog.usejournal.com/i-interviewed-at-six-top-companies-in-silicon-valley-in-six-days-and-stumbled-into-six-job-offers-fe9cc7bbc996). 
[interviewing.io](https://interviewing.io/) is a site where you can practice realistic algorithmic interviews with engineers for free.


## Do your research on companies

Most companies want to hire people who care about the mission, and they'll usually ask why you're interested in working there. It's important to do some research on a company you're applying to and to have a good answer for that question, and also to have specific questions to ask about the company.

If you're interested in working at a startup, here are a few ways to find them:

- [Angel.co](https://angel.co/)
- [YC's top companies](https://www.ycombinator.com/topcompanies/)
- [YC "Who's hiring?" lists](https://news.ycombinator.com/item?id=21419536) (example for Nov 2019)
- [Breakout list](https://breakoutlist.com/all/)
- [Hired](https://hired.com/)


## Prep for behavioral questions

**Behavioral questions** are non-technical, verbal questions. The interviewer is trying to evaluate whether you can communicate effectively and clearly about your experience and motivations. [Here's an example of using the STAR framework to answer a behavioral question well](https://yangshun.github.io/tech-interview-handbook/star-format).

Common behavioral questions:

- **Tell me about yourself.** [Here's a good reference](https://yangshun.github.io/tech-interview-handbook/self-introduction) on answering this self-introduction question.
- **Why are you interested in working at this company?** Take a look at the company's product, website, job listing, and think about what resonates with you and what you're genuinely interested in.
- **What are you looking for in your next job?**
- **Why did you leave your previous company?**
- **Talk about a challenging project you worked on.** You'll want to be able to give a solid answer — and it really helps if you have either a recent work project or a side project that you can talk about in depth (see the "Have a good side project" section for more on this). The interviewer is trying to evaluate whether you can talk coherently about a complex topic, at both a high level and a technical level. Clear communication about technical work is extremely important - you'll need to talk to PMs, stakeholders, designers, and other engineers all the time at a startup.
- [Here's a list of more behavioral questions from Tech Interview Handbook](https://yangshun.github.io/tech-interview-handbook/behavioral-questions/)

## Prep questions to ask interviewers

You'll also want to be prepared to have some questions for each interviewer (which can end up being a lot of questions at an onsite with 5 interviewers). The questions you ask can have an impact! Interviewers may use them to judge what your priorities are and whether you're interested in the mission. Here's a [list of possible questions to ask](https://yangshun.github.io/tech-interview-handbook/questions-to-ask) to get started, but I recommend thinking up your own as well.


## Have a good side project

In my opinion, this is one of the better ways to stand out as a candidate, particularly when you're just starting out in your career. Be ready to explain your side project simply and clearly, so that a technical or non-technical interviewer can understand it. It's best if this project does something interesting or substantial either on the frontend or backend.

Examples of non-trivial features:

- Backend - connects to a database and has some tables that relate to each other (relational modeling)
- Backend - connects to an external API
- Backend - user registration and login
- Frontend - fetch data from backend API
- Frontend - forms or other data input
- Frontend - state management, e.g. redux

Ideally, make your project open-source and put it up on Github. Having a good project will help you stand out during the resume screening phase. In recruiting emails or interviews, a number of people have commented on open source projects I've had.

Some tips for your project:

- Have a great README. Take a look at some good README files from open source projects you use - they usually summarize what the project is about and how to run the project in development mode.
- Make the code readable. Have descriptive function and variable names, and have comments describing what you're doing if there's complex logic.
- Have a live demo. If it's a static site, you can host it on github pages for free (check out the `gh-pages` npm package). If it has a backend, there are options like Heroku, which has a free tier.
- Write tests if possible

A side project is always easier if it's about something you care about. What are your interests? For me, I like music a lot, so I built a map that displays nearby concerts on top of the Songkick API. You can also build a tool to solve a pain point you have, something you've encountered in everyday life — like a chrome extension that generates Github release notes.


## Next section

[**Next: Data structures and algorithms**](data_structures_and_algorithms.md)
