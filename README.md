# Updated ELMv1

This package contains modified ELMv1-ECA codes associated with the paper below:

Tao, J., Zhu, Q., Riley, W. J., and Neumann, R. B.: Improved ELMv1-ECA Simulations of Zero-Curtain Periods and Cold-season CH4 and CO2 Emissions at Alaskan Arctic Tundra Sites, The Cryosphere, https://doi.org/10.5194/tc-15-5281-2021, 2021.

To use the updated ELMv1 (i.e., ELMv1a and ELMv1b), please download E3SM (https://github.com/E3SM-Project/E3SM) first, then copy the modified codes included in this package to /SourceMods/src.clm/ under the case script folder, and then rebuild the model.

For example, to use ELMv1b:

cd $CASE_NAME

cp $CODE_PATH/CH4Mod_ELMv1b.F90 ./SourceMods/src.clm/CH4Mod.F90

cp $CODE_PATH/DecompCascadeBGCMod_ELMv1b.F90 ./SourceMods/src.clm/DecompCascadeBGCMod.F90

cp $CODE_PATH/SoilTemperatureMod.F90 ./SourceMods/src.clm/


By Jing Tao (jingtao@lbl.gov) (Last updated on October 12, 2021.)
