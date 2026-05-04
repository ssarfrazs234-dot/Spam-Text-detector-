1. INTRODUCTION
1.1 Purpose 
The purpose of this Software Design Document is to provide a complete and structured description of the internal design of the Spam Text Detector system. It explains how the system will be implemented, how different modules interact with each other, and how data flows through the system to produce the final output.
This document is intended for:
•	Developers (for implementation guidance) 
•	Evaluators (for understanding system design) 
•	Future maintainers (for system upgrades) 
The system is designed using Python and Tkinter with a rule-based NLP approach, avoiding complex machine learning models. The goal is to ensure simplicity, clarity, and ease of execution on low-resource systems.
1.2 Scope 
The scope of this system includes the development of a standalone desktop application that performs spam detection using text analysis techniques.
Included in Scope
•	Desktop GUI-based application 
•	Real-time message classification 
•	Rule-based spam detection system 
•	Keyword-based scoring mechanism 
•	Text preprocessing pipeline 
•	Offline execution 
Excluded from Scope
•	Machine learning models (e.g., SVM, Naive Bayes) 
•	Cloud-based processing 
•	Database storage system 
•	Email server integration 
•	Mobile application version 
The system is strictly limited to rule-based NLP processing for educational and lightweight usage.
1.3 Design Goals 
The system is designed with the following goals:
1. Simplicity
The system should be easy to understand and implement without advanced AI knowledge.
2. Efficiency
It should process text quickly without delays.
3. Lightweight Execution
The system should run smoothly even on low-end machines.
4. Maintainability
Code should be modular so that new features (like ML models) can be added later.
5. Usability
The GUI should be simple and user-friendly for non-technical users.

