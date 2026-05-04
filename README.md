 Overview

This project represents a College Database system designed to manage student enrollment in courses. It uses both ER (Entity-Relationship) modeling and UML (Unified Modeling Language) to clearly define the data structure and system design.

 ER Diagram Concept

The ER diagram shows how data is stored and related in the database.

Entities: STUDENT, COURSE, REGISTRATION
Primary Keys (PK): Unique identifiers (StudId, courseid)
Foreign Keys (FK): Used in REGISTRATION to connect STUDENT and COURSE
Relationship:
Student ↔ Course → Many-to-Many
Resolved using REGISTRATION entity

 UML Diagram Concept

The UML Class Diagram represents the system in an object-oriented format.

Classes: Student, Course, Registration
Attributes: Same as ER entities
Associations: Relationships between classes
Multiplicity:
One student → many registrations
One course → many registrations

One-line Description

A College Database project demonstrating ER and UML concepts to model student-course enrollment with proper relationships and system structure.
