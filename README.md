# REFERENCE: A Large-Scale Benchmark for Research Feed Recommendation

The data can be downloaded from Azure blob storage at the following URLs (all sizes are compressed):

* [Computer Science (32.79Gb)](https://milacdlab.blob.core.windows.net/reference-benchmark/cs.zip)
* [Economics (14.99Gb)](https://milacdlab.blob.core.windows.net/reference-benchmark/economics.zip)
* [Geography (16.02Gb)](https://milacdlab.blob.core.windows.net/reference-benchmark/geography.zip)
* [History (11.39Gb)](https://milacdlab.blob.core.windows.net/reference-benchmark/history.zip)
* [Physics (42.14Gb)](https://milacdlab.blob.core.windows.net/reference-benchmark/physics.zip)

Please note that the datasets are much larger when decompressed. Each is a zip file with the shown structure:

```
├── documents.json.gz
├── graph.csv
├── qrels
│   ├── test.csv
│   ├── train.csv
│   └── val.csv
└── queries.json.gz
```

The repository will be updated with scripts and examples for using the data and performing retrieval in the coming days.