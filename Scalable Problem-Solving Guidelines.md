(Work in Progress - please suggest comments, edits, or additions via PR)

# Scalable Problem-Solving Guidelines

This document is intended to record and share methods for solving problems of various scales, by collecting knowledge generated across the various research projects of Protocol Labs.  We believe that important research is often performed with intention, which is not unlike plotting a course past the frontier to an unknown destination.  Let's build a trailblazer's handbook!

This document should have tips for finding destinations worth journeying to, as well as techniques for identifying and navigating obstacles, both major and minor, as you establish a route to your destination.

So far, this document looks like
 - a note on thinking creatively
 - a note on teamwork and collaboration
 - methods for deciding features of your destination (identifying)
 - methods for describing the vision of your destination (localizing)
 - methods for finding way-points that must be reached (outlining)
 - methods for establishing the path to the destination

### A preliminary note on a creative mindset
[I can't currently find a good resource to describe the playful openness of the creative mindset, but it's something to be able to ignore irrelevant details to contemplate the most important aspects of problems without being overly cynical of ideas that can't work.]

This mindset can be practiced with the typical "yes, and..." theater game, where one builds upon the ideas of others, rather than backtracking.  (Other relevant games to practice this mindset of accepting and building off an incredible premise are under development...)  [1]

### A preliminary note on collaboration
The various steps of this process seem to require substantially different skill sets, and it should be expected that individuals may enjoy or excel at different stages in this process.  A project leader should leverage the skills of coworkers, and individual researchers should use the identification/separation of skill-sets to practice and hone skills across the lifespan of projects.



## Technological Aspirations - Deciding on the features of your destination
Since necessity is the mother of invention, this is the phase in which you come up with absurd and infeasible predictions about what problems shouldn't exist in the future and/or the solutions that should exist.  It's important to maintain a creative mindset at this stage.  Unless it inherently requires violating a law of physics, I take the view that no idea is too crazy.  At this point, you're searching for a destination worth going to, you're not thinking about the directions you can start in, much less attempting to generate complete paths to be taken.



## Defining Goals - Describing the vision of your destination
We've implemented one exercise that successfully brought together a number of stakeholders who had different expectations and desires from the project.  This exercise entailed all members of the group listing any and all use cases that the completed project should be able to satisfy.  These were all actions that should be possible when using this future system.  Once these topics were loosely grouped (into four categories in our case), we studied them.  From them, we then developed system requirements: features in the construction or design that must or almost certainly must be true for the system to satisfy the use cases. [2]  After this step, we sorted the use cases into the same general categories, and then ranked them numerically in two ways.  We first ranked by the requirement's importance in our attempt to reach the goal (from "nice to have x" to "it's a failure if it doesn't x") as well as the difficulty to satisfy the requirement ex post facto (from "it's easy to add x" to "adding x to an existing system would likely require a complete overhaul").

Another useful exercise is to describe the goals of the project using the [Heilmeier Catechism](https://www.darpa.mil/work-with-us/heilmeier-catechism).  These questions should be answered iteratively, as answering each subsequent question will likely provide insight into the goals of the project that may change or improve your answers to previous questions.  Having not done so, I suggest rather than recommend following the Heilmeier Catechism as soon as possible to refocus the team on the objectives, though for a group with widely divergent goals, even answering the questions midway through the sticky exercise might be too early.



## Finding Way-points - Plotting your course around the biggest obstacles
At this point it should be possible to select the most integral design requirements, ranked highly both in that they would be difficult to add later and they're important to the success of the project.  One could find clusters of these requirements such that the engineering required to satisfy the requirements will affect the other requirements.  I will use the phrase "requirement dependency cluster" to describe a set of requirements where it's easy to satisfy any strict subset of the requirements, but difficult to satisfy all of the constraints.  One could imagine then finding cycles or subgraphs with the highest weight per node.  It's highly likely that the problem itself could be written up as an open problem, and effectively satisfying the constraints simultaneously requires an innovative result that should be written up as as an academic publication and submitted to conferences.

At this point one approach could be to trying to find specific candidate solutions from the literature and extending those solutions to fit together in an attempt to solve other problems.  Alternatively, maintaining and updating a shrinking list of requirement dependency clusters while not eliminating any possibilities can also be a good mentality.  It's important to find balance between finding a solution quickly and finding the best possible solution.

## Building a Path - Connecting the dots

At this stage, the research process is likely complete in various areas.  Parts of the path that you've trailblazed should be ready for paving - write up your results and start working on development.  At a later date, there will be at least a document on how to write academic papers as painlessly and efficiently as possible.  If you're a dedicated researcher or the project is large enough to require onboarding of developers, there also should be a document on efficiently transitioning the project from research to development at some point in the near future.


-----
### Footnotes

[1] One interesting avenue of invention that I would consider is invention through misinterpretation.  Numerous times I've witnessed one person claim to have a simple, almost trivial solution to a hard problem, and upon beginning to describe the idea to a second individual, the explainer realizes flaws while the explainee develops a workable solution inspired by the explainer's preliminary solution.

[2] I highly recommend the use of ~3" x 3" sticky notes for this exercise
