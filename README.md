# Hbmass-and-PV-prediction-model
This code allows to predict total hemoglobin mass (Hbmass) and plasma volume (PV) based on a complete blood count analysis (CBC) and anthropometric data.

The variables must be carefully named and ordered as follow:
Age; Height_cm; Weight_kg; WBC_103_uL; RBC; HGB; HCT; MCV; MCH; MCHC; PLT_103_uL; RDW_SD_fL; RDW_CV_; PDW_fL; MPV_fL; P_LCR_; PCT_; NEUT_103_uL; LYMPH_103_uL; MONO_103_uL; EO_103_uL; BASO_103_uL; NEUT; LYMPH; MONO; EO; BASO; IG_103_uL; IG_; RETP; RET_106_uL; IRF.

Where: 
Age = age (years);
Height_cm = size (cM);
Weight_kg = mass (kG); 
WBC_10^3_uL	= White Blood Cell count (#*10^3/uL);
RBC	= Red Blood Cell count (#*106/uL);
HGB	= Hemoglobin concentration (g/dL);
HCT	= Hematocrit ;
MCV	= Mean Corpuscular Volume (fL);
MCH	= Mean Corpuscular Hemoglobin (pG/cell);
MCHC = Mean Corpuscular Hemoglobin Concentration (g/dL);
PLT_10^3_uL	= Platelets (#*10^3/uL);
RDW_SD_fL	= Red Blood Cell Distribution Width (standard distribution) (fL);
RDW_CV_%	= Red Blood Cell Distribution Width (coefficient of variation) (%);
PDW_fL	= Platelet distribution width (fL);
MPV_fL	= Mean platelets volume (fL);
P_LCR_%	= Platelet-large cell ratio (%);
PCT_%	= Procalcitonin (%);
NEUT#_10^3_uL	= Neutrophils count (#*10^3/uL);
LYMPH#_10^3_uL	= Lymphocytes count (#*10^3/uL);
MONO#_10^3_uL	= Monocytes count (#*10^3/uL);
EO#_10^3_uL	= Eosinophils count (#*10^3/uL);
BASO#_10^3_uL	= Basophiles count (#*10^3/uL);
NEUT%	= Neutrophils percentage (%);
LYMPH%	= Lymphocytes percentage (%);
MONO%	= Monocytes percentage (%);
EO%	= Eosinophils percentage (%);
BASO%	= Basophiles percentage (%);
IG#_10^3_uL = Immunoglobins count (#*10^3/uL);
IG_%	= Immunoglobulins percentage (%);
RETP	= Reticulocytes percentage (%);
RET#_10^6_uL	= Reticulocytes count (#*10^6/uL);
IRF	= Immature Reticulocyte Fraction (%);
