*Quantity Always Trumps Quality*

This blog post offers a piece of advice: practice, practice, practice. It posits that the act of *writing* code will always increase your skill in it, and that you won't improve if you don't practice. 

*Clean Code: A Handbook of Agile Software Crafstmanship*

> There are two parts to learning craftsmanship: knowledge and work. You must gain
the knowledge of principles, patterns, practices, and heuristics that a craftsman knows, and
you must also grind that knowledge into your fingers, eyes, and gut by working hard and
practicing.

I was more or less on the author's side until this section: "We are deeply complicit in the planning of the project and share a great deal of the responsibility for any failures; especially if those failures have to do with bad code!"

I resent the individualist narrative that engineers should feel bad for choices they make in how to interact with their company's codebase, and I doubly resent the implicit judgment in this section. What the author seems to be proposing is that each individual should step up, work harder, and resist the pressure of culture. It is also completely ignorant to some of the things I've seen in these spaces: bosses who truly do care about the short-sighted quantity over quality dilemma, quotas or deadlines that encourage you to speed up and move on to the next ticket, or even the simple fact that you're working for a *company's existing codebase* and often not on a project that you have any passion for. 

But sure, if it strokes your ego, judge your peers for their spaghetti code and snuggle up to your managers instead. 

To be clear, I also do have a lot of care for clean code, and I think this chapter makes some compelling arguments about how much time and effort it takes to be able to develop this sense. It involves a lot of understanding, a lot of experience, and a lot of practice, and I have a lot of respect for that. 

*Red, Green, Refactor* 

> Red — think about what you want to develop

> Green — think about how to make your tests pass

> Refactor — think about how to improve your existing implementation

This article outlined the general philosophy behind test-driven development, and outlined a three-step process for writing and improving tests. 

I found the quoted text describing each step (above) to be particularly helpful, and feel that I need to practice approaching my code in a more incremental and thoughtful way, asking more whats and whys. I hope to develop more of an innate sense of these things through practice in methodically planning projects. 

*The Cycles of TDD*

> You must write a failing test before you write any production code.

> You must not write more of a test than is sufficient to fail, or fail to compile.

> You must not write more production code than is sufficient to make the currently failing test pass.

Focusing first on correct behavior, then on correct structure is an excellent way to describe the philosophy behind test-driven development, and this blog has been the most effective resrouce yet for convincing me why it's useful to appproach development in this manner. 

I don't have quite as strong a resonance with the next idea, that programmers make specific cases work by writing code that makes the general case work, but hope to soon develop it. 
