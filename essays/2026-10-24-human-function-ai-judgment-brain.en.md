# Toward a Global Unified Computational Interface for Human Models: Human Function Gives AI a Reasoning Framework for How the Human Body Works

[中文原文](2026-10-24-human-function-ai-judgment-brain.zh-CN.md) · [HFWM research home](../README.md) · [Public essays](README.md)

**Author:** Lei Che  
**Affiliation:** MoveTips / MoveTips Technology (Beijing) Co., Ltd.  
**Published:** 24 October 2026  
**Type:** Public-facing research explainer (not a peer-reviewed article or an adopted technical standard)  
**Topics:** Human Function Intelligence; human-function reasoning brain; global unified computational interface for human models; HFWM Human Function World Model; UOHF Unified Ontology of Human Function; necessity of human-function relations  
**License:** CC BY-NC 4.0

Artificial intelligence already has access to an enormous amount of knowledge about the human body.

AI can describe bones, muscles, nerves, and organs. It can explain diseases, physiological mechanisms, and movements. But can knowing so much about the body tell AI **what is actually happening to a particular person?**

Consider someone whose knee hurts when climbing stairs.

An AI system can identify muscles used during stair climbing, discuss knee-joint loading, and list diseases that may cause pain.

Yet that knowledge does not directly establish why **this person's** knee hurts.

Does the person lack the necessary capacity? Is the capacity available but not appropriately engaged in this situation? Is disease or injury involved? Are several factors interacting?

What changes if the person adjusts the movement, reduces the load, receives assistance, or trains over time?

That is the harder problem of reasoning about a person.

**Knowing what the body contains is not the same as knowing why this person's body is operating as it does.**

MoveTips researches how AI can move beyond retrieving bodily knowledge toward interpreting bodily operation, judging a person's current state, and tracking changes over time.

To investigate that goal, MoveTips has developed the **Unified Ontology of Human Function (UOHF)**, the **Human Function World Model (HFWM)**, and supporting methods for knowledge relations and reasoning.

A new theoretical preprint dated 23 October 2026 addresses a foundational question: **Why must certain human-function relations be preserved when making particular whole-person judgments?**

---

## 1. We have a great deal of knowledge about the human body. The pieces still need to connect.

Medicine studies disease, diagnosis, and treatment. Anatomy studies bodily structures. Physiology studies how organs and tissues work. Movement science studies action, force, control, and performance. Cognitive science studies perception, memory, and thought.

All of these fields matter, but they answer different questions.

A medical test may indicate disease risk. A strength test may report force under a defined measurement condition. A movement model may estimate what a task requires.

**Each observation can be valid without automatically producing a valid judgment about the same individual.**

The human body is not a static collection of parts. It is continuously operating.

The heart pumps blood, the respiratory system exchanges gases, and the body regulates temperature, responds to infection, and repairs injury. At the same time, the person walks, works, exercises, learns, thinks, and adapts to the environment.

These activities happen within one person, interact, and change over time.

For AI to understand the human body, it therefore needs more than an inventory of structures and functions. It also needs to ask:

**What demand is this person facing? What capacities are available? How are they actually engaged? What happened as a result?**

That brings us to human function.

## 2. What is human function?

MoveTips defines human function as:

> **The body's capacity to be appropriately engaged to meet internal and external demands.**

In everyday language, human function concerns the body's ability to be called upon appropriately when needed.

To sustain life, the body must breathe, circulate blood, and regulate its internal conditions. To climb stairs, it must generate force, maintain balance, and coordinate movement. To sustain work, it must manage ongoing demands and recover afterward.

Three questions must remain separate.

**First: What capacity does the body have?** Does the person have what the task requires?

**Second: How is that capacity actually used?** Having a capacity does not guarantee that it will be expressed the same way on every occasion. Pain, fatigue, disease, environment, and assistance may change the process.

**Third: What was the result?** Completing a task does not prove the absence of a problem. Failing to complete a task does not automatically identify a specific capacity deficit.

Someone who can climb stairs while holding a handrail is not necessarily fully recovered. Someone who can climb stairs may still have knee disease.

Human function is therefore more than a list of movements or test scores. It helps describe **the relationship between bodily capacity and the demands the person must meet**, and how those relationships bear on bodily operation.

## 3. New research: Why can't human-function relations simply be left out?

MoveTips had already developed a definition of human function, an ontology, a capacity system, and a world-model architecture.

But a more basic question remained: **Are human-function relations actually necessary for AI to make certain judgments about a person?**

The theoretical preprint dated 23 October 2026, [*Human-Function Relations as Necessary Conditions for Whole-Person Judgment*](https://doi.org/10.5281/zenodo.23598781), uses formal arguments and constructed examples to examine what information must be retained to answer specified questions correctly.

### A straightforward example

Imagine two situations involving the same task and the same participating anatomical structures.

In one situation, the body's available conditions are sufficient to meet the task demand. In the other, they are not.

If an AI system knows only which muscles and joints are involved—and lacks the conditions that determine whether the task can actually be realized—the two situations may look identical to that system.

Yet the correct answers differ: the task is feasible in one situation and not in the other.

No algorithm can guarantee both answers are correct if the information presented to it cannot distinguish the two cases.

This is the central idea behind one of the paper's formal results:

**If two situations require different answers, a system must have enough information to tell them apart.**

For human-body reasoning, knowing which structures participate in a task is not always enough. The conditions and relations that change the answer also matter.

### The same result can come from different processes

Two people may both climb a flight of stairs. One might rely mainly on their own force production and coordination. Another might change movement strategy or use a handrail to redistribute the load.

Both finish the task, but the processes need not be the same.

If AI observes only the outcome, it cannot automatically infer that the two people used identical bodily mechanisms—still less diagnose the cause of a condition from that outcome alone.

**What the body can do, what it actually does, and what result is observed are different questions.**

### The body also changes

Being able to perform an activity today does not ensure identical conditions tomorrow.

Training, fatigue, disease, treatment, recovery, and environmental changes can alter subsequent performance. New measurements may also change how we interpret an earlier event.

A useful judgment system must therefore keep track of the evidence behind its conclusions and reconsider the conclusions when the evidence changes.

### What did the paper establish?

The preprint presents **three theorems, six propositions, 25 synthetic checks, and additional finite computational comparisons**.

Its central conclusion is conditional but important:

**When AI must judge what a body can realize under particular demands, what actually occurred, and how judgments should change with new evidence or bodily states, it cannot discard human-function-related distinctions that change the correct answer unless it can recover those distinctions by another valid means.**

This specifies information responsibilities for a human-function reasoning system.

The formal proof and synthetic tests are **not clinical validation**, and they do not demonstrate that AI can already diagnose people accurately. Their contribution is to make a necessary condition of particular judgments explicit and examinable.

## 4. How MoveTips is building an AI reasoning framework for the human body

With a definition and a necessity argument in place, the next question is practical: **How can AI use these relations to reason?**

The MoveTips research program includes several complementary components.

### UOHF: A shared language for human function

The **Unified Ontology of Human Function (UOHF)** provides governed meanings and relations for demand, capacity, actual engagement, evidence, and related objects.

Its versioned capacity system currently organizes **18 core and 104 specific human functional capacities**. These are semantic capacity categories, **not 104 validated clinical scores**.

### Functional Bridge: Connecting function to scientific mechanisms

Naming a capacity is not enough. AI also needs reliable connections to anatomy, physiology, and other relevant mechanisms.

The **Functional Bridge** is a research and knowledge-relation layer intended to make those connections.

For stair climbing, relevant scientific knowledge may involve joints, muscles, neural control, and physiological mechanisms.

But general scientific knowledge is **not automatically evidence about one specific person**. Individual judgments still require appropriate person-specific observations.

### HFTD-BR: Reasoning in both directions

**HFTD-BR** is the human-function task decomposition and bidirectional reasoning method.

One direction starts with the question: Why does this person's knee hurt on stairs, and what would we need to examine to understand it?

The other direction starts with available evidence: What do the observations and assessments support, and what possible explanations remain untested?

The aim is not to jump from “knee pain” to “weak muscle,” or from one normal test to “no functional problem.”

**When the evidence is sufficient, explain the judgment. When it is insufficient, identify what is missing.**

### HFWM: Keeping reasoning connected to the same person over time

The **Human Function World Model (HFWM)** is not limited to exercise or rehabilitation.

Its modeled subject is the same continuing person, across health, disease, physiology, medicine, cognition, behavior, environment, personal history, and change over time.

Put simply:

**UOHF supplies common meanings and relations. Functional Bridge connects relevant scientific knowledge. HFTD-BR organizes reasoning. HFWM maintains a continuous computational view of the same person.**

Together they provide the research basis for what MoveTips calls an AI **human-function reasoning brain**.

“Brain” is a metaphor for a computational reasoning architecture, not a copied human brain or artificial consciousness.

## 5. Why work toward a global unified computational interface for human models?

A reasoning system addresses how to form judgments. A related but different problem is:

**How can different human-body models work together around the same person?**

A medical model may estimate disease risk. A movement model may analyze performance. A physiological model may describe regulation. A wearable device may provide time-stamped measurements.

These sources could all contribute to understanding the same person, but their outputs cannot be combined blindly.

A strength measurement, a disease-risk estimate, and a task outcome are not the same kind of statement. They may come from different times, settings, units, and measurement conditions.

MoveTips therefore proposes that human models need more than data transfer. They need ways to communicate **what a result means, to whom and when it applies, and what it can legitimately support**.

The 6 October 2026 preprint, [*Connecting Human Models Through Human Function: Toward a Common Computational Protocol for Whole-Person Modeling*](https://doi.org/10.5281/zenodo.23180973), explores how human-function relations could provide a shared basis for interpretation while medical, physiological, cognitive, movement, and other models retain their native methods.

This motivates the long-term research direction of a **global unified computational interface for human models**.

In plain terms:

**The reasoning brain asks: How can AI understand and judge the state of this person?**

**The computational interface asks: How can different human models exchange and interpret information together so that they can support judgments about this same person?**

The necessity paper clarifies why answer-relevant functional distinctions cannot be ignored in that process.

This is a proposed research direction, **not an existing internationally adopted technical standard or evidence of universal compatibility**.

## 6. What comes next: testing the accuracy of judgments

MoveTips has developed a scientific definition, ontology, capacity system, knowledge-relation architecture, bidirectional reasoning specifications, and HFWM framework.

The new theoretical work strengthens the argument for specific relations that the reasoning process must preserve.

The next challenge is to test actual performance.

For a person with knee pain while climbing stairs, can AI correctly identify relevant structures, capacities, engagement processes, and potential disease factors?

Can it distinguish evidence-supported conclusions from hypotheses that need further examination?

Can it revise its judgment when new measurements appear?

Can it correctly identify changes after treatment, training, or environmental adjustment?

These questions require real, appropriately governed data, independent professional reference judgments, clear evaluation criteria, and comparisons with existing approaches under the same information conditions.

Evaluation must assess not only correct answers but also incorrect certainty, missed risks, and appropriate decisions to say “the evidence is not sufficient.”

Prediction of future states requires separate tests of accuracy, time horizon, uncertainty, and conditions of use.

**The next research priority is to turn the existing computational framework into a capability that independent evaluators can test.**

---

## Conclusion: From knowing about the body to reasoning about the person

AI already has access to extensive knowledge about the body. But knowing which structures participate in an activity and which diseases might be relevant does not establish what is happening to a particular individual.

The relevant demands, bodily capacities, actual engagement, outcomes, evidence, and change over time need to be connected.

MoveTips is researching that connection through **UOHF, Functional Bridge, HFTD-BR, and HFWM**.

The new necessity preprint gives a formal account of why certain distinctions matter to specific judgments. The proposed global unified computational interface takes the next step: exploring how different human models might share and interpret information about the same continuing person.

**From knowing what the human body contains, to understanding how it operates, to testing AI's ability to reason about an individual person.**

The scientific and computational framework has been developed. Its real-world accuracy and model interoperability remain subjects for independent validation.

---

## Research references

1. **Human-Function Relations as Necessary Conditions for Whole-Person Judgment.** Theoretical preprint, V1.3, 23 October 2026. https://doi.org/10.5281/zenodo.23598781
2. **Connecting Human Models Through Human Function: Toward a Common Computational Protocol for Whole-Person Modeling.** V1.0, 6 October 2026. https://doi.org/10.5281/zenodo.23180973
3. **The Human Function World Model: Modeling the Whole Person Through Human Function Across Tasks, States, Actions, and Longitudinal Change.** https://doi.org/10.5281/zenodo.22685308
4. **UOHF Definition 2.1: Unified Ontology of Human Function.** https://doi.org/10.5281/zenodo.21630406

**Public research repositories:** [HFWM](https://github.com/dlehche/Human-Function-World-Model) · [UOHF](https://github.com/dlehche/Unified-Ontology-Of-Human-Function)

> **Research status:** This is a public-facing explanation, not a new peer-reviewed paper. The cited preprints have not been peer reviewed. Formal proofs and synthetic tests do not establish clinical diagnostic accuracy or clinical effectiveness. The global unified computational interface is a research goal, not an adopted international standard.
