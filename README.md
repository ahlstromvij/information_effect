# Modeling information effects in R: <br>A step-by-step guide

Kristoffer Ahlstrom-Vij  
Birkbeck, University of London

In politics like elsewhere, what we know matters for what we want. That's why political scientists, rightly, are concerned with studying what voters know, and what difference it would make had they known  more. The former question has been extensively investigated in the literature on public ignorance -- as it turns out, most of us know very little when it comes to politically relevant matters. The latter (what difference knowledge makes in politics) has been studied in the literature under the heading of 'information effects'.

The information effects literature makes clear that knowledge does matter for politics, and can in some cases even change the electoral outcome. But how does information effects modeling work in practice? That's the question this guide is looking to answer. It walks the reader through a complete pipeline from constructing a knowledge scale from a set of knowledge items to modeling the relevant effects, using functions written in the R programming language -- a free, open source language for statistical computing -- that can be re-used by others interested in information effects modeling on their own particular data sets.

The functions and their outputs are illustrated by way of British Election Study data [@bes-17], to estimate what difference information would make to anti-immigration sentiments. Since all functions are written with the ambition that they should be of use to others wishing to model information effects on their own data sets, if anyone spots any problems or has suggestions for improvements, please contact me on <k.ahlstrom-vij@bbk.ac.uk>.
