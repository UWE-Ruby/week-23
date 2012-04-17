## Refinement

After adding features it is useful to find the time to take some time to
evaluate your implementation. Within your implementation this week the focus is
on increasing the __quality__ of the code that you have produced.

### Exercise

The objective of the exercise is to accomplish the following:

#### Choose your problem

You and a partner have likely generated a solution. Outside of class you have
also likely developed two independent solutions. Select one of the solutions
that both of you created.

#### Perform a Code Review

The chosen solution will now be reviewed by the group. 

The original author will act in the role of the presenter or facilitator.

The other individuals within the group will act as the reviewers.

##### Facilitator

The other individuals are aware of the overall goal of the system. What they are
likely not aware of is the the implementation. Take a moment to think about your
implementation:

* Important conceptual concepts
* Application flow
* Source code layout
* Unfinished areas
* Strengths
* Areas needing improvement
* Weaknesses

Ensure during the presentation of the code you stop to answer questions.
Comments, questions, and suggestions made about the code should be captured. It
is often quickest to simply add comments within the code around the section of
discussion.

    Often times you know the strengths and weakness of your code the best and
    might actually be the strongest reviewer of it. When you do review it do
    not hesitate to write down your own comments for later self.

##### Reviewers

As a reviewer you want to gain an understanding of this system. To help guide
your questions it may be helpful to select a role (e.g. future maintainer, 
consumer) to help you guide your questions. Your first goal is to ask questions
about the code to help you gain an understanding of the implementation. Your
second goal is to ask questions and make statements to help improve the code.

    When you discover what you believe is a deficiency or discrepancy it is
    important for you to tactifully bring that to the authors attention. 
    Providing assistance tactfully is difficult. One way of providing feedback
    is to ask more *questions* that lead you to find the deficiency initially.

### Exercise Retrospective

As this is in itself a retrospective on the code that you have already written
it might feel unnecessary but I encourage you to contemplate these questions.

* Was it difficult conveying your implementation to other individuals?

* What questions or suggestions did they ask that you had not initial thought
  about while developing the code or preparing to present it?
  
* Was it uncomfortable to have other individuals look at your code and give you
  feedback?
  
* Was it difficult to give someone feedback on their code? What was difficult
  in providing the feedback?

* Was there a point where you did not understand the implementation? What did
  you do at that point?

* How did you feel about your code before it was reviewed?

* How did you feel about your code after it was reviewed?


### Reading

* [Ruby Metaprogramming](http://pragprog.com/book/ppmetr/metaprogramming-ruby)

    > Chapter 2 - Tuesday: Methods

### Further Exercise

Within the short time allotted to the exercise it was likely that you were
able to receive feedback on your implementation but not able to make the changes suggested. This exercise time is dedicated to implementing those suggestions

I encourage you to also perform the following

* Write tests or improve test coverage

* Improve documentation

#### From the previous exercise

You may have implemented none, one, or some of the additional suggestions from
last weeks exercise. I encourage you to continue pursuing an implementation: 

* Choose an additional configuration input source

* Change one of your additional configuration sources slightly, requiring you
  to change how you parse the input.
  
* Provide the ability to support but the origin configuration source and this
  new modified configuration source (this may be a configuration difference).
  
* Copy a configuration feature from __Cucumber__ or __RSpec__