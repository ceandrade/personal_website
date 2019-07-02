+++
title = "Heuristics for a Hub Location-Routing Problem"
date = 2016-01-01
publishdate = 2019-01-01
authors = ["Mauro C. Lopes", "Carlos E. Andrade", "Thiago A. Queiroz", "Mauricio G. C. Resende", "Flávio K. Miyazawa"]
publication_types = ["2"]
abstract = "We investigate a variant of the many-to-many hub location‐routing problem which consists in partitioning the set of nodes of a graph into routes containing exactly one hub each, and determining an extra route interconnecting all hubs. A variable neighborhood descent with neighborhood structures based on remove/add, swap and exchange moves nested with routing and location operations is used as a local search procedure in a multistart algorithm. We also consider a sequential version of this local search in the multistart. In addition, a biased random‐key genetic algorithm working with a local search routine, which also considers routing and location operations, is applied to the problem. To compare the heuristic solutions, we develop an integer programming formulation which is solved with a branch‐and‐cut algorithm. Capacity and path elimination constraints are added in a cutting plane fashion. The separation algorithms are based on the computation of min‐cut trees and on the connected components of a support graph. Computational experiments were conducted on several benchmark instances of routing problems and show that the heuristics are effective on medium to large‐sized instances, while the branch‐and‐cut algorithm solves small to medium sized problems to optimality. These algorithms were also compared with a commercial hybrid solver showing that the heuristics are quite competitive."
featured = false
publication = "<a href=\"https://onlinelibrary.wiley.com/journal/10970037\">*Networks*</a>"
tags = ["Hub location-routing problem", "Heuristics", "Variable neighborhood descent", "Biased random‐key genetic algorithm", "Integer formulation"]
doi = "10.1002/net.21685"
url_code = "https://github.com/ceandrade/brkga_muti_depot_multi_tsp"
scimagojr_index = "28535"
+++

