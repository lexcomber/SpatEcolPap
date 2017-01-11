# SpatEcolPap
The code and PDF of the paper submitted to Ecological Informatics expanding on the work developed for the Spatial Ecology and Conservation conference. The data are here: https://github.com/lexcomber/SpEcolCons2016 as documented in the RMD file. 

*Spatial considerations in the analysis of biological conservation data: space is special*

Alexis Comber(1), Steve Carver(1), Carol Ximena Garzon-Lopez(2), Paul Harris(3), Duccio Rocchini(4)

1 School of Geography, University of Leeds, Leeds, LS2 9JT, UK
Email: {a.comber; s.j.carver} @leeds.ac.uk 

2 Ecology and Dynamics of Human-influenced Systems Research Unit, University of Picardie Jules Verne, FR-80037 Amiens, France.
Email: c.x.garzon@gmail.com 

3 Rothamsted Research, North Wyke, EX20 2SB, UK
Email: paul.harris@rothamsted.ac.uk

4 Research and Innovation Centre, Dpt. Biodiversity and Molecular Ecology, Fondazione Edmund Mach, 38010 S. Michele all'Adige, Italy 
Email: duccio.rocchini@fmach.it

# Abstract
Geographically Weighted Regression (GWR) as first proposed by Brunsdon et al (1996) is a commonly used approach in many local geographical and biogeographical analyses. One of the of criticisms of the use of GWR is that local models may be subject to local collinearity between variables, even when none is observed globally. As yet none of the published research describing applications of GWR has addressed this issue. This paper does so. It applies GWR to the model suggested by Coudun et al (2006) to predict the presence of *Acer campestre* and to account for any spatial non-stationarity, as observed in many statistical patterns and relationships. The analysis tests for presence of local collinearity amongst predictor variables and applies a locally compensated GWR model where it is needed. The results describe the spatial variation of coefficient estimates predicting *Acer campestre* and compensates for any local collinearity amongst variables using a local ridge term. The paper discusses the need for *geography goggles* in  analyses of spatial and in so doing it encourages explicitly spatial ways of thinking. Such considerations are increasingly relevant as more and more data have a spatial component in the form of location, for instance from GPS, and all data are collected some*where*. These suggest the need for more informed approaches for analysing space and location than provided by standard statistical models.
