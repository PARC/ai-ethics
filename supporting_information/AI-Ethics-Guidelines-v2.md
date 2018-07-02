# AI Ethics Guidelines v2

## A document for the committee on how to review projects and what topics to review.

Format:

# Topic
## definition

Strategies to mitigate

# Respect for persons

Respect for persons incorporates at least two ethical convictions: 

- first, that individuals should be treated as autonomous agents, and 
- second, that persons with diminished autonomy are entitled to protection. 
- The principle of respect for persons thus divides into two separate moral requirements: the requirement to acknowledge the autonomy and the requirement to protect those with diminished autonomy 

S*ource:* ***The National Commission 1979; The Belmont Report*


  **a. Autonomy**
  - Autonomy means that people must be empowered to make decisions concerning their own actions and well-being.
  - [source: The Belmont Report]

****
  **b. Voluntariness**
  - Voluntariness means more than offering people the choice to participate in or withdraw from research (sharing their data, interaction with an AI system, participation in a service platform, etc) . Researchers should be aware of situations in which prospective (consumers) may feel pressured to participate in a study.
  - [source: The Belmont Report]
****
****
  **c. Informed Consent**
  - A prospective (consumer’s) autonomy is honored through the process of informed consent. The Office for Human Research Protections (OHRP 2014) offers these guidelines:
    - (1) disclosing to potential (consumers) information needed to make an informed decision; 
    - (2) facilitating the understanding of what has been disclosed; and 
    - (3) promoting the voluntariness of the decision about whether or not to (engage with the product or research)
  - (Researchers/Product Designers/PARC) must provide certain essential points of information, such as 
    - the purpose of the (research/product), 
    - a description of what the subject will be asked to do, 
    - any foreseeable risks of harm, and 
    - that the study is voluntary and subjects are free to withdraw at any time.
  - Informed consent also must be ***comprehensible*** to prospective subjects.
    - What are people’s expectations compared to how their information is actually used?
  - [source: The Belmont Report]


(Included is the perspective of devices that act with people, add perspective of data analysis piece where a person is a row of data in a database)

**Measurements/Metrics:**
(Use case studies to recommend strategies for the committee to recommend to researchers)

**Case Studies:**


# Beneficence
- Persons are treated in an ethical manner not only by respecting their decisions and protecting them from harm, but also by making efforts to secure their well-being. 
  - The term 'beneficence' is often understood to cover acts of kindness or charity that go beyond strict obligation. In this document, beneficence is understood in a stronger sense, as an obligation. 
  - Two general rules have been formulated as complementary expression of beneficent actions in this sense: 
    - (1) do not harm and 
    - (2) maximize possible benefits and minimize possible harms 
      - Improving Behavioral and Health Outcomes
- [source:The National Commission 1979; The Belmont Report]
- Benefits of a project. For example Michal Kosinski and Yilun Wang at Stanford created a vision application that predicts sexual preference by analyzing images of faces. https://www.economist.com/science-and-technology/2017/09/09/advances-in-ai-are-used-to-spot-signs-of-sexuality. There are almost no benefits from the technology but great potential costs when it comes to impartiality and fairness. As *The Economist* put it, “in parts of the world where being gay is socially unacceptable, or illegal, such an algorithm could pose a serious threat to safety.”

How to make product mutually beneficial? For both the company and the users.
Example/Case Study: 

- Facebook’s method of capturing and using user data
- Baby monitoring devices hacked by bot nets (kyle), companies had no incentive to spend resources on making their product more secure

Negligence - here or under each category?  = lack of compliance. Defined with your own past behavior or the people that you work with. With norms. 

# Justice

Who ought to receive the benefits of research and bear its burdens? This is a question of justice, in the sense of "fairness in distribution" or "what is deserved." An injustice occurs when some benefit to which a person is entitled is denied without good reason or when some burden is imposed unduly (The National Commission 1979).

“The right to justice is a vital element of international human rights law.
Under international law, victims of human rights violations or abuses must have access to prompt and effective remedies, and those responsible for the violations must be held to account.

- take action to ensure individuals and groups have access to meaningful remedy and redress. This may include, for example, creating clear, independent, and visible processes for redress following adverse individual or societal effects
- Ensure that if machine learning is to be used in the public sector, such use is carried out in line with standards of due process.
- Put in place effective penalties and sanctions for public or private bodies responsible for discriminatory outcomes through the use of machine learning systems where they have failed to take appropriate action to prevent or mitigate such impacts.”

*Source: Toronto declaration* 

**Measurements/Metrics:**

- we should always allow for the capability to remove data

**Example/Case Study:** 

- Facebook collects data on people that are not facebook members
- European right to be forgotten


# Accountability

enforcing oversight?

## “Accountability implies an obligation to report and justify algorithmic decision-making, and to mitigate any negative social impacts or potential harms. We’ll consider accountability through the lens of five core principles: responsibility, explainability, accuracy, auditability, and fairness”.

*Source:* [*How to hold algorithms accountable*](https://www.technologyreview.com/s/602933/how-to-hold-algorithms-accountable/)

Gaurang: more guidance to more transparency and counsel to our clients. loops back to justice notes. It also holds ourself accountable, trying to set intentions, then we hold ourself accountable to this document.

CG: helping people navigate through the regulations (ITAR, HIPAA etc) that are already in place.

**Measurements/Metrics:**

- Under different jurisdictions there are rules around specific areas (ex. ITAR, HIPPA)
  - One piece of consulting service of AI Ethics Committee is to parse current laws/rules and make recommendations based
- Look to Europe’s laws, GDPR


# Trust

Cristina: Authenticity 
Gaurang: isn’t this implicit - as in, if you have accountability, justice, beneficence, those things create trust implicitly/explicitly?


# Impartiality
## The AI design should be vetted for explicit and implicit biases, prejudices against certain populations and for the potential of withholding resources or information from populations that could benefit from the design or interaction. → Loops back to [transparency](https://paper.dropbox.com/doc/AI-Ethics-Guidelines-v2-9y1aIZWLLDLTaaj2L27eK#:uid=911500807287387770418676&h2=Transparency%2C-accuracy%2C-and-as): if you can’t be unbiased, be transparent in your decisions 
- Psychologist Joan E. Sieber maintains that the research question itself, as well as the interpretation of the data, may contain an inherent bias that singles out a particular group of subjects and leads to, or reinforces, unjust treatment of that group: 
  - "One historically sensitive area of the application of research findings is examining racial differences. Another example relates to the use of psychological test results in order to promote a policy of sterilization for the mentally retarded population" (Sieber and Stanley 1988, 49-55). On the issue of justice, Sieber summarizes:
  - Justice and equitable treatment refer to issues of procedural and distributive justice that may arise at any stage of the research process. An idea that creates prejudices against some sector of society is unfair. An experimental treatment is also unfair if resources known to be vital to subjects' well-being are withheld from subjects in one group and given to those in another (Sieber and Stanley 1988, 49-55).
  *source: Module 1 — History and Ethical Principles - SBE (ID: 490)*
  
  - procedural and distributive justice - the AI design should be vetted for explicit and implicit biases, prejudices against certain populations and for the potential of withholding resources or information from populations that could benefit from the design or interaction
  

**Take effective action to prevent and mitigate discrimination and document responses**
After identifying human rights risks, the second step is to prevent those risks. For developers
of machine learning systems, this requires:
a. Correcting for discrimination, both in the design of the model and the impact of the
system, and deciding which training data to use.
c. Submit systems that have a significant risk of resulting in human rights abuses to
independent third party audits.

Where the risk of discrimination or other rights violations has been assessed to be too high or
impossible to mitigate the private sector should consider not deploying a machine learning
application.

Another vital element of this step is documenting the effectiveness of the private sector’s
response on impacts that emerge during the course of implementation and over time. This
requires regular, ongoing quality assurances checks and real time auditing through the
design, testing and deployment stages to monitor the application for discriminatory impacts,
and correct errors and harms as appropriate. This is particularly important given the risk of
feedback loops that can exacerbate and entrench discriminatory outcomes.

**Taking effective action to promote diversity**
For developers of machine learning systems, this requires: pursuing diversity, equity and, other means of inclusion in machine learning development teams. This will help to identify and prevent inadvertent discrimination.

**Taking effective action to promote inclusion**
Inclusion, diversity and equity entails the active participation of, and meaningful consultation
with, a diverse community to ensure that machine learning systems are designed and used in
ways that respect non-discrimination, equality and other human rights.
*Source: The Toronto Declaration…*

**Conflict of interest** 
Address conflicts of interest protocol for AI Ethics Committee members specifically
Everybody has them, how do we mitigate those when they arise?

**Example/Case Study:** 

- There are legally projected attributes (ex. race) a. we should not restrict ourselves to what is required by current law and b. we should address proxy data (ex. race can be inferred by zip code)

Impartiality without beneficence means nothing because equality is not the same as justice.


# Transparency, accuracy, and assumptions
## “Transparency is a key component of human rights due diligence and involves “communication, providing a measure of transparency and accountability to individuals or groups who may be impacted and to other relevant stakeholders.” – UN guiding principles on business and human rights, principle 21. (Taken from the Toronto declaration.)

**Transparency about discrimination:**
Private sector entities that develop and implement machine learning applications should
explain the process of identifying risks, the risks that have been identified, and the concrete
steps taken to prevent and mitigate identified human rights risks. This may include:

- In instances where there is a risk of discrimination, publishing technical specification with details of the machine learning application and its functions, including samples of the training data used and details of the source of data.
- Establishing mechanisms to ensure that where discrimination has occurred as a result of a decision-making algorithm relevant parties, including affected individuals, are informed of the harms and how they can challenge a decision or outcome.

*Source: the Toronto Declaration…*

**To explain process and account for biases:** 
“We have to be transparent about what we do and be clear about the choices we have made. The ultimate purpose matters and the decisions you come to must be communicated.”  
*Source: Ethical Considerations for AI Researchers - Kyle Dent*

“Any decisions produced by an algorithmic system should be explainable to the people affected by those decisions. These explanations must be accessible and understandable to the target audience; purely technical descriptions are not appropriate for the general public.”
*Source:* [*How to hold algorithms accountable*](https://www.technologyreview.com/s/602933/how-to-hold-algorithms-accountable/)


- researchers/engineers are making design decisions that aren’t captured in real time, this disallows transparency overall
- Adding an independent monitor to the study team to make sure that the research procedures are transparent
- documenting your decision tree. we tend to focus on the final result. Not a lot of clients are interested in the decisions tree, but we should not leave it up to them. It is *our* responsibility.

Case  study: Fish plate crack detection collaboration PARC and JR East  ← note! is confidential project.


# Security

are we talking about security of data or of people affected by our product?
Security on a system
who might be adversaries? What happens if system gets “attacked” by one?
Guideline on thinking about those issues. 

Metrics/measurement: 

Case study: Equifax

# Privacy
## privacy is related to the methods of gathering info or data from or about people


- if a certain deployment is dangerous, that should be explicit and bounded
  - ex. a pop-up dialogue with legalese and an “accept” button isn’t enough for consent

anonymizing data where possible

Case study: Facebook example, Cambridge analytics scandal


# Confidentiality
## The obligations of researchers to appropriately protect the information that they collected


- looking at it from the context of how is data is kept and transferred
  - if you’re using data how is it classified?
    - hippa, itar, etc
    - each category has specific requirements of how it’s handled
    - what are the rules? incorporate into review process




maybe after?

# Maintenance and Compliance
## One area where the goals of this committee differ from an IRB is research (to a degree) has a finite time period. Though there are protocols in the IRB for what circumstances require re-review, we may want to develop our own standards and protocols for transfer of license, maintenance, follow up, etc. 

Justice remedy

