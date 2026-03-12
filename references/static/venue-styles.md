# Venue Style Guide

Style guidelines for top-tier security conferences.

## NDSS (Network and Distributed System Security Symposium)

### Paper Characteristics
- **Focus**: Network security, distributed systems security
- **Length**: 12-14 pages + references
- **Style**: Systematic, measurement-heavy
- **Key Elements**:
  - Strong empirical evaluation
  - Real-world deployment preferred
  - Clear threat model

### Typical Structure
```
1. Introduction (2 pages)
   - Motivation with real-world impact
   - Clear problem statement
   - Contributions list

2. Background & Motivation (1-2 pages)
   - Technical background
   - Measurement study (often)

3. Threat Model (1 page)
   - Clear adversary capabilities
   - Explicit assumptions

4. Design (3-4 pages)
   - Architecture overview
   - Key components

5. Implementation (1-2 pages)
   - Prototype details
   - Deployment (if applicable)

6. Evaluation (3-4 pages)
   - Security effectiveness
   - Performance overhead
   - Real-world data

7. Discussion & Limitations (1 page)

8. Related Work (1 page)

9. Conclusion (0.5 page)
```

### Writing Style
- Concrete and measurement-driven
- Quantitative results emphasized
- Clear and direct language

## CCS (ACM Conference on Computer and Communications Security)

### Paper Characteristics
- **Focus**: Broad security topics, novel techniques
- **Length**: 12-15 pages + references
- **Style**: Technical depth, theoretical grounding
- **Key Elements**:
  - Novel algorithm or technique
  - Rigorous evaluation
  - Formal analysis (when applicable)

### Typical Structure
```
1. Introduction (2 pages)
2. Background (1-2 pages)
3. Problem Definition & Threat Model (1-2 pages)
4. Approach/Methodology (4-5 pages)
5. Implementation (1-2 pages)
6. Evaluation (3-4 pages)
7. Discussion (1 page)
8. Related Work (1 page)
9. Conclusion (0.5 page)
```

### Writing Style
- Theoretical rigor valued
- Novel contributions emphasized
- Broader impact statements common

## USENIX Security Symposium

### Paper Characteristics
- **Focus**: Systems security, practical solutions
- **Length**: 13-15 pages + references
- **Style**: Practical, reproducible research
- **Key Elements**:
  - Working prototype required
  - Artifacts encouraged
  - Ethical considerations mandatory

### Typical Structure
```
1. Introduction (2 pages)
2. Background & Motivation (1-2 pages)
3. Threat Model (1 page)
4. Design (3-4 pages)
5. Implementation (2 pages)
   - Detailed enough for reproduction
6. Evaluation (4-5 pages)
   - Comprehensive
7. Limitations & Discussion (1-2 pages)
   - Honest assessment
8. Ethical Considerations (0.5 page)
   - Required for attack papers
9. Related Work (1 page)
10. Conclusion (0.5 page)
```

### Writing Style
- Reproducibility emphasized
- Artifact evaluation
- Responsible disclosure required

## S&P (IEEE Symposium on Security and Privacy, "Oakland")

### Paper Characteristics
- **Focus**: Fundamental security problems, rigorous methods
- **Length**: 12-14 pages + references
- **Style**: Theoretical depth, long-term impact
- **Key Elements**:
  - Novel theoretical contributions
  - Rigorous proofs or extensive empirical validation
  - Broad applicability

### Typical Structure
```
1. Introduction (2 pages)
2. Background (1-2 pages)
3. Problem Formalization (1-2 pages)
4. Approach (4-5 pages)
5. Analysis/Proofs (2-3 pages)
6. Evaluation (2-3 pages)
7. Discussion (1 page)
8. Related Work (1 page)
9. Conclusion (0.5 page)
```

### Writing Style
- Formal methods appreciated
- Long-term research vision
- Fundamental contributions

## Common Elements Across Venues

### Introduction Patterns
- Start with broad impact
- Narrow to specific problem
- Clear gap identification
- Explicit contributions

### Threat Model Patterns
- Adversary capabilities
- Attack surface definition
- Explicit assumptions
- Scope limitations

### Evaluation Patterns
- Security metrics (detection, prevention)
- Performance overhead
- Comparison to baselines
- Real-world validation

### Related Work Patterns
- Organized by theme, not chronology
- Clear differentiation from current work
- Fair comparison to prior art

### Discussion Patterns
- Honest limitations
- Future directions
- Broader implications

## Venue Selection Guide

### Choose NDSS if:
- Network/distributed systems focus
- Strong measurement component
- Real-world deployment story

### Choose CCS if:
- Novel algorithm/technique
- Broad security topic
- Theoretical contribution

### Choose USENIX Security if:
- Practical system implementation
- Reproducible research
- Strong artifact potential

### Choose S&P if:
- Fundamental security problem
- Theoretical depth
- Long-term impact potential

## Formatting Notes

### Anonymity (for review)
- Remove author names and affiliations
- Anonymize references to own work
- Use third-person for own prior work

### Citations
- Use author-year format typically
- "Smith et al. [1]" not "In [1]"
- Balance citation density

### Figures & Tables
- Self-contained captions
- Readable in grayscale
- Consistent formatting

---

_Update this guide as new venue patterns are observed._
