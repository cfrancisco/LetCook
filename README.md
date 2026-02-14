# 🍳 Let’s Cook

**A Serious Game Protocol for Controlled Emotional Induction**

## Overview

**Let’s Cook** is a serious game developed in 2023 as part of an experimental protocol designed for **controlled emotional induction in a laboratory setting** (CAAE: 67799523.9.0000.5407).

The project aims to systematically manipulate emotional states through structured interaction with AI-controlled agents in a time-pressured cooking simulation environment.

---

## Experimental Rationale

Digital games provide a structured, controllable environment capable of eliciting measurable emotional responses. Let’s Cook was designed to:

* Provide high experimental control
* Enable behavioral standardization
* Manipulate social interaction variables
* Induce distinct affective states under time pressure

The emotional manipulation is operationalized through controlled variation in the behavior of an AI assistant interacting with the participant.

---

## Game Design

The game was developed using **Unity 2021 LTS**, incorporating open-source and freely available assets.

Participants assume the role of a cook responsible for preparing and delivering as many orders as possible within **60 seconds per round**.

### Core Mechanics

* Cooperative interaction between:

  * The player (participant-controlled cook)
  * A virtual assistant (AI-controlled agent)
* Order generation and scoring system
* Continuous on-screen display of:

  * Remaining time
  * Current score
  * Pending orders
* Performance evaluation system (0–3 stars per round)

---

## Virtual Environment

The kitchen simulation includes:

**Workstations**

* Cutting board
* Stove
* Assembly counter
* Delivery area

**Ingredients**

* Tomato
* Onion

**Recipes**

* Tomato + Tomato
* Onion + Onion

Additional features:

* Dialogue box displaying assistant emojis
* Auditory alerts (burning food, new orders, time expiration)

---

## Experimental Manipulation: Assistant Personality Profiles

The primary independent variable consists of three AI behavioral profiles designed to elicit distinct emotional responses.

### 1. Facilitator (Positive Induction Condition)

Designed to elicit positive affect (e.g., satisfaction, confidence, enjoyment).

Behavioral parameters:

* Increased movement speed
* Efficient chopping and delivery
* Cooperative task prioritization
* Positive emoji feedback

---

### 2. Neutral (Control Condition)

Designed to minimize emotional interference.

Behavioral parameters:

* Baseline movement speed
* Neutral emoji feedback
* No cooperative enhancement or sabotage

---

### 3. Detractor (Negative Induction Condition)

Designed to elicit negative affect (e.g., frustration, stress, irritation).

Behavioral parameters:

* Reduced movement speed
* Occasional failure to prioritize tasks
* Delayed responses
* Sarcastic, confused, or sleepy emoji feedback
* Subtle task interference behaviors

---

# 🔥 Undercooked

**Technical Predecessor Project**

## Overview

**Undercooked** is a fan-made technical recreation inspired by **Overcooked**, developed as a programming and game architecture exercise.

This project:

* Has no commercial intent
* Has no legal affiliation with the original franchise
* Was created as a technical learning and production challenge
* Focused on system implementation rather than game design innovation

Undercooked served as the foundational technical prototype that later informed the architecture of Let’s Cook.

---

## Design Goals

* Recreate core cooking-game mechanics
* Implement a complete and functional gameplay loop
* Maintain reduced scope (single-level implementation)
* Emphasize code architecture and systems design

---

## Core Implemented Systems

* Context-based `Interactable` selection (proximity + orientation)
* `IPickable` interface abstraction
* Contextual Pick/Drop logic
* Ingredient sourcing from crates
* Chopping system
* Cooking system with timers and burn states
* Plate assembly and validation
* Dual-avatar control switching
* Trash and sink systems
* Animated order panel UI

Player movement and interaction timing were carefully recreated to approximate the responsiveness and pacing of the reference title.

---

## Technical Highlights

* Asynchronous programming combined with Coroutines
* Extensive use of C# Pattern Matching
* Event-based Unity Input System
* Particle Systems (smoke, steam, dust, stars)
* Custom Unity Package usage
* Shader Graph materials

---

## Development Tools

* Unity 2021.3.11f1 LTS
* Autodesk Maya
* Adobe Photoshop
* Adobe Illustrator

Auxiliary tools:

* Unity Cinemachine
* LeanGUI
* LeanTransition
* FBX Exporter

---

## Relationship Between Projects

Undercooked functioned as a technical sandbox for:

* Interaction architecture
* State management systems
* Gameplay loop refinement

Let’s Cook extends that foundation into a scientifically structured serious game framework designed for experimental research.