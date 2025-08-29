---
description: making a beamer-based slide, currently mainly for review slide
allowed-tools: Task,Read,Grep,Glob,LS,WebSearch,WebFetch,Bash
agent-hint: provide your concise synopsis.md file
---

# Instructions for making a good slide (MUST FOLLOW!!!)

- **Think deeply before creating**: Apply thorough analysis and critical thinking to understand the topic, audience, and key messages before starting slide creation. Consider the logical flow and main takeaways.

- **Literature review workflow**: 
  - When tasked with reviewing multiple papers, use web search to identify and locate the specific references
  - If paper titles or authors are ambiguous, **ALWAYS confirm with the human user** which exact papers to review before proceeding
  - Download confirmed references to the local `references/` directory
  - Extract key figures, algorithms, or pseudocode blocks that clearly illustrate the paper's main contributions
  - Prioritize visual elements that demonstrate the essence of each paper's methodology or results

- **Content precision guidelines**:
  - Limit each slide to 1-3 key points maximum
  - Prefer figures, diagrams, and tables over dense text or complex equations
  - If equations are necessary, break them into digestible components across multiple slides
  - Use bullet points with clear, concise statements (maximum 2 lines per bullet)
  - Ensure each slide can be understood in 60-90 seconds
  - Provide explanations in the form of comment in some frames if you think the human user may need this or it is mentioned that he/she is not familiar with certain content

- **Visual emphasis strategies**:
  - Use **bold text** for key terms and critical findings
  - Apply color highlighting (red, blue, or green) to emphasize important results or differences
  - Use consistent formatting throughout the presentation
  - Highlight no more than 2-3 elements per slide to avoid visual overload

- **Quality assurance process**:
  - After completing the slides, compile with `pdflatex` to check for errors
  - Make sure there is **NO Latex compilation error** and **pdf slide aligns well with the source code**
  - Review the generated PDF for logical flow and clarity
  - **Ask the human user to review** the completed slides for technical accuracy and presentation flow
  - Address any feedback before final delivery

- **Technical requirements**:
  - Resolve all LaTeX compilation errors before submission
  - Ensure all figures display properly and are properly referenced
  - Verify that all citations and references are correctly formatted
  - Test that the PDF renders correctly on different viewers