
# Dendro_R

A small repository that lists R packages used in dendrochronology or
tree-ring research. This overview might not be complete, and if you miss
anything, please add these or contact me.

<table style="width:100%;">
<colgroup>
<col style="width: 1%" />
<col style="width: 84%" />
<col style="width: 7%" />
<col style="width: 5%" />
</colgroup>
<thead>
<tr class="header">
<th>Package name</th>
<th>Description</th>
<th>Links</th>
<th>Github</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>dfoliatR</td>
<td>Tools to identify, quantify, analyze, and visualize growth
suppression events in tree rings that are often produced by insect
defoliation <span class="citation"
data-cites="guiterman2020">(Guiterman, Lynch and Axelson
2020)</span></td>
<td><a
href="https://cran.r-project.org/web/packages/dfoliatR/index.html"
class="uri">https://cran.r-project.org/web/packages/dfoliatR/index.html</a></td>
<td><a href="https://chguiterman.github.io/dfoliatR/"
class="uri">https://chguiterman.github.io/dfoliatR/</a></td>
</tr>
<tr class="even">
<td>dendroTools</td>
<td>Provides novel dendroclimatological methods, primarily used by the
Tree-ring research community. There are four core functions. The first
one is daily_response(), which finds the optimal sequence of days that
are related to one or more tree-ring proxy records. Similar function is
daily_response_seascorr(), which implements partial correlations in the
analysis of daily response functions. For the enthusiast of monthly
data, there is monthly_response() function. The last core function is
compare_methods(), which effectively compares several linear and
nonlinear regression algorithms on the task of climate reconstruction.
<span class="citation" data-cites="jevsenak2018">(Jevšenak and Levanič
2018)</span></td>
<td><a
href="https://cran.r-project.org/web/packages/dendroTools/index.html"
class="uri">https://cran.r-project.org/web/packages/dendroTools/index.html</a></td>
<td><a href="https://github.com/jernejjevsenak/dendroTools"
class="uri">https://github.com/jernejjevsenak/dendroTools</a></td>
</tr>
<tr class="odd">
<td>detrendeR</td>
<td>A Graphical User Interface (GUI) to import, save, detrend and
perform standard tree-ring analyses. The interactive detrending allows
the user to check how well the detrending curve fits each time-series
and change it when needed. <span class="citation"
data-cites="campelo2012">(Campelo, García-González and Nabais
2012)</span></td>
<td><a
href="https://cran.r-project.org/web/packages/detrendeR/index.html"
class="uri">https://cran.r-project.org/web/packages/detrendeR/index.html</a></td>
<td><a href="https://github.com/cran/detrendeR"
class="uri">https://github.com/cran/detrendeR</a> (read only)</td>
</tr>
<tr class="even">
<td>dplR</td>
<td>General package for tree-ring analyses. It is possible to perform
tree-ring analyses such as detrending, chronology building, and cross
dating. The sotware reads and writes standard file formats used in
dendrochronology. <span class="citation"
data-cites="bunn2008 bunn2010">(Bunn 2008; Bunn 2010)</span></td>
<td><a href="https://cran.r-project.org/web/packages/dplR/index.html"
class="uri">https://cran.r-project.org/web/packages/dplR/index.html</a></td>
<td><a href="https://github.com/AndyBunn/dplR"
class="uri">https://github.com/AndyBunn/dplR</a></td>
</tr>
<tr class="odd">
<td>fellingdateR</td>
<td>This R-package offers a set of functions that can assist you to
infer felling date estimates from dated tree-ring series. The presence
of (partially) preserved sapwood or waney edge allows to estimate a
range for the actual felling date, for individual series as well as for
a group of timbers. Furthermore, an additional function provides a tool
to sum sapwood probability distributions, comparable to ‘summed
probability densities’ commonly applied to sets of radiocarbon
(<sup>14</sup>C) dates.</td>
<td></td>
<td><a href="https://github.com/hanecakr/fellingDateR"
class="uri">https://github.com/hanecakr/fellingDateR</a></td>
</tr>
<tr class="even">
<td>measuRing</td>
<td>Identification of ring borders on scanned image sections from
dendrochronological samples. Processing of image reflectances to produce
gray matrices and time series of smoothed gray values. Luminance data is
plotted on segmented images for users to perform both: visual
identification of ring borders or control of automatic detection.
Routines to visually include/exclude ring borders on the R graphical
devices, or automatically detect ring borders using a linear detection
algorithm. This algorithm detects ring borders according to
positive/negative extreme values in the smoothed time-series of gray
values. Most of the in-package routines can be recursively implemented
using the multiDetect() function. <span class="citation"
data-cites="lara2015">(Lara, Bravo and Sierra 2015)</span></td>
<td><a
href="https://cran.r-project.org/web/packages/measuRing/index.html"
class="uri">https://cran.r-project.org/web/packages/measuRing/index.html</a></td>
<td></td>
</tr>
<tr class="odd">
<td>MtreeRing</td>
<td><p>A Shiny Application for Automatic Measurements of Tree-Ring
Widths on Digital Images</p>
<p>Use morphological image processing and edge detection algorithms to
automatically measure tree ring widths on digital images. Users can also
manually mark tree rings on species with complex anatomical structures.
The arcs of inner-rings and angles of successive inclined ring
boundaries are used to correct ring-width series. The package provides a
Shiny-based application, allowing R beginners to easily analyze tree
ring images and export ring-width series in standard file formats. <span
class="citation" data-cites="shi2019">(Shi et al. 2019)</span></p></td>
<td><a
href="https://cran.r-project.org/web/packages/MtreeRing/index.html"
class="uri">https://cran.r-project.org/web/packages/MtreeRing/index.html</a></td>
<td><a href="https://github.com/ropensci/MtreeRing/"
class="uri">https://github.com/ropensci/MtreeRing/</a></td>
</tr>
<tr class="even">
<td>pointRes</td>
<td>Functions to calculate and plot event and pointer years as well as
resilience indices. Designed for dendroecological applications, but also
suitable to analyze patterns in other ecological time series. <span
class="citation"
data-cites="vandermaaten-theunissen2015">(Maaten-Theunissen, Maaten and
Bouriaud 2015)</span></td>
<td><a
href="https://cran.r-project.org/web/packages/pointRes/index.html"
class="uri">https://cran.r-project.org/web/packages/pointRes/index.html</a></td>
<td><a href="https://github.com/cran/pointRes"
class="uri">https://github.com/cran/pointRes</a> (read only)</td>
</tr>
<tr class="odd">
<td>RingdateR</td>
<td>RingdateR is a graphical and statistical tool for crossdating
annually resolved time series such as tree rings or mollusc, coral and
otolith growth increments. <span class="citation"
data-cites="reynolds2021">(Reynolds, Edge and Black 2021)</span></td>
<td><a href="https://ringdater.github.io/ringdater/index.html"
class="uri">https://ringdater.github.io/ringdater/index.html</a></td>
<td><a href="https://github.com/ringdater/ringdater_pkg"
class="uri">https://github.com/ringdater/ringdater_pkg</a></td>
</tr>
<tr class="even">
<td>TRADER</td>
<td>Tree Ring Analysis of Disturbance Events in R (TRADER) package
provides only one way for disturbance reconstruction from tree-ring
data. <span class="citation" data-cites="altman2014">(Altman et al.
2014)</span></td>
<td><a href="https://cran.r-project.org/web/packages/TRADER/index.html"
class="uri">https://cran.r-project.org/web/packages/TRADER/index.html</a></td>
<td><a href="https://github.com/pavel-fibich/TRADER"
class="uri">https://github.com/pavel-fibich/TRADER</a></td>
</tr>
<tr class="odd">
<td>xRing</td>
<td>Identify and Measure Tree Rings on X-Ray Micro-Density Profiles.
This package contains functions to identify tree-ring borders based on
X-ray micro-density profiles and a Graphical User Interface (GUI) to
visualize density profiles and correct tree-ring borders. <span
class="citation" data-cites="campelo2019">(Campelo, Mayer and Grabner
2019)</span></td>
<td><a href="https://cran.r-project.org/web/packages/xRing/index.html"
class="uri">https://cran.r-project.org/web/packages/xRing/index.html</a></td>
<td><a href="https://github.com/cran/xRing"
class="uri">https://github.com/cran/xRing</a> (read only)</td>
</tr>
</tbody>
</table>

# References

<div id="refs" class="references csl-bib-body hanging-indent"
line-spacing="2">

<div id="ref-altman2014" class="csl-entry">

Altman, J, Fibich, P, Dolezal, J and Aakala, T. 2014 TRADER: A package
for tree ring analysis of disturbance events in r. *Dendrochronologia*
32(2): 107–112. DOI:
https://doi.org/[10.1016/j.dendro.2014.01.004](https://doi.org/10.1016/j.dendro.2014.01.004).

</div>

<div id="ref-bunn2008" class="csl-entry">

Bunn, AG. 2008 A dendrochronology program library in r (dplR).
*Dendrochronologia* 26(2): 115124. DOI:
https://doi.org/<https://doi.org/10.1016/j.dendro.2008.01.002>.

</div>

<div id="ref-bunn2010" class="csl-entry">

Bunn, AG. 2010 Statistical and visual crossdating in r using the dplR
library. *Dendrochronologia* 28(4): 251–258. DOI:
https://doi.org/[10.1016/j.dendro.2009.12.001](https://doi.org/10.1016/j.dendro.2009.12.001).

</div>

<div id="ref-campelo2012" class="csl-entry">

Campelo, F, García-González, I and Nabais, C. 2012 detrendeR - a
graphical user interface to process and visualize tree-ring data using
r. *Dendrochronologia* 30: 57–60. DOI:
https://doi.org/[16/j.dendro.2011.01.010](https://doi.org/16/j.dendro.2011.01.010).

</div>

<div id="ref-campelo2019" class="csl-entry">

Campelo, F, Mayer, K and Grabner, M. 2019 xRingAn R package to identify
and measure tree-ring features using X-ray microdensity profiles.
*Dendrochronologia* 53: 17–21. DOI:
https://doi.org/[10.1016/j.dendro.2018.11.002](https://doi.org/10.1016/j.dendro.2018.11.002).

</div>

<div id="ref-guiterman2020" class="csl-entry">

Guiterman, CH, Lynch, AM and Axelson, JN. 2020 dfoliatR: An R package
for detection and analysis of insect defoliation signals in tree rings.
*Dendrochronologia* 63: 125750. DOI:
https://doi.org/[10.1016/j.dendro.2020.125750](https://doi.org/10.1016/j.dendro.2020.125750).

</div>

<div id="ref-jevsenak2018" class="csl-entry">

Jevšenak, J and Levanič, T. 2018 dendroTools: R package for studying
linear and nonlinear responses between tree-rings and daily
environmental data. *Dendrochronologia* 48: 32–39. DOI:
https://doi.org/[10.1016/j.dendro.2018.01.005](https://doi.org/10.1016/j.dendro.2018.01.005).

</div>

<div id="ref-lara2015" class="csl-entry">

Lara, W, Bravo, F and Sierra, CA. 2015 measuRing: An r package to
measure tree-ring widths from scanned images. *Dendrochronologia* 34:
43–50. DOI:
https://doi.org/[10.1016/j.dendro.2015.04.002](https://doi.org/10.1016/j.dendro.2015.04.002).

</div>

<div id="ref-vandermaaten-theunissen2015" class="csl-entry">

Maaten-Theunissen, M van der, Maaten, E van der and Bouriaud, O. 2015
pointRes: An r package to analyze pointer years and components of
resilience. *Dendrochronologia* 35: 34–38. DOI:
https://doi.org/[10.1016/j.dendro.2015.05.006](https://doi.org/10.1016/j.dendro.2015.05.006).

</div>

<div id="ref-reynolds2021" class="csl-entry">

Reynolds, DJ, Edge, DC and Black, BA. 2021 RingdateR: A statistical and
graphical tool for crossdating. *Dendrochronologia* 65: 125797. DOI:
https://doi.org/[10.1016/j.dendro.2020.125797](https://doi.org/10.1016/j.dendro.2020.125797).

</div>

<div id="ref-shi2019" class="csl-entry">

Shi, J, Xiang, W, Liu, Q and Shah, S. 2019 MtreeRing: An R package with
graphical user interface for automatic measurement of tree ring widths
using image processing techniques. *Dendrochronologia* 58: 125644. DOI:
https://doi.org/[10.1016/j.dendro.2019.125644](https://doi.org/10.1016/j.dendro.2019.125644).

</div>

</div>
