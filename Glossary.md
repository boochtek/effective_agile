Agile Glossary
==============

* 5 whys - a way to determine a root cause, by asking why something happened, then why that answer happened, repeatedly (nominally 5 times)
* acceptance criteria - criteria for a story defined by the stakeholders (or a proxy for them) that will be used to determines whether the story is complete
* acceptance test - a high-level test describing how the application should work from the user's perspective
* acceptance-test-driven development - writing acceptance tests before writing unit tests, to drive a better user experience
* affinity estimation - estimation of stories by comparing them relative to other stories
* ATDD - acceptance-test-driven development
* backlog - set of stories that are not currently ready to be worked (possibly due to prioritization)
* backlog grooming - reviewing stories in the backlog to see if they're still valid, whether things have changed so as to need to update them, or whether they should be reprioritized
* BDD - behavior-driven development
* behavior-driven development - a way of thinking about TDD as a way to specify behaviors, instead of writing tests; ATDD
* big up-front design - waterfall method of attempting to design a program before getting any feedback
* branching strategy - how a team handles branches in their source code repository; for example, a main branch for development, a branch for each story, and a branch for the currently production deployment
* burn-down chart - graph showing remaining work over time within the iteration
* burn-up chart - graph showing work in progress and completed within an iteration (or multiple iterations)
* CD - continuous delivery
* chickens - people who have a peripheral role on the team, as opposed to pigs (from a story by Ken Schwaber about bacon and eggs)
* CI - continuous integration
* coach - role of a person helping a team learn how to employ Agile practices, principles, and values more effectively
* code review - process of one or more team members reviewing the code written by others; involves checking for errors, omissions, test coverage, and any room for improvement
* code smell - an indication that there may be an issue with a piece of code, requiring it to be refactored or rewritten
* collective ownership - all team members are equally responsible for all portions of the code; any member can work on any portion of the code, and knowledge hoarding/silos are reduced
* continuous delivery - deploying new features as soon as the code is written and fully tested
* continuous integration - automatically running all tests whenever code is checked in
* cycle time - expected (determined empirically) amount of time from when a story is started to when it is completed
* daily scrum - daily standup meeting, as directed by Scrum
* daily standup - standup meeting held once a day to communicate the most important things
* definition of done - requirements for a story to be marked as "completed", fully ready for production use
* design pattern - reusable (and cataloged) solution to a common software design problem
* domain model - abstractions (and code) that model the real-world processes that are being implemented in software
* done done - completed so as to meet the definition of done
* end-to-end test - a test that exercises the entire technology stack
* epic - a set of stories that go together to define all the pieces of a feature or related set of features
* epic - a story that takes much longer than anticipated, and keeps dragging on
* estimation - the process of assigning story points (see planning poker)
* exploratory testing - manual testing to find issues not identified by automated tests
* Extreme Programming - an Agile methodology designed by Kent Beck, which takes several good ideas and pushes them to their extremes
* fail fast - finding out more quickly if an idea will work or not, so as to spend less time and money
* Fibonacci sequence - often used in assigning points to stories, a set of numbers where each is the sum of the previous two in the sequence - 1, 1, 2, 3, 5, 8, 13, 21,
* functional test - a mid-level test meant to test functionality of several components together
* given/when/then - a way of writing acceptance criteria, specifications, or tests, as recommended by BDD; a "given" is a pre-condition, "when" specifies the action being specified, and "then" describes the expected result
* information radiator - highly visible display of information, so anyone can see what's going on in a team "at a glance"
* integration test - a mid-level test meant to test integration of 2 or more smaller units
* INVEST - independent, negotiable, valuable, estimable, small, testable; mnemonic describing the properties of a well-designed story
* iteration - time box (usually a week or 2) to work on a set of stories; at the end of an iteration, a new set of functionality should be deployable
* iteration 0 - first iteration of a project, to set up the architecture and get everything running, but with nearly no actual useful functionality
* iteration planning - deciding what stories to work on in the next iteration; may also include backlog grooming and story estimation
* job story - alternative to user story format, focusing more on *why*: When (a given situation), I want to (motivation), so that I can (expected outcome)
* Kaizen - Japanese for "improvement"; methodology focusing on continuous improvement of all aspects of business processes
* Kanban - Japanese for "billboard"; methodology focusing on flow of work through different phases of a process, where tasks are "pulled" into later phases
* Kanban board - a board showing all the tasks in flight, in columns corresponding to the steps in the process
* Lean - methodology derived from Lean Manufacturing principles, focused on eliminating waste
* minimal marketable feature - first release of a feature that proves whether the feature is worth having (from Lean)
* minimum viable product - first release of an application that proves the product is valid, without having to have all the features right away (from Lean)
* MMF - minimal marketable feature
* mob programming - a method of programming where the entire team looks at and works on the code at the same time on a single computer
* MVP - minimum viable product
* open space - an "unconference", with topics not decided until the beginning of the meeting, and everyone encouraged to either participate or learn at each session they attend
* overhead - a derogatory term used to describe management (used when management refers to workers as "resources")
* pair (n) - two programmers that are pair programming, or shorthand for "pair partner"
* pair (v) - pair programming
* pair partner - the other person with whom you are pair programming
* pair programming - two programmers working together on the same code
* pairing - pair programming
* pattern - usually refers to "design pattern"
* PDCA - plan, do, check, adjust; method for continuous improvement, originating with Edwards Deming, used in Lean methodology
* pigs - people fully committed to the team, as opposed to chickens (from a story by Ken Schwaber about bacon and eggs)
* pivot (n) - a change in direction of the project, after getting feedback
* pivot (v) - to change direction of the project, after getting feedback
* planning game - planning poker
* planning poker - a way of determining story points; after discussing the story, team members blindly vote on how many points the story should be
* PR - pull request
* practice - a method of doing things that puts principles into concrete action
* principle - a general idea about how things should be done, derived from a set of values
* product owner - role of a person who decides how the product should work, and the priorities of what should be worked on
* project charter - document laying out the scope and objectives of a project, as well as stakeholders, roles, and responsibilities
* pull request - request for a branch of recently-written code to be reviewed and merged into the main development branch of code
* randori - Japanese for "free-style practice"; mob programming on some code as an exercise, as opposed to a "real" project
* red/green/refactor - a mnemonic device to remind ourselves how to do TDD correctly: first write a failing test, then write code to pass the test, then refactor to improve the code (while keeping the tests passing)
* refactor - to restructure existing code without changing its external behavior; often mistakenly used to mean any change to code
* regression - a condition where a feature stops working or a bug returns after it had been fixed
* regression testing - (hopefully automated) testing to ensure that features continue working and bugs do not recur
* relative estimation - affinity estimation
* resource - a derogatory term used to describe workers in a dehumanizing manner
* retro - shorthand for "retrospective"
* retrospective - a meeting to review how the team is functioning, and determine ways to improve
* SAFe - Scaled Agile Framework
* Scaled Agile Framework - methodology applying Agile principles across many teams within an organization
* Scrum - methodology focused on the process of software development; defines events, roles, and artifacts
* scrum - daily standup meeting, as directed by Scrum
* Scrum master - role of a person facilitating Scrum events and accountable for removing impediments
* self-organizing team - a team that decides its own processes and structures
* SMART - specific, measurable, achievable, relevant, time-bounded; mnemonic describing the properties of a well-designed objective
* smoke test - a test run against production services (possibly right before promoting the service to production status) to ensure that a deploy went OK
* spike (n) - a story where the goal is to explore how something works
* spike (v) - to write some code to explore how something works; usually time boxed
* sprint - Scrum's name for an iteration
* sprint planning - see "iteration planning"
* standup meeting - a short meeting, where participants stand in order to move the meeting along more quickly (see also daily standup)
* story - shorthand for "user story" describing a feature to be developed
* story card - physical or virtual card on a task board, representing a story
* story grooming - see "backlog grooming"
* story mapping - method of story planning, with stories arranged by both priority and complexity, which helps split up stories into smaller pieces
* story points - a rough estimate of the level of effort required to complete an individual story
* story splitting - splitting up a large or complex story into smaller stories
* sustainable pace - working reasonable hours, so as not to get burned out or make mistakes due to being too tired to think
* SWOT - strengths, weaknesses, opportunities, threats; mnemonic to describe main things to look at when reviewing potential team or personal improvements
* T-shaped - description of an ideal developer than has both depth of experience in several areas and a wide breadth of experience
* TDD - test-driven development
* tech debt - short for "technical debt"
* technical debt - problems within the code base that increase the amount of time it takes to add additional functionality
* test-driven development - test-first programming used to drive out better program design
* test-first programming - writing unit tests before writing the code to pass those tests
* theme - a set of features or stories that go together; usually larger/longer than an epic
* thin vertical slice - story broken down so that it will implement a small feature that has some value to the end users, implemented at all layers of the technology stack
* time box (n) - a limit on the amount of time spent on a particular activity
* time box (v) - to limit the amount of time spent on a particular activity
* ubiquitous language - all team members using the same vocabulary as the end users
* unit test - a low-level test meant to exercise a single function, method, or small portion of a class
* user story - format for describing a feature: As a (role), I want (goal) So that (benefit)
* value - general belief or ideal about what is desirable
* velocity - the number of story points completed by a given team in a given iteration
* walking skeleton - the basic framework of the project, but with nearly no actual useful functionality
* waste - work that is done that could be eliminated; from Lean/Kanban
* waterfall - traditional (non-Agile) development methodology, in which each phase is completely finished before the next (specially, all the design is completed before starting the implementation)
* WIP - work in progress
* WIP limit - a limit to how much can be worked on at once, to reduce wasted effort
* XP - Extreme Programming
