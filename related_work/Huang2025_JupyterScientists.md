# How Scientists Use Jupyter Notebooks: Goals, Quality Attributes, and Opportunities

**Authors:** Ruanqianqian (Lisa) Huang et al.  
**Year:** 2025  
**Venue:** arXiv:2503.12309  
**URL:** https://arxiv.org/abs/2503.12309  

## CS197 Analysis Framework

### Problem
Computational notebooks are designed to prioritize scientists' needs, but little is known about how scientists actually interact with notebooks, what requirements drive their software development processes, or what tactics they use to meet their requirements.

### Prior Assumptions in Literature
- Scientists primarily use notebooks for linear, exploratory data analysis
- Notebook design requirements are well-understood from tool-user perspectives
- Scientists' software development practices mirror those of professional developers
- Quality attributes valued by scientists are similar across all use cases

### Key Insight
Scientists prioritize different quality attributes depending on their specific goals, and their actual usage patterns reveal distinct requirements for creating and managing state, dependencies, and abstractions that current notebook systems don't adequately support.

### Technical Approach
Observational study methodology:

1. **Participant Study Design**
   - 20 scientists across disciplines using Jupyter notebooks
   - Day-to-day task observation and analysis
   - Goal-oriented workflow documentation
   - Quality attribute identification and prioritization

2. **Usage Pattern Analysis**
   - Qualitative analysis of scientist behaviors
   - Goal categorization and mapping to quality attributes
   - Tactic identification for quality promotion
   - AI tool integration patterns

3. **Design Recommendation Framework**
   - User requirement extraction from observed behaviors
   - Gap analysis between current tools and actual needs
   - Design principles for improved notebook systems

### Evaluation
- Comprehensive qualitative analysis of 20 scientists' workflows
- Cross-disciplinary usage pattern validation
- Quality attribute taxonomy development
- Design recommendation validation through user feedback

### Impact
- **Tool Design**: Informs development of scientist-centered computational tools
- **Understanding**: Provides empirical foundation for scientist workflow assumptions
- **Research Methods**: Establishes methodology for studying scientific computing practices
- **AI Integration**: Documents how scientists incorporate AI tools into research workflows

## Key Assumptions Identified
1. **Traditional**: Notebook tools should prioritize linear, exploratory workflows
2. **Challenged**: Scientists need sophisticated state management, dependency tracking, and abstraction tools
3. **New assumption**: Scientist quality priorities are goal-dependent and require adaptive tool support

## Key Findings for Version Control
- Scientists struggle with state management across notebook sessions
- Dependency tracking is critical but poorly supported
- Abstraction and reuse patterns suggest need for version control of notebook components
- AI tool integration creates new collaboration patterns requiring tracking

## Relevance to Version Control for Science
Direct evidence for version control needs in scientific computing. Scientists' state management and dependency challenges highlight specific requirements for version control systems supporting computational research workflows.

## Citation
Huang, R. L., et al. (2025). How Scientists Use Jupyter Notebooks: Goals, Quality Attributes, and Opportunities. arXiv preprint arXiv:2503.12309.