---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Please see the Publications tab for a complete list of my work.

Statistical Methodology
------

## Model-agnostic Variable Importance

It is often of interest to understand the population interplay between
the outcome and measured covariates. Variable importance is a useful
tool towards this goal. Examples include: HIV vaccine studies,
correlates of risk analyses, and identifying patients at high risk of
returning to a hospital after discharge for heart failure. I first considered inference on a model-free generalization of the commonly-used R-squared measure ([Williamson et al., 2020](https://doi.org/10.1111/biom.13392), [Feng et al., 2018](https://proceedings.mlr.press/v80/feng18a.html)). Next, I considered a general framework for inference on model-agnostic variable importance ([Williamson et al., 2021](https://doi.org/10.1080/01621459.2021.2003200)). We have further extended this framework to handle potentially correlated variables using Shapley values ([Williamson and Feng, 2020](https://proceedings.mlr.press/v119/williamson20a.html)).

## Bayesian Methods

In this work, we propose a statistical method for combining inexpensive
(but often lower-quality) estimates of relative abundance (e.g.,
collected using universal primers for the 16S rRNA gene) and higher
quality (but often expensive) estimates of absolute abundance (e.g.,
from quantitative PCR) to estimate absolute abundance of all taxa.
Crucially, our proposal accounts for differences in the efficiency of
taxon detection in the relative and absolute abundance data ([Williamson et al., 2021](https://doi.org/10.1111/biom.13503)).

## Non-inferiority Trials

In settings where it is not ethical to perform a classical
placebo-controlled trial, new interventions must be evaluated against
the standard of care. Non-inferiority trials are often used to evaluate
new interventions in this context. Here, the goal is for the
experimental intervention to be “not unacceptably worse” than the
standard of care, so that there are an increased number of viable
intervention options. A common assumption in non-inferiority trials is
that the active control population (typically receiving standard of
care) is similar to the populations in prior placebo-controlled
randomized trials. However, if characteristics in the current trial
differ from previous trials – for example, adherence to the active
control regimen is lesser or greater than planned – then the chance of a
false positive result (type I error) or a false negative result (type II
error) can be different than planned. In this work, we proposed a method
for rigorously adapting a non-inferiority trial based on observed
characteristics of the active control participants ([Hanscom et al., 2018](https://doi.org/10.1177/0962280218801134)).

Collaborative Science
------

## Infectious Diseases

### Broadly Neutralizing Antibodies

The broadly neutralizing antibody VRC01, developed by the Vaccine
Research Center of the National Institute of Allergy and Infectious
Diseases, was recently evaluated in the [Antibody Mediated
Prevention](https://ampstudy.org/) (AMP) trials. To prepare for AMP, we used data on HIV viruses from the
[Compile, Neutralize, and Tally NAb
Panels](https://www.hiv.lanl.gov/components/sequence/HIV/neutralization/main.comp)
database to (i) develop a score that performed well for
predicting whether or not an HIV virus was sensitive to neutralization
by VRC01, and (ii) to identify groups of HIV genome features that were
important in predicting neutralization sensitivity ([Magaret et al., 2019](https://doi.org/10.1371/journal.pcbi.1006952)). The latter objective will prioritize regions of the HIV-1 genome to test for differential vaccine efficacy in downstream sieve analyses. We have extended the methods used for the VRC01 analysis to combinations
of antibodies – a prevention strategy involving multiple bnAbs is likely
to be much more effective than a strategy with a single bnAb ([Williamson et al., 2021](https://doi.org/10.1093/bioinformatics/btab398)).

### Immune Correlates of Risk and Surrogate Endpoints

#### Correlates of Risk of HIV-1
While we do not yet have a broadly efficacious vaccine against HIV-1,
clinical trials of HIV-1 vaccine candidates can identify potential
correlates of risk or of protection. These correlates are measurable
signs that a person is at risk of or is protected from infection by
HIV-1, respectively. In this work, I collaborated with researchers from the [HIV Vaccine Trials
Network](https://www.hvtn.org/en.html) to analyze data from the [HVTN
505](https://www.hvtn.org/en/community/community-compass/vol19-issue1/hvtn-505-recap.html)
clinical trial. We identified three antibody features that inversely
correlated with HIV-1 infection risk ([Neidich et al., 2019](https://doi.org/10.1172/JCI126391)). This may help in designing future
HIV-1 vaccines.

#### Surrogate endpoints for cytomegalovirus disease
We used a combination of classical statistical methods and ensemble-based machine learning to assess various viral load kinetics as potential surrogate endpoints for cytomegalovirus disease after transplant. We found that mean, peak, and change in viral load over the first five weeks of treatment fulfilled the Prentice criteria for surrogacy and captured a large proportion of the treatment effect in two randomized, controlled trials ([Duke et al., 2020](https://doi.org/10.1172/JCI144960)).

### Non-vaccine HIV Prevention

Using data from the HIV Prevention Trials Network
(HPTN) 068 trial, we aimed to identify factors associated
with age-discordant partnerships (one partner greater than 5 years older
than the other) and examine the association between partner age
discordance and HIV risk in young South African women. We found that a
history of age-discordant partnerships is associated witih greater odds
of reporting HIV risk factors ([Ritchwood et al., 2016](https://doi.org/10.1097/QAI.0000000000000988)).

HPTN 063 was a clinical trial that aimed to examine potential HIV
transmissions and the frequency of bacterial sexually transmitted
infection (STI) acquisition among an international group of HIV-positive
individuals in HIV care. The long-term goal was to inform
treatment-as-prevention programs and provide ways of evaluating the
potential impact of such programs. We found that there were substantial
numbers of both estimated HIV transmissions and STIs, despite sampling
individuals in HIV care. This suggested that augmenting secondary
prevention interventions may be a means to decrease HIV incidence ([Safren et al., 2016](https://doi.org/10.7448/IAS.19.1.21096)).

## Cancer Treatment

In this work, we developed an algorithm for optimally
assigning patients to cancer treatment strategies. We leveraged data
from single-cell mass cytometry to: automatically determine
subpopulations of cells; create a nested effects model to infer gene
hierarchy based on perturbation effects due to administered drugs; and
create a scoring and ranking algorithm that identifies the minimal
number of drugs among a combination of drugs with teh maximal desired
intracellular effects ([Anchang et al., 2018](https://doi.org/10.1073/pnas.1711365115)).
