# shapAAR_pres
Abstract for CAA 2018

Classifying vessel shapes using automated shape extraction and unsupervised classification

Since the beginning of scientific archaeology, vessels have been classified primarily by their form. Especially since the advent of computers in archaeology, there has been a variety of pursuits to achieve a classification by means of metric measures and on a statistical basis. An example of this approach is Koch 1998, where the vessels were recorded at significant measuring points. Of course, the (subjective) selection of the measuring points is a decisive and time-consuming aspect of the procedure. Another approach involves methods in which the entire form is digitized and evaluated (Mom 2005, Chapman et al., 2006, Keogh et al., 2009). 

Our approach follows in general the second premise, but is very simple: we consider the vessels as a rotation body, and evaluate one side of the profile by transferring it into measuring points. The resulting measurement series can then easily be evaluated by common multivariate methods. Other nominal features such as e.g. rim shape or decoration can be added as additional parameters.

In this paper, we would like to present the approach and its application in different case studies (copper age ceramics of the southern Iberian Peninsula, neolithic vessels from switzerland). We apply a more conventional classification (PCA and hierarchical cluster analysis) and compare the results to the ones achieved by more modern techniques (t-SNE and HDBSCAN). By means of the proposed method and our R package, it is easily possible to process large quantities of vessel profiles and to follow development trends beyond the classical typological classification.[