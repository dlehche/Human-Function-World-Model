# From Multimodal Sensing to Warranted Whole-Person Inference / 从多模态感知到有依据的完整人推断

## A Human-Function-Based Measurement-to-Claim Specification and Falsifiable Validation Protocol

**Author / 作者:** CHE, LEI / Lei Che / 车雷  
**ORCID:** [0009-0001-8143-1675](https://orcid.org/0009-0001-8143-1675)  
**Affiliation / 机构:** MoveTips Technology (Beijing) Co., Ltd. / 木梯科技（北京）有限公司  
**Manuscript date / 稿件日期:** 4 November 2026 (from supplied English and Chinese manuscripts; not independently verified Zenodo deposition date)  
**Resource type / 类型:** Methods and falsifiable prospective validation protocol / 计算方法及可反驳的前瞻性验证方案  
**Zenodo DOI:** [10.5281/zenodo.23936454](https://doi.org/10.5281/zenodo.23936454)  
**Archived record / 存档记录:** [https://zenodo.org/records/23936454](https://zenodo.org/records/23936454)  
**Publication status / 状态:** Author-identified Zenodo preprint; not represented as peer reviewed or empirically validated  
**License / 版权说明:** HFWM repository documentation defaults to CC BY-NC 4.0; the license displayed on the deposited Zenodo record was not independently accessible and should be confirmed there before relying on it for reuse.  
**Source provenance / 来源:** The author-provided bilingual Word manuscripts titled `HFWM_Multimodal_Sensing_to_Warranted_Inference_EN.docx` and `HFWM_从多模态感知到有依据的完整人推断_中文.docx`; this README is an explanatory index, not a byte-for-byte reproduction of the archived record.

## Research question / 研究问题

A technically valid device-derived measure **does not automatically warrant a claim about a specific person's available bodily capacity, actual functional engagement, health state, or response to an internal/external demand**.

For one continuing person and a specified question, can explicit qualification of the **measurement-to-claim transfer** reduce unwarranted decisive judgments **without sacrificing independently supported affirmative and negative conclusions**, compared with equally informed alternatives?

针对同一个人的特定需求与状态问题，传感器测量即使技术有效，也不自动成为其身体能力、实际功能调用或健康状态的充分证据。本研究检验：明确规定**从测量到个体命题的证据资格**，能否在不丢失有依据的肯定与否定结论的情况下，减少无依据的确定性判断？

## Proposed method / 拟议方法

1. **Typed evidence objects / 类型化证据对象.** Distinguish `Observation`, derived `Measure`, `ConstructBridge`, `EvidenceRoute` and person-specific `Claim`. Retain subject, protocol, device, timing, sampling/availability, quality, uncertainty, derivation and source dependencies.
2. **Three per-route qualification gates / 按证据路径检查三道资格门.** G1 tests measurement validity; G2 tests construct and inferential relevance; G3 tests applicability to the named person, time, demand and intended use. A qualified route is admissible evidence, **not proof that the claim is true**. Failure of one route does not invalidate unrelated qualified routes.
3. **Identifiability of capacity and engagement / 能力及实际调用可辨识性.** Do not infer an unobserved bodily process from task completion, a wearable proxy, or an ICF qualifier alone. Demand independent, question-appropriate reference evidence where feasible; otherwise retain alternatives or unresolved status. A separate capacity assessment is not an automatic prerequisite for every directly process-supported engagement claim.
4. **Separate event and knowledge clocks / 双时间轴.** Distinguish actual bodily event time from evidence availability time; late records, device firmware changes, sampling variation and real bodily changes must not be conflated.
5. **Independent prospective validation / 独立前瞻性验证设计.** Formal constructed cases test whether the specification behaves as declared. Separate real-person studies with independent construct references, blinded adjudication and information/annotation-matched strong baselines are required to test empirical judgment quality.

## Falsifiable comparative protocol / 可反驳比较方案

- **Comparator families:** validated sensor/clinical-measurement approaches; context- and provenance-aware inference; ontology-aware methods; equally expressive generic state/rules engines; proposed human-function-qualified system.
- **Fair inputs:** the same permissible raw records, measurement quality information, observation regime and cutoff, relevant context, expert knowledge opportunities, and comparable resource/annotation budgets.
- **Claim outcomes:** warranted affirmative retention (`SCR`), warranted negative/refutative retention (`RCR`), unwarranted decisive responses (`UDR`) and decisive-claim coverage, reported jointly. Match coverage and predefine noninferiority constraints rather than rewarding abstention or automatic rejection.
- **Evaluation layers:** finite synthetic/constructed rule-conformance cases **versus** independent real-person construct validation. The former cannot substitute for the latter.
- **Report the null:** a generic engine with equivalent knowledge may yield the same judgments. Failure of superiority or of prespecified retention requirements must be reported as nonachievement, not rewritten as `NOT_ESTIMABLE` when adequate data exist.

## Prior art and boundaries / 既有研究与科学边界

Device verification, analytical/clinical validation and fit-for-purpose digital measures (V3/V3+; FDA), interoperable observation/provenance resources (FHIR), ICF capacity/performance, and clinician-facing wearable interpretation are **prior art**, not inventions claimed for HFWM. The candidate increment is a **question-scoped, executable, falsifiable relation between validated measurements and particular person-level human-function claims**.

**Not reported in this publication / 本文未报告：** a new human-participant study, independently validated actual-engagement measurements, a completed clinical adjudication, a production HFWM implementation of this specific interface, demonstrated predictive superiority, causal treatment effects or improvements in health disparities. NIH SCHARE is an application context, not a statement of prize eligibility or completed challenge work.

## Relationship to existing program / 与既有成果的关系

- **UOHF:** The authoritative definition, human-function semantics and governed capacity coordinate remain in the [UOHF repository](https://github.com/dlehche/Unified-Ontology-Of-Human-Function). This is **not** a UOHF ontology revision.
- **HFWM framework:** [Canonical HFWM V1.0](https://doi.org/10.5281/zenodo.22685308) remains the root computational architecture. This is **not** HFWM V2.0.
- **Computational relations:** [DOI 10.5281/zenodo.23922582](https://doi.org/10.5281/zenodo.23922582) addresses broader cross-disciplinary qualified relation specifications.
- **Temporal understanding and prediction:** [DOI 10.5281/zenodo.23934150](https://doi.org/10.5281/zenodo.23934150) addresses present-state interpretation and future temporal inference under evidence cutoffs.
- **This focused preprint:** [DOI 10.5281/zenodo.23936454](https://doi.org/10.5281/zenodo.23936454) is limited to the **sensor measurement-to-person-claim transfer problem** and proposed independent validation.

The supplied English and Chinese manuscripts are **two language editions of one study**, not two independent results or separate Zenodo publications.

## Citation / 引用

Che, Lei (2026). *From Multimodal Sensing to Warranted Whole-Person Inference: A Human-Function-Based Measurement-to-Claim Specification and Falsifiable Validation Protocol*. Methods and prospective validation protocol preprint. Zenodo. https://doi.org/10.5281/zenodo.23936454

See [paper-specific citation metadata](CITATION.cff), [HFWM papers index](../README.md), [publication registry](../../PUBLICATIONS.json), and [rights and reuse](../../RIGHTS_AND_REUSE.md). The repository-root `CITATION.cff` must continue to cite canonical HFWM V1.0.
