# language-tree-priors
Sample BEAST 2 control files for Ritchie AM &amp; Ho SYW: Influence of the tree prior and sampling scale on Bayesian phylogenetic estimates of the origin times of language families.

Abbreviations used in the filenames refer to:

BDConst - Estimates dates under a Constant-rate Fossilized Birth-Death tree prior.
BDSkyline - Estimates dates under a Fossilized Birth-Death Skyline tree prior.
CoalConst - Estimates dates under a Constant-size Coalescent tree prior.
CoalSkyline - Estimates dates under a Coalescent Skyline tree prior.

BCTMC - Uses a simple Binary Continuous Time Markov Chain cognate replacement model.
BCOV - Uses a Binary Covarion cognate replacement model.
RGSM - Uses a Relaxed Gamma Site Model.
SDOLLO - Uses a Stochastic Dollo cognate replacement model (no re-evolution or reborrowing).

ascbias - Uses ascertainment bias correction (all files do this).
DivTurn - For birth-death tree priors, indicates that the tree prior uses the
         diversification-turnover parameterisation, rather than the birth-death parameterisation.

Cognate data within these files is sourced from the following publications:

Ainu - 
Lee S, and Hasegawa T. 2013. Evolution of the Ainu language in space and time. 
PLOS ONE 8:e62243. 10.1371/journal.pone.0062243.

Indo-European - 
Bouckaert R, Lemey P, Dunn M, Greenhill SJ, Alekseyenko AV, Drummond AJ, Gray RD, Suchard MA, and Atkinson QD. 2012. Mapping the origins and expansion of the Indo-European language family. Science 337:957-960. 10.1126/science.1219669.

Japonic - 
Lee S, and Hasegawa T. 2011. Bayesian phylogenetic analysis supports an agricultural origin of Japonic languages. Proceedings of the Royal Society B-Biological Sciences 278:3662-3669. 10.1098/rspb.2011.0518.
Lee S, and Hasegawa T. 2014. Oceanic barriers promote language diversification in the Japanese Islands. Journal of Evolutionary Biology 27:1905-1912. 10.1111/jeb.12442.

Semitic - 
Kitchen A, Ehret C, Assefa S, and Mulligan CJ. 2009. Bayesian phylogenetic analysis of Semitic languages identifies an Early Bronze Age origin of Semitic in the Near East. Proceedings of the Royal Society B-Biological Sciences 276:2703-2710. 10.1098/rspb.2009.0408.
