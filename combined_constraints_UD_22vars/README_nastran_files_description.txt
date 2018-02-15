===================================================================
NASTRAN SOL200 Master files:
===================================================================

>> test_CRM_SOL200_0_217vars
   This is the reference cruise shape model
   Analysis: -1g rigid trim case  
   Output: Trim forces/moments (test_CRM_SOL200_0_217vars.pch)

>> test_CRM_SOL200_00_217vars 
   This is the reference cruise shape model
   Analysis: -1g static loads case (with 1g rigid loads from the baseline geometry) 
   Output: grid displacements and rotations 

>> ITER_1_1g_flexaero_jigshape.bdf 
   This jig shape model is derived from the reference cruise shape model above (test_CRM_SOL200_0_217vars.bdf)
   Analysis: Flexible 1g trim analysis 
   Output: disp_1.bdf (external code)
   
>> test_CRM_SOL200_1_217vars_f0_FP1.bdf
   Analysis: Flexible trim analysis at Flight point 1  
   Output: Trim forces/moments  (test_CRM_SOL200_1_217vars_f0_FP1.pch)
           f_f0.csv (Mass and root angle of attack design response output)
           Critical element strains (from .f06)

>> test_CRM_SOL200_2_217vars_f0_FP1.bdf
   Analysis: Static loads and buckling analysis at Flight point 1  
   Output: Buckling eigenvalues
   

===================================================================
Other files:
===================================================================

>> AIC_XXX_YYY_BIN.op4
   Input AIC data 

>> CAERO1.bdf, DMI_mod.bdf
   DLM aero mesh definition
   
