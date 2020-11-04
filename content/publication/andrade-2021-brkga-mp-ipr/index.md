+++
title = "The Multi-Parent Biased Random-Key Genetic Algorithm with Implicit Path-Relinking and its real-world applications"
date = 2021-02-16
publishdate = 2019-11-22
authors = ["Carlos E. Andrade", "Rodrigo F. Toso", "José F. Gonçalves", "Mauricio G.C. Resende"]
publication_types = ["2"]
abstract = "In this paper, we present the Multi-Parent Biased Random-Key Genetic Algorithm with Implicit Path-Relinking (BRKGA-MP-IPR), a variant of the Biased Random-Key Genetic Algorithm that employs multiple (biased) parents to generate offspring instead of the usual two, and is hybridized with a novel, implicit path-relinking local search procedure. By operating over the standard unit hypercube, such path-relinking mechanism leverages the population representation of the BRKGA and thus provides complete independence between the local search procedure and the problem definition and implementation. This approach contrasts with traditional path-relinking procedures that are tied to the problem structure. Having both BRKGA and IPR operate over the same solution space not only makes the intensification/diversification paradigm more natural but also greatly simplifies the development effort from the perspective of the practitioner, as one only needs to develop a decoder to map unit random-key vectors to the solution space of the problem on hand. Apart from such key benefits, extensive computational experiments solving real-world problems, such as over-the-air software upgrade scheduling, network design problems, and combinatorial auctions, show that the BRKGA-MP-IPR offers performance benefits over the standard BRKGA as well as the BRKGA with multiple parents."
featured = true
publication = "<a href=\"https://www.sciencedirect.com/journal/european-journal-of-operational-research\">*European Journal of Operational Research*</a>"
tags = ["Genetic Algorithms", "Path-relinking algorithms", "Hybrid heuristics"]
doi = "10.1016/j.ejor.2019.11.037"
scimagojr_index = "22489"
url_code1 = "https://github.com/ceandrade/brkga_mp_ipr_cpp"
url_code2 = "https://github.com/ceandrade/brkga_mp_ipr_julia"
url_code3= "https://github.com/ceandrade/brkga_mp_ipr_python"
+++

