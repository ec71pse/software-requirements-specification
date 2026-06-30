# software-requirements-specification
# Chatty 2.0

## About the Project

**Chatty 2.0** is a web application for learning English designed as an improved version of the original Chatty platform. The project extends the existing functionality by introducing a personal vocabulary, flashcards, and self-study tools to make vocabulary acquisition more effective.

The system supports two user roles:

* **Students** — search for new words, build a personal vocabulary, create flashcards, and practice with self-testing.
* **Teachers** — create and assign learning activities for students.

---

## Project Goal

The goal of the project was to define clear and complete software requirements for the next version of the application, ensuring that the development team had a well-structured specification covering both business needs and technical constraints.

---

## My Role — System Analyst

As a **System Analyst**, I was responsible for:

* gathering and analyzing business requirements;
* eliciting and documenting functional and non-functional requirements;
* identifying user roles and business processes;
* describing user scenarios (Use Cases);
* defining the system's data model and core entities;
* specifying integrations with external dictionary, audio, and video services;
* documenting performance, security, availability, and compatibility requirements;
* preparing a complete **Software Requirements Specification (SRS)** for the development team.

---

## Key Features

### Dictionary

* Search for word translations.
* Display definitions and additional word information.
* Listen to pronunciation.
* Watch contextual videos containing the searched word.
* Manage a personal vocabulary (add, view, and remove words).

### Flashcards

* Create flashcards from saved vocabulary.
* Manage flashcards.
* Practice vocabulary using a self-testing mode.

### User Roles

* Student
* Teacher

---

## Non-Functional Requirements

* Browser support: **Chrome**, **Safari**
* Mandatory user authentication
* Integration with third-party dictionary, audio, and video services
* PostgreSQL as the primary database
* HTML5-based web interface
* Page loading time ≤ **3 seconds**
* Word addition time ≤ **1 second**
* System availability ≥ **99%** during daytime

---

## Deliverables

The final outcome of the project is a complete **Software Requirements Specification (SRS)** that includes:

* Functional Requirements
* Non-Functional Requirements
* User Roles
* Use Cases
* Business Rules
* Data Model
* Integration Requirements
* System Constraints

