
# Integrated data-driven modeling and experimental optimization of granular hydrogel matrices


need to update this section below:
* * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * 

*This repository contains code, data, and SI Material for the paper:
C. A. Verheyen, S.G.M. Uzel, A. Kurum, E. T. Roche, J. A. Lewis (2023) Integrated data-driven modeling and experimental optimization of granular hydrogel matrices. Matter, doi.10.1098/rsif.2021.0856.*

*Citation:
Please cite C. A. Verheyen, S.G.M. Uzel, A. Kurum, E. T. Roche, J. A. Lewis (2023) Integrated data-driven modeling and experimental optimization of granular hydrogel matrices. Matter, doi.10.1098/rsif.2021.0856. when using any part of this repository or associated Zenodo archive.*

Journal article:

[![DOI](https://zenodo.org/badge/DOI/10.1098/rsif.2021.0856.svg)](https://doi.org/10.1098/rsif.2021.0856)

* * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * 

Zenodo code/data archive: 

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7506819.svg)](https://doi.org/10.5281/zenodo.7506819)



### Project abstract

Granular hydrogel matrices have emerged as promising candidates for cell encapsulation, bioprinting, and tissue engineering. However, the design and optimization of these materials remain challenging given their broad compositional and processing parameter space. Here, we combine experimentation and computation to create granular matrices composed of alginate-based bioblocks with controlled structure, rheological properties, and injectability profiles. A custom machine learning pipeline is applied after each phase of experimentation to automatically map the multidimensional input-output patterns into condensed data-driven models. These models are used to assess generalizable predictability and define high-level design rules to guide subsequent phases of development and characterization. Our integrated approach opens new avenues to understanding and controlling the behavior of complex soft materials.

![Visual overview](/data/Fig1_v2.png)
(A) The data-driven modeling paradigm leverages machine learning to build predictive frameworks directly from data itself. (A) The traditional paradigm relies on empirical exploration to optimize structures, properties, and performance of soft materials. (C-F) Our approach combines data-driven modeling with experimentation to map complex input-output relationships for granular matrices at each stage of development.

## Repository structure

### Data

#### Base datasets \[structured empirical results from each experimental phase\]

- Dataset_MicrogelFormation_and_MicrogelShape
- Dataset_Microgel_InitialSize_and_SizeEvolutionInFluids
- Dataset_PhaseSepVolumeFractionEstimation
- Dataset_CompilingAllRheology
- Dataset_PrelimFunctionalExtrusionScreening
- Dataset_FollowUp_QuantitativeExtrusion_Compiled_ExtractedValues
- Dataset_FollowUpRheologicalStudy_FittedParamsForExtrusionModeling
- Dataset_FollowUp_QuantitativeExtrusion_Compiled_ExtractedValues
- Dataset_FollowUp_QuantitativeExtrusion_Compiled_FullCurves_CondensedDownsampled

#### Final datasets \[fully processed for a given supervised ML problem\]

- Data_for_Model_Predicting_Microgel_Formation
- Data_for_Model_Predicting_Microgel_Shape
- Data_for_Model_Predicting_Microgel_Initial_Size
- Data_for_Model_Predicting_Microgel_Evolution_in_Fluids
- Data_for_Model_Predicting_PhaseSep_VolumeFraction
- Data_for_Model_Predicting_Rheo_MultiOutput_OscStressCurves
- Data_for_Model_Predicting_Rheo_MultiOutput_OscStrainCurves
- Data_for_Model_Predicting_Rheo_SingleOutput_OscYieldStress
- Data_for_Model_Predicting_Rheo_SingleOutput_OscYieldStrain
- Data_for_Model_Predicting_Rheo_SingleOutput_FlowCurves
- Data_for_Model_Predicting_Rheo_SingleOutput_RotYieldStress (supplemental only)
- Data_for_Model_Predicting_Extrusion_PreliminaryModel
- Data_for_Model_Predicting_Extrusion_FinalModel_BinaryStability
- Data_for_Model_Predicting_Extrusion_FinalModel_FullCurves

### Analysis

#### Data-driven modeling notebooks \[in Python - with full ML pipelines and results\]

- Model_Predicting_Microgel_Formation
- Model_Predicting_Microgel_Shape
- Model_Predicting_Microgel_Initial_Size
- Model_Predicting_Microgel_Evolution_in_Fluids
- Model_Predicting_PhaseSep_VolumeFraction
- Model_Predicting_Rheo_MultiOutput_OscStressCurves
- Model_Predicting_Rheo_MultiOutput_OscStrainCurves
- Model_Predicting_Rheo_SingleOutput_OscYieldStress
- Model_Predicting_Rheo_SingleOutput_OscYieldStrain
- Model_Predicting_Rheo_SingleOutput_FlowCurves
- Model_Predicting_Rheo_SingleOutput_RotYieldStress (supplemental only)
- Model_Predicting_Extrusion_PreliminaryModel
- Model_Predicting_Extrusion_FinalModel_BinaryStability
- Model_Predicting_Extrusion_FinalModel_FullCurves

#### Data-driven prediction matrices \[predicted outputs generated by the trained models\]

- Predictions_for_Model_Predicting_Bioblock_Formation
- Predictions_for_Model_Predicting_Bioblock_Shape
- Predictions_for_Model_Predicting_Bioblock_Initial_Size
- Predictions_for_Model_Predicting_Bioblock_Evolution_in_Fluids
- Predictions_for_Model_Predicting_PhaseSep_VolumeFraction
- Predictions_for_Model_Predicting_Rheo_MultiOutput_OscStressCurves
- Predictions_for_Model_Predicting_Rheo_MultiOutput_OscStrainCurves
- Predictions_for_Model_Predicting_Rheo_SingleOutput_OscYieldStress
- Predictions_for_Model_Predicting_Rheo_SingleOutput_OscYieldStrain
- Predictions_for_Model_Predicting_Rheo_SingleOutput_FlowCurves
- Predictions_for_Model_Predicting_Rheo_SingleOutput_RotYieldStress (supplemental only)
- Predictions_for_Model_Predicting_Extrusion_PreliminaryModel
- Predictions_for_Model_Predicting_Extrusion_FinalModel_BinaryStability
- Predictions_for_Model_Predicting_Extrusion_FinalModel_FullCurves
