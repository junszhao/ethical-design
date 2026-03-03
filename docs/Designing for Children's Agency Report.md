# **Designing for Children's Agency in AI -- A Public Report** 

# **1. Introduction**

## **Why Ethical Design, Why Agency by Design**

As AI becomes more deeply embedded in children’s lives, algorithmic manipulations and behavioural engineering are prevalently applied to enable personalisation or so-called effective user engagement. These systems shape children’s learning, play, and everyday decision-making in ways that are often invisible. Children, whose cognitive and socio-emotional capacities are still developing, are particularly susceptible to persuasive or manipulative design patterns. 

Within this landscape, children’s **agency** – the ability to make meaningful choices and act upon them – has been increasingly recognised as a central value in the design of AI-enabled systems. Agency is not limited to individual control. It includes relational forms: children’s actions and decisions are shaped by caregivers, peers, educators, and the platforms they use. A child’s capacity to act meaningfully depends on these relationships and on the structures of the systems they interact with. 

Critically, agency should be treated not as an optional ethical principle but as a **foundational lens** through which other ethical commitments are realised in practice. Without agency, transparency cannot be meaningfully interpreted, accountability cannot be exercised, and fairness cannot be contested. Designing for agency operationalises ethical commitments by enabling children to understand, question, and engage with AI systems in developmentally appropriate ways.  

This motivates the need for **agency by design**: systematically integrating considerations of children’s autonomy, participation, and voice into the design process from the outset. 

## **Gaps and Our Objectives**

Despite growing recognition of its importance, supporting children’s agency remains difficult in practice. Agency is often discussed at a high level of abstraction, leaving design teams with limited guidance on how to translate principles into concrete design decisions. As a result, agency is frequently treated as implicit or justified only retrospectively. 

There is currently little practical guidance or tool support to help designers systematically reason about children’s agency. Addressing this gap is the core objective of our project. By collaborating with designers of AI systems for children, we aim to: 

- Understand how designers conceptualise and apply agency in practice 
- Co-create a practical toolkit to support agency-oriented design 
- Evaluate how this toolkit integrates with and strengthens existing design processes 

We hypotheses that designing for agency is fundamentally a **cognitive and reasoning challenge**, instead of being a simple matter of optimising system outcomes. It requires a systematic process of recognising the value of agency, identifying children’s needs in relation to system structures and stakeholder roles, and carefully reasoning through trade-offs. 

Through co-design with practitioners and a review of existing literature on agency, we developed the **CHAI (Designing for
Children's Agency in AI) framework**. CHAI is a conceptual framework designed to support structured reasoning about children’s agency throughout the design process. It makes assumptions and trade-offs explicit and connects abstract ethical values to concrete system functions. 

# **2. The CHAI Conceptual Framework**

## **The Journey and Context**

Beginning in May 2025, we took the eight ethical design principles, including fairness, transparency, safety, and etc, from [an extensive literature review](https://www.nature.com/articles/s42256-024-00805-x)  as the starting point to development our ethical design framework. Through an extensive interview with experts and a mapping of current regulatory space and ethical design curriculum, led by our project partner Fam Studio, we decided to focus on supporting the designing for children’s agency in our ethical design framework. Through further user requirement analysis and piloting exercises with our designer partners and inspired by the [UNICEF/LEGO RITEC Digital Design Toolbox](https://www.unicef.org/childrightsandbusiness/workstreams/responsible-technology/online-gaming/ritec-design-toolbox), we decided to take an interactive approach with our agency design framework. 

This gives us the CHAI framework, which contains a four-step reasoning process, including agency assessment, mapping, application, and reflection. Below we describe the details of the four steps of the CHAI framework. 

## **Core Components**

CHAI supports designers through a four-stage reasoning process, including: **Assessment** (articulating the value of agency  in the system and clarifying which forms of agency are valued, for whom, and why); **Mapping** (linking agency types and levels to concrete system components and interactions via an agency mapping matrix); **Application** (updating system functions and exploring redesigns to better support agency); and **Reflection** (examining how reasoning evolved, surfacing tensions and constraints of different stakeholders (children and others), and preparing for implementation). 

![The four-stage reasoning process of the CHAI framework, enabling designers’ to reason about children’s agency through assessment, mapping, application, and reflection. The process produces intermediate reasoning artefacts and allows iteration among later stages.](/images/four_stages.png)
*Fig. 3: The four-stage reasoning process of the CHAI framework, showing how designers’ reasoning about children’s agency is transformed from an initial design context into explicit agency design through assessment, mapping, application, and reflection. The process produces intermediate reasoning artefacts and allows iteration among later stages.*

To complement the overall reasoning process of CHAI, we provide **an agency conceptualisation framework** to assist designers to map the types of agencies that are relevant to their applications or systems. Furthermore, to help designers externalise the priority the different types of agencies for them within their system, we provide **an agency mapping matrix**, giving designers an instrument to reason about degrees of participation, control, and autonomy as experienced by the child, in relation to themselves or through interactions with different types of others. 

## **The agency conceptualisation framework** 

The framework distinguishes four analytically distinct types of agencies, which function as lightweight prompts for designers to consider deeply how children’s agency is distributed across stakeholders and system components: 

1.  **Individual agency:** the child's capacity to make choices and act
    independently within or through the system.

2.  **Co-agency:** control, responsibility, and influence over outcomes
    are shared between the child and others such as a parent, peer, or
    teacher.

3.  **Proxy agency:** others act on the child's behalf (e.g. parents
    configuring settings), while the child's voice and preferences
    should remain represented.

4.  **Collective agency:** children act together with peers, families,
    or communities to influence shared outcomes through coordinated
    effort.

    
<figure align="center">
  <img src="/images/four_types_of_agency.png" alt="Four types of agency used in the CHAI framework as reasoning lenses." width="60%">
  <figcaption>Fig. 1: Four types of agency used in the CHAI framework. The visual abstractions represent different loci of action, control, and coordination across key stakeholders in each agency type.</figcaption>
</figure>

## **The agency mapping matrix**

For each type of agency, the mapping tool uses three levels (low, medium, high) to represent degrees of children’s involvement in the AI system, expressed from the child’s perspective. At a **low** level, the child’s role is primarily reactive. At a **medium** level, children can meaningfully influence interactions within bounded conditions. At a **high** level, children play an active role in shaping interactions and outcomes. Importantly, we have noted that maximising agency is not always the optimal goal; tensions and trade-offs may arise in practice, and children’s best interests should guide decisions. 

<figure align="center">
  <img src="/images/three_levels_of_agency.png" alt="Three levels of agency used in the CHAI framework as reasoning lenses." width="70%">
  <figcaption>Fig. 2: Three levels of agency. The levels capture differences in children's involvement in initiating actions, influencing decisions, and shaping outcomes, as well as how these processes are mediated by other stakeholders and the AI system.</figcaption>
</figure>

## **Open-Source Resources**

The CHAI framework materials, including workshop templates, the agency
mapping matrix, and case study examples, are openly available at:
<https://github.com/junszhao/ethical-design>

# **3. Findings from Our Engagement with Designers**

Since the initial development of the framework in October 2025, CHAI has been further refined through three iterative pilot workshops with a child–AI design competition winner team, and assessed by four teams of early-stage designers and three teams of experienced designers; the latter was run jointly with our project partner FamStudio. Here we report the findings of our engagement. 

## **What Worked Well** 

A key benefit of the workshop was helping designers surface and articulate “designing for agency” explicitly and map it directly to system functions. As reflected in post-workshop questionnaire responses (see Figure 1), designers reported increased awareness of agency-related trade-offs (Q1) and greater confidence in discussing agency explicitly with stakeholders (Q2). 

While perceptions varied slightly regarding how confident participants felt about translating agency into concrete design features (Q3–Q6), overall confidence in the design process increased. 

Designers also reported that the framework supported more systematic reasoning about design choices and trade-offs. For example, participants reflected on how decisions made for efficiency or protection, such as adult-first workflows, restrictive settings, or highly structured prompt, could unintentionally remove children from the interaction loop or narrow their meaningful choices. 

By applying the CHAI framework to their own systems, participants recognised instances where children’s voices had been unintentionally excluded from design decisions. They were able to identify opportunities to strengthen children’s participation, decision-making power, and overall agency. 

<figure align="center">
  <img src="/images/understanding_of_agency.png" alt="Pre- and post-workshop self-reported agency understanding" width="60%">
  <figcaption>Fig. 1: Pre- and post-workshop self-reported agency understanding. Q1 evaluates participants' conceptual understanding of agency. Q2 understands stakeholder awareness. Q3--Q6 estimate concept translation to design.</figcaption>
</figure>

## **Barriers and Challenges**

Three main areas of friction emerged: conceptual boundaries, operationalisation, and effort. 

First, designers often struggled to distinguish between co-agency and proxy agency, particularly in cases where adults configure settings or make decisions “on behalf of” the child. The key question was not simply whether adults are involved, but who ultimately holds decision-making power, and whether the child can influence, contest, or revise outcomes. 

Second, while CHAI strengthened awareness and structured reasoning, translating insights into concrete features remained challenging for some participants. Designers could identify tensions related to agency but felt less certain about which specific interaction patterns, settings, or workflows would best address them. This difficulty was heightened by practical constraints such as age differences among children, safeguarding requirements, and limited development time. 

Finally, applying the CHAI framework required cognitive effort. Participants noted that structured reasoning about agency can be demanding, particularly within fast-paced product cycles. They suggested that curated examples, case libraries, or additional tool support could help reduce this overhead while preserving the benefits of systematic reflection. 

# **4. Future Steps**

Our assessment with designers and policymakers demonstrates that the CHAI framework has genuine potential to support designers in applying agency-oriented design practices. In particular, it helps make existing value commitments more explicit and actionable within the design and development processes. 

- **Expanding and diversifying evaluation** across different levels of design expertise, professional contexts, target child age groups, and AI application domains. This includes examining how experienced industry practitioners engage with the framework under commercial and organisational constraints. 
- **Simplifying and clarifying agency conceptualisation** to make it more accessible and easier to operationalise across multidisciplinary teams. 
- **Building a case study library** of concrete examples illustrating how different child–AI systems have navigated agency-related trade-offs in practice. This would support shared learning and calibration across diverse design contexts. 
- **Connecting to longitudinal evidence** on how children’s agency develops over time in AI-mediated environments, integrating insights from the wider CHAILD project’s observational and empirical research. 
- **Developing towards an ethical and agency design certificate** to make the design for children’s digital wellbeing and agency a priority for designers and to boost industrial practice changes.
- 
We believe that designing for children’s agency is fundamentally a reasoning challenge that requirements embracement of complexity, make tensions visible, and enable negotiation rather than simplification. The CHAI framework is a first step towards making that practice structured, communicable, and grounded in the lived experiences of the children these systems are built to serve. 

We would welcome feedback to our framework either through our GitHub repository or emails. 
