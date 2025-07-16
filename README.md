# medical-conja-evaluator
An LLM-based evaluation system that benchmarks graph vs. tabular data structures for healthcare unit transition analysis and clinical decision support.

#Medical Unit Transitions Con-J Evaluator

A comprehensive evaluation framework for comparing graph-based and tabular data representations in medical unit transition analysis using Large Language Model (LLM) judges.

#Overview
This project implements an enhanced Medical Con-J (Conjunction) evaluator that analyzes how different data structure representations (graph vs. tabular) perform when answering clinical questions about patient unit transitions and hospital admissions. The system uses LLM-based evaluation to determine which representation format provides more accurate and clinically relevant responses.

#Key Features
- Dual Representation Analysis: Compares graph-structured data (nodes and edges) with tabular data (headers and rows) for the same medical information
- LLM Judge Evaluation: Uses language models as judges to evaluate response quality across multiple criteria (accuracy, completeness, clarity, clinical relevance)
- Medical Domain Focus: Specifically designed for healthcare unit transition data, including emergency department transfers, ICU admissions, and care unit movements
- Comprehensive Metrics: Provides detailed analysis including confidence levels, criteria breakdowns, and performance statistics
- Bias Mitigation: Implements randomized response ordering to reduce evaluation bias

#Technical Stack
- Models: Supports multiple LLMs including Qwen2, Table-R1, and custom medical models
- Framework: Built on HuggingFace Transformers with PyTorch backend
- Data Processing: Handles JSONL format medical datasets with structured patient admission data
- Evaluation: Automated pipeline with detailed reporting and case-by-case analysis

#Use Cases
Evaluating optimal data representation formats for medical AI systems
Comparing structured vs. unstructured data presentation in clinical settings
Benchmarking LLM performance on healthcare-specific tasks
Research into medical data visualization and interpretation

Output
The system generates comprehensive evaluation reports including winner distributions, confidence analyses, detailed case studies, and recommendations for optimal data representation strategies in medical contexts.
