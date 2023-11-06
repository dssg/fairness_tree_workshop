# Fairness Tree Workshop

## Presenters
- [Lingwei Cheng](https://lwc.netlify.app/), Carnegie Mellon University
- [Rayid Ghani](http://www.rayidghani.com), Carnegie Mellon University
- Kit T. Rodolfa, RegLab, Stanford University

## Why this workshop? 

The typical process used today in eliciting fairness goals when designing ML systems is not systematic and either involves selecting an arbitrary ML-based fairness metric to achieve or computing disparities (and auditing) across a variety of (often, all of the ones that can be computed) fairness metrics. This typically results in a system that is not designed for the use case under consideration and does not result in outcomes that are fair and equitable. [Fairness Tree (FT)](https://lw334.github.io/fairness_tree/) provides a simple framework to help guide stakeholders involved in design and development decisions in:
- prioritizing notions of fairness that most appropriately match the use case setting and the deployment context of the socio-technical system being developed.
- supporting the collaborative and transparent process of eliciting fairness requirements 
- supporting the mediation across conflicting fairness needs of different stakeholder groups by pinpointing the underlying source of the conflicting priorities. 

Participants will leave the tutorial with enhanced proficiency in eliciting, understanding, discussing, and managing conflicting fairness objectives which they can then use to design better and more equitable ML systems.

## What will we cover? 
 
In this hands-on tutorial, we will start with an overview of AI fairness and the AI fairness pipeline, survey the landscape of existing AI fairness tools, and show where FT fits in. To illustrate how FT works, we will pose a hypothetical policy question where AI could be used to predict risks and allocate resources accordingly. We will walk participants through the decision points in FT, explaining relevant case studies to illustrate the nuances associated with the questions and notions of fairness. The key points for discussions are shown in the worksheets below. Participants may arrive at different fairness requirements based on their priorities, and we will show how FT can help them identify the underlying sources of conflicting priorities, which may result in different fairness needs for different stakeholder groups. The discussions will conclude with how to make sense of and operationalize these requirements.

### Pre-requisites

- Please bring a laptop so you can interact with fairness tree
- Caring about the world, fairness, and equity

### Schedule and Structure
[Google Slides](https://docs.google.com/presentation/d/1xXQjlpeJSRXkhb9RSqAOh3v4oK59nN24bP-_5XLvbcE/edit#slide=id.p)

[Fairness Tree (FT)](https://lw334.github.io/fairness_tree/)

Worksheets: 

- Exercise 1: [Determining the societal and policy goals](https://docs.google.com/document/d/1GpJKTEFi4Qp098djT5_RcN5UYD3AfIg9m664pO6qxjQ/edit?usp=sharing)
- Exercise 2: [Cost & Benefit Analysis of Intervention](https://docs.google.com/document/d/1zhD6Dvkv3enQGYKQ9zspEmkDow08JCPCcaMw8C7wxlA/edit?usp=sharing)
- Exercise 3: [Fairness Tree](https://docs.google.com/document/d/1lqd8_yvjjh6mEPakHDPjx2Jrn7wvLpLdujDizqqtM24/edit?usp=sharing)
- Exercise 4: [Caveat on Data Quality]()

1. Motivating Case Studies
   - Case Study 1: Deciding whether to open an investigation for a reported child maltreatment case based on predicted risk of maltreatment
   - Case Study 2: Deciding whether to grant bail based on predicted flight risk 
   - Case Study 3: Prioritizing who to provide housing rental assistence to based on predicted risk of future adverse events
2. Thinking about overall fairness and equity when building Data Science/ML/AI systems
3. Exploring different views around ML and fairness
4. Defining the desired societal goals of the system (from the perspective of each stakeholder group)
   - overview
   - breakout activity
5. Understanding the cost and benefits of interventions  (from the perspective of each stakeholder group)
   - overview
   - breakout activity
6. Applying the Fairness Tree Framework
   - overview
   - breakout activity
7. Caveats
8. Wrap-up
