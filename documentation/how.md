# [Project Name]: Technical Blueprint (How)

This document is the **definitive implementation guide** for [Project Name]. It defines the required state of the system architecture, modules, and implementation milestones.

## 1. Technical Philosophy
*   **[Philosophy 1]:** [Description using declarative language].
*   **[Philosophy 2]:** [Description].
*   **Strict Types:** [Description of type safety strategy].
*   **Small Modules:** Logic is decomposed into small, independent functional units (target < 200 LOC per file).
*   **Readability:** Code prioritization favors verbose naming and clear control flow over conciseness.

## 2. System Architecture

### 2.1. Tech Stack
*   **Technology 1:** [Technology name and version]
*   **Runtime:** [e.g. Node.js 22 (LTS)]
*   **Orchestration:** [e.g. Temporal]
*   **Database:** [e.g. PostgreSQL 17]
*   **ORM:** [e.g. Drizzle]
*   **Frontend:** [e.g. SvelteKit 2]
*   **AI:** [e.g. OpenAI Node SDK]
*   **CI/CD:** [e.g. GitHub Actions]

### 2.2. Directory Structure and Responsibilities

*   **`/[root]`**: Root directory.
    *   `[file]`: [Description of purpose].
*   **`/[path/to/module_a]`**: [Module Name].
    *   [Description of responsibilities].
*   **`/[path/to/module_b]`**: [Module Name].
    *   [Description of responsibilities].

## 3. Implementation Roadmap

The implementation is structured by Version. Within each Version, work is divided into functional Modules to minimize context switching.

### v0: [Version Name]
**Goal:** [Declarative goal, e.g., A hermetic environment where `devenv up` starts all services.]

#### 3.0.1. Infrastructure Module
1.  **[Component]:** [Declarative statement of what exists/is configured].
2.  **[Component]:** [Declarative statement].

#### 3.0.2. Testing & Verification
*   **Unit Tests:** [Requirements for unit tests].
*   **Integration Tests:** [Requirements for integration tests].
*   **Manual Verification:**
    1.  [Step 1 to manually verify results].
    2.  [Step 2 to manually verify results].

---

### v1: [Version Name]
**Goal:** [Goal description].

#### 3.1.1. [Module Name] (e.g., Orchestration)
1.  **[Feature]:** [Declarative statement].
2.  **[Feature]:** [Declarative statement].

#### 3.1.2. [Module Name] (e.g., User Interface)
1.  **[Feature]:** [Declarative statement].

#### 3.1.3. Testing & Verification
*   **Unit Tests:** [Requirements for unit tests].
*   **Integration Tests:** [Requirements for integration tests].
*   **Manual Verification:**
    1.  [Step 1 to manually verify results].
    2.  [Step 2 to manually verify results].

---

### v2: [Version Name]
**Goal:** [Goal description].

#### 3.2.1. [Module Name]
1.  **[Feature]:** [Declarative statement].

#### 3.2.2. Testing & Verification
*   **Unit Tests:** [Requirements for unit tests].
*   **Integration Tests:** [Requirements for integration tests].
*   **Manual Verification:**
    1.  [Step 1 to manually verify results].
    2.  [Step 2 to manually verify results].
