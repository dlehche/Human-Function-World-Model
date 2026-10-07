# Connecting Human Models Through Human Function: Toward a Common Computational Protocol for Whole-Person Modeling

## Conceptual architecture and research agenda

> **Version-controlled GitHub text edition of the Zenodo Version 1.0 preprint.**  
> Canonical archival record and PDF: https://doi.org/10.5281/zenodo.23180973  
> [中文全文](Human_Model_Interoperability_ZH_V1.0.md) · [Publication overview](README.md)

**Lei Che**

MoveTips Technology (Beijing) Co., Ltd.

Beijing, China

Correspondence: dlehche@gmail.com

Version 1.0 \| 6 October 2026

DOI: 10.5281/zenodo.23180973

License: Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)

Copyright © 2026 Lei Che and MoveTips Technology (Beijing) Co., Ltd.

Keywords: Human function; Whole-person modeling; Model interoperability; UOHF; Human Function World Model; Functional capacity; Functional engagement

# Abstract

Heterogeneous human models can concern the same person while describing different constructs, times and possible outcomes. We propose human function as a common relational coordinate for their joint interpretation. The architecture connects task demands, evidence-supported capacity, actual functional engagement, performance, cost, boundaries and recovery while preserving native medical, physiological, psychological, cognitive, movement, nutritional, behavioral, environmental and device-model outputs. The Unified Ontology of Human Function supplies semantic identities and governed relations; the Human Function World Model coordinates a typed network with recursive submodels, distinct graph views and versioned updates. General interoperability principles are separated from HFWM conventions and domain-specific measurement rules. We position the proposal against functional classification, higher-level ontology fusion, context-based knowledge fusion and model-composition standards. A hypothetical stair-descent case traces how independent capacity support and qualified process observations yield a specific functional judgment, how missing inputs limit only dependent conclusions, and how assistance or medical forecasts remain distinct. The evaluation agenda compares matched-evidence alternatives across semantic, measurement, computational, predictive and practical outcomes. This is a conceptual architecture with explicit testable consequences, not evidence of universal model compatibility or clinical benefit.

# 1. The scientific problem: making different models jointly intelligible

A disease forecast, a physiological simulation, a movement analysis and an account of everyday demands may describe the same individual while answering different questions. Their outputs cannot be treated as interchangeable merely because they appear in one record. What is needed is a way to relate those answers to what this person must sustain or accomplish, which bodily capacities are available, how those capacities are actually used, and what changes after action or new evidence. This is a problem of computational interpretation as well as data exchange.

Integrated modeling is not new. Medical digital-twin research already addresses individualized simulation and integration. Higher-level fusion has long used ontologies to represent situations and relationships, and context-based knowledge fusion has explicitly considered the autonomy of contributing sources. The question is not whether these fields have discovered integration, but which person-level relations should be made explicit when their outputs concern human function.\[1,2,3\]

We propose an architecture in which human function organizes heterogeneous model contributions around the same continuing person. Its central relationship connects task demands, evidence-supported capacity, actual functional engagement, performance, cost, boundaries and recovery. The intended contribution is a specified organization of these relationships and their computational responsibilities, together with a traceable cross-model example and a falsifiable evaluation agenda. It is not a claim that a new label alone improves inference.

This work develops the author’s published UOHF and HFWM research program and specifies a cross-model interoperability architecture centered on human function. The paper distinguishes semantic commitments, architecture design requirements, external standards, and items that still require empirical calibration. The common protocol is proposed rather than internationally adopted; the cases are hypothetical design analyses, not reported patient outcomes.\[4,5,6\]

# 2. Human function, UOHF and HFWM are different layers

Human function is defined in this framework as “the body’s capacity to be appropriately engaged to meet internal and external demands.” Capacity is not the actual process of using it. Appropriate use is conditional on the person, demand, context and relevant boundaries, rather than a single movement appearance, population mean or productivity target. Human function is an organizing coordinate, not a synonym for health or the entirety of a person.\[4,5\]

The Unified Ontology of Human Function (UOHF) provides semantic identities, object distinctions and governed relations. The Human Function World Model (HFWM) uses that semantic foundation to organize states, evidence, actions, feedback and longitudinal updating for the same person. Domain models supply their own mechanisms, estimators, observations, predictions or qualified judgments. An organ model is therefore not a capacity object, and a model output is not automatically a personal fact.\[6,7\]

Table 1 separates the general proposal from the HFWM realization and the domain rules needed to make it operational. This separation is essential for a public interoperability claim: shared meaning does not require every participant to use one vendor, one algorithm or one internal variable name.

**Table 1. Three levels of the interoperability proposal.**

| **Level**                   | **What is specified**                                                                                               | **What remains open or distinct**                                                                                  |
|-----------------------------|---------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| General organizing proposal | Bind model contributions to the same person, demand, conditions, time and justified interpretation.                 | Other ontologies and implementations can be aligned through explicit, tested mappings.                             |
| HFWM realization            | UOHF references; one coordinating kernel; typed model network; four graph views; capacity and engagement contracts. | The 18/104 catalogue and three-valued labels are version-specific conventions, not internationally mandated codes. |
| Domain realization          | Measurement protocols, models, parameterization, construct interpretation, uncertainty and approved uses.           | Clinical, movement, cognitive and other methods retain their own evidence and professional boundaries.             |

This distinction organizes the source design for this paper; it does not add an ontology layer or a new physiological law.

The current capacity catalogue comprises 18 core capacities and 104 specific objects, including subcapacities and capacity components. It is a versioned semantic hierarchy, not a 104-dimensional interchangeable score vector or 104 validated measurement instruments. One model may support several capacities, and one capacity may depend on several models and observations. C07, Sustained Task Endurance Capacity, intentionally has no subordinate capacity objects in this version.\[8\]

Internal regulation, defense, recovery, consciousness, sleep–wake regulation, cognition and communication belong within the scope alongside movement. Medicine is one contributor, including diagnostic and predictive models, not the organizing center. Psychological experience, nutrition, environment, personal priorities and medical findings can remain in their native meanings even when no capacity interpretation is justified. A person’s choice not to undertake an activity must not be reclassified as a bodily deficit.\[7\]

# 3. The relationship to existing approaches

The World Health Organization’s ICF already distinguishes capacity in a standardized setting from performance in the current environment and incorporates environmental influences. HFWM should not claim to have invented the separation of ability and real-life accomplishment. Its actual-engagement construct concerns the bodily process through which available capacity is organized in a particular episode; that is not automatically equivalent to the ICF performance qualifier. A correspondence requires a defined construct and scope, not a name substitution.\[5,9\]

Little and Rogova provide a relational ontology approach to higher-level contextual understanding; Smirnov and colleagues analyze context-based fusion with attention to source structure and autonomy. These are direct intellectual comparators. The proposed HFWM contribution is the demand–capacity–engagement interpretation contract for human-model composition, not the general idea of preserving sources.\[2,3\]

CellML, SBML comp and FMI provide complementary facilities for model definition, composition and execution. They can support native coupling within an HFWM realization. PROV-O and UCUM can support provenance and unit representation. None should be portrayed as a weak alternative simply because its intended role differs from a functional interpretation contract.\[10,11,12,13,14\]

Table 2 identifies what should be compared. Its final column states questions for evaluation, not results establishing HFWM superiority. An alternative implementation that preserves the same relevant distinctions may perform equally well.

**Table 2. Closest approaches and the proposed comparison.**

| **Approach**                        | **Contribution to retain**                                             | **Question for a matched comparison**                                                                                               |
|-------------------------------------|------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| ICF-based functional representation | Capacity, performance, activities, participation and environment.      | Does explicit, separately evidenced actual engagement add information beyond a well-implemented ICF-informed representation?        |
| Higher-level ontology fusion        | Typed entities, processes and relations for contextual interpretation. | Does the specific functional relation improve target qualification, rather than merely adding labels?                               |
| Context-based knowledge fusion      | Contextual integration with source structure and autonomy considered.  | Can both systems preserve source dependence and distinguish changed demand from changed capacity?                                   |
| Model composition / co-simulation   | Native equations, components, connections and execution interfaces.    | Does the added person-level interpretation preserve valid coupled results while limiting unsupported task transfer?                 |
| Provenance-aware integration        | Recorded origin, derivation, responsibility and time.                  | Does interpretation distinguish a forecast, an observation and a justified judgment when provenance is otherwise equally available? |

Comparison dimensions are this manuscript’s analysis of the cited approaches. They do not assert that those approaches are incapable of extension.

# 4. One kernel, a typed model network and recursive composition

The HFWM architecture is organized as 1 + N with recursive submodels. The “1” is a versioned coordinating kernel, not a universal numerical formula; “N” denotes models with different computational roles. A model may contain submodels, but each execution must expand to a finite required subgraph. Adding a model does not automatically create an ontology child or require recalculating every capacity.\[7\]

The kernel coordinates identity, model and rule selection, evidence qualification, calculation plans, capacity and engagement judgments, safety, authority, versioning and report projections. Several software components can implement those responsibilities. Physiological models, statistical estimators, machine-learning predictors and rule systems retain their own mathematics. Their roles and permitted outputs, not their model-family names, determine how they enter a calculation.
Figure 1 distinguishes four graph views. The composition graph expresses containment; the coupling graph expresses inputs, outputs, shared variables and temporal constraints; the evidence graph records real derivation; the task–capacity explanation graph connects requirements to qualified evidence and judgments. A feedback loop in physiology is legitimate when solved appropriately, while a circular derivation cannot create independent evidence.

**Figure 1. A shared person-level architecture without a compulsory scalar bottleneck.**

> **Figure 1 visual:** the exact archived figure is available in the canonical Zenodo PDF: https://zenodo.org/records/23180973
>
> **Alt text:** One person and a stated time and purpose enclose a network of medical, physiological, movement, psychological, cognitive, nutritional, behavioral, environmental and device models. A unified kernel uses UOHF references and four separate graph views to coordinate evidence, judgments and updates. Direct connections remain between domain models; outputs include domain assertions as well as functional interpretations.

Human function provides the organizing relation; UOHF supplies semantic identities and governed relations; HFWM coordinates a person-bound model network. Native domain models can couple directly. The four graph views express different relationships, not four serial conversion stages. Only qualified contributions support capacity, engagement or task-state judgments. Medical facts and forecasts retain their own identities. The diagram summarizes the architecture specified in this manuscript and the cited UOHF/HFWM framework.

Shared physical states require an owner, read-only references or joint constraints. Competing estimates of a state retain their different sources rather than being added as two physical states. Models that reuse an observation disclose that dependency. Physical conservation applies only to appropriate physical ports, not to a universal pool combining pain, emotion and physiological energy. Bond-graph work illustrates how semantic and physical consistency can both inform suitable biosimulation connections.\[7,15\]

The four views also make disagreements interpretable. A composition change asks which module contains another; a coupling change asks which variables or constraints interact; a new source asks which assertions depend on it; a task change asks which requirements must now be met. These changes can coincide, but none substitutes for the others. A shared measurement may legitimately support two different questions without becoming two independent observations. A physiological loop may be well defined even though circular evidential self-confirmation is prohibited.

Execution is scoped to the question. The kernel selects requested outputs and their necessary dependencies instead of evaluating every model or every catalogue entry. An optional module can be omitted only under a stated, qualified fallback. A missing required module limits the affected interpretation, but does not erase observations or prove a bodily limitation. Unloaded, unmeasured, inapplicable, invalid and computationally failed remain distinguishable reasons for missing conclusions.\[7\]

# 5. From measurements to two distinct judgments

A capacity standard package names the exact construct, population, conditions, measurement procedure, data meanings, estimation method, uncertainty, demand-comparison rule and limits. It answers what an observation can support about a capacity. A source result can be valid while its transfer to a particular real-life task is not justified. Matching units is necessary for some comparisons but does not establish construct or protocol equivalence.\[7\]

Five references remain separate: a suitable population reference, the person’s demand, a comparable personal baseline, safety and action boundaries, and meaningful-change criteria. Lowering a task demand can change adequacy without increasing capacity. A test stopped at its prescribed endpoint establishes what was observed, not necessarily maximum ability. Completing 20 minutes of walking can support a matched 10-minute requirement under an appropriate rule; by itself it cannot prove inability to walk for 30 minutes.

An engagement standard package instead binds the episode, independently supported current capacity, acceptable process patterns, actual-process observations, matched conditions, competing explanations and a judgment rule. Independently supported capacity means that the questioned performance is not circularly used to define and confirm its own capacity explanation. It does not require all observations or model inputs to be statistically independent.\[5,7\]

Table 3 gives the source version’s two judgment axes. NORMAL means that the relevant adequacy or appropriateness claim is supported under the specified demand and conditions. PROBLEM requires positive evidence for the relevant problem. NO_EVIDENCE records that the necessary judgment cannot currently be supported, with a reason; it is not a zero-capacity score. These machine labels are HFWM conventions, not universal diagnoses.

**Table 3. Capacity and engagement judgments remain separate.**

| **Capacity / engagement**    | **Interpretation under the source contract**                                                | **What does not follow**                                        |
|------------------------------|---------------------------------------------------------------------------------------------|-----------------------------------------------------------------|
| NORMAL / NORMAL              | Both judgments are supported in the specified context.                                      | No universal health, recovery or safety guarantee.              |
| PROBLEM / NORMAL             | Capacity is insufficient for the requirement; use of the remaining capacity is appropriate. | No automatic failure of cooperation or engagement.              |
| NORMAL / PROBLEM             | Capacity is supported; actual engagement has a separately supported problem.                | No established neurological, structural or psychological cause. |
| PROBLEM / PROBLEM            | Both problems have their own sufficient evidence.                                           | One axis cannot establish the other automatically.              |
| Known capacity / NO_EVIDENCE | Preserve the supported capacity judgment and unresolved engagement.                         | No forced complete profile.                                     |
| NO_EVIDENCE / NO_EVIDENCE    | Keep observations, constraints and exact evidence gaps.                                     | Unknown is not normal, impaired or a failure to record facts.   |

When current capacity lacks adequate independent support, this source version does not permit a known formal engagement judgment. Integrated task-state categories remain a separate interpretation.

Normal, compensated, critical and disabled are separately defined task-state categories. They require relevant state rules and consideration of consequences, boundaries and recovery; they are not the capacity or engagement scale. Safety blocking, missing evidence and a numerical solver failure remain different statuses. Assistance or an alternative strategy can be appropriate, and improvement after a cue alone does not establish why it occurred.\[7\]

For multidimensional capacities, observed successful points need not identify every attainable combination. Separate maxima may not be jointly achievable. Parent-capacity interpretation likewise requires its own justified synthesis rule rather than the minimum, maximum or average of children. If that rule is unavailable, the system reports the known child results and unassessed dimensions. The same discipline applies when a capacity has no child entries: the current catalogue retains Sustained Task Endurance Capacity, C07, directly instead of inventing children to make a symmetrical hierarchy.\[7,8\]

A demand-conditioned judgment should remain useful without becoming a permanent label on the person. Adequacy for an assisted, lower-load task and insufficiency for another requirement can coexist. Their difference may concern the demand rather than a changed bodily capacity. Reports therefore retain the capacity–task relationship and the evidence cutoff. Numerical reserve, meaningful change or recovery time is reported only when its own scale, measurement interpretation and conditions are supported; a completed task alone does not provide them.

# 6. Contributions from medicine and other domains

A common module envelope identifies the model and run, person, intended use, applicable population, inputs, output types, units, time, state ownership, dependencies, uncertainty, failure behavior and replacement conditions. It preserves the producer’s original output and separately qualifies its relationship to a recipient construct. An appropriate interface can therefore accept an informative medical forecast without manufacturing a capacity estimate.\[7\]

Medical models include diagnosis, disease-risk prediction, prognosis, early warning, complications and treatment-response prediction. Each forecast retains its endpoint, horizon, version, inputs and applicability. FHIR RiskAssessment illustrates an existing representation for predicted outcomes and their basis. Receiving such a record would not by itself validate an HFWM mapping or convert risk into present impairment.\[16\]

Medical predictions can inform a permitted reassessment question or action review when their intended use supports it. Conversely, qualified functional observations may become inputs to a medical predictor whose contract permits them. The returning forecast is derived from those observations and cannot count as an independent measurement confirming them. Changing the predictor’s input set requires evaluation; additional functional features are not assumed to improve accuracy.

The same contract applies to forecasts of training response, sleep, behavior or environmental exposure. Native physiological and biomechanical models can exchange compatible variables directly. Cognitive, psychological and nutritional models contribute only within their constructs and validated uses. Device signals, derived metrics and professional interpretations remain different objects. A general-purpose AI can organize information or express supported statements, while any learned estimator requires its own defined role and validation.

Internal and non-medical domains make this separation particularly important. A nutritional account of intake is not, by itself, an estimate of nutrient processing or availability. A model of internal regulation can contribute variables or constraints relevant to that question, but only a qualified construct model turns appropriate evidence into a capacity estimate. Similarly, a record of psychological experience preserves what the person reports; an emotional-regulation or cognitive interpretation requires its own construct, context and evidence. These examples specify possible roles, not completed integrations.\[7\]

Neither biological change nor useful observation depends on a current external task record. Internal regulation, protection, repair and development remain within the framework’s demand scope. The operational task entry requires governed definitions and triggering grounds; a disease keyword does not automatically instantiate every internal task. Where no adequate observation or comparison exists, the relevant process or medical fact can still be represented without an unsupported capacity label. This avoids both reducing human function to visible movement and treating every physiological measurement as a measured ability.

# 7. A complete hypothetical connection: descending stairs

The following design case extends the source manuscript’s stair-descent example. It is not a participant record. All measurement validity, task-transfer rules and process-comparison rules stated as sufficient are explicit assumptions for this case; no clinical threshold, diagnosis or device performance is supplied. The purpose is to show exactly which contributions make a judgment possible and which do not.\[7\]

The person’s goal is to descend a familiar flight of stairs under specified step geometry, pace, carried load and assistance conditions. The focal capacity is braking-force output; this is one component of a task that can involve other capacities. A judgment about this component will not certify the entire descent. Table 4 gives the source records and their distinct roles.

**Table 4. Case inputs, retained identities and permitted uses.**

| **Illustrative record** | **Source contribution and conditions**                                                                                                | **Permitted role**                                                                        |
|-------------------------|---------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| Task T1                 | A governed task description records geometry, pace, load, phase, assistance and successful completion conditions.                     | Defines the focal braking requirement; does not show personal insufficiency.              |
| Assessment A1           | An independently obtained assessment supports braking capacity under an explicitly applicable interpretation and task-alignment rule. | Assumed to support adequacy for the focal T1 requirement.                                 |
| Process O1              | Separate task-process observations document braking organization during T1; matching and an approved interpretation rule are assumed. | Assumed to support a problem in actual engagement despite adequate focal capacity.        |
| Experience X1           | The person reports discomfort and effort during T1.                                                                                   | Retained as reported experience and cost, not automatically as a cause or capacity score. |
| Forecast P1             | An optional medical predictor reports its own event endpoint and future horizon.                                                      | Retained as prediction; only a qualified use may trigger reassessment or action review.   |
| Report R1               | A report cites A1, O1 and P1 rather than adding measurements.                                                                         | Audience projection with the same source ancestry; no new independent evidence.           |
| Follow-up O2            | A later descent uses added support and has improved observed performance.                                                             | A new assisted-condition episode, not proof that capacity improved.                       |

Identifiers are local to this hypothetical illustration, not production records or new ontology identifiers. The sufficient-evidence assumptions must be replaced by real protocols and sources in an empirical study.

First, task interpretation establishes what is required in the relevant phase. Second, the assessment interpretation and alignment establish adequacy for the focal braking requirement. Third, the separate process observation and rule support an engagement problem under matching conditions. Their joint contribution is a demand-bound NORMAL / PROBLEM judgment for that capacity–task relationship. No single diagnosis, task label or video finding supplies that entire conclusion. Other unassessed capacities remain unknown.

The report can now state: “Current evidence supports the braking capacity required in these conditions, while observed use of that capacity during descent remains problematic. The specific mechanism is unresolved; further work should address the actual process and competing explanations within the applicable safety limits.” This is a positive functional interpretation, not merely a refusal to infer. It does not prescribe a treatment or explain the finding by a medical diagnosis.

Remove A1, or remove its valid task-alignment rule, and the adequacy claim no longer follows. O1, discomfort and assistance remain visible, but the capacity and engagement judgments remain unresolved under the contract. Retain A1 but remove the qualified interpretation of O1, and the capacity judgment remains NORMAL while engagement is NO_EVIDENCE. A missing observation does not erase unrelated supported information.

When O2 shows improvement with added support, a new context is recorded. The supported change is assisted performance; it does not retrospectively prove that the first difficulty had a particular cause or that bodily capacity increased. A medical forecast remains on its own horizon. A new, applicable medical restriction would revise the permitted action set without having to turn the focal capacity judgment into PROBLEM. The same person is maintained across these different objects and updates.

# 8. Time, authority and the meaning of change
HFWM separates bodily change, measurement, revision of knowledge and model evolution. Observation time, retrospective window, ingestion time and inference or confirmation time have different meanings. A late-arriving assessment can support a revised account of an earlier period without moving the biological event to the upload date. The previously confirmed report remains available, linked to a subsequent correction rather than silently overwritten.\[7\]

An algorithm change applied to the same stored signal can revise an estimate without establishing bodily change. Dependency declarations identify which current judgments require requalification. A compatible module replacement preserves the meaning and guarantees relied on by its consumers, while changed outputs still require review. If meaning, uncertainty, input assumptions or timing changes, the contract version and affected composition must be reconsidered.

Action eligibility is distinct from choosing the most attractive action. Necessary safety, consent, authority, intended-use evidence and practical-feasibility conditions must be met. A forecast of an outcome is not automatically evidence for the effect of changing an action. Plans are not executed interventions. Common semantics likewise do not authorize unrestricted sharing of personal data: shared model governance can coexist with regional data handling and purpose-limited exchange.\[7\]

A model upgrade is a further kind of change. A replacement can preserve the meaning of its output while improving precision; it can also change its input conditions, uncertainty or output construct. The former still requires review of affected downstream judgments. The latter needs an explicit contract or semantic migration rather than a silent substitution. Historical reports continue to show the source and model versions used at the time. Preserving an interface therefore does not mean freezing all future science or promising identical values for every possible input.\[7\]

Governance also determines what is shared. Common model definitions and exchange rules do not imply a global repository of unrestricted personal data. Each exchange has a person, purpose, recipient and minimal necessary content. Person-level state must remain isolated even when two individuals use the same model definition. These are architecture requirements; legal compliance, security and regional deployment need their own review and are not established by the conceptual model.

# 9. What would count as evidence for the proposal?

The primary hypothesis is that explicit demand–capacity–engagement relations improve the validity and usefulness of cross-model interpretation beyond strong alternatives given the same evidence. The comparison must not confuse additional data, expert attention or more elaborate prose with an architectural benefit. An equally expressive alternative should be allowed to succeed; the claim concerns testable behavior rather than exclusive ownership of a representation.

Evaluation should separately examine semantic conformance, measurement and construct validity, combined computation, judgment and prediction, and service outcomes or user understanding. V3 and COSMIN provide relevant measurement-validation distinctions, but neither establishes validity for the entire model network. For each intended use, the relevant evidence must be specified independently.\[17,18\]

Case labels should be adjudicated from independent assessment evidence and explicit conditions, not by agreement with HFWM’s own outputs. Test both warranted positive judgments and appropriate uncertainty. Relevant errors include unsupported transfer between tasks, treating improved assistance as improved capacity, counting returned forecasts as independent evidence, or confusing algorithm failure with personal disability. Measurement and judgment errors can be assessed before any claim of clinical benefit.

A prediction study needs person- and time-appropriate separation, endpoint definitions, calibration and distribution-shift checks. An intervention study needs evidence addressing the action effect, not only prediction accuracy. Model-replacement studies should examine affected downstream interpretations as well as individual module performance. User evaluation should ask whether people can explain what is known, what remains uncertain and why a next step is proposed. These are planned research requirements, not results reported here.

Three contrasts sharpen the research question. First, compare a record that merely places a test and a task together with one that explicitly qualifies whether the test supports that demand. Second, compare a general performance interpretation with one that requires distinct capacity and actual-process support. Third, compare indiscriminate recalculation with dependency-based requalification after a model or condition changes. A well-designed alternative may implement all three. In that event, the study should assess equivalence or differences in cost and reproducibility, not redefine success to favor the HFWM name.

The strongest evidence would include both warranted conclusions and justified restraint. A system that always returns unknown can avoid some false claims while failing the person; a system that fills every field can conceal unsupported inferences. Evaluation should therefore count missed supported conclusions, unsupported conclusions, retained valid partial results and accurately explained gaps. Expert disagreement and uncertain reference judgments should remain visible. The source’s acceptance scenarios provide design targets, but an empirical study must supply its actual inputs, versions, outcomes and independent adjudication.\[7\]

# 10. Limitations and conclusion

This manuscript specifies an architecture and interprets hypothetical cases. It does not supply calibrated rules for every capacity, demonstrate integration of arbitrary external models or establish comparative benefit. The 18/104 catalogue, the source design requirements and individual data sufficiency are distinct maturity claims. A common functional coordinate also cannot substitute for personal values, access to care, social opportunity or professional judgment.

The architecture leaves domain equations, parameters, measurement tools and comparison criteria to qualified implementations. A common interface can make assumptions inspectable without making them true. Its scientific value therefore depends on both the validity of those components and the validity of their combined use; neither a catalogue nor a consistent data structure establishes that result.

Whole-person modeling need not replace specialized human models. It can preserve their domain meanings while making explicit how qualified contributions support the same person’s demands, capacities, actual engagement and change. UOHF supplies a semantic foundation; HFWM specifies coordination, evidence and updating responsibilities; domain models supply their own science. The proposed public protocol should be judged by whether these relations produce valid, useful and reproducible interpretation—not by the breadth of its name.

# Declarations

**Study and data scope.** This manuscript presents a conceptual or technical architecture and explicitly hypothetical examples. No new participant dataset, executed benchmark, clinical evaluation or production-system test is reported. No patient-level performance or benefit is inferred from the illustrations. There is no new empirical dataset or executable implementation accompanying this preprint.

**Source basis and availability.** Public UOHF/HFWM definitions, formal framework, world-model descriptions, capacity-system materials, and the external standards and literature cited in this manuscript constitute the source basis for the paper. The explanatory figure and case identifiers are manuscript illustrations, not production objects or evidence of an implemented integration.

**Related work.** This full-length preprint develops the same UOHF/HFWM research program as the cited public framework publications. Any later journal version should identify this preprint and disclose substantive overlap to the receiving editor.

**Generative AI assistance.** ChatGPT assisted with source comparison, literature checking, drafting, language editing and preparation of the document and explanatory figure. AI-generated text and diagrams are not research evidence; responsibility for the published content remains with the named author.

# References

1\. Laubenbacher R, Mehrad B, Shmulevich I, et al. Digital twins in medicine. *Nat Comput Sci.* 2024;4:184–191. doi:10.1038/s43588-024-00607-6.

2\. Little EG, Rogova GL. Designing ontologies for higher level fusion. *Information Fusion.* 2009;10(1):70–82. doi:10.1016/j.inffus.2008.05.006.

3\. Smirnov A, Levashova T, Shilov N. Patterns for context-based knowledge fusion in decision support systems. *Information Fusion.* 2015;21:114–129. doi:10.1016/j.inffus.2013.10.010.

4\. Che L. UOHF Definition 2.1: Unified Ontology of Human Function. Version 2.1.1. Repository publication; 2026. doi:10.5281/zenodo.21630406. Author-maintained definition and version record: [Public source](https://github.com/dlehche/Unified-Ontology-Of-Human-Function/blob/main/README.md) (accessed 6 October 2026).

5\. Che L. A Formal Framework for Human Function in UOHF: Capacity, Functional Engagement, Demand-Bounded Realizability, and Evidence-Constrained Decision Support. Version 1.0. Repository preprint; 2026. doi:10.5281/zenodo.21721599. Full-text source index: [Public source](https://github.com/dlehche/Unified-Ontology-Of-Human-Function/blob/main/papers/formal-framework/UOHF_Formal_Framework_EN_V1.0.md) (accessed 6 October 2026).

6\. Che L. The Human Function World Model: Modeling the Whole Person Through Human Function Across Tasks, States, Actions, and Longitudinal Change. Version 1.0. Repository preprint; 2026. doi:10.5281/zenodo.22685308. Author-maintained model statement: [Public source](https://github.com/dlehche/Human-Function-World-Model/blob/main/WHOLE_PERSON_HUMAN_FUNCTION_WORLD_MODEL.md) (accessed 6 October 2026).

7\. Che L. Human Function World Model: Computational Architecture, Capacity Standards and Engagement Standards. Technical design manuscript. 30 September 2026.

8\. Che L. The UOHF Human Function Capacity System, Version 1.0: Unified Definitions of 18 Core and 104 Specific Human Functional Capacities. Repository publication; 2026. doi:10.5281/zenodo.21975100. Catalogue overview and source index: [Public source](https://github.com/dlehche/Unified-Ontology-Of-Human-Function/blob/main/papers/capacity-system/README.md) (accessed 6 October 2026).

9\. World Health Organization. Towards a Common Language for Functioning, Disability and Health: ICF. Geneva: WHO; 2002. pp. 2, 11–13. [Public source](https://cdn.who.int/media/docs/default-source/classification/icf/icfbeginnersguide.pdf) (accessed 6 October 2026).

10\. CellML. CellML 2.0: Normative Specification. [Public source](https://www.cellml.org/cellml/2.0) (accessed 6 October 2026).

11\. SBML. SBML Level 3 Version 1: Hierarchical Model Composition (comp) package. [Public source](https://sbml.org/documents/specifications/level-3/version-1/comp/) (accessed 6 October 2026).

12\. Modelica Association. Functional Mock-up Interface Specification. Version 3.0.2. [Public source](https://fmi-standard.org/docs/3.0.2/) (accessed 6 October 2026).

13\. World Wide Web Consortium. PROV-O: The PROV Ontology. W3C Recommendation. 30 April 2013. [Public source](https://www.w3.org/TR/2013/REC-prov-o-20130430/) (accessed 6 October 2026).

14\. The Unified Code for Units of Measure. UCUM specification. [Public source](https://ucum.org/ucum) (accessed 6 October 2026).

15\. Shahidi N, Pan M, Safaei S, et al. Hierarchical semantic composition of biosimulation models using bond graphs. *PLoS Comput Biol.* 2021;17(5):e1008859. doi:10.1371/journal.pcbi.1008859.

16\. HL7 International. FHIR Release 5, version 5.0.0: RiskAssessment. [Public source](https://hl7.org/fhir/R5/riskassessment.html) (accessed 6 October 2026).

17\. Goldsack JC, Coravos A, Bakker JP, et al. Verification, analytical validation, and clinical validation (V3): the foundation of determining fit-for-purpose for Biometric Monitoring Technologies (BioMeTs). *npj Digit Med.* 2020;3:55. doi:10.1038/s41746-020-0260-4.

18\. COSMIN. COSMIN Taxonomy of Measurement Properties. [Public source](https://www.cosmin.nl/tools/cosmin-taxonomy-measurement-properties/) (accessed 6 October 2026).

