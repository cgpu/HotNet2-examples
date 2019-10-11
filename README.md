# HotNet2-examples
HotNet2 results for testing subsequent analyses.

The structure of directory is this:

```
results/
├── consensus
│   ├── stats.tsv
│   ├── subnetworks.json
│   ├── subnetworks.tsv
│   └── viz-data.json
├── networka-example
│   ├── delta_0.06690435856580734
│   │   ├── components.txt
│   │   ├── results.json
│   │   └── significance.txt
│   ├── delta_0.12327784672379494
│   │   ├── components.txt
│   │   ├── results.json
│   │   └── significance.txt
│   └── viz-data.json
└── networkb-example
    ├── delta_0.05886441096663475
    │   ├── components.txt
    │   ├── results.json
    │   └── significance.txt
    ├── delta_0.06037798896431923
    │   ├── components.txt
    │   ├── results.json
    │   └── significance.txt
    ├── delta_0.1108575388789177
    │   ├── components.txt
    │   ├── results.json
    │   └── significance.txt
    └── viz-data.json
```

From HotNet2 documentation:

>The output of HotNet2.py consists of a directory containing the following:

>`{network_name}-{heat_name}`/: For each (network, heat score) pair, HotNet2.py outputs a directory of results. The directory contains subdirectories starting with "delta" for each delta parameter tested, each of which contain the subnetworks and statistical signifciance associated with that delta parameter.

>`consensus`/: The consensus/ directory contains the consensus file across all networks and heat scores
