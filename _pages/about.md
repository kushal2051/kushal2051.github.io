---
permalink: /
title: "Kushal Koirala"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

# 👋 Hi, I'm Kushal!

🔬 I'm a PhD candidate in the **Curriculum in Bioinformatics and Computational Biology** at the **University of North Carolina at Chapel Hill**, working on computational drug discovery.

💊 My work spans **structure-based drug design, molecular docking, molecular dynamics and enhanced-sampling simulations, free energy and binding kinetics, QSAR, ultra-large virtual screening, and machine learning** (deep learning, graph and knowledge-graph models). I enjoy building reproducible HPC pipelines that take a project from target identification through hit identification and lead optimization.

📚 I have co-authored 8 peer-reviewed publications and 1 preprint, including 3 first or co-first-author works, with 2 more first or co-first-author manuscripts in review or preparation. I've presented posters at ACS national meetings.

🎓 Before UNC, I was a graduate researcher in computational chemistry at the **University of Kansas**, and I hold a B.Tech. in Biotechnology from **Kathmandu University**, Nepal.

🤝 I'm always happy to chat about research or collaborations. Feel free to reach out!

[📄 Download my CV (PDF)](/files/Kushal_Koirala_Resume.pdf)

---

# Research

## Manuscripts Under Review & Preprints

1. **Koirala, K.**, DeLuca, M., Chung, C.-H., Sundar, S., Kapadia, S., Kaneva, V., Ding, E., Chirkova, R., Haendel, M. A., Bizon, C., Tropsha, A. (2026). *Drug-Target-Disease Embeddings Improve the Accuracy of Drug Repurposing Model.* Under review, ICLR 2027.
2. Kelestemur, E.\*, **Koirala, K.**\*, Tropsha, A. *PURE: Protein–ligand benchmark for Unbiased and Rigorous Evaluation.* Manuscript in preparation.
3. Dey, R., Brocidiacono, M., **Koirala, K.**, Tropsha, A., Popov, K. I. (2025). *Extending machine learning model for implicit solvation to free energy calculations.* arXiv preprint. [doi:10.48550/arXiv.2510.20103](https://doi.org/10.48550/arXiv.2510.20103)

## Research Articles

1. DeLuca et al. (2025). *Medicines, Diseases, Indications, and Contraindications (MeDIC): A Foundational Resource to Support Drug Repurposing.* **Nucleic Acids Research**, gkaf1312. [doi:10.1093/nar/gkaf1312](https://doi.org/10.1093/nar/gkaf1312)
2. Ashizawa et al. (2025). *Modeling Protein–Protein and Protein–Ligand Interactions by the ClusPro Team in CASP16.* **Proteins: Structure, Function, and Bioinformatics**. [doi:10.1002/prot.70066](https://doi.org/10.1002/prot.70066)
3. Hegde et al. (2025). *Mechanistic studies of small molecule ligands selective to RNA single G bulges.* **Nucleic Acids Research**, 53(12). [doi:10.1093/nar/gkaf559](https://doi.org/10.1093/nar/gkaf559)
4. Wang, J.\*, **Koirala, K.**\*, Do, H. N., Miao, Y. (2024). *PepBinding: a workflow for predicting peptide binding structures by combining peptide docking and peptide Gaussian accelerated molecular dynamics simulations.* **J. Phys. Chem. B**. [doi:10.1021/acs.jpcb.4c02047](https://doi.org/10.1021/acs.jpcb.4c02047)

## Review Papers

1. Adediwura, V. A.\*, **Koirala, K.**\*, Do, H. N., Wang, J., Miao, Y. (2024). *Understanding the impact of binding free energy and kinetics calculations in modern drug discovery.* **Expert Opinion on Drug Discovery**. [doi:10.1080/17460441.2024.2349149](https://doi.org/10.1080/17460441.2024.2349149)
2. Wang, J., Do, H. N., **Koirala, K.**, Miao, Y. (2023). *Predicting biomolecular binding kinetics: A review.* **J. Chem. Theory Comput.** [doi:10.1021/acs.jctc.2c01085](https://doi.org/10.1021/acs.jctc.2c01085)

## Book Chapters

1. Do, H. N., Wang, J., Joshi, K., **Koirala, K.**, Miao, Y. (2025). *Gaussian Accelerated Molecular Dynamics in Drug Discovery.* In *Computational Drug Discovery: Methods and Applications*, Wiley-VCH, 21–43. [doi:10.1002/9783527840748.ch2](https://doi.org/10.1002/9783527840748.ch2)
2. **Koirala, K.** et al. (2024). *Accelerating molecular dynamics simulations for drug discovery.* In *Computational Drug Discovery and Design*, 187–202, Springer US.

\* Co-first author. Full list on [Google Scholar](https://scholar.google.com/citations?hl=en&user=nXP0hIkAAAAJ).

---

# Experience

**Graduate Research Assistant, Computational Drug Discovery** · *Aug 2023 – Present*
Curriculum in Bioinformatics and Computational Biology, University of North Carolina at Chapel Hill

- Developed a knowledge-graph (KG) drug repurposing pipeline with a TensorFlow multilayer perceptron for drug–disease–target classification; nominated novel drug hypotheses for neurodegenerative diseases (first-author manuscript under review, ICLR 2027).
- Collaborated with the non-profit Every Cure on MATRIX, an AI platform for drug repurposing ([TIME Best Inventions 2025](https://time.com/collections/best-inventions-2025/7318443/every-cure-matrix/)). Built and ran ML experiments with TensorFlow, scikit-learn, Seaborn, Kedro, and a biomedical KG to generate repurposing nominations across all known diseases. Co-author of the MeDIC resource supporting the platform.
- Engineered transformer and diffusion models (millions of parameters) trained on protein–ligand complexes for binding pose prediction and ligand affinity estimation.
- Built an automated pipeline for PDB data extraction, curation, and train/test splitting; curated ~190K protein–ligand structures into PURE, a benchmark for unbiased evaluation of docking and affinity models (co-first-author manuscript in preparation).
- Screened the Enamine REAL database (~14B compounds) against UppS in *Neisseria gonorrhoeae* using SMARTS-based pharmacophore filtering and HTVS; identified 356 early-stage hits for experimental validation and optimization.
- Built QSAR models for YCK2 kinase to rank candidate compounds for SAR optimization.
- Contributed to a machine-learning implicit solvation model for free energy calculations (arXiv, 2025).
- Competed in the CACHE (Critical Assessment of Computational Hit-finding Experiments) blind prediction challenges, nominating top 100 hits for multiple targets; placed 7th of 25 teams in CACHE Challenge #5.

**Graduate Research Assistant, Computational Chemistry** · *Aug 2021 – Aug 2023*
University of Kansas, Lawrence, KS

- Developed PepBinding, a Python workflow combining peptide docking with peptide Gaussian accelerated MD (GaMD) to predict peptide–protein binding structures (co-first-author publication, *J. Phys. Chem. B*).
- Characterized binding mechanisms of small-molecule ligands selective for RNA single-G bulges with MD simulations; identified structural determinants of ligand selectivity (*Nucleic Acids Research*, 2025).
- Co-authored reviews on binding free energy and kinetics prediction (*J. Chem. Theory Comput.*; *Expert Opin. Drug Discov.*) and book chapters on accelerated MD for drug discovery.

**Experimental Research Experience**

- **Molecular Lab Technologist**, Decode Genomics and Research Center, Kathmandu, Nepal · *Jun 2020 – Apr 2021*: frontline COVID-19 testing (sample preparation, DNA/RNA isolation, PCR, gel electrophoresis).
- **Research Intern**, Center for Health and Disease Studies (CHDS), Nepal · *Apr 2019 – Dec 2020*: analyzed EGFR mutations in non-small cell lung carcinoma patients at Nepal Cancer Hospital and Research Center; set up laboratory space for microbial studies.
- **Undergraduate Researcher**, Kathmandu University, Nepal · *Mar 2018 – Sep 2018*: optimized production of high-fructose corn syrup for industrial application.

---

# Education

- **PhD, Bioinformatics and Computational Biology**, University of North Carolina at Chapel Hill · *Aug 2023 – Dec 2027 (expected)*
- **Bachelor of Technology, Biotechnology**, Kathmandu University, Kathmandu, Nepal · *Jul 2014 – Jul 2018*

---

# Conference Presentations

- **Koirala, K.**, et al. *Accurate prediction of binding affinity from single structure.* ACS Spring 2026 Meeting, Atlanta, GA, March 2026. (Poster)
- **Koirala, K.**, et al. *Generation of novel drug repurposing hypotheses using LLM-augmented biomedical graph embeddings via multi-layer perceptron model.* ACS Fall 2025 Meeting, Washington, DC, August 2025. (Poster)

---

# Technical Skills

- **Computational Chemistry & Drug Design:** Molecular docking (GNINA, Glide), molecular dynamics (AMBER, CHARMM, GROMACS), Gaussian accelerated MD (GaMD), free energy and binding kinetics, QSAR, pharmacophore modeling, high-throughput virtual screening (HTVS), fragment-based screening, structure-based and ligand-based drug design, hit-to-lead optimization
- **Cheminformatics & Structural Biology:** RDKit, Schrödinger Suite (Maestro, Glide), AlphaFold, PDB data curation, MDAnalysis, PyMOL, VMD, UCSF Chimera
- **Machine Learning & Data:** PyTorch, TensorFlow, scikit-learn, transformers, diffusion models, graph neural networks and knowledge graphs (Neo4j, Cypher), Kedro, Seaborn, Pandas, NumPy
- **Programming & Infrastructure:** Python, R, Bash, MATLAB, SQL; Linux/Unix, Git, Docker, High-Performance Computing (HPC), SLURM, Google Cloud, Jupyter
- **Languages:** English, Nepali, Hindi

---

# Teaching & Leadership

**Graduate Teaching Assistant, Statistical Modeling (BCB 720)** · *Aug 2024 – Dec 2024*, UNC Chapel Hill
- Supported 10+ graduate students and led problem-solving sections.

**Graduate Teaching Assistant, Biochemistry** · *Aug 2021 – Jul 2023*, University of Kansas
- Led laboratory sessions for 50 undergraduates, taught conceptual biochemistry, ran 3 problem-solving sections, and held office hours.
- Mentored 2 high school students on computational summer projects.

**Steering Committee Member, BCB Department, UNC Chapel Hill** · *Jun 2024 – Present*
- Evaluated 10+ faculty candidates (CV review, research talks); contributed to 5 successful hires and provided the graduate student perspective on curriculum and program development.

**Python Programming Tutor, How To Learn To Code (HTLTC)** · *Jun 2024 – Present*
- Mentored 10+ students from non-technical backgrounds in Python fundamentals; 100% course completion.

**Hackathons and Training**
- CMU x NVIDIA Federated Learning Hackathon for Biomedical Applications (2026)
- Bio-Agent Knowledge Graph Construction Challenge, NVIDIA x AWS (ongoing)
- High-Throughput Virtual Screening for Hit Finding and Evaluation, Schrödinger (2024)