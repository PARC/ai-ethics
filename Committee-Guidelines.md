# Committee Guidelines

![]({{ site.url }}/ai-ethics/assets/images/world_AI_ethics.jpg)

This document helps the AI Ethics Committee ask questions to mitigate ethical
concerns in PARC projects. Before starting the review of a PARC project,
consider whether or not any of the committee members have a conflict of
interest related to the project. If so, can these be mitigated or should the
members recuse themselves?

If the scope of a project, or the data it uses, changes in any significant way, projects should be submitted for review again.

## Business development

In addition to developing technology, PARC often provides expertise to
clients. Many clients are not aware of the issues in safeguarding their
customers' information or protecting their interests. Furthermore, there may be
legal requirements when conducting studies or focus groups with human subjects
or handling special types of data like that produced in a healthcare setting.

- Does the project require an IRB review? Any study or focus group working with
  human subjects should go through the IRB review.
- Is there a plan to provide transparency to all stakeholders when the project
  or data will be handed off to other parties (e.g., transitive consent through
  third-parties)?
- Do clients need advice related to transparency and accountability?
- Have steps been taken to anonymize and remove any data that is not necessary for the analysis? If possible, the client should remove and anonymize sensitive information before delivering the data to PARC.

## Data

Respect for people as individuals is essential. Data collection of personal
information and behavior may include less than fully informed consent from the
subjects. Think about how the analysis might affect each subject involved. If
the data represents any vulnerable individuals (elderly, e.g.) or individuals
with diminished autonomy (children, e.g.) special consideration should be given
to their protection. People should have their individuality and autonomy
respected, and steps should be taken to protect them from harm.

- Has the PI taken appropriate data protection steps considering the sensitivity of the data and does it conform to rules required by its data classification (PII, HIPAA, ITAR, etc.)?
- If the project is for a public entity, can you disclose the sources of your data?
- Has the provenance and veracity of the data been evaluated and have alternative data sources been considered?
- Has there been a validity check performed by randomly sampling a portion of the data (e.g., input or training data)
and manually checking its correctness? This check should be completed early in the development process before the 
algorithms are developed or analyses are done. Does the overall data error rate on this random sample need to be reported to stakeholders. 
Data and algorithms should be vetted for explicit and implicit biases and prejudices against specific populations. Consider whether there is the potential of withholding
resources or information from populations that could benefit from the design or interaction.
   - In instances where there is a risk of discrimination, include technical specification with details of the machine learning application
and its functions, including samples of the training data used and details of the source of data.
   - If identified, is there a process to take effective action to mitigate discrimination? If not, is it documented?
- For projects that have a significant risk of causing human rights abuse, is it possible to submit them for independent third-party audits?
- Can the ability to audit (i.e., probing, understanding, reviewing of system behavior) be provided to stakeholders or is there sensitive information that would necessitate auditing by a designated 3rd party?
- If data is needed to properly audit the algorithm, such as in the case of a machine-learning algorithm, can the sample data (e.g., training) be made available?
- Is there a plan to communicate the decisions about trade-offs project assumptions, shortcomings, error rates, etc. to stakeholders? 
Researchers/engineers are making design decisions that aren't captured in real time; this disallows transparency overall.
- Is there a process developed by which people can correct errors in input data, training data, or in output decisions?
- If appropriate, is there a way for data to be removed when necessary (e.g., the right to be forgotten as practiced in the EU and Argentina)?

## Social impact

AI is increasingly becoming a more prominent part of many aspects of our lives, including decision-making processes that could alter the course of it. Succesful technologies aim to not make the possible social impact an afterthought or taxation on a project but actively think how to prevent harm while the system is being developed. 

### AI decisions that could bias or alter societal norms

- Are there particular groups which may be advantaged or disadvantaged, in the context in which you are deploying, 
or by the algorithm/system you are building?
   - Are there particular groups which may be excluded from the advantages of the algorithm/system you are building? Can the system be changed to include these groups?
   - Think about what services, products and industries, and perhaps jobs might be replaced by the deployment of the algorithm/system. How will this impact society?
- Is there potential for damaging effects of uncertainty/errors on different groups?
- Should the team talk to people who are familiar with the subtle social context in which they are deploying the system? 
For example, consider whether the following aspects of people's identities will have impacts on their equitable access to and 
results from the system: race, sex, gender identity, ability status, socio-economic status, education level, religion, country of origin.
- When using human data, do the benefits outweigh the risks to those involved?
- Will there be a calculation of the error rates and types (e.g., false positives vs. false negatives) for different sub-populations and also an assessment of the potential differential impacts?
   - What are the effects of false positives or false negatives on the subjects who are misclassified?
- Consider the benefits of a project and the potential harm to those affected by it. 
For example, Michal Kosinski and Yilun Wang at Stanford created a vision application that predicts sexual preference by analyzing 
images of faces. There are almost no benefits from the technology, but great potential costs when it comes to impartiality and 
fairness. As [The Economist](https://www.economist.com/science-and-technology/2017/09/09/advances-in-ai-are-used-to-spot-signs-of-sexuality) 
put it, "In parts of the world where being gay is socially unacceptable, or illegal, such an algorithm could pose a serious threat to safety."

### Where AI is being used to make a decision about a population

- Are the decisions produced by an algorithmic system explainable to the people affected by those decisions? 
These explanations must be accessible and understandable to the target audience; purely technical descriptions are not 
appropriate for the general public. (8th-grade reading level is appropriate)
- Do stakeholders know who to contact with questions about the research?

## Environmental impact

Where AI has been doing exceptional things for the environment, from [wildlife protection](https://news.nationalgeographic.com/2016/06/paws-artificial-intelligence-fights-poaching-ranger-patrols-wildlife-conservation/) to [advancing agriculture](https://www.ibm.com/blogs/client-voices/feed-future-generations-cognitive-precision-farming/) to feed the world's growing population, resource conservation while deploying the system itself might be an overseen segment of the design. 

- Consider the energy impact of the computational resources necessary for the project. Is there a way to minimize that impact? Can the computation be handled differently to use less energy?
- Do resources provisioned for the project match the requirements or are they too excessive?
- Does the algorithm/system/design encourage unsustainable behavior?

## Physical interaction

Much of the concern related to AI has to do with respecting individuals'
privacy and rights. Risk of physical injury may also be a concern with certain
projects. Broadly speaking users should be aware of possible risks and
developers should think through potential unintended consequences of
interacting with the technology.

- Is there the equivalent of informed consent for the usage?
- Will individuals interacting with the technology understand the capabilities
  and limits of it?
- Does the design minimize potential risk? 
- Do the warning signals match the severity of the danger?

## Misuse and malicious intent

One of the most often overlooked concern is how a technology might be misused.
Misuse can happen either by mistake, overconfidence in the technology, or by
bad actors trying to subvert it. In all cases care should be taken to mitigate
potential harm and provide appropriate restrictions to limit misuse.

- Is there a description of the ideal outcome of the design, including how this
  outcome looks across technological, cultural, social, institutional and
  organizational spheres.
    - Useful exercise: Draw a timeline for 5-10 years in the future. Place your
      ideal outcome at the end of the timeline, and chart out potential obstacle
      and consequences leading up to it. Repeat until you have three possible
      timelines. Did any of these timelines account for possible negative
      consequences?
- Are there guardrails in place to prevent malicious usage (the intentional
  misuse of the design)?
- Has the system been adequately secured to prevent unwarranted manipulation?
- If physical devices are used, are they adequately secured from hacking or
  subversion? 
    - For example, baby monitors were hijacked to launch [botnet attacks](https://gitlab-internal.parc.com/ai-ethics/ai-ethics-committee.git).

## Miscellaneous

- Who will have the power to decide on necessary changes to the algorithmic system during design stage, pre-launch, and post-launch?

## Post deployment

The responsibility of a design or system doesn't always end at the handoff. Although every effort should be made to prevent unexpected outcomes considering a sunset plan before delivering the project to the client can prevent confusion about how to solve unforeseen consequences.

- Changing functionality of AI systems: the integration of software, including AI, into products can modify the functioning of such products and systems during their lifecycle. This is particularly true for systems that require frequent software updates or which rely on machine learning. These features can give rise to new risks that were not present when the system was placed on the market. These risks are not adequately addressed in the existing legislation which predominantly focuses on safety risks present at the time of placing on the market. (Taken from EU Whitepaper on AI, Feburary 2020)

- Is there a plan to take action to ensure individuals and groups have access to meaningful remedy and redress. This may include, for example, creating clear, independent, and visible processes for redress following adverse individual or societal effects.
- What will the reporting process and process for recourse be?
- Is there a plan for what to do if the project has unintended consequences? This may be part of a maintenance plan and should involve post-launch monitoring plans.
   - Establish mechanisms to ensure that where discrimination has occurred as a result of a decision-making algorithm, relevant parties, including affected individuals, are informed of the harms and how they can challenge a decision or outcome.
- Is there a sunset plan developed for the system to manage algorithm or data risks after the product is no longer in active development?
- Did the team determine how to communicate the uncertainty/margin of error for each decision?

## Possible points of discussion

- Do you trust the client you're working with?
- Is the the group pursuing diversity, equity and, other means of inclusion within the teams (i.e.,is the team working on the project diverse)? This will help to identify and prevent inadvertent discrimination.
- Useful exercise: Imagine yourself subject to all possible outcomes of a system, are they all equally fair and just from that point-of-view? (e.g., John Rawls theory of justice)

## Sources

- [Principles for Accountable Algorithms and a Social Impact Statement for Algorithms](https://www.fatml.org/resources/principles-for-accountable-algorithms#social-impact)
- [How to Hold Algorithms Accountable](https://www.technologyreview.com/s/602933/how-to-hold-algorithms-accountable/)
