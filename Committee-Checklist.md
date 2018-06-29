# Committee Checklist

Document for the Committee to ask questions/mitigate the concerns of ethics in PARC projects

## Business development ##

- Does the project require IRB?
  - Any study or focus group working with human subjects should go through IRB review.

## Data ##

- If the project is for a public entity, can you disclose the sources of your data?
- Have you evaluated the provenance and veracity of data and considered alternative data sources?
- Has there been a validity check performed by randomly sampling a portion of your data (e.g., input and/or training data) and manually checking its correctness? This check should be performed early in your development process before derived information is used. Report the overall data error rate on this random sample to stakeholders.
- Can you provide for stakeholders auditing (i.e. probing, understanding, reviewing of system behavior) 
  - or is there sensitive information that would necessitate auditing by a designated 3rd party?
- Did you/will you make sure that if data is needed to properly audit your algorithm, such as in the case of a machine-learning algorithm, that sample (e.g., training) data is made available?
- Is there a plan to communicate the project assumptions, shortcomings, error rates, etc. to stakeholders?

## Societal impact ##

  *AI decisions that could bias or alter societal norms*
- Are there particular groups which may be advantaged or disadvantaged, in the context in which you are deploying, by the algorithm / system you are building?
- Is the potential there of damaging effect of uncertainty / errors to different groups?
- Did you talk to people who are familiar with the subtle social context in which you are deploying? For example, you should consider whether the following aspects of people’s identities will have impacts on their equitable access to and results from your system: Race, Sex, Gender identity, Ability status, Socio-economic status, Education level, Religion, Country of origin.
- When using human data, do the benefits outweigh the risks to those involved?
- Has there been a calculation of the error rates and types (e.g., false positives vs. false negatives) for different sub-populations and assess the potential differential impacts?


  *Where AI is being used to make a decision about a population*
- Are the decisions produced by an algorithmic system explainable to the people affected by those decisions? These explanations must be accessible and understandable to the target audience; purely technical descriptions are not appropriate for the general public. (8th grade reading level is appropriate)
  - Is there an explanation of whom to contact for answers to questions about the research?

## Environmental impact##

- Consider the energy impact of the computational resources necessary for the project. Is there a way to minimize that impact? Can the calculations be handled in a different way?
- Do resources provisioned for the project match the requirements or are they too excessive?

## Misuse ##

- Is there a description of the ideal outcome of your design, including how this outcome looks across technological, cultural, social, institutional and organizational spheres.
  - Draw a timeline for 5-10 years in the future. Place your ideal outcome at the end of the timeline, and chart out potential obstacle and consequences leading up to it.
  - Repeat until you have three possible timelines.
  - Did any of these timelines account for possible negative consequences?
- Are there guardrails in place to prevent malicious usage (the intentional misuse of the design)?
- Has the system been adequately secured to prevent unwarranted manipulation?

## Miscellaneous ##

- Who will have the power to decide on necessary changes to the algorithmic system during design stage, pre-launch, and post-launch?

## Last question ##

- Have any of your answers to the questions above changed?
- Has the data you are using changed?

If yes, seek new approval.

## Post deployment:##

- Is there a process developed by which people can correct errors in input data, training data, or in output decisions?
- Did you determine how to communicate the uncertainty / margin of error for each decision?
- What will the reporting process and process for recourse be?
- Is there a plan for what to do if the project has unintended consequences? This may be part of a maintenance plan and should involve post-launch monitoring plans.
- Is there a sunset plan developed for the system to manage algorithm or data risks after the product is no longer in active development?

## Possible points of discussion ##

- Do you trust the client you’re working with?
- Is the machine learning team pursuing diversity, equity and, other means of inclusion within machine learning development teams? (is the team working on the project diverse?) This will help to identify and prevent inadvertent discrimination.

*Sources:* 
- [Principles for Accountable Algorithms and a Social Impact Statement for Algorithms](https://www.fatml.org/resources/principles-for-accountable-algorithms#social-impact)
- [How to Hold Algorithms Accountable](https://www.technologyreview.com/s/602933/how-to-hold-algorithms-accountable/)

------

- AI that uses data from individuals
- AI that interacts with or affects humans

*I suspect there are non-human impacts of AI that reach in to environmental impact (oil drilling, fracking, animal migrations) that could require study, think AI that impacts gov policy.  Though I want to be careful about expanding scope, I do believe it should be examined.*

- data
- environmental impact
- societal
  - where AI is being used to make a decision about a population
  - AI decisions that could bias or alter societal norms
- (mis)usage
  - consider possible negative consequences
  - consider possible malicious uses (purposely using it incorrectly) intentional misuse
- 

One area where the goals of this committee differ from an IRB is research (to a degree) has a finite time period. Though there are protocols in the IRB for what circumstances require re-review, we may want to develop our own standards and protocols for transfer of license, maintenance, follow up, etc. 

1. What research/projects need to be reviewed?
  - For IRB it’s defined by “research” with “human subjects”
  - How is it defined for AI Ethics?
    - AI that uses data from individuals
    - AI that interacts with humans
2. What research/projects are eligible for exemption?
3. What research/projects are eligible for expedited review (low risk)?
4. What are the penalties to not adhering to the Committees feedback?
  - penalties vs. incentives
  - is there an aspirational ranking system for AI Ethics?




