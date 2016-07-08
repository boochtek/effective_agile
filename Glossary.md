Agile Glossary
==============

* time box (v) - to limit the amount of time spent on a particular activity
* time box (n) - a limit on the amount of time spent on a particular activity
* standup meeting - a short meeting, where participants stand in order to move the meeting along more quickly (see also daily standup)
* daily standup - standup meeting held once a day to communicate the most important things
* daily scrum - daily standup meeting, as directed by Scrum
* CI - continuous integration
* continuous integration - automatically running all tests whenever code is checked in
* CD - continuous delivery
* continuous delivery - deploying new features as soon as the code is written and fully tested
* spike (n) - a story where the goal is to explore how something works
* spike (v) - to write some code to explore how something works; usually time boxed
* self-organizing team - a team that decides its own processes and structures
* pairing - pair programming
* pair (v) - pair programming
* pair (n) - two programmers that are pair programming, or shorthand for "pair partner"
* pair programming - two programmers working together on the same code
* pair partner - the other person with whom you are pair programming
* Kanban - a methodology (TODO: expand)
* Kanban board - a board showing all the tasks in flight, in columns corresponding to the steps in the process
* Scrum - an Agile methodology (TODO: expand)
* scrum - daily standup meeting, as directed by Scrum
* XP - Extreme Programming
* Extreme Programming - a methodology (TODO: expand)
* Lean - a methodology derived from Lean Manufacturing principles (TODO: expand)
* practice - TODO
* principle - TOOO
* value - TODO
* TDD - test-driven development
* test-driven development - test-first programming used to drive out better program design
* test-first programming - writing unit tests before writing the code to pass those tests
* BDD - behavior-driven development
* behavior-driven development - a way of thinking about TDD as a way to specify behaviors, instead of writing tests; ATDD
* ATDD - acceptance-test-driven development
* acceptance-test-driven development - writing acceptance tests before writing unit tests, to drive a better user experience
* acceptance test - a high-level test describing how the application should work from the user's perspective
* end-to-end test - a test that exercises the entire technology stack
* smoke test - a test run against production services (possibly right before promoting the service to production status) to ensure that a deploy went OK
* sustainable pace - working reasonable hours, so as not to get burned out or make mistakes due to being too tired to think
* Lean - a methodology (TODO: expand)
* unit test - a low-level test meant to exercise a single function, method, or small portion of a class
* functional test - a mid-level test meant to test functionality of several components together
* integration test - a mid-level test meant to test integration of 2 or more smaller units
* chickens - people who have a peripheral role on the team, as opposed to pigs (from a story by Ken Schwaber about bacon and eggs)
* pigs - people fully committed to the team, as opposed to chickens (from a story by Ken Schwaber about bacon and eggs)
* coach - role of a person helping a team learn how to employ Agile practices, principles, and values more effectively
* Scrum Master - role of a person ensuring that Scrum practices are done correctly (TODO: verify)
* sprint - Scrum's name for an iteration
* iteration - a short period of time (usually a week or 2) to work on a set of stories (TODO: more)
* resource - a derogatory term used to describe workers in a dehumanizing manner
* overhead - a derogatory term used to describe management (used when management refers to workers as "resources")
* story - shorthand for "user story"
* user story - TODO
* job story - TODO
* story card - physical or virtual card on a task board, representing a story
* story points - a rough estimate of the level of effort required to complete an individual story
* velocity - the number of story points completed by a given team in a given iteration
* planning game - planning poker
* planning poker - a way of determining story points; after discussing the story, team members blindly vote on how many points the story should be
* Fibonacci sequence - often used in assigning points to stories, a set of numbers where each is the sum of the previous two in the sequence - 1, 1, 2, 3, 5, 8, 13, 21,
* estimation - the process of assigning story points (see planning poker)
* relative estimation - affinity estimation
* affinity estimation - TODO
* retro - shorthand for "retrospective"
* retrospective - a meeting to review how the team is functioning, and determine ways to improve
* collective ownership - all team members are equally responsible for all portions of the code (TODO: needs some work)
* open space - TODO: the unconference thing
* product owner - role of a person who decides how the product should work, and the priorities of what should be worked on
* mob programming - a method of programming where the entire team looks at and works on the code at the same time (TODO: more)
* randori - mob programming (TODO: is there a distinction?)
* refactor - TODO (include what it is NOT)
* red/green/refactor - a mnemonic device to remind ourselves how to do TDD correctly: first write a failing test, then write code to pass the test, then refactor to improve the code (while keeping the tests passing)
* definition of done - TODO
* done done - completed so as to meet the definition of done
* burn-down chart - TODO
* burn-up chart - TODO
* WIP - work in progress
* WIP limit - a limit to how much can be worked on at once, to reduce wasted effort
* waste - work that is done that could be eliminated; from Kanban (and lean TODO: is this true?)
* MVP - minimum viable product
* minimum viable product - first release of an application that proves the product is valid, without having to have all the features right away (from Lean)
* MMF - minimal marketable feature
* minimal marketable feature - first release of a feature that proves whether the feature is worth having (from Lean)
* code smell - an indication that there may be an issue with a piece of code, requiring it to be refactored or rewritten
* T-shaped - description of an ideal developer than has both depth of experience in several areas and a wide breadth of experience
* backlog - set of stories that are not currently ready to be worked (possibly due to prioritization)
* backlog grooming - reviewing stories in the backlog to see if they're still valid, whether things have changed so as to need to update them, or whether they should be reprioritized
* story grooming - see "backlog grooming"
* domain model - code modeling the real-world domain (things being worked on) TODO: fix
* design pattern - TODO
* pattern - usually refers to "design pattern"
* technical debt - TODO
* tech debt - short for "technical debt"
* branching strategy - TODO
* fail fast - TODO
* pivot (v) - to change direction of the project, after getting feedback
* pivot (n) - a change in direction of the project, after getting feedback
* acceptance criteria - criteria for a story defined by the stakeholders (or a proxy for them) that will be used to determines whether the story is complete
* epic - a story that takes much longer than anticipated, and keeps dragging on
* epic - a set of stories that go together to define all the pieces of a feature or related set of features
* theme - a set of features or stories that go together; usually larger/longer than an epic
* thin vertical slice - story broken down so that it will implement a small feature that has some value to the end users; usually requires implementation at all layers of the technology stack (TODO: fix)
* exploratory testing - manual testing to find issues not identified by automated tests
* given/when/then - a way of writing acceptance criteria, specifications, or tests; given = pre-conditions; when = action being specified; then = expected results (TODO: clean up)
* information radiator - person who transmits information to a large number of people (TODO: fix)
* INVEST - independent, negotiable, valuable, estimable, small, testable; mnemonic describing the properties of a well-designed goal (TODO: verify)
* SMART - specific, measurable, achievable, relevant, time-bounded; mnemonic describing the properties of a well-designed goal (TODO: verify)
* SWOT - strengths, weaknesses, opportunities, threats; mnemonic to describe main things to look at when reviewing potential team or personal improvements
* PDCA - plan, do, check, adjust (TODO: more, origin)
* Kaizen - TODO
* cycle time - expected (determined emperically) amount of time from when a story is started to when it is completed (TODO: more)
* project charter - TODO
* story mapping - TODO
* story splitting - splitting up a large or complex story into smaller stories
* ubiquitous language - all team members using the same vocabulary as the end users
* 5 "whys" - a way to determine why things happened; repeatedly asking why things happened, until getting to the root cause or reason (TODO: fix)
* waterfall - traditional (non-Agile) methodologies (TODO: origin)
* SAFe - Scaled Agile Framework
* Scaled Agile Framework - TODO
* regression testing - (hopefully automated) testing to ensure that features continue working and bugs do not recur
* regression - a condition where a feature stops working or a bug returns after it had been fixed
* code review - process of one or more team members reviewing the code written by others (TODO: more)
* pull request - request for a branch of recently-written code to be merged into the main development branch of code (TODO: fix)
* PR - pull request
* iteration 0 - first iteration of a project, to set up the architecture and get everything running, but with nearly no actual useful functionality
* walking skeleton - the basic framework of the project, but with nearly no actual useful functionality
* big up-front design - waterfall method of attempting to design a program before getting any feedback
* sprint planning - see "iteration planning"
* iteration planning - deciding what stories to work on in the next iteration; may also include backlog grooming and story estimation
