# Quasar Selection within |b|&lt;5 deg with Transfer Learning

Quasars behind the Galactic plane (GPQs) are useful tools for studying the gas structure of Milky Way, and provide important astrometric references that help to improve the accuracy of astrometric data.   
  
However, due to the severe extinction and high source densities in the Galactic plane, search for GPQs has long been a ‘zone of avoidance’ for extragalactic astronomy. Expanding the GPQ samples can help sky surveys extend their probing regions to the Galactic Center, which can ensure further investigation of the nature of Galactic Plane.   
  
We build on the Transfer Learning Quasar selection method constructed by Fu et al. (2021), which applies the sample mocking method and designs a two-step binary XGBoost classification algorithm to mitigate the dataset shift caused by different probability distributions between high-b Quasars and low-b Quasars, and we improve this method in several aspects: 
  
· We build a Bootstrap Mocking method and increase the selection rate of high-b QSO and Galaxy samples to 95% and 99% respectively.   
· We remove the highly-extincted PS1 g and r bands and add UKIDSS J,H,K bands photometry to the XGBoost classification features so as to improve the selection efficiency of high redshifted Quasars.   
· We increase the pixel numbers of Healpixmap and correct the boundary outliers to smooth the prior probability distribution of Mock GPQ samples. We also apply a further color cut to remove stellar contaminants. 
  
Results give 4222 Quasar candidates within |b| < 5 deg, and this modified method is of great scientific value in boosting the Quasar selection efficiency behind dense stellar fields.
