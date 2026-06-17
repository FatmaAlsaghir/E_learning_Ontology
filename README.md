# E-Learning Ontology

## Project Overview

This repository contains the implementation, validation, and documentation of an E-Learning Ontology developed for the Knowledge Engineering and Ontologies course.

The ontology models the main concepts and relationships within an academic e-learning environment, including students, instructors, courses, modules, assignments, submissions, grades, feedback, and learning objectives. It was developed using Semantic Web technologies to support semantic querying, knowledge representation, and automated reasoning.

## Project Objectives

The main objectives of this project are:

* Design and implement an ontology for an e-learning system.
* Model academic entities and their relationships using OWL and RDF.
* Construct a knowledge graph representing educational data.
* Support semantic querying through SPARQL.
* Validate ontology constraints using SHACL.
* Generate ontology documentation using WIDOCO.

## Dataset Sources

The ontology was populated using simulated academic data representing a realistic e-learning environment. The data includes:

* Students
* Instructors
* Courses
* Modules
* Assignments
* Submissions
* Grades
* Feedback
* Learning Objectives

The structure of the dataset was inspired by publicly available educational datasets such as the Open University Learning Analytics Dataset (OULAD).

## Tools and Technologies

* Protégé
* OWL 2 DL
* RDF/RDFS
* SPARQL
* SHACL
* HermiT Reasoner
* WIDOCO
* WebVOWL
* GitHub

## Installation and Usage

### Opening the Ontology

1. Download the ontology file from the `ontology` folder.
2. Open Protégé.
3. Select **File → Open**.
4. Load `E-Learning_Ontology.owl`.

### Running SPARQL Queries

Example SPARQL queries are available in the `sparql` directory and can be executed using Protégé, Apache Jena Fuseki, GraphDB, or any SPARQL-compatible tool.

### SHACL Validation

Validation rules are available in the `shacl` directory and can be used to verify ontology consistency and data quality.

## Repository Structure

```text
E-Learning-Ontology/
│
├── README.md
│
├── ontology/
│   └── E-Learning_Ontology.owl
│
├── rdf/
│   ├── E-Learning_Ontology.rdf
│   └── E-Learning_Ontology.ttl
│
├── sparql/
│   └── queries.rq
│
├── shacl/
│   └── validation.ttl
│
├── docs/
│   └── WIDOCO documentation
│
└── diagrams/
    └── ontology_diagram.png
```

## Documentation

Ontology documentation was generated using WIDOCO and is available through GitHub Pages.

## Team Members

* Fatma Alsaghir (220315105)

## Academic Use

This repository was developed for educational and research purposes as part of the Knowledge Engineering and Ontologies course project.
