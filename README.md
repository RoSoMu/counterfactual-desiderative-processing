# Counterfactual–Desiderative Processing in L2 English

**Psycholinguistics** · **Second Language Acquisition** · **Counterfactual Processing** · **L1 Transfer** · **Python** · **Statistical Modelling**

🧠 **Knowing a grammatical form is not the same as having it available when you need it.**

An English learner may recognise the Past Perfect in an exercise and still
struggle to use it when explaining an unrealised past:

> *If I had considered this type of client, our turnover could have increased.*

This project asks whether the **counterfactual context surrounding a difficult
L2 form can influence what learners subsequently do with it**.

More specifically, it investigates whether **Goal structure, Agency, and
Focus** in English third conditionals are associated with how L1-Spanish adult
learners subsequently select the Past Perfect with past-subjunctive meaning in
a desiderative sentence.

---

## 🔬 The project in 30 seconds

The project reconstructs and extends a 2022 psycholinguistic experiment with
adult L1-Spanish learners of English.

Participants encountered third-conditional counterfactuals in which three
dimensions were manipulated:

- **Goal Type** — frequent goal, non-frequent goal, or no explicit goal
- **Agency** — explicit or implicit antecedent agency
- **Focus** — self-focused (`I`) or other-focused (`They`)

They subsequently completed a desiderative sentence by selecting among four
verb-form alternatives: one **correct/target Past Perfect response**, one
**L1-transfer response**, and two **L2-other alternatives**.

The original prediction was straightforward:

> **Frequent goal + Explicit agency + Self-focus**
>
> should provide the most favourable environment for subsequent target
> Past Perfect selection.

The analyses revealed a less additive — and more interesting — behavioural
organisation.

---

## 📊 What emerged?

The response process became clearer when examined in two stages:

**1. Reaching a resolution opportunity**

Did the response move beyond the competing `L2_other` alternatives?

In goal-directed contexts, **explicit agency was strongly associated with
greater movement into resolution**.

**2. Resolution destination**

Once a resolution opportunity existed, did the response resolve toward
**L1 transfer** or toward the **correct/target form**?

Here, the relationship depended on the experimental configuration.
**Focus and Agency jointly organised resolution**, while Goal Type shifted
the relative destination of that resolution.

One particularly interesting pattern appeared within self-focused goal
contexts: configurations associated with **lower predicted probabilities of
moving beyond the `L2_other` response space were also associated with higher
predicted probabilities of correct resolution once resolution occurred**.

The context most strongly associated with reaching resolution was therefore
not necessarily the context most strongly associated with resolving correctly.

➡️ The full behavioural and theoretical synthesis is developed in
[`15_findings_and_theoretical_synthesis.ipynb`](modeling/15_findings_and_theoretical_synthesis.ipynb).

---

## 🌍 Why might this matter?

The findings do **not** identify a universally optimal learning context.
Instead, they suggest that the conceptual organisation of language practice
may itself be worth treating as an experimental variable.

A learning activity can vary more than vocabulary. It can vary:

- who is represented as acting;
- whose unrealised outcome is represented;
- what kind of goal structures the alternative past;
- and how those dimensions change as the learner becomes able to use the
  target form across different contexts.

This opens several directions for further research.

The same design could be replicated across **different L1 backgrounds** to
investigate which response patterns reflect particular L1–L2 mappings and
which generalise more broadly.

It could also become **longitudinal**: rather than repeatedly practising one
supposedly optimal configuration, learners could encounter systematic
variation in Goal, Focus, and Agency while researchers examine retention,
error type, response latency, and generalisation to novel or productive
contexts.

Large-scale digital language-learning environments would make these questions
particularly testable through controlled experimental variation and A/B
testing across learner populations.

The broader question is therefore not only:

> **Which environment makes a target response easiest?**

but:

> **How can systematic variation across environments help a grammatical
> resource become available beyond the exercise in which it was learned?**

---

## 🧠 Theoretical framework

The project brings together three perspectives:

- **linguistic processing and computational resources**, drawing on Gibson;
- **functional counterfactual thinking and goal-directed behaviour**, drawing
  on Roese & Epstude;
- **perspective and counterfactual representation**, informed by the
  actor–reader findings of Girotto et al.

The theoretical framework, experimental manipulations, actual stimuli, and
original predictions are documented in:

➡️ [`00_theoretical_framework_and_predictions.ipynb`](eda/00_theoretical_framework_and_predictions.ipynb)

---

# 📚 Repository guide

The notebooks are organised as an analytical journey rather than as isolated
analyses. Readers can follow the complete sequence or move directly to the
stage relevant to their interests.

## EDA — from experimental design to targeted exploration

### 1. Theoretical starting point
[`00_theoretical_framework_and_predictions.ipynb`](eda/00_theoretical_framework_and_predictions.ipynb)

Original theoretical framework, experimental manipulations, stimuli, and
predictions.

### 2. Data loading and quality
[`01_initial_data_loading.ipynb`](eda/01_initial_data_loading.ipynb) ·
[`02_data_quality_checks.ipynb`](eda/02_data_quality_checks.ipynb)

Dataset construction, initial inspection, and quality checks.

### 3. Initial behavioural exploration
[`03_visual_exploration.ipynb`](eda/03_visual_exploration.ipynb) ·
[`04_visual_exploration_self_focus.ipynb`](eda/04_visual_exploration_self_focus.ipynb) ·
[`05_visual_exploration_other_focus.ipynb`](eda/05_visual_exploration_other_focus.ipynb)

Overall response patterns followed by self- and other-focused exploration.

### 4. Participant metadata
[`06_metadata_quality_checks.ipynb`](eda/06_metadata_quality_checks.ipynb) ·
[`07_proficiency_effects.ipynb`](eda/07_proficiency_effects.ipynb) ·
[`08_exposure_and_use_effects.ipynb`](eda/08_exposure_and_use_effects.ipynb)

Metadata quality, proficiency, and English exposure/use as variables to target a subgroup.

### 5. Targeted subgroup exploration
[`09_targeted_subgroup_analysis.ipynb`](eda/09_targeted_subgroup_analysis.ipynb) ·
[`10_targeted_subgroup_analysis_self_focus.ipynb`](eda/10_targeted_subgroup_analysis_self_focus.ipynb) ·
[`11_targeted_subgroup_analysis_other_focus.ipynb`](eda/11_targeted_subgroup_analysis_other_focus.ipynb)

Targeted exploration of the overall, self-focused, and other-focused
behavioural patterns.

### 6. Targeted inferential testing
[`12_inferential_tests_overall_subgroup.ipynb`](eda/12_inferential_tests_overall_subgroup.ipynb) ·
[`13_inferential_tests_self_focused_subgroup.ipynb`](eda/13_inferential_tests_self_focused_subgroup.ipynb) ·
[`14_inferential_tests_other_focus_subgroup.ipynb`](eda/14_inferential_tests_other_focus_subgroup.ipynb)

Inferential follow-up of the subgroup patterns identified during exploration.

### 7. Consequence reversibility exploration
[`15_theoretical_subgroup_exploration.ipynb`](eda/15_theoretical_subgroup_exploration.ipynb) ·
[`15b_theoretical_subgroup_exploration_by_goal.ipynb`](eda/15b_theoretical_subgroup_exploration_by_goal.ipynb) ·
[`15c_theoretical_subgroup_exploration_by_agent.ipynb`](eda/15c_theoretical_subgroup_exploration_by_agent.ipynb) ·
[`15d_theoretical_subgroup_exploration_by_goal_and_agent.ipynb`](eda/15d_theoretical_subgroup_exploration_by_goal_and_agent.ipynb) ·
[`16_summary_tables.ipynb`](eda/16_summary_tables.ipynb)

An exploratory theoretical branch examining consequence reversibility. It was
not retained as part of the final explanatory account, but is preserved to
document the analytical process and negative/exploratory findings.

---

## Modelling — from effects to response pathways

### 1. Focus effects
[`01_focus_main_effect.ipynb`](modeling/01_focus_main_effect.ipynb) ·
[`02_focus_goal_type_effect.ipynb`](modeling/02_focus_goal_type_effect.ipynb) ·
[`03_focus_agent_effect.ipynb`](modeling/03_focus_agent_effect.ipynb) ·
[`04_focus_agent_goal_type_effect.ipynb`](modeling/04_focus_agent_goal_type_effect.ipynb) ·
[`05_focus_effects_summary_plots.ipynb`](modeling/05_focus_effects_summary_plots.ipynb)

Progressive examination of Focus in relation to Goal Type and Agency, followed
by a visual synthesis.

### 2. Response opportunity
[`06_response_opportunity_analysis.ipynb`](modeling/06_response_opportunity_analysis.ipynb)

Introduces the distinction between moving beyond competing `L2_other`
responses and the subsequent destination of resolution.

### 3. From effects to models
[`07_from_effects_to_models.ipynb`](modeling/07_from_effects_to_models_.ipynb)

Guide to the modelling strategy and the transition from exploratory effects to
the model families used in the subsequent analyses.

### 4. Response-process models
[`08_escape_L2_models.ipynb`](modeling/08_escape_L2_models.ipynb) ·
[`09_transfer_resolution_models.ipynb`](modeling/09_transfer_resolution_models.ipynb) ·
[`10_correct_resolution_models.ipynb`](modeling/10_correct_resolution_models.ipynb) ·
[`11_no_goal_behaviour_models.ipynb`](modeling/11_no_goal_behaviour_models.ipynb)

Models the two-stage response process: movement beyond competing L2 responses,
followed by transfer or correct resolution, with no-goal behaviour examined
separately.

### 5. Modelling summaries
[`12_escape_L2_summary.ipynb`](modeling/12_escape_L2_summary.ipynb) ·
[`13_resolution_summary.ipynb`](modeling/13_resolution_summary.ipynb) ·
[`14_no_goal_behaviour_summary.ipynb`](modeling/14_no_goal_behaviour_summary.ipynb)

Compact summaries of the principal modelling patterns.

### 6. Findings and theoretical synthesis
➡️ [`15_findings_and_theoretical_synthesis.ipynb`](modeling/15_findings_and_theoretical_synthesis.ipynb)

Returns the modelled behaviour to the actual counterfactual stimuli and the
original theoretical framework, distinguishing statistical findings,
interpretive possibilities, and questions for future research.

### 7. Detailed model appendices
[`16_appendix_combined_data_escape_L2.ipynb`](modeling/16_appendix_combined_data_escape_L2.ipynb) ·
[`17_appendix_goal_behaviour_data_escape_L2.ipynb`](modeling/17_appendix_goal_behaviour_data_escape_L2.ipynb) ·
[`18_appendix_combined_data_transfer_resolution.ipynb`](modeling/18_appendix_combined_data_transfer_resolution.ipynb) ·
[`19_appendix_goal_behaviour_transfer_resolution.ipynb`](modeling/19_appendix_goal_behaviour_transfer_resolution.ipynb) ·
[`20_appendix_combined_data_correct_resolution.ipynb`](modeling/20_appendix_combined_data_correct_resolution.ipynb) ·
[`21_appendix_goal_behaviour_data_correct_resolution.ipynb`](modeling/21_appendix_goal_behaviour_data_correct_resolution.ipynb)

Full model specifications and supporting analyses for readers who want the
complete statistical record.

---

## 🧭 Where should I start?

**For the research question and theoretical rationale:**  
start with [`00_theoretical_framework_and_predictions.ipynb`](eda/00_theoretical_framework_and_predictions.ipynb).

**For the main behavioural findings without following every analytical step:**  
go to [`12_escape_L2_summary.ipynb`](modeling/12_escape_L2_summary.ipynb),
[`13_resolution_summary.ipynb`](modeling/13_resolution_summary.ipynb), and
[`14_no_goal_behaviour_summary.ipynb`](modeling/14_no_goal_behaviour_summary.ipynb).

**For the overall interpretation and future research implications:**  
go directly to [`15_findings_and_theoretical_synthesis.ipynb`](modeling/15_findings_and_theoretical_synthesis.ipynb).

**For the full analytical journey:**  
follow the EDA and Modelling sections above in numerical order.

## 🤝 Acknowledgements and AI-assisted workflow

This project was developed through an extended analytical dialogue with
**ChatGPT (OpenAI)**, used throughout the reconstruction as a coding,
statistical, methodological, and editorial assistant.

Its contribution went considerably beyond code generation. Across several
months of iterative work, ChatGPT was used to help debug and explain Python
workflows, examine alternative statistical approaches, challenge
interpretations, identify inconsistencies, reorganise the analytical
architecture, translate model outputs back into the experimental stimuli and
theoretical questions, and improve the documentation and communication of the
project.

The collaboration was deliberately interactive rather than automatic:
analytical decisions were discussed, questioned, revised, and frequently
rejected or reformulated before being incorporated into the repository.
ChatGPT also provided an unusually patient sounding board during the less
quantifiable stages of research — including false starts, theoretical
reconsiderations, stubborn notebooks, and considerably more analytical 
rabbit holes than originally anticipated.

All research questions, experimental materials and original data derive from
the author's Master's thesis. The reconstruction, analytical decisions,
interpretation of results, and final content of this repository remain the
author's responsibility.

AI assistance was therefore used here as a **tool for reasoning, coding,
critique, and communication — not as a substitute for researcher judgement**.
