# Metamorphic Tests

This repository contains the experimental artifacts related to the application of Metamorphic Testing in machine learning–based measuring systems under black-box evaluation conditions.

The repository supports the execution, organization, and analysis of the experiments described in the submitted manuscript, enabling reproducibility and systematic evaluation of metamorphic test cases across different operational knowledge levels.

---

# 1. Scientific Context

The experiments conducted in this repository build upon a previously published public repository containing pre-trained predictive models and simulation artifacts associated with vehicular emission estimation.

The original system repository was adapted and extended to support the implementation and evaluation of metamorphic testing procedures within the context of this study.

The objective of this repository is not to redesign or retrain the predictive models, but rather to evaluate their behavioral properties through metamorphic testing procedures under black-box conditions.

---

# 2. System Under Test (SUT)

The System Under Test (SUT) corresponds to a collection of notebooks, predictive models, and simulations associated with vehicular emission estimation.

The system includes:

* Vehicular trip data analysis
* Predictive models for variables used in emission calculations
* Simulations involving urban mobility scenarios

The SUT serves as the basis for defining, applying, and evaluating the metamorphic relations investigated in this research.

## Dataset Characteristics

The experimental datasets employed in this repository were derived from a previously published ML-based vehicular emission estimation study and are associated with real-world and simulated urban driving conditions.

### Dataset Summary

* Total operational records: 153,255
* Gasoline operation records: 112,964
* Ethanol operation records: 40,291
* Operational context: Urban traffic conditions
* Route length: Approximately 13 km
* Location: Natal, Brazil

The datasets include sequential operational measurements such as:

* Vehicle speed
* Vehicle acceleration
* Geographic coordinates (latitude and longitude)
* Emission-related variables

These datasets were treated as immutable experimental artifacts under black-box evaluation conditions during the metamorphic testing procedures.

---

# 3. Organization of Metamorphic Tests

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

# 4. Metamorphic Test Plans

The Metamorphic Test Plans are available in the `metamorphic_test_plans/` folder and document the planning and execution strategy adopted at each operational level.

Available files:

* `Test_Plan_Level_1.md`
* `Test_Plan_Level_2.md`
* `Test_Plan_Level_3.md`

These documents provide traceability between the planned test cases and their corresponding implementations.

---

# 5. Supporting Notebooks

The repository also includes supporting notebooks associated with the original system under test.

These notebooks are used exclusively to reproduce the execution environment and predictive workflow evaluated during the experiments and do not constitute metamorphic testing artifacts themselves.

---

# 6. Experimental Results

The consolidated experimental results are available in the `results/` folder in PDF format, including:

* Generated graphs
* Quantitative metrics
* Results organized by operational knowledge level

---

# 7. Experimental Environment

The dependencies and execution environment are described in:

* `requirements.txt`
* `environment.yml`

The experiments were designed to run in standard CPU-based environments without requiring GPU acceleration.

---

# 8. Reproducing the Experiments

To reproduce the experiments:

1. Install the required dependencies using:

   * `requirements.txt`
   * or `environment.yml`

2. Execute the notebooks corresponding to the intended operational knowledge level:

   * `Level_1_metamorphic_tests.ipynb`
   * `Level_2_metamorphic_tests.ipynb`
   * `Level_3_metamorphic_tests.ipynb`

3. Review the generated outputs and consolidated reports available in the `results/` directory.

---

# 9. Research Purpose

The materials provided in this repository are intended exclusively for academic and scientific reproducibility purposes.
