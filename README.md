# CSE-326 Information System Design

## 📚 Project: StudyBuddy - AI-Powered Learning Platform

This repository contains comprehensive system design artifacts developed as part of the CSE-326 (Information System Design) course. The project focuses on designing **StudyBuddy**, an intelligent learning platform that helps students enhance their study experience through AI-powered features.

## 🎯 Project Overview

**StudyBuddy** is an educational platform designed to assist students by providing intelligent study tools including:
- **Document Processing**: Upload and analyze PDF documents to extract text, images, and tables
- **Content Generation**: Automatically generate study materials from uploaded resources
- **Quiz System**: Create and take AI-generated quizzes based on study materials
- **Interactive Chat**: AI-powered chat assistance for learning
- **Recommendation System**: Personalized study resource recommendations
- **Resource Management**: Organize and process educational materials

## 📂 Repository Structure

```
.
├── BPMN/                      # Business Process Model and Notation diagrams
├── Class Diagram/             # UML Class diagrams
├── Collaboration Diagram/     # UML Collaboration diagrams
├── Layered Architecture/      # System architecture documentation
├── Mock UI/                   # User interface mockups
├── UseCase-TestCase/          # Use cases and test cases
└── README.md                  # This file
```

## 📁 Directory Contents

### 🔄 BPMN (Business Process Modeling)
Contains BPMN diagrams illustrating the system's business processes and workflows.

**Location**: `BPMN/`

**Key Files**:
- `final/ISD-BPMN-StudyBuddy.pdf` - Final BPMN diagram (PDF)
- `final/BPMN-Diagram-StudyBuddy.svg` - Final BPMN diagram (SVG)
- `final/v4.bpmn` - BPMN source file
- `versions/` - Historical versions of BPMN diagrams

**Purpose**: Visualizes the workflow and processes within the StudyBuddy system, including user interactions and system operations.

---

### 🏗️ Class Diagram
Contains UML class diagrams showing the system's object-oriented structure.

**Location**: `Class Diagram/`

**Key Files**:
- `StuddyBuddy.drawio_finalv6.pdf` - Final class diagram

**Purpose**: Illustrates the static structure of the system, including classes, attributes, methods, and relationships between objects.

---

### 🤝 Collaboration Diagram
Contains UML collaboration diagrams demonstrating object interactions.

**Location**: `Collaboration Diagram/`

**Key Files**:
- `collab.pdf` - Collaboration diagram

**Purpose**: Shows how objects interact in a particular scenario, focusing on the organization of objects and their relationships.

---

### 🏛️ Layered Architecture
Documents the system's architectural layers and component organization.

**Location**: `Layered Architecture/`

**Key Files**:
- `StudyBuddy Layered Architecture With Images.pdf` - Architecture documentation

**Purpose**: Describes the multi-tier architecture of the StudyBuddy system, including presentation, business logic, and data layers.

---

### 🎨 Mock UI
Contains user interface mockups and design prototypes.

**Location**: `Mock UI/`

**Key Files**:
- `A1_G4_MockUI_StudyBuddy.pdf` - UI mockups and wireframes

**Purpose**: Visualizes the user interface design and user experience flow of the StudyBuddy application.

---

### ✅ UseCase-TestCase
Contains detailed use cases and corresponding test cases for system validation.

**Location**: `UseCase-TestCase/`

**Key Files**:
- `A1-4_StudyBuddy_submitted.json` - Complete use cases and test cases (JSON format)
- `A1_G4_StudyBuddy_UseTest_slide.pdf` - Presentation slides for use cases and test cases
- `beamer_preparation.py` - Python script to generate LaTeX Beamer presentation from JSON
- `Modules/` - Module-specific use cases and test cases:
  - `resource-processing.json` - Document processing use cases
  - `content-generation.json` - Content generation use cases
  - `use_test_quiz.json` - Quiz system use cases
  - `use_test_chat.json` - Chat system use cases
  - `UcaseTcase_recommender.json` - Recommendation system use cases

**Purpose**: Documents functional requirements through use cases and defines test scenarios to validate system behavior.

#### Sample Use Cases
The repository includes comprehensive use cases for:
1. **Resource Document Preprocessing** - PDF upload and processing
2. **Content Generation** - Automated study material creation
3. **Quiz Generation** - Interactive quiz creation from study materials
4. **Chat System** - AI-powered learning assistance
5. **Recommendation System** - Personalized resource suggestions

## 🛠️ Tools & Technologies Used

- **BPMN Modeling**: Business Process Model and Notation for workflow design
- **UML**: Unified Modeling Language for system design
- **Draw.io**: Diagramming tool
- **Python**: For presentation generation utilities
- **LaTeX/Beamer**: For presentation slides
- **JSON**: Data format for use cases and test cases

## 📖 How to Use This Repository

### Viewing Design Artifacts
1. **BPMN Diagrams**: Open PDF/SVG files in `BPMN/final/` directory
2. **Class Diagrams**: View `Class Diagram/StuddyBuddy.drawio_finalv6.pdf`
3. **Architecture**: Review `Layered Architecture/StudyBuddy Layered Architecture With Images.pdf`
4. **UI Mockups**: Check `Mock UI/A1_G4_MockUI_StudyBuddy.pdf`
5. **Use Cases**: Examine JSON files in `UseCase-TestCase/` or view the presentation PDF

### Generating Presentation from Use Cases
To generate a LaTeX Beamer presentation from the use case JSON files:

```bash
cd UseCase-TestCase
python beamer_preparation.py
```

This will create an `output_beamer.tex` file that can be compiled with LaTeX.

## 🎓 Course Information

- **Course**: CSE-326 - Information System Design
- **Project**: StudyBuddy - AI-Powered Learning Platform
- **Focus Areas**: System design, requirements engineering, UML modeling, process modeling

## 📋 Design Artifacts Included

- ✅ Business Process Model and Notation (BPMN) diagrams
- ✅ UML Class diagrams
- ✅ UML Collaboration diagrams
- ✅ Layered architecture design
- ✅ User interface mockups
- ✅ Comprehensive use cases with test cases
- ✅ Module-specific functional requirements

## 🤝 Contributing

This is an academic project repository. Design artifacts are organized by type and version-controlled for iterative development.

## 📄 License

This repository is part of academic coursework for CSE-326.

## 👥 Team

Group 4 (G4) - CSE-326

---

**Note**: This repository contains design documentation and artifacts. No implementation code is included as this is a system design course focusing on requirements analysis, modeling, and architectural design.
