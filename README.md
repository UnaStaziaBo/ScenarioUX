# ScenarioUX

> **Experience your product before your users do.**

**ScenarioUX** is an AI-powered scenario-based UX simulation platform that helps product teams discover usability issues by simulating realistic user journeys on websites and web applications.

Instead of checking interfaces against static rules or predefined heuristics, ScenarioUX creates AI-driven user scenarios that attempt to complete real-world tasks, explaining every decision, hesitation, and failure along the way.

---

## The Idea

Today, software is tested automatically before release.

Developers run:

- Unit Tests
- Integration Tests
- End-to-End Tests

But user experience is still largely tested by real people after launch.

ScenarioUX aims to change that.

We believe UX should be testable before users ever visit your product.

Instead of waiting for customer feedback or conducting expensive usability studies, ScenarioUX simulates realistic user scenarios and identifies potential UX problems early in the development process.

---

## Example

Imagine you're building a healthcare website.

Instead of asking a real participant to test it, you create a scenario:

```
User
72-year-old first-time visitor

Goal
Book a doctor's appointment

Device
Mobile phone

Experience
Low digital literacy
```

ScenarioUX launches an AI agent that attempts to complete the task.

While navigating the website it continuously explains its reasoning:

> "I expected to find the booking button in the navigation."

> "This icon is unclear."

> "There are too many options."

> "I believe online booking is unavailable."

At the end, you receive a complete journey replay together with UX insights.

---

## Scenario-Based UX Simulation

Traditional tools answer:

> **What is wrong with the interface?**

ScenarioUX answers:

> **Why did the user struggle?**

Instead of generating technical reports, ScenarioUX focuses on behavior, decision making, and context.

Every simulation tells a story.

---

## Vision

ScenarioUX is not another accessibility checker.

It is not another UI audit.

It is not another browser automation framework.

ScenarioUX introduces a new category:

> **Scenario-Based UX Simulation**

AI agents perform realistic user journeys to evaluate user experience before real customers interact with your product.

---

## Planned Features

- Analyze any public website
- AI-powered browser agent
- Custom user scenarios
- Device simulation
- Different user experience levels
- AI reasoning during navigation
- Journey replay
- UX insights
- Compare multiple scenarios
- Shareable reports

---

## Example Workflow

```
Website URL
        │
        ▼
Create Scenario
        │
        ▼
Assign User Profile
        │
        ▼
Define Goal
        │
        ▼
Run Simulation
        │
        ▼
AI navigates the website
        │
        ▼
Journey Replay
        │
        ▼
UX Insights
```

---

## Why

Real usability testing is expensive.

User interviews take time.

Accessibility audits focus primarily on technical compliance.

ScenarioUX explores a different question:

> **Can a specific person successfully complete a specific task on this website?**

---

# Development Roadmap

ScenarioUX is being developed incrementally, with GPT-5.6 assisting throughout every stage of the engineering process.

## Phase 1 — Product Research

**Goal**

Define the product vision, identify the problem space, and establish a new category for AI-assisted UX evaluation.

**GPT-5.6 Used**

**GPT-5.6 Luna**

Tasks:

- Product brainstorming
- Naming
- Category definition
- UX positioning
- README drafting
- Documentation

---

## Phase 2 — System Architecture

**Goal**

Design the overall architecture of ScenarioUX.

Components:

- Frontend
- Backend API
- Browser Agent
- LLM Reasoning Engine
- Scenario Engine
- Reporting

**GPT-5.6 Used**

**GPT-5.6 Terra (High Reasoning)**

Tasks:

- Architecture design
- API planning
- Data flow
- Browser-agent interaction
- Scenario execution pipeline
- Technology selection

---

## Phase 3 — MVP Development

**Goal**

Build the first working prototype.

Features:

- Website URL input
- Scenario editor
- Browser automation
- AI reasoning
- Simulation results

**GPT-5.6 Used**

**GPT-5.6 Sol (Medium Reasoning)**

Tasks:

- React development
- Next.js implementation
- FastAPI backend
- Playwright integration
- API development
- Component generation
- General programming

---

## Phase 4 — AI Scenario Engine

**Goal**

Develop an intelligent browser agent capable of reasoning about user behavior.

Features:

- Goal planning
- Navigation decisions
- Context understanding
- Action selection
- Failure analysis

**GPT-5.6 Used**

**GPT-5.6 Terra (Ultra Reasoning)**

Tasks:

- Prompt engineering
- Agent reasoning
- Memory strategy
- Decision making
- Multi-step planning

---

## Phase 5 — UX Reports

**Goal**

Transform browser actions into human-readable UX insights.

Outputs:

- Journey replay
- AI reasoning
- UX observations
- Recommendations

**GPT-5.6 Used**

**GPT-5.6 Luna**

Tasks:

- Natural language generation
- Report formatting
- Insight summarization
- Storytelling

---

## Phase 6 — Optimization

**Goal**

Improve performance and reliability.

Tasks:

- Refactoring
- Performance optimization
- Debugging
- Code review
- Testing

**GPT-5.6 Used**

- GPT-5.6 Sol
- GPT-5.6 Terra

---

# GPT-5.6 Development Workflow

ScenarioUX is built using different GPT-5.6 models depending on the engineering task.

| Model | Primary Responsibility |
|---------|-----------------------|
| **GPT-5.6 Luna** | Product design, documentation, UX writing, README, reports |
| **GPT-5.6 Terra** | System architecture, AI reasoning, prompt engineering, planning |
| **GPT-5.6 Sol** | Application development, React, FastAPI, Playwright, debugging |

Reasoning levels are selected depending on the complexity of the task:

| Reasoning | Usage |
|------------|-------|
| Light | Small code changes, documentation, simple components |
| Medium | Daily development, APIs, frontend, backend |
| High | Architecture decisions, browser agent design |
| Ultra | Complex AI reasoning, planning, multi-agent behavior |

---

## Built with GPT-5.6

ScenarioUX is not only powered by AI—it is also engineered with AI.

GPT-5.6 serves as an active development partner throughout the entire software lifecycle, from product ideation and architecture to implementation, debugging, documentation, and UX design.

---

## Project Status

**Early Prototype**

Currently building the first proof of concept that combines:

- Playwright
- Vision-capable LLMs
- Browser automation
- AI reasoning
- Scenario simulation

---

## Contributing

Contributions, ideas, UX research, and discussions are welcome.

Let's build the future of automated UX testing together.

---

## License

MIT