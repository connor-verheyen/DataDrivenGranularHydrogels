# Integrating experimental exploration and data-driven modeling for granular hydrogel development

### Project abstract
Granular hydrogels have emerged as promising candidate materials for a range of future biotechnologies, but their structures and behaviors remain challenging to predict or design. Here, we combine experimentation and computation to develop an alginate-based granular hydrogel system in a bottom-up, stepwise fashion. Experimentally, we explored the initial synthesis of microgel building blocks, the intermediate processing of microgels into granular hydrogels, the characterization of critical rheological properties, and the ultimate assessment of injectability in diverse functional contexts. Computationally, we developed a flexible but rigorous machine learning pipeline that was applied after each phase of experimentation to automatically map the multidimensional input-output patterns into condensed data-driven models. These models were leveraged to assess the predictability of each heterogeneous experimental process and extract high-level design insights to support our progression into subsequent phases of material development and characterization. This combined approach made it feasible to derive material-specific predictive frameworks at each step in the material development workflow, which could potentially support the design of customized granular hydrogels with user-defined structures, properties, and performance profiles for future biotechnologies. Overall, the flexible integration of data-driven modeling into experimental workflows should be broadly applicable for applied materials scientists aiming to advance their understanding and control of complex emerging material systems. 

![Visual overview](/data/Fig1_v1.png)


# Repository structure

## Data
### Base datasets (structured empirical results)
- Dataset_MicrogelFormation_and_MicrogelShape
- Dataset_Microgel_InitialSize_and_SizeEvolutionInFluids
- Dataset_PhaseSepVolumeFractionEstimation
- Dataset_CompilingAllRheology
- Dataset_PrelimFunctionalExtrusionScreening
- Dataset_FollowUp_QuantitativeExtrusion_Compiled_ExtractedValues
- Dataset_FollowUpRheologicalStudy_FittedParamsForExtrusionModeling
- Dataset_FollowUp_QuantitativeExtrusion_Compiled_ExtractedValues
- Dataset_FollowUp_QuantitativeExtrusion_Compiled_FullCurves_CondensedDownsampled

### Final datasets (fully processed for supervised ML)
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
- Data_for_Model_Predicting_Extrusion_PreliminaryModel
- Data_for_Model_Predicting_Extrusion_FinalModel_BinaryStability
- ______________________________________________________________

## Analysis
### Data-driven modeling notebooks 

### Data-driven prediction matrices 



## Add separate section for cripts and functions???????
