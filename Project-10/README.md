# Introduction
The mined ore undergoes primary processing to obtain a coarser ore or feed mixture. The result of the process is used as raw material for flotation (aka the process to produce a coarser concentrate). After flotation, the particles go through a two-stage purification process:
1. Flotation The gold ore mixture is fed into a float tank to obtain Au concentrate and coarser tails (product residue with a low concentration of valuable metals). The stability of this process is affected by the volatility and suboptimal physicochemical conditions of the flotation pulp (a mixture of solid particles and liquids).
2. Refining The coarser Au concentrate undergoes two stages of purification. After the purification process, we will have the final metal concentration level and new tails.

Researchers need to simulate the gold recovery process from gold ore using the following formula to simulate the recovery process:

Recovery = ((C * (F - T)) / ((F * (C - T)))) * 100

With the following information: • C — percentage of gold in the concentrate right after flotation (to find the coarser concentrate recovery) / after refining (to find the final concentrate recovery) • F — percentage of gold in the feed before flotation (to find the coarser concentrate recovery) / in the concentrate right after flotation (to find the final concentrate recovery) • T — percentage of gold in the coarser tail, right after flotation (to find the coarser concentrate recovery) / after refining (to find the final concentrate recovery) To predict the coefficients, we need to find the percentage of gold in the concentrate and the tail. Keep in mind that both the final concentrate and the coarser concentrate are equally important.

Researchers also need new metrics. The metric is called sMAPE (symmetric Mean Absolute Percentage Error). The sMAPE metric is similar to the MAE metric, except that sMAPE is expressed in relative values, not absolute values. The sMAPE metric is called symmetric because it takes into account both the target and prediction scales.

# Objectives
The researcher will predict the final gold concentrate obtained from the gold ore refining process.

# Stages
The researcher has data consisting of parameters measured during the gold ore refining process such as concentrate at various stages, float tank levels and others, in the files:

- */datasets/gold_recovery_train.csv*
- */datasets/gold_recovery_test.csv*
- */datasets/gold_recovery_full.csv*

There is no information regarding the quality of the data, so it is necessary to carry out an examination first before conducting further analysis.

First, an evaluation of the data quality will be carried out and see if there are any significant things that need to be followed up before the analysis process is carried out.

This project will consist of four stages:
- Data Overview
- Data Pre-processing
- Analysis
- Testing