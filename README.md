# Intelligent-Tutoring-System-for-Phishing-Email-Detection
Ontology-based Intelligent Tutoring System for phishing email detection using OWL, SWRL, Python, and Flask. Implements semantic reasoning to classify email header indicators and support cybersecurity training.

A semantic web–driven cybersecurity training system that models phishing indicators using OWL ontology and applies SWRL rule-based reasoning to classify suspicious email characteristics. The system integrates Python (Owlready2) with a Flask API to provide an interactive learning interface.

Overview
This project presents the design and implementation of an ontology-driven Intelligent Tutoring System (ITS) for modelling and detecting phishing indicators within email headers.
The system applies semantic web technologies to formally represent phishing knowledge and uses rule-based reasoning to generate explainable classifications.

Research Aim
The project investigates how ontology engineering and semantic reasoning can support cybersecurity education by:
Modelling phishing indicators using OWL
Encoding expert knowledge with SWRL rules
Providing transparent, explainable classification
Integrating ontology reasoning with a web-based interface

The scope focuses on email header attributes such as domain mismatch, display name spoofing, return-path inconsistencies, and authentication results (SPF, DKIM, DMARC).

Methodology
A hybrid development approach was adopted:
Top-down modelling to define core cybersecurity concepts
Bottom-up refinement to incorporate specific phishing indicators
The ontology was developed in Protégé and validated through reasoning and structural visualisation.
System Architecture

The system consists of:
Ontology Layer – OWL classes, object/data properties, and SWRL rules
Reasoning Layer – Owlready2 for ontology interaction and inference
Integration Layer – Flask API for backend communication
Interface Layer – Web-based tutoring interface

Contributions
A structured ontology for phishing header analysis
Rule-based, explainable phishing classification
Integration of semantic reasoning with Python-based web technologies
A working prototype for cybersecurity tutoring applications

Technologies
Python • Flask • Owlready2 • Protégé • OWL • SWRL
