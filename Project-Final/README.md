# Introduction
The Steel metallurgical plant decided to reduce electricity consumption at the steel processing stage. The researcher must build a model that predicts the steel temperature.

# Objectives
To optimize production costs by building a model that predicts the steel temperature. Therefore, we need to:

*prepare data*:
- perform EDA
- go through the process
- calculate total power
- calculate total heating time
- check features for multicollinearity
- build graphs and distributions for data visualization and determination of statistical outliers
- determine the frequency of use of a particular material for alloying. Cut off rarely used
- delete batches that do not have the target feature (outlet temperature)
- create a table of marks

*train the model*:
- Linear regression
- Decision tree (regression)
- Random forest (regression)
- XGBoost
- Fully connected neural network.

For all models, it is planned to use automatic parameter selection using GridSearchCV or RandomizedSearchCV.

RANDOM_STATE will be set to "281122".

MAE will be used as a metric to validate the model.

We split the data into two samples:
- training
- testing

We use the test sample to analyze features in terms of their relative importance to the target features for the best model.

# Stages
Steel is processed in a metal ladle with a capacity of about 100 tons. In order for the ladle to withstand high temperatures, it is lined with refractory bricks from the inside. Molten steel is poured into the ladle and heated to the desired temperature with graphite electrodes. The electrodes are mounted on the lid of the bucket.

Sulfur is removed from the alloy (desulfurization), the chemical composition is corrected by adding impurities, and samples are taken. Steel is alloyed - its composition is changed - by feeding alloy scrap from the bunker for bulk materials or wire through special equipment (English "mass").

Before the first introduction of alloying additives, the temperature of the steel is measured and its chemical analysis is performed. Then the temperature is raised for several minutes, alloying materials are added, and the alloy is purged with inert gas. Then it is stirred and measured again. This cycle is repeated until the target chemical composition and optimal melting temperature are reached.

Then the molten steel is sent to finish the metal or enters a continuous casting machine. From there, the finished product comes out in the form of a blank slab (English slab, “slab”).

#Data Description
Data obtained from Kaggle at the address https://www.kaggle.com/datasets/yuriykatser/industrial-data-from-the-ladlefurnace-unit

The data consists of several files as follows:
- data_arc.csv — electrode data
- data_bulk.csv — data related to bulk material supply (volume)
- data_bulk_time.csv — data related to bulk material supply (time)
- data_gas.csv — data related to alloy gas purge
- data_temp.csv — temperature measurement data
- data_wire.csv — data related to wire material (volume)
- data_wire_time.csv — data related to wire material (time).

In all files, the key column contains the batch number.

There can be multiple rows in a file with the same key value, these rows correspond to different processing iterations.

For orderly placement of files, a folder named '*steel*' is created in the datasets folder (*datasets/steel/*)