# Modern Testing (MT)

## principles

### https://www.angryweasel.com/ABTesting/modern-testing-principles/

### Why Do We have MT Principles?

- WHAT GOT US HERE WON"T GET AS THERE

	- MT is looking how to get "THERE"

		- Moving test from cost center to cost benefit 
		- Being Force multiplier

- Software is much easier to produce
- Thanks to advancements in Continuous Delivery, the customer has much more options to choose from

	- Companies are shipping faster

- It's much easier to compete with any company

	- For customers, the switching cost has gone way down

### The principles are not just theory

- They are based on Experience and observation

### Why modern testing

- To make contrast with Traditional 

	- Traditional testing is not only a cost but also delay 

### Principle 1

- Our priority is improving the business.

	- 
What it means to improve the business?

		- MTer needs to be seen as positive influence
		- Boiling Frogs

			- Adoption has to be gradual 

		- Delta from Idea to deployments is rapid 
		- Get that mvp out with just enough quality to get feedback from customers 
		- “You don’t get value from engineering effort until it is in customer hands”

			- Think not only how to get it out but what’s next 

		- No one tests your product better than your customer

			- what in case of software houses? They don't have product per se

		- There are bugs and bugs that customer cares about 
		- The GOAL

			- Short Term

				- Provide Value to customer Frequently

			- Long Term

				- Making sure Principle are Followed

### Principle 2

- We accelerate the team, and use models like Lean Thinking and the Theory of Constraints to help identify, prioritize and mitigate bottlenecks from the system.

	- WHAT

		- Our goal is to accelerate team 

			- that doesn't mean "we have to go fast"

				- Instead we are force multiplier

		- its about

			- adaptiblity
			- Reaction
			- ???

				- Brent went on tagnent and never finished his thought.

		- Lean Principles

			- Deliver fast by managing the flow 
			- source: https://www.lean.org/WhatsLean/Principles.cfm

		- Books to read

			- The Goal: A Business Graphic Novel
			- Phonix Project
			- Lean Thinking

	- WHY

		- Don’t forget MT context
		- By focusing the MT Practitioner on identifying their role as acceleration” 

			- this model were chosen because they are proven

		- It’s important cause far to much of The TEST is reverse of this

			- they create the bottleneck instead of resolving them

				- Example: stabilization period just before release
				- It’s easier to "build quality In" instead of trying to test "quality in"
				- Test Complete date 

					- No i don't mean the tool
					- “If you test after test complete you will find bugs and that will cause us to miss the deadline"

	- HOW

		- This mantra is About completion and predictability not about value in order to accelerate you need mechanism to identify what value is and what the next bottleneck

			- Mt don’t want testing to be viewed as bottle neck 

		- Quality is problem solved to humans being
		- Fast feedback loop is critical in context of understanding what is quality 
		- By Balancing fallacy of value with failure to launch

### Principle 3

- We are a force for continuous improvement, helping the team adapt and optimize in order to succeed, rather than providing a safety net to catch failures.

	- WHAT

		- “We are going to favour continuously adapting and improving above safety net presentation model.”

			- Thou shall kill your safety net

				- Traditional testing is treated as safty net

		- It’s wrong that testers feel validated by the fact the developers don’t want to test.

			- If we are going to move quality upstream, we have to retrain developers without the safety net

				- “Too many people think the quality is limited to testing “

		- Code correctnes

			- The tester can coach code correctness, but devs own it. 
			- Developers have to learn from their mistakes. 

				- Continuous improvement is about not being afraid of making mistakes but embracing them as a learning opportunity.

			- Isn’t unit testing a safety net too?

				- Yes it is.  And it should be there.  TESTERS aren't though.

		- Safty net is a problem

			- Example

				-  Brent test harness lead to developers stopped using design patterns and ended doing code reviews. Cause automation would catch mistakes. - it’s terrible cause sloppy architecture can’t scale and is hard to maintain.

			- To remove safety net, you need also ensure minimal risk of getting harm and consequences of damage cannot be severe

		- Continuous improvement

			- getting better all the time

				- Every time, *not* every half year, *not* every two weeks 

					- ALL THE TIME

			- Actionable vs vanity 
			- Kaizen

				- looking for improvement every time everywhere 
				- reducing the waste.
				- Efficiency vs productivity 

	- WHY

		- It’s a critical process change directly related to   Quality 
		- Testers are well suited to drive continuous improvement 

			- Tester has to see the system as a whole because of this they can easily spot place for improvement 
			- Testers are specialists in asking questions 

	- HOW

		- By measuring 

			- Visibility 

		- Unified engineering 

			- Specialists is a bottleneck!

		- Lots of small changes 
		- Frequent retrospective (only 1-3 action)

			- Testers are well suited for driving retros
			- Also starfish  model for long term  retros

		- A small vertical slices of architecture 

			- MVP!

		- Master branch owned by the business they can release it whenever they want

### Principle 4

- We care deeply about the quality culture of our team, and we coach, lead, and nurture the team towards a more mature quality culture.

	- WHAT

		- Quality culture and leadership 
		- Testers need to  stop being passive
		- Quality culture

			- Quality

				- is not Bugs
				- is not code correctnes
				- is user reaction to what you built 

					- What is a higher quality app with no bugs but with few users, or app with lots of bugs but 100k users?

				- is about eliminating friction (enchanting positive, reducing negativities)

			- Alan Defintion

				- The shared mindset that delivering high-quality software to the customer is our top priority and all our practices support this effort

			- Bren Definiton

				- IT is how do we build healthy, actives, not intuition based, useful view of users empathy within the organisation, caring about problems that users have 

			- Getting people closer to understanding the problems that users are facing, how software developers are geared to solve it and how to stay current. 

				- Getting people closer to understanding the problems that users are facing, how software developers are geared to solve it and how to stay current. 
				- “Hey, customer are you happier ?”

			- What it mature Quality culture

				- It is maturity model use with caution 

					- its alan model - it doesn't has to work for you

				- Testing breadth 

					- infancy example

						- functional testing

					- adulthood example

						- contextual testing

				- Quality test ownership ship

					- infancy example

						- Tester are doing all the testing

					- adulthood example

						- Testers are coaches
						- No testeres needed, cause team gets it

				- Bug life cycle 

					- infancy example

						- bug backlog

					- adulthood example

						- zero bug policy

				- how do you use code corretnes tools
				- Data analysis 

					- infancy example

						- oblivous

					- adulthood example

						- data centric

				- Development approach 

					- infancy example

						- ad-hoc

					- adulthood example

						- super small pathes

				- Learn and improvement 

					- infancy example

						- no learning happens

							- retrospectives are for whining

					- adulthood example

						- every failure is oportunity to learn

							- and oportunity is taken

				- Leadership support 

					- infancy example
					- adulthood example

						- good quality pratices are  praised suported and celebrated

					- read book 

						- Book leadership on the line 

		- ADKAR Model

			- source 

				- https://www.prosci.com/adkar

			- Awareness
			- Desire
			- Knowledge
			- Abilty
			- Reinforcment

	- WHY

		- The reason is we want feedback from our customers more often

			- we want to understand and react to what they are doing,

				-  we want to reduce risk in the ability to do that

		- To work in the way we want to function, to keep, retain and engage more users we need the quality culture 
		- to move testing

			- From Risk minimalisation

				- to reacting to knowledge gained. 

	- HOW

		- Unless the whole team has a common understanding of the problem trying to solve it is pointless 
		- Small Batches 
		- Knowledge sharing (software is knowledge works)
		- Try stuff -> fail -> learn 

			- Experiment 
			- Don’t make sweeping changes at once 
			- Small changes, and don’t give up

				- Don’t try to change all at once 

		- Reaping the band-aid works only when people are ready.
		- Brent example on slack TL:DR verion

			- my history: most time as QA, then as dev, now DS.  I went to dev as a manager. Half of my dev were old school we dont test and half were ex Testers.  3 things I did to start: 0 bug backlog allowed , trained everyone on TDD , and lastly, bugs will not be fixed by the code author.

				- After learning/rumbling period was over, the whole team mentioned they would not ever go back to old ways....
				- bugs will NOT be fixed by the code author?

					- is the social pressure...   teammates do not appreciate having to fix a bug in code *you* should have tested....  motivates correct behavior in long term.

						- Even better is to assign bug fixing to the peeps who approved the checkin
						- What about toxicty and hostily

							- combine with retrospective 
							- and a clear non-negotiable expectation that the team works as a team 

					-  great way for knowledge sharing about code.

### Principle 5

- We believe that the customer is the only one capable to judge and evaluate the quality of our product

	- WHAT

		- Definition customer - it is a human who takes a dependency on what you are releasing, and that human can make decisions what quality is 
		- It is not about preventing harm 

			- How do we help business to go faster

	- WHY

		- Customers don’t want software; they want the problem solved.
		- It is seductive to believe “hey I am doing it forever I know what I am doing 
		- There is a risk in trust that QA belife in requirements doc and PMs , are solving a customer problem 

			- which is not often true
			- Features are developed cause we think they are cool, not because It solves problems. 
			- Quite often asking teams

				- Q: “What problem it solves? “

					- lead to answer

						- “They will use it”

							- Q2:“What value does it bring? “ 

								- “They will use it”

		- Need vs want

			- Usually, you need to decompose the want to Find the need
			- B2B

				- Even in B2B case delivering what customer want not what they need, may end with customer leaving and never returning

		- Example of building wrong thing 

			- Microsoft Kin

				- https://en.wikipedia.org/wiki/Microsoft_Kin

	- HOW

		- Ask your self

			- Who is my customer ?

				- What is the case when I am delivering software to business?

					- Who is customer then? Buissness or its customer?

						- Both
						- You need to be able to help your customers help their customers.

				- End users who benefit from software you are producing.
				- Testers are not customers.  

					- Unless you are selling software for testers.

		- Requirements from the business should be treated as hypothesis 
		-  For each feature request you can ask question:

			- “Imagine you had that what would you do with it?”

		- Leaders ship is disappointing people at level they can absorb 

			- ergo

				- Small changes!

### Principle 6

- We use data extensively to deeply understand customer usage and then close the gaps between product hypotheses and business impact.

	- WHAT

		- Validating hypotheses doesn’t mean pushing buggy software.
		- Your reaction time is important. 
		- we need to be able to know

			- What metrics meter 
			- What part of your product 

	- WHY

		- Data is critical to scale 
		- As long as you have good telemetry, you can find and fix bugs 
		- Relaying on telemetry and customer data doesn’t mean it is using the customer as testers 
		- Customer don’t care about test cases run, nor about  a code coverage 

			- They care if theirs problem was solved

	- HOW

		- Instrument the hell out of your software 
		- Use automation as a load generator and let the telemetry be a test oracle.
		- Data tells you where to focus.
		- Check episode 82
		- Once the product ship - look at the data and try to figure out which testing effort was wasted.

			-  Which feature is barely used? 

				- It will help you count What is the ROI of current testing 

		- Who values your product?

### Principle 7

- We expand testing abilities and knowhow across the team; understanding that this may reduce (or eliminate) the need for a dedicated testing specialist. 

	- WHAT

		- Modern Tester doesn’t test

			- It is also transitory role

		- If you follow all principles you may not need testing specialists 
		- No testing isn’t dead

			- but testers are on their way out 

	- WHY

		- Testing is not a unique skill for testers others can do it too
		- Testing is an activity, not a job.

	- HOW

		- There is a risk that Dev manager may not be able to deal with the mixed team - he will need a boiling frog
		- You need people that genuinely understand testing to help with the transition.
		- At the beginning you need experts to teach others how to test.

			- Aka Bootstrapping effort

		- There is social pressure to conform

			-  when you achieve quality culture

				- it will be kept with minimal help, unless some one will actively try to change it

		- If you are a manager start working with your people. and easing them into transition

			-     Give them a new place for their career to go

				- And that new place is a positive one.

## Historical information

### Episode 77

https://www.angryweasel.com/ABTesting/ab-testing-episode-77-the-conception-of-the-modern-testing-principles/

- General

	- Based on agile principles

	  I have taken them from here:
	  https://www.agilealliance.org/agile101/12-principles-behind-the-agile-manifesto/

		- 1.  Our highest priority is to satisfy the customer through early and continuous delivery of valuable software.
		- 2. Welcome changing requirements, even late in development. Agile processes harness change for the customer's competitive advantage.
		- 3. Deliver working software frequently, from a couple of weeks to a couple of months, with a preference to the shorter timescale.
		- 4. Business people and developers must work together daily throughout the project.
		- 5. Build projects around motivated individuals. Give them the environment and support they need, and trust them to get the job done.
		- 6. The most efficient and effective method of conveying information to and within a development team is face-to-face conversation.
		- 7.  Working software is the primary measure of progress.
		- 8. Agile processes promote sustainable development. The sponsors, developers, and users should be able to maintain a constant pace indefinitely.
		- 9. Continuous attention to technical excellence and good design enhances agility.
		- 10. Simplicity--the art of maximizing the amount of work not done--is essential.
		- 11. The best architectures, requirements, and designs emerge from self-organizing teams.
		- 12. At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly.

	- Who is customer for MT Principles?
	- Modern Tester

		- Existed in this version
		- Tester as coach 
		- He is not Champion of quality
		- Responsible for quality culture

	- Principle importance

		- Alan think all are equaly important
		- Brent thinks principle 1 is most important

- Principlaces first version

	- 1. The customer is the only one suitable to judge and evaluate the quality of our software

		- it is combination of Testing Discipline , agile and Budisness as data

	- 2. We apply the theory of constraints to identify, prioritize and mitigate bottlenecks from the system (and accelerate the team).

		- Constant re-evaluate of bottle necks 
		- Testing often is a bottle neck but rarly is a root cause of  one.

	- 3. We are not the safety net for software correctness – we focus on improving the business, and not the code.

		- Testing is not responsible for code correctness

			- Software quality!=code correctness 

	- 4. We are responsible for the quality culture of our team, and are accountable for helping and coaching the team in this regard.
	- 5. We use data to deeply understand customer usage and customer pain.
	- 6. Embrace continuous improvement, and help the team adapt and optimize in order to solve customer pain

		- neither It doesn’t need to be now, nor it doesn’t have to be perfect- balance 

			- its about ballance

	- 7. We strive to reduce or eliminate the need for a dedicated testing specialist on our teams by increasing testing abilities and knowhow across the team.

## How it aplies to polish market?

### See principle #5 - B2B 

## FAQ

### Q: “These principles sound like Agile things. Why are they called out separately in MT principles ?“ 

- A: Agile is more fundamental than MT and addressees generic issues. MT principles are more focused on addressing testing issues

### Q: Most of them sound more like managers' principles than testers

- There is no MT specialist but MT activities are part of unified development, MT practitioner can take PM hat from time to time if needed

	- He is optimizer 
	- Reducing  waste and increasing value
	- Follower of MT notices patterns
	- unified development defintion

		- https://testastic.wordpress.com/2016/01/03/the-combined-engineering-software-model/

## AB Testing episodes to listen

### basics

- 77

	- https://www.angryweasel.com/ABTesting/ab-testing-episode-77-the-conception-of-the-modern-testing-principles/
	- general: who is customer of the principles?

- 78

	- https://www.angryweasel.com/ABTesting/ab-testing-episode-78-digging-in-on-modern-testing-principles/

### Principle 1

- 81

	- https://www.angryweasel.com/ABTesting/ab-testing-episode-81-business-rulz/

### Principle 2

- 83

	- https://www.angryweasel.com/ABTesting/ab-testing-episode-83-accelerating-the-team/

### Principle 3

- 84

	- https://www.angryweasel.com/ABTesting/ab-testing-episode-84-stories-about-changes-and-nets/

### Principle 4

- 85

	- https://www.angryweasel.com/ABTesting/ab-testing-episode-85-the-community-principle/

### Principle 5

- 86

	- https://www.angryweasel.com/ABTesting/ab-testing-episode-86-not-the-customers-champion/

- 92

	- https://www.angryweasel.com/ABTesting/ab-testing-episode-92-customers-bugs-and-triangles/

### Principle 6

- 87

	- https://www.angryweasel.com/ABTesting/ab-testing-episode-87-the-one-about-data/

- 82

	- https://www.angryweasel.com/ABTesting/ab-testing-episode-82-brent-talks-to-alan-about-data/

### principle 7

- 88

	- https://www.angryweasel.com/ABTesting/ab-testing-episode-88-testing-isnt-dead-testers-otoh/

### Modern testing vs Context driven

- 94

	- https://www.angryweasel.com/ABTesting/ab-testing-episode-94-modern-testing-meets-context-driven-testing/

### https://testastic.wordpress.com/2016/09/05/whats-so-special-about-specialists/

### Transition guide

- https://www.angryweasel.com/ABTesting/ab-testing-episode-93-the-quality-culture-transition-guide/

### slack

### traditional vs modern debate

- https://www.angryweasel.com/ABTesting/ab-testing-episode-67/

## PARKING LOT - Place for notes without home

### in martial art black belt is begining up to that point you just learn what you need to start

### Modern testing principles not modern testers principles 

### Specialists is bottleneck

### ...automation especially UI black hole of payroll 

