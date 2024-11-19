## Regionalized Characterization Factors for Microplastic Emissions in Life Cycle Assessment considering Multimedia Modelling ##

#### Description
This script can be used to calculate <B>Characterization Factors</B> (CFs) for microplastic emissions in LCA for the category physical effects on biota following the MarILCA framework: https://marilca.org/<br>
<br>
This script is divided into several parts: <br>
<ul>
<li>Calculation of Fate Factors with a Fate Model adapted from SimpleBox4Plastic: https://doi.org/10.5281/zenodo.5743268  </li>
<li>Implementation of Exposure and Effect Factors for the aquatic, sedimentary and terrestrial species</li>
<li>Calculation of Characterization Factors based on 2 approaches:</li>
  <ul>
  <li>a <I>surface</I> approach indicating the fraction of species lost on a surface in PDF*m2*year/kg (endpoint level)</li>
  <li>a <I>species</I> approach quantifying the fraction of species lost in one of the three major ecosystems (marine, freshwater, terrestrial) in PAF*year/kg (midpoint level), PDF*year/kg (endpoint level) and species*year/kg (endpoint level)</li>
</ul>
</ul>
Characterisation factors can be calculated for: 
<ul>
<li>14 polymers: EPS, PP, LDPE, HDPE, PS, PHA, PA, PLA, starch blend, PBAT, PET, PVC, TRWP</li>
<li>every size of microplastic (between 1 and 5000 μm)</li>
<li>9 emission compartments: air, lake water, river water, sea water, lake water sediment, river water sediment, sea water sediment, natural soil, agricultural soil</li>
<li>8 regions: North America, Latin America, Europe, Africa & Middle East, Central Asia, Southeast Asia, Northern regions, Oceania</li>
<li>3 ecosystems: marine, freshwater, terrestrial</li>
</ul>

#### How to use?
The script will ask you:
<ul>
<li>a region to study</li>
<li>a polymer to study</li>
<li>a size to study</li>
</ul>
Answer these questions, taking care to write the answers as they appear in the code. <br>
Then scroll down to the end of the script to find the CFs in the unit of your choice. 
