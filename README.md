# How to Repair Data? The HoloClean Framework

Report about the HoloClean Framework ([Github-repository](https://github.com/HoloClean/holoclean)) written for the Seminar _Horrible Data_ at HPI.
The paper, on which this work is based on ([1]), can be found [online](http://www.vldb.org/pvldb/vol10/p1190-rekatsinas.pdf).

## Abstract

In a world, where big data and machine learning approaches are used in a growing number of enterprise applications, maintaining data quality has become more important than ever.
Data repairing is one way to deal with that.
Most repairing tools limit themselves to only one input signal, such as quantitative statistics, Integrity Constraints, or external data, to compute repairs.
Rekatsinas et al. therefore propose a new holistic framework, called HoloClean \[1\], that observes multiple input signals and generates a probabilistic model out of unclean datasets and those signals.
It uses DeepDive to perform statistical learning and probabilistic inference to compute the marginal probabilities of repairs, while scaling to dataset sizes with millions of tuples.
Rekatsinas et al. show that HoloClean achieves an average accuracy improvement of 2x against single-input state-of-the-art approaches across four different datasets.

## Sources

\[1\]: Theodoros Rekatsinas, Xu Chu, Ihab F Ilyas, and Christopher Ré. 2017. **Holoclean: Holistic data repairs with probabilistic inference**. In Proceedings of the VLDB Endowment, Vol. 10. VLDB Endowment, 1190–1201.
