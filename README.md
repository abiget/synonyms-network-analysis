# synonyms-network-analysis

## Synonym Networks in WordNet and LLMs: A Comparative Analysis Perspective

        ## 1. Network Properties

        | Property | WordNet | LLM |
        |----------|---------|-----|
        | Nodes | 873.0 | 916.0 |
        | Edges | 893.0 | 1885.0 |
        | Density | 0.002346 | 0.004498 |
        | Avg. Closeness Centrality | 0.017373322115949406 | 0.13502472681659308 |
        | Avg. Betweenness Centrality | 0.001589170773632462 | 0.006238159216675416 |
        | Avg. Degree Centrality | 0.0023461227234990597 | 0.0044980552175054285 |
        | Number of Components | 149.0 | 7.0 |
        | Nodes in Largest CC | 341.0 | 885.0 |
        | Avg. Clustering | 0.1864 | 0.3119 |
        | Avg. Shortest Path Length LCC | 10.05789201311023 | 7.108096224148069 |
        | Avg. Clustering Random | 0.0013341110334237482 | 0.00558884234290412 |
        | Avg. Shortest Path Length Random | 8.479748552998362 | 4.666557999326439 |

        ## 2. Top 10 Hub Words by Degree

        ### WordNet
        - good: 12
        - dim: 10
        - fresh: 8
        - free: 8
        - strong: 8
        - sharp: 8
        - new: 7
        - keen: 7
        - slight: 7
        - small: 7
        
                ### LLM
                - clear: 18
        - paramount: 17
        - sharp: 16
        - notable: 16
        - modest: 14
        - preeminent: 14
        - insignificant: 13
        - reasonable: 13
        - significant: 13
        - small: 13
        
                ## 3. Top 10 Words by Clustering Coefficient
        
                ### WordNet
                - adept: 1.0000
        - inaugural: 1.0000
        - maiden: 1.0000
        - final: 1.0000
        - terminal: 1.0000
        - different: 1.0000
        - dissimilar: 1.0000
        - unlike: 1.0000
        - minor: 1.0000
        - humble: 1.0000
        
                ### LLM
                - perplexing: 1.0000
        - elementary: 1.0000
        - delusive: 1.0000
        - thirsty: 1.0000
        - promising: 1.0000
        - licit: 1.0000
        - frosty: 1.0000
        - grimy: 1.0000
        - unparalleled: 1.0000
        - mistaken: 1.0000

        ## 4. Key Findings

        1. Even with identical vocabulary, the LLM network creates 2.1x more connections between words.
        2. LLM shows higher clustering (0.3119 vs 0.1864), suggesting more tightly defined semantic neighborhoods.
        3. The top hub words differ significantly:
        - WordNet prioritizes: good, dim, fresh
        - LLM prioritizes: clear, paramount, sharp
        4. This suggests fundamentally different organizing principles:
         * WordNet tends to prioritize synonyms that are more traditional and widely accepted, such as good, dim, and fresh.

         * The LLM, on the other hand, favors synonyms that can be more contextually nuanced or expressive, like clear, paramount, and sharp.

        ## 5. Visualizations

