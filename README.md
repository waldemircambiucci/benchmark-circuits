[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wcamb/)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/wcambiuc)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@waldemircambiucci)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/waldemircambiucci/)

# benchmark-circuits
Quantum circuits used as benchmark for different experiments during the research.

Benchmark circuits play a crucial role in quantum circuit partitioning, especially within the framework of hypergraphic exploratory approaches. Here's why they are important:

- Quantifying Performance: Benchmark circuits provide a standardized set of quantum circuits with known characteristics, such as size, depth, and gate composition. By using benchmark circuits, researchers can quantitatively evaluate the performance of different quantum circuit partitioning algorithms. This evaluation includes metrics such as gate count, circuit depth, qubit connectivity requirements, and the distribution of gates across partitions. For this research, we are using thi methodology to define classical dimensions from well defined quantum circuits. 

- Comparative Analysis: Using benchmark circuits allows for fair and unbiased comparisons between different partitioning algorithms. By subjecting the algorithms to the same set of benchmark circuits, researchers can identify strengths, weaknesses, and trade-offs inherent in each approach. This comparative analysis helps in selecting the most suitable partitioning algorithm for specific quantum circuits and hardware architectures.

- Algorithm Development and Optimization: Benchmark circuits provide a testbed for developing and optimizing quantum circuit partitioning algorithms. Researchers can iteratively refine their algorithms by benchmarking them against a diverse set of circuits with varying complexities and structural characteristics. This iterative process helps in fine-tuning the partitioning algorithms to achieve better performance in terms of minimizing gate count, reducing circuit depth, and optimizing qubit connectivity. To accomplish this task, we are using the MQT Bench platform, to produce different categories of benchmark circuits, in several combinations of optimization, as opt0, opt1, opt2, and opt3. 

Ref.: QUETSCHLICH, Nils; BURGHOLZER, Lukas; WILLE, Robert. MQT Bench: Benchmarking software and design automation tools for quantum computing. Quantum, v. 7, p. 1062, 2023. https://arxiv.org/abs/2204.13719

- Generalization and Standardization: Benchmark circuits contribute to the generalization and standardization of quantum circuit partitioning techniques. By establishing a common set of benchmarks, researchers can establish a baseline for evaluating the effectiveness of new partitioning algorithms across different quantum computing platforms and application domains. This standardization fosters collaboration, reproducibility, and knowledge exchange within the quantum computing community.


