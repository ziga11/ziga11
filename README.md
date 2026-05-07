# Technical Portfolio
### B.Sc. Computer Science & Informatics | Full-Stack & Systems Engineering

Most interested in full-stack and backend development. Most interested in algorithms. 

## 🏗️ Core Engineering Projects
### Modular HR System (HRIS & Onboarding)
**[System Hub/Main Repo](https://github.com/ziga11/hr_system_hub)**
* **Scope:** **Solo Development** of a system which helps the recruiter as well as the recruitee.
* **Mobile Infrastructure:** * **Backend:** Engineered in **Go (Golang)** for the ease of implementation and potential large user handling by using **GoRoutines**.
    * **Client:** Developed a cross-platform mobile **ESS (Employee Self-Service)** app using **Flutter (Dart)** for candidate onboarding and employment tracking.
* **System of project tables** * **Frontend:** Built with TypeScript and Vite. I focused on making the UI feel like a spreadsheet (like Monday.com) where you can add rows and columns on the fly, while also be able to trigger code elsewhere via automations built into the boards.
    * **Data Layer:** Used **Supabase** as an experimental choice to evaluate its "Backend-as-a-Service" features.
* **Project forms** Separate **Node.js/TypeScript** backends and **Vite** frontends for dynamic form generation (stores info about the companies the HR firm employ for).

### Vanilla WebGL2 MMO Engine
**[Repo](https://github.com/ziga11/MMOGame/)**
* **Scope:** **Solo Implementation** of a 3D game engine.
* **Core Engine:** Pure JavaScript & WebGL2. Built without external graphics, physics, or entity-management libraries.
* **Spatial Data Structures:** * Implemented recursive **Octrees** for 3D collision detection and frustum culling.
* **AI & Logic:** Custom **A\* Pathfinding** with **Binary Heaps** for autonomous mob behavior and ray-casting mechanics for combat interaction.

### Geospatial Matching Engine (Specialized Utility)
**[Repo](https://github.com/ziga11/candidate-matching)**
* **Scope:** Individual script developed for industry application to solve high-volume candidate matchmaking.
* **Problem:** Standard SQL/Linear search methods for thousands of candidates were inefficient for real-time proximity matching.
* **Optimization:** Engineered a **Quadtree spatial indexing** algorithm to reduce candidate-to-job proximity search complexity from $O(n)$ to $O(\log n)$.
* **Workflow:** Used **AI** to find the best fitting job, used candidate's coordinates and skills, .

### MonoGame Engine & Creature Battler
**[Repo](https://github.com/ziga11/TINR)**
* **Scope:** **Solo Implementation** of a 2D RPG engine using C# and the MonoGame framework.
* **Collision Engineering:** Developed a **Pixel-Perfect Collision** system using a dual-texture masking technique (visual vs. collision stencil) to handle complex entity interactions.
* **Optimization & Memory:** Leveraged **Texture Atlasing** and efficient SpriteBatch management to minimize draw calls and optimize GPU memory usage.
* **State Management:** Architected a **Finite State Machine (FSM)** to handle global game states, enabling decoupled logic between exploration, turn-based combat, and UI overlays.

### Image Processing Tool: Histogram Equalization
**[Repo](https://github.com/ziga11/Histogram-Equalization/)**
* **Scope:** Implementation of a **Contrast Enhancement** algorithm for digital image processing.
* **Core Logic:** Developed an algorithm to calculate **Probability Density Functions (PDF)** and **Cumulative Distribution Functions (CDF)** to re-map pixel intensities.
* **Implementation:** Built a custom pipeline to process image histograms, effectively spreading out the most frequent intensity values to increase global contrast and reveal hidden detail in low-exposure images.

---

## 🛠️ Technical Proficiencies
* **Languages:** JavaScript (ES6+), Python, SQL, GLSL (Shaders), C#, C, Go, Dart.
* **Computer Science:** Spatial Partitioning (Quadtrees, Octrees), Pathfinding (A*), Computational Geometry.
* **Back-End:** Node.js, Event-Driven Middleware, RESTful API Design.
* **Front-End & Graphics:** Flutter, WebGL2 (Buffer/Shader management).
