1. Introduction
  - Introduction to AI code completion tools and hint at the problems on using them.
  - (NE: Be a bit speculative about what this might mean, the space of code completion. Define code completion tools. You might look at Github's website or the intros to the AlphaCode paper. What does it mean for a tool to be *useful*)
  - research questions
  	- RQ1: What are the current boundaries of code completion tools
  		- (NE: define "boundary" - what does a boundary help us understand)
  		- RQ1.1 How do AI-supported CC tools manage programming Idioms
  		- RQ1.2 How do AI=supported CC tools manage to write non-smelly code?
  		- structuring these boundaries. (NE: because the boundary is not a clear line, we want to show where th tools work well)
  	- RQ 2: Given the current boundary, how far is it from suggesting design decisions which seem much beyond the boundary?
2. Background and Related Work
  - Code completion tools journey to Copilot.
  - alternatives to Copilot.
  - existing research papers testing Copilot.
  - Scoping the Thesis to Copilot and its current capabilities.
  - current challenges with Copilot - correctness part - obvious errors with easy fixes.
  	- structuring these challenges in next chapters.
3. idioms
  - (NE: make sure you clearly describe the method followed)
  - Best practices
  - Python Idioms
  - Async example of promises and callbacks.
4. Smells
  - Licence infringements
  - code review best practices
  	- Security issues.
  	- common errors/Bugs.
  - more specifications in input resolving these issues?
5. Framework
  - RQ1: taxonomy helps assess this boundary. explain each stage in taxonomy and capabilities required for each stage to be completed.
  - syntax level
  - correctness (NE: with respect to a spec or set of requirements)
  - idioms
  - smells
  - Design - focus more on distance between smells and design. (RQ2)
  	- Async examples
  	- design patterns.
  	- future directions to improve and get to the design level (longer term needs)
6. Discussion
  - existing tools for resolving some of the issues faced - recommendations part of ASE submission paper.
  - Limitations
  - Explainability
  - Control
7. Conclusion
