# Procedural Knowledge Libraries: Towards Executable (Research) Memory

**Authors:** Hamidah Oderinwale et al.  
**Year:** 2025  
**Venue:** arXiv:2506.14715  
**URL:** https://arxiv.org/abs/2506.14715  

## CS197 Analysis Framework

### Problem
Traditional research libraries store static end products but lose the tacit knowledge embedded in research processes - the hypotheses, failures, decisions, and iterations that lead to results. This knowledge is typically buried in notebooks, emails, or researcher memory, making research difficult to reproduce and build upon.

### Prior Assumptions in Literature
- Research outputs (papers, datasets) are the primary valuable artifacts
- Static documentation of methods is sufficient for reproducibility
- Research processes are too complex and contextual to systematically capture
- Tacit knowledge transfer happens primarily through human mentorship

### Key Insight
Research *processes* are as valuable as research products. Capturing the full arc of scientific inquiry - including failures, decision rationales, and iterative refinements - creates "executable memory" that dramatically improves reproducibility and knowledge transfer.

### Technical Approach
Procedural Knowledge Libraries (PKLs) framework:

1. **Process Capture Architecture**
   - Version-controlled records of complete research workflows
   - Decision point documentation with rationales
   - Failed approach tracking and analysis
   - Hypothesis evolution monitoring

2. **Jupyter Ecosystem Integration**
   - Extended notebook format capturing process metadata
   - Lens-based transformation model for different views
   - Procedural storage schema for systematic organization

3. **Executable Documentation**
   - Runnable workflow documentation
   - Parameter exploration tracking
   - Alternative approach branching
   - Contextual annotations and reasoning

### Evaluation
- Framework proposed with implementation plan in Jupyter ecosystem
- Conceptual validation through research workflow analysis
- Comparison with traditional static documentation approaches

### Impact
- **Reproducibility**: Addresses root causes of irreproducibility in computational research
- **Knowledge transfer**: Enables systematic capture of research expertise
- **Collaboration**: Provides shared understanding of research decision-making processes
- **Education**: Creates rich learning resources from real research processes

## Key Assumptions Identified
1. **Traditional**: Research papers and final code are sufficient documentation
2. **Challenged**: Research processes and decision-making contexts are critical knowledge artifacts
3. **New assumption**: Tacit research knowledge can be systematically captured and made executable

## Bit Flip Potential
**Bit**: Research documentation should focus on final outcomes and methods  
**Flip**: Research processes, including failures and decision rationales, are primary knowledge artifacts requiring systematic preservation

## Relevance to Version Control for Science
PKLs extend version control concepts beyond code to capture complete research reasoning chains. Highly relevant for understanding how version control systems could track not just *what* changed but *why* changes were made and *how* decisions evolved.

## Connection to Research Context
Directly applicable to the goal of creating version control interfaces for human-agent collaboration. PKLs provide framework for capturing decision-making processes that could inform how AI agents understand and contribute to research workflows.

## Citation
Oderinwale, H., et al. (2025). Procedural Knowledge Libraries: Towards Executable (Research) Memory. arXiv preprint arXiv:2506.14715.