# Managing Software Provenance to Enhance Reproducibility in Computational Research

**Authors:** Akash Dhruv, Anshu Dubey  
**Year:** 2023  
**Venue:** arXiv:2308.15637  
**URL:** https://arxiv.org/abs/2308.15637  

## CS197 Analysis Framework

### Problem
Management of computation-based scientific studies is often left to individual researchers who design computational experiments based on personal preferences. Quality, efficiency, and reproducibility suffer from lack of systematic traceability, particularly in high-performance computing (HPC) environments.

### Prior Assumptions in Literature
- Individual researchers can adequately manage computational experiment documentation
- Software development practices are separate from scientific computing practices
- HPC environments make reproducibility documentation impractical
- Personal workflow preferences are acceptable for scientific computing

### Key Insight
Systematic software provenance tracking - maintaining comprehensive records of computational experiments including execution environments, dependencies, and decision points - is essential for reproducibility in complex HPC-based scientific studies.

### Technical Approach
Comprehensive documentation framework for HPC computational experiments:

1. **Execution Environment Documentation**
   - Complete software stack specifications
   - Hardware configuration details
   - Environment module specifications
   - Dependency version tracking

2. **Workflow Provenance Tracking**
   - Input data lineage and transformations
   - Parameter space exploration documentation
   - Computational resource usage patterns
   - Decision point rationales

3. **Flash-X Integration Tools**
   - Automated provenance collection during execution
   - Standardized metadata formats
   - Integration with HPC job scheduling systems
   - Reproducible workflow specifications

### Evaluation
- Case studies with Flash-X multi-physics software
- HPC workflow reproducibility assessment  
- Overhead analysis of provenance collection
- User adoption and workflow integration studies

### Impact
- **HPC Reproducibility**: Addresses specific challenges of large-scale computational reproducibility
- **Scientific Computing**: Establishes systematic approaches for computational experiment management
- **Community Practice**: Provides concrete tools and practices for adoption
- **Policy Alignment**: Supports funding agency reproducibility requirements

## Key Assumptions Identified
1. **Traditional**: HPC complexity makes systematic reproducibility documentation impractical
2. **Challenged**: Systematic provenance tracking is feasible and essential even in complex HPC environments
3. **New assumption**: Scientific computing requires software engineering rigor equivalent to commercial development

## Relevance to Version Control for Science
Demonstrates how version control principles extend to computational environment management and execution provenance. Important for understanding full scope of what "version control for science" must encompass beyond source code.

## Citation
Dhruv, A., & Dubey, A. (2023). Managing Software Provenance to Enhance Reproducibility in Computational Research. arXiv preprint arXiv:2308.15637.