+++
title = "Scheduling software updates for connected cars with limited availability"
date = 2019-07-01
publishdate = 2019-07-01
authors = ["Carlos E. Andrade", "Simon D. Byers", "Vijay Gopalakrishnan", "Emir Halepovic", "David J. Poole", "Lien K. Tran", "Christopher T. Volinsky"]
publication_types = ["2"]
abstract = "The current and the new generation of Internet of Things (IoT) devices present several challenges, among them the software update of legacy and new devices using wireless connections. In this paper, we study a problem of scheduling massive Firmware-Over-The-Air updates for millions of connected cars.  We model this problem as a new generic problem called  Time- and Machine-Dependent Scheduling Problem (TMDSP) that resembles project scheduling problems with variable-intensity activities.  In the TMDSP, jobs, machine utilization, and production rates vary over time. In each period, a given job can be executed by a subset of machines with different capacities and production rates. The objective is to deploy a feasible schedule with minimum total completion time.  We explore solving the problem using several approaches among than Biased Random-Key Genetic Algorithm (BRKGA), Iterated Local Search (ILS), Simulating Annealing (SA), two variations of Tabu Search (TB), and traditional genetic algorithms (TGA), in addition to a Mixed Integer Programming (MIP) model.  We test the proposed approaches on a synthetic benchmark and very large real instances in IoT space. While using a commercial solver and the MIP model, we are able to solve only a few real instances (with, at most, 1,976 cars and 9,116 sectors); on the other hand, BRKGA presents significantly better results when compared to ILS, MIP solver and a simple multi-start heuristic."
featured = false
publication = "<a href=\"https://www.journals.elsevier.com/applied-soft-computing\">*Applied Soft Computing*</a>"
tags = ["Connected Cars", "Internet of Things", "IoT", "Scheduling", "Time- and Machine-Dependent Scheduling", "Biased random-key genetic algorithm"]
doi = "10.1016/j.asoc.2019.105575"
scimagojr_index = "18136"
url_dataset = "https://github.com/ceandrade/tmdsp_instances"
+++


