# Lou Andaya
## Systems & Backend Engineer
> Software Developer focused on architecting **high-concurrency systems** and production-ready full-stack tools.
*Status:* **Self-Employed** open for Hiring
---

### **Primary Stack (Production-Ready)**
* **Backend:** Golang (Gorilla, Gin, Pgx, Sqlx)
* **Data:** PostgreSQL, Redis, Shopspring/Decimal (Financial Accuracy)
* **Frontend:** Svelte/SvelteKit, TypeScript/JS, Tailwind, Shad/cn, JQuery, Bootstrap
* **DevOps:** GitLab-CI, Docker, Docker Compose, Nginx
* **Cryptography:** Bcrypt (Passwords), SHA2, MD5/SHA1 (Integrity)
* **Tooling:** Git, SSH, BASH (Arch Linux / Vim workflow)

### **Extended Experience**
* **Web3/Systems:** Solidity (OpenZeppelin, Hardhat, Ethers.js), C/CMake
* **Messaging/NoSQL:** BullMQ, MongoDB/Mongoose
* **UI Libraries:** React, ReactRouter(v5/v6), Preact, SolidJS, Redux
* **Graphics/Rendering:** HTML Canvas, WebGL (Pixi.js)

### **Design & Media**
* **Prototyping:** Figma, Excalidraw, Notion
* **Editing:** Gimp, Audacity

---

### **Selected Project Work**

####  **Current Project - (Active Development)**
*A high-performance Merchant & Payment System architected for **Super Microtransactions**.*
* **Live Demo:** [Check it out here](https://your-demo-url.vercel.app)
* **Architecture:** Go (Backend) + Svelte/SvelteKit (Frontend).
* **Reviewer Access:** Use any of the following credentials (Password: `password123`)
    * `johndoe@mail.com` | `johndoe1@mail.com` | `johndoe3@mail.com` | `johndoe4@mail.com` | `johndoe5@mail.com`
* **Demo Constraints:** * Signups and Profile modifications are disabled for security.
    * Subscription and "Pro" features are currently mocked for architectural review.
    * Manual approval processes (e.g., deposits) are monitored periodically.

####  **Freenet Project - (actual name undiscloese)**
**What is it** During the crypto boom 2019 - 2022 I decided to build an ecosystem with one usable  platform and two tokens, sadly tokens never took off.
* **Note** this project was the last viable version of the project, because it was aquired by a startup, after its 4 months operation which has caused a lost after the peak of 3 months, and deu to the no disclosure agreement nature of the deal it was removed and handed over to them. What remains is the version that is in the pre-shipping but is working based on features. 




--- 

### Some Valuable Informations
- 💬 **Ask me about:**
    * **Systems & Infrastructure:** Planning, designing, and executing the full lifecycle from architecture to production shipping.
    * **The 81/19 Rule:** Why the "boring" 1% of setup prevents 20% of scaling failures.

- 🌱 **Currently Scaling My Knowledge:**
    * **Advanced DevOps:** Deep diving into Kubernetes and Ansible to supplement my Docker/GitLab-CI workflows.
    * **High-Performance Queues:** Transitioning to **RabbitMQ** for native Go integration (moving beyond JS-based BullMQ).
    * **Mobile & Native Development:** Architecting for the "Mobile-First" reality of modern user bases.
    * **System Design & Methodology:** Better translating complex ideas into executable processes.
    * **Business & Strategy:** Studying Management, Marketing, and Accounting to ensure project profitability and longevity.
    * **Communication:** Actively improving how I relay technical architecture to stakeholders and collaborators.


- 📫 **How t reach me:**
    * 📧 [Your Email]
    * 📱 [Your Mobile]
    * 🔗 [Your Facebook/LinkedIn]



--- 

# Notable Experiences 
> **Note:** Only  compiled from late 2025-2026. Research & Development Proof of Concepts (PoC).

---

### 1. Resource Sharding & Liquidity Locking (High-Concurrency)
**Problem:** A slot machine engine required high-speed, cluster-like matching for RTP (Return to Player) the balances and resouce getting exhausted.

**Solution: The "Vault Sharding" Pattern**
* **Architecture:** Segmented the central resource into **30 independent sub-vaults** to eliminate long locking and ending wait.

* **Fail-Safe:** Implemented a strict **3-second timeout** for funding requests. If a vault isn't secured within the window, the transaction fails gracefully rather than hanging the system.
* **Secondary Logic:** Developed a high-frequency variant specifically for systems requiring sub-millisecond response times.

**Contact me to discuss:** for systems like Slot machine logic, High-Frequency Trading (HFT), and liquidity tracking.

---

### 2. Fast Phased Development Methodology (Solo/Small Team)
**Problem:** Prioritizing coding velocity often leads to "shipping bottlenecks" where infrastructure and dependencies are not setup and neglected early on pileup and slow down shipping and launching of any service or feature

**Solution: Shift-Left Architectural Strategy**
1. **Prepare needs and Identify Dependecies:** Pre-identify infrastructure, DB schemas, and deployment targets *before* the first line of code, also works for any ventures.
2. **Limit Team size:** The more people working on a project or feature does not mean more productivity often times it leads to long development days and none are pushed.
3. **Iterative Development (A→B→C):**Building a feature or product can be done in one sprint, however it leads to  undiscovered variables that would cause a  rollback and redoing of same task because of causes that havent been concedred, by doing it in cycles you have a little bit of pause time to review, check and discover viable options for the next cycles.
4. **Pre-Logistic Handling:** Integrating market data and pricing early so "Shipping" is a toggle, not a 2-week task, because though menial it is a big part of the project.
5. **81/19 Rule:**  80/20 rule is the standard enough to not overengineer or to spend less time than needed, however the 1% that are usually brushed of would be a botleneck, like documentatons, some tests and others.

**Verdict:** Would 30% but more stable and linear and stable production launch .

---

### 3. Administrative Tools
**Problem:** Automation should not be the  replacement for monitoring. In high-stakes systems,  downtime or an unmonitored anomaly can cause massive losses.

**Solution: Dedicated Admin & Monitoring Systems**
*  **Admin/Observability Tools**  should be made viable, because as the project scale this tools would be needed, building a tool then would cost so much time and resource as path ways for this service must be opened opposed to alrady open pipeline for monitoring
---


**For more information or to discuss collaboration, reach out via Email or Facebook.**


