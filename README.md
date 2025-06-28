# UE5 Blueprint Scripting Journey - Fahim Kamal Ahmed

[![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-5.5.1-blueviolet)](https://www.unrealengine.com/)
[![Focus](https://img.shields.io/badge/Focus-Blueprint%20Scripting-blue)](https://dev.epicgames.com/documentation/en-us/unreal-engine/blueprints-visual-scripting-in-unreal-engine)
[![Coursera Course](https://img.shields.io/badge/Coursera-Blueprint%20Scripting%20(Course%204)-0056D2?logo=coursera)](https://www.coursera.org/learn/blueprint-scripting?specialization=epic-games-game-design-professional-certificate)
[![Certificate Program](https://img.shields.io/badge/Coursera-Epic%20Games%20Game%20Design%20Certificate-0056D2?logo=coursera)](https://www.coursera.org/professional-certificates/epic-games-game-design-professional-certificate#courses)
[![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)](./)
[![GitHub Repository](https://img.shields.io/badge/GitHub-View%20Repository-blue?logo=github)](https://github.com/FahimKamal/UE5_BlueprintCourse)

---

## 🎓 Project Context & Motivation

This repository documents my learning journey and practical exercises undertaken by **Fahim Kamal Ahmed** as part of **Course 4: Blueprint Scripting**. This course is a component of the **[Epic Games Game Design Professional Certificate](https://www.coursera.org/professional-certificates/epic-games-game-design-professional-certificate#courses)** offered on Coursera.

The primary goal of this Unreal Engine project is to diligently apply the concepts taught in the "Blueprint Scripting" course. This involves practicing the creation of various gameplay mechanics and systems, thereby building a tangible portfolio of Blueprinting examples and deepening my understanding of Unreal Engine's visual scripting capabilities.

---

## 🎯 Overview

This Unreal Engine **5.5.1** project serves as a dedicated, hands-on workspace for exploring, implementing, and mastering **Blueprint visual scripting**. It will contain a progressively growing collection of scenes, Actors, components, and gameplay systems developed following the curriculum of the Epic Games Blueprint Scripting course.

This repository will showcase:
*   Implementations of course-specific exercises and challenges.
*   Experimentation with diverse Blueprint nodes, logic flows, and communication patterns.
*   Small, focused prototypes demonstrating core gameplay mechanics.

---

## 📚 Modules & Implemented Projects

This section highlights the major practical projects completed for each course module.

*   **Module 1: Blueprint Fundamentals & Interactive Elements**
    *   **Status:** ✅ Completed
    *   **Project: Interactive Door & Trigger System**
        *   Developed a `BP_Door` and a parent `BP_Trigger` class with three child variations: `BP_PressurePad`, `BP_Button`, and `BP_Lever`.
        *   The door system features an instance-editable `IsLocked` state and a configurable opening direction (Sideways or Up/Down) using an Enumeration.
        *   Visual feedback is provided via a dynamic emissive material on the door (Red for locked, Green for unlocked).
        *   This project demonstrates a robust, configurable, and reusable set of interactive elements.
    *   **Key Concepts Applied:** Actor Components, Variables (Boolean, Enum, Object Reference), Instance Editable Properties, Custom Events & Functions, Timelines, Event Dispatchers, Inheritance, Logic & Flow Control, Construction Script, Dynamic Material Instances.

*   **Module 2: Blueprint Communication & Advanced Triggers**
    *   **Status:** ✅ Completed
    *   **Challenge Project: Self-Contained Elevator**
        *   Created a `BP_Lift` as a child of the `BP_Trigger` class, demonstrating inheritance and system reuse.
        *   The elevator platform includes railings and a self-contained lever for activation.
        *   When the player interacts with the lever (via the Interaction Interface), the lever animates first. Upon completion of the lever's animation, the main platform begins its movement.
        *   The elevator's destination is determined by the position of a hidden "Roof" static mesh component, allowing for easy adjustment of travel height directly in the editor. The elevator returns to the world origin when toggled again.
    *   **Key Concepts Applied:** Advanced Component Hierarchy (using Scene Components as pivots), Stateful Logic (tracking up/down state), Sequential Animation (lever then platform), Traces, Interfaces, and combining multiple learned systems into a single, functional gameplay mechanic.

*   **Module 3: Characters, Cameras & Controls**
    *   **Status:** 🔄 In Progress / Current Focus
    *   Focus: Player character setup, camera controls, Enhanced Input system.

*   **Module 4: Gameplay Mechanics & Inventory System Example (Escape Room Capstone)**
    *   **Status:** ⏳ Not Yet Started
    *   Focus: Data Assets, UI (UMG), gameplay systems (e.g., inventory), capstone project development.

*(Emoji Legend: ✅ Complete, 🔄 In Progress / Current Focus, ⏳ Not Yet Started)*

---

## ✨ Key Learning Objectives (Guiding This Project)

This project aims to solidify my understanding and practical application of:
*   The foundational principles of Blueprint visual scripting and its synergy with C++ in Unreal Engine.
*   Core programming constructs within Blueprints: variables, data types, functions, macros, flow control (branches, loops), and event handling.
*   Designing and implementing interactive game elements and dynamic environmental features.
*   Effective Blueprint communication strategies: direct communication, casting, interfaces, and event dispatchers.
*   Developing player characters, controllers, camera systems, and responsive input configurations using the Enhanced Input system.
*   Creating user interfaces (UI) and heads-up displays (HUD) with Unreal Motion Graphics (UMG).
*   Managing game data using Data Assets and other appropriate structures.
*   Employing debugging techniques and best practices for testing and refining Blueprint logic.
*   Approaching game development tasks with a prototyping mindset, leveraging Blueprints for rapid iteration.

---

## 💻 Technology & Tools

*   **Engine:** Unreal Engine 5.5.1 ⚙️
*   **Primary Language/Tool:** Unreal Engine Blueprint Visual Scripting
*   **Course Provider:** Epic Games via Coursera
*   **Course:** [Blueprint Scripting (Course 4 of Epic Games Game Design Certificate)](https://www.coursera.org/learn/blueprint-scripting?specialization=epic-games-game-design-professional-certificate)
*   **Version Control:** Git & GitHub ([FahimKamal/UE5_BlueprintCourse](https://github.com/FahimKamal/UE5_BlueprintCourse))
*   **Documentation:** Markdown (for this README)
*   **Editor/IDE (for auxiliary tasks like README editing, light coding):** Visual Studio Code

---

## 🌱 Learning & Development Focus

The primary focus of maintaining this repository is to:
*   Systematically document the practical application of Blueprint scripting techniques as taught in the course.
*   Build a series of functional, working examples demonstrating common and advanced gameplay mechanics.
*   Develop a high level of proficiency in navigating, utilizing, and extending the Unreal Engine Blueprint system.
*   Create a valuable personal reference point for future Blueprinting projects and professional development.
*   Showcase progress and understanding of game development principles through practical implementation.

---

## 🔮 Future Plans (Beyond Course Completion)

*(This section will be populated with ideas as the course progresses or upon its completion. Potential avenues include expanding course projects into more robust portfolio pieces or exploring personal game concepts using the skills acquired.)*

*   Example: Deep-dive into more advanced Blueprint optimization techniques.
*   Example: Combine several learned mechanics into a cohesive mini-game or unique interactive experience.
*   Example: Explore the integration of Blueprints with C++ for more complex systems.

---

## 📜 Assets & Attributions

*   **Course Content & Instruction:** Provided by Epic Games, delivered via Coursera.
*   **Unreal Engine & Default Assets:** Copyright Epic Games, Inc. Used under the Unreal Engine EULA.
*   **All custom Blueprint logic, project structure, and specific implementations within this repository (unless otherwise explicitly stated for a particular asset):** Original work by **Fahim Kamal Ahmed** created as part of the learning process for the "Blueprint Scripting" course. No proprietary course materials (slides, videos, direct code solutions not created by Fahim Kamal Ahmed) will be hosted in this repository.

---

## ⚖️ Licensing

The original Blueprint scripts, unique configurations, and specific project work created by **Fahim Kamal Ahmed** within this `UE5_BlueprintCourse` repository are licensed under the **MIT License**. Please see the `LICENSE` file in this repository for the full license text.

**Note on Third-Party Assets & Course Material:**
Unreal Engine and any assets provided directly by Epic Games are subject to their respective End User License Agreements (EULAs) and licensing terms. Educational materials from the Epic Games / Coursera course are subject to Coursera's and Epic Games' terms of use. The MIT license for this repository applies to the original contributions and learning artifacts created by Fahim Kamal Ahmed.

---