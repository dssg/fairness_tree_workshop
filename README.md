# Fairness Tree Workshop - Presented at APPAM  (Association for Public Policy Management and Analysis) 2023
### A Guide to Determining Fairness Goals for AI Systems through Facilitated Multistakeholder Discussions

## Presenters
- [Lingwei Cheng](https://lwc.netlify.app/), Carnegie Mellon University
- [Rayid Ghani](http://www.rayidghani.com), Carnegie Mellon University
- [Kit Rodolfa](https://reglab.stanford.edu/team-members/kit-rodolfa/), RegLab, Stanford University

## Why this workshop? 

The typical process used today in eliciting fairness goals when designing ML systems is not systematic and either involves selecting an arbitrary ML-based fairness metric to achieve or computing disparities (and auditing) across a variety of (often, all of the ones that can be computed) fairness metrics. This typically results in a system that is not designed for the use case under consideration and does not result in outcomes that are fair and equitable. Our framework, [Fairness Tree (FT)](https://lw334.github.io/fairness_tree/), provides a simple framework to help guide stakeholders involved in design and development decisions in:
- prioritizing notions of fairness that most appropriately match the use case setting and the deployment context of the socio-technical system being developed.
- supporting the collaborative and transparent process of eliciting fairness requirements 
- supporting the mediation across conflicting fairness needs of different stakeholder groups by pinpointing the underlying source of the conflicting priorities. 

Participants will leave the workshop with enhanced proficiency in eliciting, understanding, discussing, and managing conflicting fairness objectives which they can then use to design better and more equitable ML systems.

## What will we cover? 
In this interactive workshop, we will start with an overview of AI fairness and the AI fairness pipeline, survey the landscape of existing AI fairness tools, and show where FT fits in. To illustrate how FT works, we will present a series of case studies where AI is being considered as a tool to allocate resources. Participants will work through the case studies role-playing each group of stakeholders and determine fairness needs from the perspective of each stakeholder, assess the cost and benefit of the interventions available, and finally come up with appropriate fairness metrics for the task at hand. The key points for discussions are shown in the worksheets below. Participants may arrive at different fairness requirements based on their priorities, and we will show how FT can help them identify the underlying sources of conflicting priorities, which may result in different fairness needs for different stakeholder groups. The discussions will conclude with how to make sense of and operationalize these requirements.

### Pre-requisites

- Please bring a laptop so you can interact with the fairness tree
- Caring about the world, fairness, and equity

### Schedule and Structure
[Google Slides](https://docs.google.com/presentation/d/1xXQjlpeJSRXkhb9RSqAOh3v4oK59nN24bP-_5XLvbcE/edit#slide=id.p)

[Fairness Tree (FT)](https://lw334.github.io/fairness_tree/)

![Fairness Tree](fairnessfultree.png?raw=true "Fairness Tree")

Worksheets: 

- Exercise 1: [Determining the societal and policy goals](https://docs.google.com/document/d/1GpJKTEFi4Qp098djT5_RcN5UYD3AfIg9m664pO6qxjQ/edit?usp=sharing)
- Exercise 2: [Cost & Benefit Analysis of the Intervention](https://docs.google.com/document/d/1zhD6Dvkv3enQGYKQ9zspEmkDow08JCPCcaMw8C7wxlA/edit?usp=sharing)
- Exercise 3: [Determining Fairness Metrics to Prioritize ](https://docs.google.com/document/d/1lqd8_yvjjh6mEPakHDPjx2Jrn7wvLpLdujDizqqtM24/edit?usp=sharing)
  
1. Motivating Case Studies
   - [Case Study 1](https://docs.google.com/document/d/1rnstbzKDBfrpj4vTV1gJJTarqZ5ltcvxvHdFnZuYKik/edit#heading=h.2v0rv9rx3b4u): Child Welfare: Determining whether to open an investigation for a reported child maltreatment case based on predicted risk of maltreatment
   - [Case Study 2](https://docs.google.com/document/d/1mdrcdwTQU9afV3cCESuJUQpT98-iyeOOszb4W_aEAQk/edit#heading=h.4oe3nkjkjaps): Housing: Prioritizing rental assistance allocation  based on predicted risk of future homelessness
   - [Case Study 3](https://docs.google.com/document/d/1ye-T-CpLLAPza9oGaVSTdk1rScO409Ts5r9HIYMKJjc/edit) Tax/Fraud Audits: Determining which tax returns to prioritize to audit based on risk of fraud/abuse/error 

2. Understanding overall fairness and equity goals when building Data Science/ML/AI systems
3. Exploring different views around ML and fairness
4. Defining the desired societal goals of the system (from the perspective of each stakeholder group)
   - overview
   - breakout activity: [Cost & Benefit Analysis of Intervention](https://docs.google.com/document/d/1zhD6Dvkv3enQGYKQ9zspEmkDow08JCPCcaMw8C7wxlA/edit?usp=sharing)
5. Understanding the cost and benefits of interventions  (from the perspective of each stakeholder group)
   - overview
   - breakout activity - [Cost & Benefit Analysis of the Intervention](https://docs.google.com/document/d/1zhD6Dvkv3enQGYKQ9zspEmkDow08JCPCcaMw8C7wxlA/edit?usp=sharing)
6. Applying the Fairness Tree Framework
   - overview
   - breakout activity - [Determining Fairness Metrics to Prioritize](https://docs.google.com/document/d/1lqd8_yvjjh6mEPakHDPjx2Jrn7wvLpLdujDizqqtM24/edit?usp=sharing)
7. Discussion
8. Wrap-up
