# A Reproducible Comparison of Classical and Deep Learning Models for High Frequency NILM Using Harmonic Features

This repository provides the full experimental framework, code, and results
associated with the paper:

**A Reproducible Comparison of Classical and Deep Learning Models for
High Frequency NILM Using Harmonic Features**

submitted to the SBRC conference.

---

## 📌 Overview

Non Intrusive Load Monitoring (NILM) has become a key enabling
technology for smart metering and smart grid infrastructures, particularly as
high frequency electrical measurements are increasingly processed at the net-
work edge to reduce latency, communication overhead, and privacy risks. In
such distributed environments, the choice of learning models directly affects
system level properties, including inference latency, computational cost, and
scalability.
This paper presents a fully reproducible benchmark comparing classical ma-
chine learning and deep learning models for high frequency NILM, with a par-
ticular emphasis on the role of harmonic features extracted from aggregate elec-
trical measurements. Nine learning architectures are evaluated, namely Linear
Regression, k-Nearest Neighbors, Decision Trees, Random Forests, Gradient
Boosting, XGBoost, LightGBM, a Multilayer Perceptron, and a Seq2Point deep
learning model under a unified experimental pipeline explicitly designed with
edge oriented constraints in mind.
Rather than addressing supervised appliance level disaggregation, this work
investigates the contribution of high-frequency harmonic features to electrical
power modeling within smart grid monitoring scenarios. Using a large scale,
high resolution dataset and targeted ablation studies, we demonstrate that har-
monic components account for the dominant share of predictive information,
while lightweight classical models achieve performance comparable to more
complex architectures. These results highlight the practical relevance of har-
monic analysis for scalable, edge oriented energy monitoring systems.

**Keywords:*** Non Intrusive Load Monitoring; Edge Computing; Smart Metering;
Distributed Systems; High Frequency Measurements; Harmonic Analysis.

## Data

The dataset used in this study is publicly available and was obtained from the
high-frequency NILM repository maintained by [Dinar et al. 2025] The dataset can be
accessed at https://github.com/fariddinar/nilm-dataset (accessed on 20 December 2025).


---

## 📂 Repository Structure

```text
notebook/    -> Jupyter notebook with all experiments
data/        -> Instructions to obtain the dataset
figures/     -> Final figures used in the paper
paper/       -> LaTeX source of the camera-ready paper
results/     -> Tables with numerical results

