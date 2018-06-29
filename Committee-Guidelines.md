# Committee Guidelines

Document for the Committee to ask questions/mitigate the concerns of ethics in PARC projects

Before starting a review consider whether or not any committee members have a
conflict of interest related to the project. Can they be mitigated or should
the members recuse themselves.

If the scope of a project or the data changes in any significant way, projects
should be sumbitted for review again.

## Business development ##

- Does the project require IRB?
  - Any study or focus group working with human subjects should go through IRB review.
- Is there a plan to provide transparency to all stakeholders when project or
  data is being handed off to other parties. (e.g transitive consent through
  third-parties)
- Do clients need advice related to transparency and accountability?
 

## Data ##

Respect for people as individuals is important. Data analysis projects related
to customers or actions of individuals may not include fully informed consent
from those people. Think about how the analysis might affect each person in the
analysis. If the data represents any vulnerable individuals (elderly, e.g.) or
individuals with diminished autonomy (children, e.g.) special consideration
should be given to their protection. People should have their decision
respected and all steps should be taken to protect them from harm.

Data privacy is also important. Has the PI taken appropriate data protection
steps considering the sensitivity of the data and does it conform to rules
required by its data classification (PII, HIPAA, ITAR, etc.)? Have steps been
taken to anonymize and remove any data that is not necessary to the analysis?
If possible the customer should do removal and anonomyzation before delivering
the data to PARC.

- If the project is for a public entity, can you disclose the sources of your data?
- Have you evaluated the provenance and veracity of data and considered alternative data sources?
- Has there been a validity check performed by randomly sampling a portion of
  your data (e.g., input and/or training data) and manually checking its
  correctness? This check should be performed early in your development process
  before derived information is used. Report the overall data error rate on this
  random sample to stakeholders. Data and algorithms should be vetted for
  explicit and implicit biases and prejudices against certain populations and for
  the potential of withholding resources or information from populations that
  could benefit from the design or interaction. 
   - If identified, is there a process to take effective action to mitigate
     discrimination? If not, is it documented?
- For projects that have a significant risk of causing human rights
  abuses, is it possible to submit them for independent third party audits.
- Can you provide for stakeholders auditing (i.e. probing, understanding, reviewing of system behavior) 
  - or is there sensitive information that would necessitate auditing by a designated 3rd party?
- Did you/will you make sure that if data is needed to properly audit your
  algorithm, such as in the case of a machine-learning algorithm, that sample
  (e.g., training) data is made available?
- Is there a plan to communicate the decisions about trade-offs project
  assumptions, shortcomings, error rates, etc. to stakeholders? Researchers/engineers are making design decisions that aren’t captured in real time, this disallows transparency overall
- Is there a process developed by which people can correct errors in input data, training data, or in output decisions?
- If appropriate, is there a way for data to be removed when necessary (e.g.
  European right to be forgotten)?

## Social impact ##

  *AI decisions that could bias or alter societal norms*
- Are there particular groups which may be advantaged or disadvantaged, in the
  context in which you are deploying, by the algorithm / system you are building?
- Is the potential there of damaging effect of uncertainty / errors to different groups?
- Did you talk to people who are familiar with the subtle social context in which you are deploying? For example, you should consider whether the following aspects of people’s identities will have impacts on their equitable access to and results from your system: Race, Sex, Gender identity, Ability status, Socio-economic status, Education level, Religion, Country of origin.
- When using human data, do the benefits outweigh the risks to those involved?
- Has there been a calculation of the error rates and types (e.g., false
  positives vs. false negatives) for different sub-populations and assess the
  potential differential impacts?
  - What are the effects of false positives or false negatives on the people
    who are misclassified?
- If physical devices are used, are they adequately secured from hacking or
  subversion. For example, baby monitors were hijacked to launch [botnet
attacks](https://gitlab-internal.parc.com/ai-ethics/ai-ethics-committee.git)
- Consider the benefits of a project and the benefits or harms to those
  affected by it. For example Michal Kosinski and Yilun Wang at Stanford
  created a vision application that predicts sexual preference by analyzing
  images of faces.
  (https://www.economist.com/science-and-technology/2017/09/09/advances-in-ai-are-used-to-spot-signs-of-sexuality.)
  There are almost no benefits from the technology but great potential costs when
  it comes to impartiality and fairness. As The Economist put it, “in parts of
  the world where being gay is socially unacceptable, or illegal, such an
  algorithm could pose a serious threat to safety.”


  *Where AI is being used to make a decision about a population*
- Are the decisions produced by an algorithmic system explainable to the people affected by those decisions? These explanations must be accessible and understandable to the target audience; purely technical descriptions are not appropriate for the general public. (8th grade reading level is appropriate)
  - Is there an explanation of whom to contact for answers to questions about the research?

## Environmental impact##

- Consider the energy impact of the computational resources necessary for the project. Is there a way to minimize that impact? Can the calculations be handled in a different way?
- Do resources provisioned for the project match the requirements or are they too excessive?

## Physical interaction ##

If the project is working with technology that interactions with people,
respect for individual autonomy must be considered.

- Is there the equivalent of informed consent for the usage?
  - Will individuals interacting with the technology understand the capabilities and limits of it?

## Misuse ##

- Is there a description of the ideal outcome of your design, including how this outcome looks across technological, cultural, social, institutional and organizational spheres.
  - Draw a timeline for 5-10 years in the future. Place your ideal outcome at the end of the timeline, and chart out potential obstacle and consequences leading up to it.
  - Repeat until you have three possible timelines.
  - Did any of these timelines account for possible negative consequences?
- Are there guardrails in place to prevent malicious usage (the intentional misuse of the design)?
- Has the system been adequately secured to prevent unwarranted manipulation?

## Miscellaneous ##

- Who will have the power to decide on necessary changes to the algorithmic system during design stage, pre-launch, and post-launch?

## Post deployment:##

- Is there a plan to take action to ensure individuals and groups have access
  to meaningful remedy and redress. This may include, for example, creating
  clear, independent, and visible processes for redress following adverse
  individual or societal effects
- Is there a plan for what to do if the project has unintended consequences? This may be part of a maintenance plan and should involve post-launch monitoring plans.
- Is there a sunset plan developed for the system to manage algorithm or data risks after the product is no longer in active development?
- Did you determine how to communicate the uncertainty / margin of error for each decision?
- What will the reporting process and process for recourse be?
- In instances where there is a risk of discrimination, include technical
  specification with details of the machine learning application and its
  functions, including samples of the training data used and details of the
  source of data.
- Establish mechanisms to ensure that where discrimination has occurred as a
  result of a decision-making algorithm, relevant parties, including affected
  individuals, are informed of the harms and how they can challenge a decision or
  outcome.

## Possible points of discussion ##

- Do you trust the client you’re working with?
- Is the machine learning team pursuing diversity, equity and, other means of inclusion within machine learning development teams? (is the team working on the project diverse?) This will help to identify and prevent inadvertent discrimination.
- Imagine yourself as subject to all possible outcomes of a system, are they
  all equally fair and just from that point-of-view? "If you can't decide what
  side you will end up on, any side should be good." (e.g. John Rawls theory of
  justice)

*Sources:* 
- [Principles for Accountable Algorithms and a Social Impact Statement for Algorithms](https://www.fatml.org/resources/principles-for-accountable-algorithms#social-impact)
- [How to Hold Algorithms Accountable](https://www.technologyreview.com/s/602933/how-to-hold-algorithms-accountable/)

