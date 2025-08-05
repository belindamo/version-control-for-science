# An open framework for archival, reproducible, and transparent science (ARTS)

**Authors:** Sabar Dasgupta, Paul Nuyujukian  
**Year:** 2024  
**Venue:** arXiv:2504.08171  
**URL:** https://arxiv.org/abs/2504.08171  

## CS197 Analysis Framework

### Problem
Digital computational outputs are ubiquitous in research workflows, but even with accessible data and code, the barrier to recreating figures and reproducing scientific findings remains high. Missing components include computational environments and associated pipelines needed to execute data and code.

### Prior Assumptions in Literature
- Making data and code available is sufficient for reproducibility
- Computational environments can be adequately described in text
- Researchers will invest time to recreate complex computational setups
- Static archives of code/data are adequate for long-term preservation

### Key Insight
What's missing for reproducibility is the complete computational context - the environment and pipelines in which data and code execute. True reproducibility requires storing data, code, figures, AND their execution environment together as an integrated, recreatable unit.

### Technical Approach
ARTS framework incorporates three core technologies:

1. **Containers** (Docker/Singularity)
   - Capture complete computational environment
   - Ensure consistent execution across platforms
   - Include all dependencies and system configurations

2. **Version Control Systems** (Git)
   - Track changes in code, data, and configurations
   - Maintain complete history of analytical decisions
   - Enable branching for different analytical approaches

3. **Persistent Archives**
   - Long-term storage with stable identifiers
   - Integration with institutional repositories
   - Automated backup and preservation workflows

**Integration approach:**
- Container definitions stored in version control
- Data management with Git LFS or DVC
- Automated workflows for figure generation
- Integration with HPC and cloud resources

### Evaluation
- Proof-of-concept implementations in neuroscience research
- Assessment of storage requirements and costs
- User workflow analysis and adoption barriers
- Comparison with existing reproducibility solutions

### Impact
- **Technical**: Provides complete solution for computational reproducibility
- **Policy**: Addresses federal mandates for research data management
- **Cultural**: Promotes shift toward proactive reproducibility practices
- **Economic**: Reduces long-term costs of research replication

## Key Assumptions Identified
1. **Traditional**: Sharing code and data files is sufficient for reproducibility
2. **Challenged**: Complete computational environments must be preserved and shareable
3. **New assumption**: Reproducibility infrastructure should be integrated into research workflow from the start

## Bit Flip Potential
**Bit**: Research outputs (papers, data, code) are the primary artifacts to preserve  
**Flip**: Research *processes* and *environments* are equally important artifacts requiring systematic preservation

## Relevance to Version Control for Science
ARTS framework exemplifies sophisticated integration of version control with reproducibility infrastructure. Shows how Git can be foundation for comprehensive research data management beyond simple code tracking.

## Citation
Dasgupta, S., & Nuyujukian, P. (2024). An open framework for archival, reproducible, and transparent science. arXiv preprint arXiv:2504.08171.