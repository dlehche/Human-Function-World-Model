# What Is a Whole Person?

**Toward an Ontological and Computational Definition for Whole-Person Modeling**

**Lei Che** · 25 October 2026 · English

> Research manuscript. A searchable Markdown text edition of the author's full manuscript. The formatted source manuscript remains the reference for table layout. The Zenodo DOI 10.5281/zenodo.23642975 has been reserved but publication is not confirmed.

Abstract
Background: Whole-person care, whole-person health, human digital twins, and patient digital twins have produced
several accounts of persons and their computational representations. The unresolved issue is not whether humans have
multiple dimensions, but whether claims about an actual person, a model’s domain coverage, cross-domain
explanations, task-specific validity, and the requirements of digital twinning are being conflated. Methods: We
conduct a targeted comparison of English- and Chinese-language literature, conceptual analysis, constructive
counterexamples, and a formal argument based on representational indistinguishability. We propose an ontological
working definition of the whole person and an auditable framework for claims about whole-person-oriented models.
Results: A whole person is the same concrete human individual whose multiple aspects cannot be arbitrarily replaced
by a single local indicator. A model’s scope and relational claims (P0/P1) must be assessed separately from its
independently demonstrated validity for particular tasks (V). Candidate requirements address identity, temporal
information, semantics, evidence, personal goals, and cross-domain inference. Counterexamples show why multi-domain data or accurate local predictions alone do not justify unrestricted claims about a person as a whole.
Conclusion: Whole-person modeling requires an explicit separation between the actual subject, finite computational
representations, and the conclusions that available evidence supports. The proposed framework is a conceptual and
methodological proposal requiring comparative validation; it is neither an international standard nor a claim that
HFWM or UOHF is the only implementation.
Keywords: whole person; whole-person computation; ontology; personal identity; human digital twin; model claims and validation;
cross-domain explanation; scope of inference; HFWM; UOHF



## 1. Introduction: Why “Whole Person” Still Needs Clarification

Contemporary science can characterize the same individual in terms of disease risk, organ-level mechanisms, motor
performance, cognition, behavioral choices, environmental exposures, and social participation. The problem is not that
these specialized bodies of knowledge lack scientific merit. Rather, it is whether conclusions that are separately valid
can jointly justify an assessment of how this person is doing now, why, and how their condition might change. Success
on a rehabilitation test does not establish that the corresponding daily activity is feasible without assistance. A
reduction in disease risk does not necessarily entail a reduction in the person’s burden of living. These statements
concern the same individual but are supported by different evidence.
The intellectual history of holistic approaches is substantial. In 1977, Engel proposed the biopsychosocial model in
Science [1]. The WHO International Classification of Functioning, Disability and Health (ICF) relates health
conditions to body functions and structures, activities, participation, and environmental factors [2]. The NIH and US
National Academies address whole-person health and individual goals [3,4]. Lin and colleagues published a
multidimensional account of human digital twins in 2024 [20], while Luo and colleagues examined definitions of
whole-person approaches across 127 Chinese- and English-language publications in 2025 [27]. Computational
precedents include the National Academies’ requirements for prediction and feedback in digital twins [23], Drummond
and Gonsard’s operational account of patient digital twins [22], and Tudor and colleagues’ assessment of 149 human
digital twin studies [25]. Accordingly, neither the multidimensionality of persons nor multi-domain human modeling
nor the importance of digital-twin evaluation is novel in itself.
The remaining question concerns what “whole” denotes when investigators claim to study a whole person. Does it
modify the actual subject, a clinical or ethical orientation, the quantity of data assembled, the architecture connecting
domains, or a claim that a particular task has been validated? None of these automatically implies the others. In
particular, a relationship between heart rate and exercise load does not by itself license the claim that a model
computes the whole person. We separate a model’s stated whole-person orientation and coverage from independent
evidence supporting task-specific claims, while requiring an explicit account of what remains outside the model.
This analysis does not adjudicate all philosophical controversies about personhood, replication of consciousness, or the
beginning and end of life. Nor does it equate human worth with computational predictability. Its domain is biomedical
and cross-domain modeling of concrete human individuals: identifying the subject, clarifying the model’s claims, and
delimiting the evidence supporting its inferences.


## 2. Methods: Targeted Literature Comparison and Formal Analysis

We searched publicly available academic databases, publishers’ sites, PubMed/PMC, institutional standards pages, and
citation networks using English- and Chinese-language terms including “whole person,” “whole-person approach,”
“whole person modeling,” “human/patient digital twin,” “virtual human twin,” “person-centered ontology,” “personal
identity,” “digital twin definition,” and “verification, validation, and uncertainty quantification.” Published studies
were preferred, while other sources were identified according to their actual publication type. We compared definitions
of the subject, stated model coverage, identity continuity, cross-domain relationships, state updates, prediction, model
categories, validation evidence, and ethical boundaries. This was a targeted conceptual review rather than an
exhaustive systematic review.
Our approach comprised four steps: (1) distinguishing a real individual, whole-person health, whole-person care,
person-indexed local models, and whole-person computation; (2) comparing existing human digital twin and whole-person modeling definitions and introducing an operational account, two scope labels (P0/P1), and an independent
validity marker (V); (3) using a general indistinguishability argument and constructive counterexamples to examine
limits of inference; and (4) proposing a procedure for future independent evaluation. UOHF and HFWM serve as
research approaches for comparison, not as independent evidence of effectiveness.


## 3. What Have Existing Studies Actually Defined?

    Research tradition                             What it already addresses                     What it does not establish
                                                   Disease cannot be explained by biological     Formal qualification criteria for all person-
    Engel’s biopsychosocial model [1]
                                                   factors alone                                 level computational models
                                                   Classification and relationships among
                                                                                                 An exhaustive account of all personal
    WHO ICF [2]                                    functioning, activities, participation, and
                                                                                                 states or personhood
                                                   environment
                                                   Understanding and promoting whole-
    NIH / National Academies whole-person
                                                   person health while recognizing personal      An ontology of the whole person as such
    health [3,4]
                                                   goals
    Systematic review of whole-person care         Multidimensional and relational features of   Equivalence of care ethics or service
    [5]                                            clinical care                                 coverage with computational adequacy
                                                   Quantitative integration of biological and    A universal ontological definition of a
    Felsky et al., Whole Person Modeling [6]
                                                   psychosocial data in mental health            whole person
                                                   Questions of personhood, diachronic           A single universally accepted
    Philosophy of personal identity [7]
                                                   identity, and identification                  philosophical resolution
                                                   Multiscale physiological mechanisms and       Automatic representation of personal
    Physiome [8]
                                                   quantitative dynamics                         values and social relations
                                                   Individual representation, information        The equivalence of a twin label or maturity
    Human digital twins [9–12]
                                                   flow, updating, and maturity assessment       score with whole-person sufficiency
    Lin et al., HDT survey [20]                    Cross-physiological, psychological,           Novelty of multi-domain modeling in this
                                                   cognitive, and behavioral HDT concepts        paper or exhaustive representation of
                                                   and architecture                              persons
    Whole-person health measurement review         Disagreement about health domains and         A definitive ontology of persons or cross-
    [21]                                           conflation of outcomes with determinants      domain model claims
    Patient digital twin definitions (2024) [22]   Criteria for individualized,                  Identity with a whole-person ontology,
                                                   multidimensional models of patients,          although model qualification is already
                                                   organs, or biological systems                 addressed
    ISO/IEC and National Academies (2023–          Terminology, physical–digital                 Automatic digital-twin qualification from a
    2024) [23,31]                                  correspondence, updating, prediction, and     whole-person-oriented architecture
                                                   feedback
    Healthcare digital twin reviews and            Multidimensional frameworks, five             Originality of model assessment itself;
    classifications [24–26]                        components, and categorization of 149         only added discriminatory value remains
                                                   studies                                       open
    East–West whole-person approaches and          Cross-language comparison and multi-          A claim that whole-person definitions or
    Research tradition                     What it already addresses                   What it does not establish
    ontology-based patient twins [27,28]   domain OWL-based patient                    cross-domain ontologies did not previously
                                           representations                             exist
    Agentic AI human digital twin review   Foundation models, agents, and dynamic      Novelty of combining language models
    (2026) [30]                            patient models in an integrated framework   with human digital twins



Directly relevant precedents include the quantitative criteria for Whole Person Modeling in mental health proposed by
Felsky and colleagues [6]; Lin and colleagues’ human digital twin framework [20]; the design conditions examined by
Lauer-Schmaltz and colleagues [9]; Zhu and Yang’s function-oriented information model [11]; Luo and colleagues’
bilingual comparison of whole-person approaches [27]; Pellegrino and colleagues’ healthcare digital-twin meta-review
[24]; Drummond and Gonsard’s classification of patient digital twins [22]; and the medical digital-twin components
discussed by Sadée and colleagues in The Lancet Digital Health [26]. Elgammal and colleagues have also proposed an
ontology-based patient digital twin framework with preliminary evaluation [28]. Thus, patient identity, cross-domain
semantics, longitudinal trajectories, model categorization, and evaluation dimensions all have established precedents.
Further precedents include the terminology of ISO/IEC 30173:2023 [31], the National Academies’ analysis of
feedback and prediction [23], Tudor and colleagues’ review of conformity to digital-twin criteria across 149 studies
[25], a cross-sector ontology-based digital twin metamodel [32], and a JAMIA rubric applied to 26 virtual human twin
studies in healthcare [12]. A review of agentic AI-driven human digital twins discusses the integration of multimodal
foundation models and clinical decision systems [30], while work on lifelong health twins has proposed event-driven
trajectory models [19]. Cross-domain aggregation and model evaluation, by themselves, are not original contributions
of this paper.


## 3.1 Definitions and Formal Frameworks That Must Be Considered

The 2024 review “Definitions and Characteristics of Patient Digital Twins Being Developed for Clinical Use”
classified 80 proposed twin systems. It operationally characterized patient digital twins as visualizable digital
counterparts of patients, organs, or biological systems that incorporate individualized, multidimensional information
and support decisions [22]. Because that work already addresses what qualifies as a twin, merely assigning models to
categories would not constitute a new methodological contribution.
The US National Academies’ 2024 report offers a more demanding general account of digital twins, emphasizing
representations of structure, context, and behavior that are dynamically updated by physical-system data, have
predictive capacity, and inform decisions [23]. ISO/IEC 30173:2023, by contrast, characterizes a digital twin in terms
of a digital representation connected to a target entity so their states can converge at an appropriate rate; simulation
and analysis are among possible capabilities, while all of the National Academies’ prediction and feedback
requirements are not mandatory elements of the ISO definition [31]. Definition 2 below concerns a candidate whole-person-oriented computational architecture; it does not automatically confer the status of a validated whole-person
digital twin. Any such designation requires separate evidence about data linkage, prediction, and feedback.
A 2025 study in npj Digital Medicine examined 149 human digital twin publications and found that only 18 (12.08%)
met the National Academies-derived criteria used in that review; only two referred to verification, validation, and
uncertainty quantification (VVUQ) [25]. A paper in The Lancet Digital Health organized medical digital twins into
five components: the patient, data connection, in-silico patient, interface, and twin synchronization [26]. These studies
already make the gap between a model’s label and its implemented capability an explicit research concern. The
proposed framework must therefore demonstrate any added discriminatory value against these precedents.
In scholarship on the whole person, Luo and colleagues synthesized 38 Chinese-language and 89 English-language
publications and identified shared themes involving multidimensionality, dynamism, capacity, and collaboration,
alongside differences in the emphases of Eastern and Western research traditions [27]. Seixas and Chung subsequently
proposed a triadic framework for whole-person health addressing ontological, epistemic, and institutional
fragmentation [29]. These works establish a substantial conceptual history without demonstrating that a single
universally accepted ontology of human persons has emerged.
The patient digital twin framework of Elgammal and colleagues uses an OWL ontology to organize physiological,
psychosocial, behavioral, and genomic information and reports expert assessment and initial piloting [28]. Singh and
colleagues further review connections among agents, multimodal foundation models, clinical decision systems, and
human digital twins [30]. The present question is therefore whether distinguishing subject, scope, use, and evidence—
and auditing these claims jointly—produces additional measurable value, rather than whether ontology-based
modeling or AI orchestration has been proposed before.


## 3.2 Two Distinct Traditions of Definition

A minimum definition of a patient digital twin may permit an organ-specific twin [22], whereas a whole-person model
raises a broader question concerning the level at which the subject is represented. This is not a defect of organ-level
modeling: an organ-specific model may have excellent predictive validity without warranting claims about cognition,
living circumstances, or unmodeled aspects of the person. Conversely, meeting the proposed scope requirements for a
whole-person-oriented architecture does not satisfy the separate dynamic and predictive criteria for a digital twin under
the National Academies’ framework [23,25].


## 4. Distinguishing Four Commonly Conflated Concepts



## 4.1 Human Being, Personhood, and Whole Person

For the biomedical purposes of this study, the subject is a concrete human individual. This is a choice of domain, not a
general philosophical verdict about all possible bearers of personhood [7]. Two different questions must be
distinguished: (a) whether the individual continues to exist through time, and (b) how records, identifiers, or biological
evidence allow an observer to determine whether two observations concern the same individual. Two database records
sharing an ID need not refer to the same person, and two different IDs need not identify different people. Memory,
speech, mobility, the expression of consciousness, and independent decision-making are not prerequisites for being a
whole person. Infants, people with profound disabilities, and people with disorders of consciousness are not excluded.
“Whole” does not mean free of disease, disability, or impairment; possessing normal capacities; displaying a fixed
psychological trait; or having every relevant fact captured in a database. At the level of the object of study, it
acknowledges the person’s multiple interconnected aspects. At the level of modeling, it requires that the scope of any
representative claim be made explicit. This usage does not settle every exceptional case in philosophical debates over
personal and biological identity.


## 4.2 Whole Person, Whole-Person Health, Whole-Person Care, and Whole-Person Model

In this paper, “whole person” refers to a stance that does not equate a concrete human individual with a local indicator.
Whole-person health concerns health-related questions about that individual, while whole-person care concerns
practices and relationships across relevant domains. A local human model addresses a bounded target or task. A
whole-person-oriented computational architecture claims an explicit, extensible, and auditable representation of
relationships across domains concerning the same person. The actual person and the computational representation are
not the same entity. A reliable kidney-function predictor may have strong local validity without becoming a whole-person model; conversely, a system labeled “whole person” gains no automatic task accuracy by adding fields.


## 4.3 Defining the Subject Is Not the Same as Qualifying the Model

Three questions must remain separate: (A) Who is the subject, and what evidence links that individual across
observations? (B) Which domains and relationships does the model actually represent and connect, and with what
boundaries? (C) Has its performance been independently validated for stated tasks, time horizons, and uses? A cannot
be decided by predictive accuracy; B cannot be decided merely by IDs or data volume; and C does not follow from the
breadth of B. Even strong answers to all three do not mean that the software reproduces the person’s entire existence.


## 5. A Working Definition of the Whole Person

Definition 1 (Whole Person). Within scientific research on concrete human individuals, a whole person is the same
individual considered in the context of life processes, bodily states, cognition and subjective experience, behavior,
history, needs, goals, and relationships with the physical, social, and cultural environment. These aspects may
constrain one another or form relevant explanatory contexts for different questions. “Whole” does not denote a human
subclass opposed to “non-whole” people, require any fixed capacity or experience, or imply that a model can exhaust
all attributes of a person. Where meaning, beliefs, or spiritual experiences are relevant, they should be considered
through the individual’s own account, a legally authorized representative, or trustworthy evidence—not inferred
directly from physiological measurements. The definition should be compared with existing whole-person care,
personal identity, and human digital twin scholarship [5,7,21,27,29].
Three distinctions follow. First, the persistence of the actual individual is different from the system’s success in linking
longitudinal records; philosophical accounts of identity disagree on relevant criteria [7]. Second, an environment is a
relational context in which a person lives and acts, not an additional organ. Likewise, subjective experiences and
personal values cannot reliably be reverse-engineered from physiological values. Third, a holistic orientation
constrains reduction and inference; it does not require every possible domain to appear in every task. Inclusion must
follow relevance and evidence rather than model labels or value preferences.
Definition 1 offers an ontological and methodological orientation, not an empirical law established by a single
experiment. “Whole person” is not a diagnostic category that excludes infants, disabled persons, or individuals unable
to express preferences. Its testable consequences concern model claims and inference discipline: whether it helps
detect evidential gaps, unsupported cross-domain extrapolation, misleading claims of comprehensiveness, and
disagreement among external reviewers.


## 5.1 Logical Status and Applicability of the Definition

Definition 1 is not a checklist of measurable traits used to determine whether a human individual is “whole”:
wholeness here is not a physiological property that some individuals possess and others lack. It instead expresses an
ontological and methodological commitment that a person cannot be adequately substituted, for all scientific purposes,
by one local measurement. It does not settle all controversies between biological individuality and philosophical
personhood, nor does it purport to state the final necessary and sufficient conditions for being human. Its implications
include transparency about model scope, continuity of reference, and constraints on cross-domain inference; the
effectiveness of these implications is a further empirical question.
Two kinds of contribution must therefore be assessed separately. Conceptually, Definition 1 may clarify the logical
distinction between the same actual human being and finite models of that being. Methodologically, Definition 2 may
improve the identification of overstated model claims through a structured and auditable declaration. Evidence
favoring the latter would not establish that the former is the only possible ontology; philosophical support for the
former would not establish predictive gains from the latter.


## 6. From the Object of Study to Computational Representation

Let P denote the concrete human individual under study, t the event time, r the time at which evidence is recorded or
becomes available, Q the family of research questions, H the time horizon, U the intended use, and D the set of
domains and relationships the model claims to cover. Let E_{≤r} denote the evidence available by recording time r;
X(P,t) the task-relevant and generally only partly observable personal state under a specified theory; and X̂ (P,t|
E_{≤r},M) a finite estimate produced by model M. Distinguish actions or interventions A, environmental context C,
observed measurements O, and knowledge state K. Event time t must not be confused with the time r at which
information becomes available. This notation is abstract; it is not a discovered universal equation for the human body
and does not imply that every aspect of a person is quantitatively measurable.
Definition 2 (Whole-Person-Oriented Computational Model). A system continuously refers to the same concrete
human subject P and specifies its questions Q, horizon H, intended uses U, domains and relationships D, evidence
sources, and identifiable unknowns. For person-level inferences that the system claims to support, it makes the
relevant joint explanations and inferential evidence inspectable; preserves the native meanings, times, and contexts of
specialized models; permits revision when new evidence arrives; and specifies how identity-linkage errors, absent
domains, and out-of-scope circumstances are handled. A single cross-domain correlation does not establish whole-person orientation. The system must also identify the person-level research questions it addresses, its implemented
cross-domain representation, and explicit coverage boundaries. Specific predictive claims about health, behavior, or
the life course require their own independent evidence.
Two independent audit dimensions should be distinguished. (I) Scope and structure: P0 denotes a bounded local or
single-domain model, or a system that merely juxtaposes data sources. P1 denotes a candidate whole-person-oriented
architecture that states person-level, multi-domain or cross-context questions and discloses inspectable relational
evidence and coverage limits. P0 and P1 are coarse labels, not an exhaustive binary taxonomy. A single physiological–
exercise relationship may still belong to a specialized local model. (II) Independent task validity (V): external
performance evidence for stated questions Q, horizons H, uses U, target populations, and baselines. Either P0 or P1
may achieve V for particular tasks. Qualification as a digital twin is assessed separately against applicable ISO/IEC
concepts of synchronization and, where appropriate, the National Academies’ requirements concerning prediction and
feedback [23,25,31].
A model claim can be recorded as Claim(M) = (P, D, Q × H × U, V). Here P states the subject and identity-linkage
rule, D specifies the domains and cross-domain relationships represented, Q × H × U identifies the questions, horizons,
and intended uses, and V records independent validation results and the population to which they apply. Validation for
one task does not extend the model’s supported domain automatically, and adding domains does not confer better
validity. This is a proposed convention for expressing model claims, not a new mathematical theorem or an adopted
international standard.


## 7. Candidate Criteria: Separating Architectural Scope From Task Evidence

    Criterion                                  Proposed assessment                           Allowable exceptions and boundaries
                                               Distinguish actual identity continuity from   Anonymized or protected IDs are
    C1. Subject anchoring (P1)                 evidence of record linkage; state identity    acceptable; matching IDs are not sufficient
                                               basis, time, and source                       proof of identity
                                               Preserve relevant distinctions among          Only task-relevant semantics are required;
    C2. Semantic distinctions (P1)             diagnosis, mechanism, capacity, action,       not all constructs must become functional
                                               outcome, and personal goals                   scores
                                                                                             An exercise–heart-rate relation supports
                                               Show a materially relevant relation for a
                                                                                             only narrow claims and neither
    C3. Cross-domain relational witness (P1)   stated task, with applicability conditions
                                                                                             comprehensive coverage nor reliable
                                               and explicit D coverage and exclusions
                                                                                             prediction
                                               Document relational direction, units, time,   Inference must be constrained when
    C4. Joint-inference entitlement (P1)       population applicability, and evidential      mappings are unsupported; correlation
                                               limits                                        alone does not establish causation
                                               Separate events, observations, late data      Real-time monitoring or comprehensive
    C5. Time and updating (P1)                 entry, knowledge revision, and actual         prediction is not required for every use;
                                               change; update estimates when relevant        cross-sectional inference is permitted
                                               Distinguish observed facts, estimates,        Preserving unknowns is epistemically
    C6. Unknowns and evidence (P1)             hypotheses, predictions, missing              appropriate, but is not the same as
                                               observations, and non-identifiable claims     successfully answering
                                               Respect preferences or lawful                 Non-action-oriented mechanistic
    C7. Preferences and governance (use-
                                               representation when actions or goals are      simulation need not invent preference
    dependent)
                                               involved; minimize data exposure              variables
                                               For declared tasks report accuracy,           P0 and P1 may both attain V on bounded
    C8. Independent task validity (V)          calibration, justified abstention,            tasks; broader coverage does not entail
                                               robustness, and resource costs                better validity



Criteria C1–C6 concern the scope and structural claims of candidate P1 systems; C7 addresses personal goals and
governance, and C8 concerns independent task validity V. Correlations between isolated variables do not, by
themselves, establish whole-person orientation. Status as a digital twin is assessed separately with reference to the
correspondence and synchronization requirements in ISO/IEC standards and, when the National Academies’
framework is adopted, its distinct conditions for prediction, feedback, and validation [23,25,31]. These are proposed
review criteria requiring independent blinded review, cross-system testing, and comparison against strong baselines.


## 7.1 Minimum Auditable Claim Record

An auditable model declaration should provide at least six types of information: (1) identification of the subject and
procedures for handling record-linkage errors; (2) person-level questions Q, horizons H, and intended uses U; (3) the
native specialized models, units, event times, and evidence sources for covered domains; (4) the type, direction,
applicability conditions, and reproducible inputs and outputs of relevant cross-domain relationships; (5) exclusions and
unknowns outside the declared coverage; and (6) when effectiveness is asserted, independent samples, comparison
baselines, accuracy, calibration, and failure cases. Completeness of this record makes claims inspectable; it does not
demonstrate comprehensive simulation or satisfaction of digital-twin technical requirements.
Reviewers may classify each item as “supported,” “absent,” or “indeterminate,” and agreement should be assessed
between at least two independent reviewers. A list of fields from multiple domains cannot substitute for a reproducible
witness of a cross-domain relationship. The procedure requires cross-institutional testing.


## 8. Formal Proposition: Why Partial Information Cannot Justify Unrestricted

Judgments
Proposition 1 (Application of Representational Indistinguishability). Consider a question q with a sufficiently specified
evaluation criterion and an answer that is determinable for contexts in a set S. Let J_q: S → Y denote the evaluation
label, and R: S → Z the representation available to a downstream algorithm. If there exist s₁, s₂ ∈ S such that R(s₁) =
R(s₂) but J_q(s₁) ≠ J_q(s₂), then no deterministic mapping g: Z → Y can correctly classify both g(R(s₁)) and g(R(s₂)).
Where experiences or values do not admit a single observable ground truth, J_q must not be arbitrarily treated as an
objective label.
Proof. Since R(s₁) = R(s₂), any deterministic g produces g(R(s₁)) = g(R(s₂)). Because J_q(s₁) and J_q(s₂) differ, at least
one response must be incorrect. Randomized or probabilistic outputs may communicate uncertainty but cannot
guarantee discrimination between situations whose relevant information is absent. This is a necessary information
condition, not a guarantee of sufficient performance: even when R(s₁) ≠ R(s₂), incorrect mechanisms, poorly calibrated
parameters, biased data, or inappropriate thresholds may produce erroneous conclusions.
Proposition 1 is an application of general representational indistinguishability, not a newly discovered information-theoretic theorem. It does not require every task to incorporate every domain and does not imply that UOHF or
HFWM is a unique solution. Judgments involving individual goals, experience, and values must respect evaluative
conditions supplied by the individual or an authorized representative rather than treating algorithmic labels as
uncontested facts. The empirical question is whether additional relevant cross-domain information or rules reduce
verifiable errors under matched-information and matched-resource comparisons.


## 9. Constructive Counterexamples: When a Part Is Mistaken for the Whole



## 9.1 Identical Medical Predictions, Different Living Conditions

Two hypothetical individuals may have identical predictions for a disease outcome while only one has verified support
at home. The decision as to whether a specified discharge plan can be followed without additional assistance may
differ; where support is unknown, further information or abstention may be warranted. The disease prediction may be
perfectly valid. The error occurs when it is transferred into a daily-living decision without the necessary contextual
evidence. This example does not establish the necessity of any particular whole-person architecture.


## 9.2 Identical Task Performance, Different Processes of Completion

Two stair-climbing trials may take the same time, although one relies on a handrail and external assistance and the
other does not. Conclusions about what was actually accomplished, and under which conditions it could be repeated,
differ. Even observed performance improvement does not establish an increase in underlying bodily capacity without
independent evidence. This distinction is relevant to UOHF’s demand–capacity–actual engagement relations, but any
added explanatory value must be compared with existing ICF distinctions, including capacity and performance.


## 9.3 Database Updates Are Not Changes in a Person’s State

An examination conducted three months earlier might be entered into a system today. What the system knows today
about the person’s past may change, but the entry date must not be interpreted as the time of a new physiological
event. Conflating knowledge updates with actual changes corrupts longitudinal state estimation.

## 9.4 Even Comprehensive Organ Coverage May Be Inadequate for a Particular Question

A multiorgan physiological simulator might accurately predict a biomarker without representing the individual’s
preferences concerning treatment burden. It can remain an excellent scientific physiological model. However, when
asked which treatment best aligns with this person’s goals, a numerically optimal physiological prediction is not
necessarily the person’s preferred option.


## 9.5 Wholeness Is Not Conditional on Ability

A person with severe cognitive or motor impairments does not lose identity or continuity of life history because of
reduced capacity. A definition requiring independent reasoning, action, or employment as prerequisites for being a
whole person would wrongly convert disease or disability into a denial of the person as the subject of inquiry.
These examples are constructive counterexamples, not measured patient observations or statistical evidence of
predictive superiority. They expose unsupported cross-domain transfer, confusion between event time and knowledge
time, and the substitution of physiological optimization for personal goals. A model connecting exercise volume with
heart rate may be an excellent exercise physiology model; that connection alone does not support claims of
comprehensive coverage of disease, nutrition, behavior, and environment.


## 9.6 Minimal Cross-Domain Links and the Limits of Wholeness Claims

Consider a system containing a single validated relationship between activity intensity and heart-rate response. It
should ordinarily be described as a specialized exercise physiology model, even though its variables span different
descriptive domains. Without inspectable person-level questions, principled inclusion criteria for other relevant
domains, and explicit coverage and exclusion statements, this relationship cannot automatically qualify the
architecture as P1. Likewise, adding data from ten domains does not yield stronger person-level conclusions unless
credible joint explanations and supporting evidence are supplied. Such boundary cases show why the interpretation of
P1 requires testing with a blinded set of negative examples.


## 10. Relationship to HFWM and the Definition of Human Function

The Unified Ontology of Human Function (UOHF) defines human function as “the body’s capacity to be appropriately
engaged to meet internal and external demands” [16]. Human function is not an exhaustive definition of a person. The
Human Function World Model (HFWM) takes the whole person as its object of inquiry, encompassing anatomy,
physiology, health, disease and medicine, nutrition, exercise, rehabilitation, cognition, emotion, psychology, behavior,
social environments, and life history. Human function is a cross-domain organizing principle of HFWM, not its entire
subject matter; neither diagnoses and treatments nor individual experiences are reduced to functional scores [14,17].
Neither Definition 1 nor Definition 2 requires other investigators to use UOHF or HFWM, nor do they establish a
proprietary certification scheme. Human digital twins spanning multiple domains [20], quantitative whole-person
models in mental health [6], function-oriented digital twin architectures [11], ontology-based patient twins [28],
lifelong health twins [19], and general-purpose AI coupled to specialized dynamical models could potentially satisfy
some or all of the proposed requirements. Comparisons with ISO and National Academies frameworks [23,31], patient
digital twin definitions [22], healthcare digital twin meta-reviews [24], and the npj Digital Medicine classifications

[25] are necessary to determine whether a joint audit adds substantive discriminatory value.
Two errors must be avoided: forcing medical entities, diseases, and individual experiences into a single “functional-capacity score”; and assuming that aggregating specialized datasets automatically provides a justified explanation of
the whole person. The testable task is to preserve domain-specific scientific computations while specifying which
integrated conclusions their evidence can support.


## 11. Evaluation Strategy: Making Whole-Person Claims Testable

An independent interdisciplinary panel should first define questions Q, horizons H, intended uses U, and permissible
coverage statements D before systems are unblinded. The evaluation set should include tasks adequately answered
within one domain; tasks genuinely requiring information across domains; cases where causal attribution must be
withheld because the mechanism is not identifiable; and conditional decisions that change with an individual’s goals or
an authorized representative’s preferences. Relevant expertise includes medicine, physiology, exercise science,
rehabilitation, nutrition, computational science, and representatives of affected individuals. Inclusion and exclusion
criteria must be public. Strong single-domain models must not be excluded merely to make HFWM appear necessary,
and subjective experiences without observable ground truth must not be assigned artificial definitive scores.
Comparators should include (A) specialized single-domain models; (B) systems that concatenate multi-domain data
for one person without joint modeling; (C) established multivariate biopsychosocial models; (D) existing human
digital twins and event-driven longitudinal health models; and (E) other systems with cross-domain relationships,
including HFWM without requiring its use. Evaluators should assess the suitability of P0/P1 and D independently
before reporting V for the declared tasks and uses. Matched-information ablation studies can remove selected
relational inferences while preserving raw observations and controlling access to professional models, compute
budgets, and human assistance. If established baselines perform equivalently, no incremental benefit of HFWM or the
proposed claim framework should be inferred.
The scope audit should report inter-rater agreement (e.g., Krippendorff’s alpha or κ when appropriate), sensitivity to
overbroad model claims, incremental discrimination beyond existing frameworks, false positives, audit costs, and
reproducibility. Validity assessment V should independently report task accuracy, calibration, justified abstention,
identity-linkage errors, event-time confusion, subgroup differences, and computational cost. Predictive evaluation
should use temporal or institutional holdout data; causal effects of interventions require separate identification
assumptions. Comparators must extend beyond the 2026 JAMIA rubric [12] to the National Academies’ framework
[23], Drummond and Gonsard’s patient twin classification [22], Tudor and colleagues’ criteria [25], and Pellegrino and
colleagues’ dimensions [24]. If no useful discrimination is added, an independent methodological advance has not
been established.
The proposed framework is falsifiable in several ways. F1: Independent reviewers cannot reliably reproduce P0/P1 and
coverage D. F2: Detection of excessive model claims does not outperform established patient or digital twin
assessment frameworks [22–25]. F3: Under matched information and resources, removing selected cross-domain
relations does not alter performance, undermining their claimed necessity for the tested tasks. F4: Validated, high-quality cross-domain models are systematically rejected. F5: A P1 architecture performs poorly in longitudinal
prediction or intervention estimation yet claims those capabilities. F6: Reviewers incorrectly infer National
Academies-style digital twin status directly from P1 or V. Negative results must be reported rather than dismissed by
changing the definition after the fact.


## 12. Ethics, Epistemic Boundaries, and the Standing of the Subject

Whole-person computation raises significant privacy and attribution risks. Identity continuity must not entail
unnecessary central exposure of identifiable personal data; data minimization, tiered authorization, and auditable
access are preferable. Predictions about subjective experience, intent, or values must not replace the person’s own
account. When direct communication is impossible, authorized representation, professional ethics, and explicit
uncertainty are essential. No prediction determines a person’s destiny or automatically justifies restricting opportunity
or autonomy.
“Whole” does not mean that a model replicates consciousness, attains the person’s moral status, or can replace the
individual. In research on digital doubles, simulated personas, and agents authorized to act on behalf of people, the
distinction between representation and represented individual carries ethical and legal significance. The aim is an
accountable scientific model, not a “second person.”


## 13. Discussion: Where Might the Contribution Lie?

Holistic medicine, whole-person health, multidomain human digital twins, function-oriented information models,
ontological representations of medical twins, and model assessment have all been studied previously [1,6,9–12,20–32].
Prior work includes patient digital twin definitions [22], the National Academies’ framework [23], healthcare digital
twin meta-reviews [24], classification of 149 publications in npj Digital Medicine [25], the five-component medical
twin architecture in The Lancet Digital Health [26], a cross-language comparison of 127 publications on whole-person
approaches [27], and ontology-driven patient models [28]. The testable contribution proposed here is narrower:
whether jointly auditing subject identity, declared person-level coverage, and the evidential entitlement for particular
conclusions—without relying on the label assigned to a model—detects additional substantive errors, reduces
unsupported inference, and improves reviewer agreement.
Second, scope and empirical validity should be treated as orthogonal dimensions rather than successive maturity
levels. A well-validated specialized model (P0 with V) is not scientifically inferior merely because it represents fewer
domains than an unvalidated cross-domain architecture (P1 without V). Nor does success on one task justify a general
claim that the entire person has been simulated. Proposition 1 establishes only that the distinctions needed to produce
different correct answers must be retained; it does not establish the necessity of cross-domain information for every
task or the uniqueness of UOHF/HFWM.
Third, standing as the subject of inquiry is independent of ability, health, or the breadth of a model’s coverage.
Individual goals may be decisive in selecting interventions, but expressed preferences do not replace objective
physiological measurements; equally, inability to express autonomous preferences does not render anyone less whole.
Research must avoid both reducing people to physiology and converting scientific prediction into unsupported
assertions about their values.
This study is a targeted comparison rather than a systematic review, and research in other languages or outside indexed
sources may have been missed. Definition 1 includes ontological and methodological commitments; it is not a final
necessary-and-sufficient account of personhood. The P0/P1 scope labels have ambiguous boundaries, and independent
validity procedures for V remain to be established. The indistinguishability proposition is general logic, not a newly
identified equation of human dynamics. Existing National Academies, ISO, and patient twin frameworks already cover
related issues. We do not yet demonstrate additional discriminatory performance, new clinical predictions, or cross-institutional model trials.


## 14. Conclusion

A whole person is neither a “perfectly healthy person” nor “a person for whom every datum has been collected.”
Definition 1 identifies the same concrete human subject and maintains that the subject’s interrelated aspects cannot be
arbitrarily replaced by one local indicator. Definition 2 requires whole-person-oriented computational models to
disclose their questions, cross-domain coverage, relational evidence, and unknowns. P0/P1 describe scope, whereas V
independently denotes validity for particular tasks. Broader domain coverage does not imply better prediction, and
whole-person orientation does not automatically meet digital twin requirements for synchronization, prediction, and
feedback [23,25,31].
The joint subject–scope–evidence framework proposed here should be tested directly against Whole Person Modeling,
whole-person health measures, patient digital twin classifications, the National Academies’ digital twin framework,
and virtual human twin evaluation schemes. Its potential benefit is to help research teams describe what their models
actually cover, which conclusions they support, and which remain unknown. Any advantage over established
assessment approaches must be established through independent reviewer agreement, detection of unsupported claims,
and comparisons on realistic cases.


## References


[1] Engel GL. The need for a new medical model: a challenge for biomedicine. Science. 1977;196:129–136.
doi:10.1126/science.847460. https://doi.org/10.1126/science.847460

[2] World Health Organization. International Classification of Functioning, Disability and Health (ICF).
https://www.who.int/classifications/international-classification-of-functioning-disability-and-health

[3] National Center for Complementary and Integrative Health (NCCIH). Whole Person Health: What It Is and Why
It’s Important. https://www.nccih.nih.gov/health/whole-person-health-what-it-is-and-why-its-important

[4] National Academies of Sciences, Engineering, and Medicine. Achieving Whole Health: A New Approach for
Veterans and the Nation. National Academies Press; 2023. https://www.ncbi.nlm.nih.gov/books/NBK591730/

[5] Thomas H, Mitchell G, Rich J, Best M. Definition of whole person care in general practice in the English language
literature: a systematic review. BMJ Open. 2018;8:e023758. doi:10.1136/bmjopen-2018-023758.

[6] Felsky D, Cannitelli A, Pipitone J. Whole Person Modeling: a transdisciplinary approach to mental health research.
Discover Mental Health. 2023;3:16. doi:10.1007/s44192-023-00041-6.

[7] Olson ET. Personal Identity. Stanford Encyclopedia of Philosophy. Substantive revision 30 Jun 2023.
https://plato.stanford.edu/entries/identity-personal/

[8] International Union of Physiological Sciences (IUPS). The Physiome Project.
https://www.iups.org/activities/physiome-project

[9] Lauer-Schmaltz MW, Cash P, Hansen JP, Maier A. Towards the Human Digital Twin: Definition and Design—A
Survey. arXiv:2402.07922; 2024. doi:10.48550/arXiv.2402.07922.

[10] Gaffinet B, Al Haj Ali J, Naudet Y, Panetto H. Human Digital Twins: A systematic literature review and concept
disambiguation for Industry 5.0. Computers in Industry. 2025;166:104230. doi:10.1016/j.compind.2024.104230.
https://doi.org/10.1016/j.compind.2024.104230

[11] Zhu E, Yang S. Towards human digital twin: Reviewing human modelling and simulation. Journal of Industrial
Information Integration. 2025;48:100975. doi:10.1016/j.jii.2025.100975.

[12] Krishnamurthi V, Edirisinghe R, John SE, Wickramasinghe N, Plebanski M. Designing evaluation rubrics for the
development of virtual human twins in healthcare. J Am Med Inform Assoc. Published online 19 October 2026.
doi:10.1093/jamia/ocag174. https://doi.org/10.1093/jamia/ocag174

[13] National Institutes of Health. Digital Twins and/or Synthetic Data Population Modeling for Whole-Person Health
to Mitigate Chronic Disease Disparities Grand Challenge. Launched Sep 2026. https://www.nih.gov/challenges/digital-twins-andor-synthetic-data-population-modeling-whole-person-health-mitigate-chronic-disease-disparities-grand-challenge

[14] Che L. Modeling the Whole Person. 2026.

[15] Che L. Human-Function Relations as Necessary Conditions for Whole-Person Judgment. 2026.

[16] Che L. Unified Ontology of Human Function: Definition. 2026. doi:10.5281/zenodo.21630406.

[17] Che L. Human Function World Model. 2026. doi:10.5281/zenodo.22685308.

[18] Tang C, Yi W, Occhipinti E, Dai Y, Gao S, Occhipinti LG. A roadmap for the development of human body
digital twins. Nature Reviews Electrical Engineering. 2024;1:199–207. doi:10.1038/s44287-024-00025-w.

[19] Jiang J, Yates S, Chong J, Brooks R, Lawson A, Qin Y, Gao L. LifeLong Digital Twin: A Unified Modeling
Paradigm and Agent Harness for Event-Driven Lifelong Health State Trajectories. arXiv:2610.05566; 2026.

[20] Lin Y, Chen L, Ali A, et al. Human digital twin: a survey. Journal of Cloud Computing. 2024;13:131.
doi:10.1186/s13677-024-00691-z. https://doi.org/10.1186/s13677-024-00691-z

[21] DiGuiseppi G, Rodriguez A, Qureshi N, et al. Measuring Whole Person Health: A Scoping Review. Journal of
Integrative and Complementary Medicine. 2025;31(8):684–704. doi:10.1089/jicm.2024.0817.
https://doi.org/10.1089/jicm.2024.0817

[22] Drummond D, Gonsard A. Definitions and Characteristics of Patient Digital Twins Being Developed for Clinical
Use: Scoping Review. J Med Internet Res. 2024;26:e58504. doi:10.2196/58504. https://doi.org/10.2196/58504

[23] National Academies of Sciences, Engineering, and Medicine. Foundational Research Gaps and Future Directions
for Digital Twins. Washington, DC: National Academies Press; 2024. doi:10.17226/26894.
https://doi.org/10.17226/26894

[24] Pellegrino G, Gervasi M, Angelelli M, Corallo A. A Conceptual Framework for Digital Twin in Healthcare:
Evidence from a Systematic Meta-Review. Information Systems Frontiers. 2025;27:7–32. doi:10.1007/s10796-024-
10536-4.

[25] Tudor BH, Shargo R, Gray GM, et al. A scoping review of human digital twins in healthcare applications and
usage patterns. npj Digital Medicine. 2025;8:587. doi:10.1038/s41746-025-01910-w.

[26] Sadée C, Testa S, Barba T, et al. Medical digital twins: enabling precision medicine and medical artificial
intelligence. Lancet Digital Health. 2025;7(7):100864. doi:10.1016/j.landig.2025.02.004.

[27] Luo M, Liu K, Hong S. East Meets West: A Whole-Person Approach in Integrated Care. Int J Integr Care.
2025;25(2):1. doi:10.5334/ijic.9003.

[28] Elgammal A, Krämer BJ, Papazoglou MP, Raheem M. A Semantic Framework for Patient Digital Twins in
Chronic Care. arXiv:2510.09134; 2025.

[29] Seixas AA, Chung DP. Reintegrating the Human in Health: A Triadic Blueprint for Whole-Person Care in the
Age of AI. Int J Environ Res Public Health. 2026;23(4):426. doi:10.3390/ijerph23040426.

[30] Singh A, Bajpai B, Arif M. Agentic AI-driven human digital twins for personalized healthcare: a comprehensive
survey. Discover Computer Vision. 2026;1:4. doi:10.1007/s44584-026-00004-x.

[31] ISO/IEC. ISO/IEC 30173:2023. Digital twin — Concepts and terminology. 2023.
https://www.iso.org/standard/81442.html

[32] Araghi SN, Liu Z, Sarkar A, Louge T, Karray MH. Digital Twin’s Anatomy: A Cross-Sector Framework With
Healthcare Validation. IEEE Access. 2025;13:21306–21334. doi:10.1109/ACCESS.2025.3528736.


## Appendix: Proposed Comparative Evaluation Tasks

Each scenario should specify the source of ground truth or evaluation criteria, event timing, available evidence, and
appropriate rules for abstention. Synthetic scenarios can test logical consistency but cannot replace studies involving
real individuals.
A1. Identity continuity: Can a system avoid conflating different individuals after records are moved or identifiers are
remapped?
A2. Observation time: When a historical record is entered today, does the system incorrectly infer a new physiological
change today?
A3. Context variation: With an unchanged bodily state but different environments or assistance, does the system adjust
its conclusions appropriately?
A4. Explanatory identifiability: When distinct mechanisms can generate the same observation, does the system retain
plausible alternative explanations?
A5. Medicine and personal goals: With an unchanged medical prediction, do recommendations change appropriately
when the person’s goals or support conditions change?
A6. Non-exclusivity: Can HFWM, existing human digital twins, and general-purpose AI paired with professional
models use equivalent facts and semantics? When answers under the same information are equally correct, is
exclusivity avoided?
A7. Disability and subjecthood: Does the system preserve the person’s identity and lawful governance boundaries in
severe disability or where preferences cannot be directly expressed?
A8. Preventing local-model overclaiming: Does a validated kidney predictor remain a local model rather than
automatically becoming P1? Is an exercise–heart-rate connection prevented from being described as a comprehensive
model?
A9. Cross-domain ablation: Holding raw observations fixed, do conclusions change—and improve—when biological–
environmental or medical–goal relations are represented?
A10. Strong baseline equivalence: Can existing virtual human twin models, ICF workflows, and general-purpose AI
with professional models use equivalent information? When performance is equivalent, is incremental value left
unproven?
