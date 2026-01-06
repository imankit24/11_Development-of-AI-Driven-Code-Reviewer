# Topic - Development of AI-Driven Code Review System

## Model Research

### Introduction
Manual code review in academic environments is time-consuming and inconsistent due to large volumes of student submissions. This project focuses on developing an AI-driven code review system that automatically analyzes student code for correctness, coding style, logical structure, and optimization opportunities. The system combines Abstract Syntax Tree (AST)–based static analysis with AI-based reasoning to provide structured and meaningful feedback.

### Research Objective
The objective of this research is to design a scalable model that:
- Detects syntax and logical errors in code
- Evaluates adherence to coding standards
- Suggests optimizations and improvements
- Generates clear, human-readable feedback for students

### Model Architecture
The system follows a hybrid analysis approach:
1. Code preprocessing and normalization  
2. AST-based static analysis for structural validation  
3. AI-based reasoning for logic understanding and feedback generation  
4. Aggregation of results into a unified review report  

### Methodology
Student code samples are analyzed using AST parsing and AI reasoning. The generated feedback is compared with manual reviews to evaluate accuracy, clarity, and educational value. The system is refined iteratively to improve feedback consistency.

### Limitations and Future Scope
The system does not execute code and may face challenges with complex logic. Future enhancements include test-case execution, multi-language support, and personalized feedback based on student proficiency.

### Conclusion
This research demonstrates that combining AST-based static analysis with AI-driven reasoning enables effective automated code review. The hybrid approach ensures accurate evaluation while delivering clear, educational feedback suitable for academic and training environments.
