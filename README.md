### 1. AuReMe (Automatic Reconstruction of Metabolic Models，2018)

```bash
# Description
good traceability of the whole reconstruction process
offer docker image
creates GSMMs with a template-based algorithm
incorporate information from MetaCyc and BIGG

# reference
DOI: https://doi.org/10.1093/nar/gkv1049
```

### 2. CarveMe (2018)

```bash
# Description
command-line python-based tool
use for Flux Balance Analysis (FBA) in a few minutes
create models from a BIGG-based manually curated universal template
own gap-filling algorithm
prioritize the incorporation into the network of reactions with higher genetic evidence

# reference
DOI: https://doi.org/10.1093/nar/gky537
```

### 3. MetaDraft (2018) 

```bash
# Description
Python-based user-friendly software
create GSMMs from manually curated models(BIGG or any other)
users can set priorities when multiple templates match
support the SBML Level 3

# reference
DOI: https://doi.org/10.1371/journal.pone.0173183
DOI: 10.5281/zenodo.2398336
```

### 4. RAVEN version2 (Reconstruction, Analysis and Visualization of Metabolic Networks, 2018)

```bash
# Description
runs in MATLAB is compatible with COBRA Toolbox v3
allow users reconstruct GSMMs from KEGG, MetaCys(transporters and spontaneous reactions) and template models
integrate an algorithm that merges network from two databases

# reference
DOI: https://doi.org/10.1371/journal.pcbi.1006541
```

### 5. ModelSEED version 2.2 (2018)

```bash
# Description
web resource for reconstruction of GSMMs (microorganisms and plants)
use RAST for genome annotation (first step)
users can select or create a medium for gap-filling
allow model creation in under 10 minutes (including annotation) 
provide reaction and metabolite aliases in other databases

# reference
DOI: https://doi.org/10.1038/nbt.1672
```

### 6. Pathway Tools version 22.0 (2018)

```bash
# Description
users can interactively explore, visualize and edit different components
network can be visualized using Cellular Overview diagrams
experimental data like gene expression can be color-mapped based on expression levels

# reference
DOI: https://doi.org/10.1093/bib/bbv079
```

### 7. Merlin version 3.8 (2018) flexible

```bash
java application based on the KEGG database
re-annotation of genomes through the online service of BLAST (EBI) or HMMER
flexible adjust parameters (expected value threshold and maximum number) of annotation algorithms
the interface enables comparing gene function agreement between annotation and UniProt

# reference
DOI: https://doi.org/10.1093/nar/gkv294
```



**Table 1 List of selected genome-scale metabolic reconstruction tools and their main features**

| Reconstruction tool | Mapping method                                              | Reactions are inherited from | Associated databases | Version | Type of software     |
| :------------------ | :---------------------------------------------------------- | :--------------------------- | :------------------- | :------ | :------------------- |
| AuReMe              | Pantograph (Inparanoid and OrthoMCL)                        | Template model(s)            | BIGG-MetaCyc         | 1.2.4   | Command line         |
| CarveMe             | Diamond, eggNOG-mappera                                     | Template model               | BIGG                 | 1.2.1   | Command line         |
| Merlin              | Mapping from annotation with BLAST or HMMER                 | Database                     | KEGG                 | 3.8     | Standalone interface |
| MetaDraft           | Autograph (Inparanoid)                                      | Template model(s)            | BIGG                 | 0.9.2   | Standalone interface |
| ModelSEED           | Annotation ontology map from RAST data                      | Template model               | ModelSEED            | 2.2–2.4 | Online service       |
| Pathway Tools       | Pathologic                                                  | Database                     | MetaCyc              | 22.0    | Standalone interface |
| RAVEN               | Autograph-type method from BLASTP and Bidirectional BLASTPb | Database- Template model(s)  | KEGG-MetaCyc         | 2.0.1   | Command line         |

Reference：Mendoza SN, Olivier BG, Molenaar D, Teusink B. A systematic assessment of current genome-scale metabolic reconstruction tools. Genome Biol. 2019 Aug 7;20(1):158. doi: 10.1186/s13059-019-1769-1. PMID: 31391098; PMCID: PMC6685185.
