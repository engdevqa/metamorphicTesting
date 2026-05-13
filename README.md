# Metamorphic Tests

This repository contains the experimental artifacts related to the application of Metamorphic Testing in machine learning–based measuring systems under black-box evaluation conditions.

The repository supports the execution, organization, and analysis of the experiments described in the submitted manuscript, enabling reproducibility and systematic evaluation of metamorphic test cases across different operational knowledge levels.

---

## 1. Scientific Context

The experiments conducted in this repository build upon a previously published public repository containing predictive models and simulation artifacts associated with vehicular emission estimation.

The original system repository was adapted and extended to support the implementation and evaluation of metamorphic testing procedures within the context of this study.

---

## 2. System Under Test (SUT)

The System Under Test (SUT) corresponds to a collection of notebooks, predictive models, and simulations associated with vehicular emission estimation.

The system includes:

* Vehicular trip data analysis
* Predictive models for variables used in emission calculations
* Simulations involving urban mobility scenarios

The SUT serves as the basis for defining, applying, and evaluating the metamorphic relations investigated in this research.

---

## 3. Organization of Metamorphic Tests

The Metamorphic Tests were organized into progressive operational knowledge levels according to the experimental design presented in the manuscript and implemented in independent Jupyter notebooks:

* `Level_1_metamorphic_tests.ipynb`
* `Level_2_metamorphic_tests.ipynb`
* `Level_3_metamorphic_tests.ipynb`

Each notebook includes:

* Definition of metamorphic test cases
* Application of metamorphic relations
* Execution of tests over the SUT
* Collection and analysis of evaluation metrics

---

## 4. Metamorphic Test Plans

The Metamorphic Test Plans are available in the `metamorphic_test_plans/` folder and document the planning and execution strategy adopted at each operational level.

Available files:

* `Test_Plan_Level_1.md`
* `Test_Plan_Level_2.md`
* `Test_Plan_Level_3.md`

These documents provide traceability between the planned test cases and their corresponding implementations.

---

## 5. Supporting Notebooks

The repository also includes supporting notebooks associated with the original system under test.

These notebooks are used exclusively to reproduce the execution environment and predictive workflow evaluated during the experiments and do not constitute metamorphic testing artifacts themselves.

---

## 6. Experimental Results

The consolidated experimental results are available in the `results/` folder in PDF format, including:

* Generated graphs
* Quantitative metrics
* Results organized by operational level

---

## 7. Experimental Environment and Reproducibility

The dependencies and execution environment are described in:

* `requirements.txt`
* `environment.yml`

These files support independent reproduction of the experiments presented in the manuscript.

---

## 8. Research Purpose

The materials provided in this repository are intended exclusively for academic and scientific reproducibility purposes.
