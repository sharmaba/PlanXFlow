# Planning Functionalities and Classes

This page provides an overview of various planning functionalities in AI systems, including their definitions, and categorization in classes. These functionalities serve as building blocks for designing, deploying, and integrating advanced AI planning systems.

---

## Planning Functionalities

### Core Functionalities

| **Functionality**      | **Description**                                                                                              |
|------------------------|----------------------------------------------------------------------------------------------------------|
| **Parsing**            | Parsing analyzes whether a planning problem conforms to the syntactic rules of the chosen modeling language, such as PDDL or HDDL. This ensures that the problem definitions are valid and interpretable, identifying errors early and reducing debugging time. |
| **Conversion**         | Conversion transforms planning data into representations tailored to specific needs, such as translating domain models into programming objects or plan outputs into visualization formats. The conversion to programming objects would be to enable planner to solve the planning problems. |
| **Problem Generation** | Automatically creates planning problem instances using real-time data, such as IoT inputs. This functionality adapts systems to dynamic environments, vital for fields like robotics, living environments, and autonomous driving. |
| **Plan Generation**    | Computes a course of action that can take a form of a sequence, set, policy, or other structure. The execution of the course of action or plan in the initial state should satisfy the objective e.g. a goal state, a goal task etc. Various algorithms and methods can be used to generate plans. |

---
### Plan Execution and Management Functionalities

| **Functionality**      | **Description**                                                                                              |
|------------------------|----------------------------------------------------------------------------------------------------------|
| **Execution**          | Manages the execution of plans in real-world or simulated environments, ensuring correct sequencing and integration with external systems.  |
| **Monitoring**         | Observes plan execution to detect anomalies, such as delays or failures. Triggers fault tolerance to maintain alignment with goals. |
| **Fault Tolerance**          | Addresses unexpected events during execution, providing error recovery and re-planning mechanisms. Essential for critical applications like healthcare or autonomous systems. |
| **Plan Validation**    | Validates plans for feasibility and consistency before execution, improving reliability and user trust.  |

---
### Domain Learning and Adaptation Functionalities

| **Functionality**      | **Description**                                                                                              |
|------------------------|----------------------------------------------------------------------------------------------------------|
| **Knowledge Learning** | Automates the creation of domain models, heuristics, and control knowledge. By utilizing machine learning, it minimizes manual effort and adapts to changing scenarios. |

---

### Performance-Driven Functionalities

| **Functionality**      | **Description**                                                                                              |
|------------------------|----------------------------------------------------------------------------------------------------------|
| **Learning-Enhanced Plan Generation**           | Enhances planning efficiency and quality by learning from past results, refining algorithms, and minimizing computational overhead. |
| **Strategising**       | Applies domain-specific heuristics or preferences to guide planning, enabling high-quality or approximate solutions quickly. Strategies can optimize time, cost, or other objectives. |


---

### System Operation Functionalities

| **Functionality**      | **Description**                                                                                              |
|------------------------|----------------------------------------------------------------------------------------------------------|
| **Data Management**    | Manages the storage and retrieval of domain models, problem instances, plans and other relevant data, ensuring accessibility and scalability. |
| **System Management**  | Handles coordination and communication across planning components, managing errors and ensuring smooth operations. |
| **System Monitoring**  | Oversees the performance and health of the planning system, tracking resource usage and interactions for optimization. |

---
### Human-Interaction Functionalities

| **Functionality**      | **Description**                                                                                              |
|------------------------|----------------------------------------------------------------------------------------------------------|
| **Explanation**        | Offers insights into planning decisions, explaining why actions were chosen or structured. Enhances transparency and user understanding through visual aids or summaries. |
| **Modelling**          | Enables manual specification of planning problems through textual or graphical tools, simplifying complex scenarios for users. |
| **Visualization**      | Provides graphical representations, such as charts or tables, to aid decision-making and track execution progress in real-time. |
---

### Other Functionalities

| **Functionality**      | **Description**                                                                                              |
|------------------------|----------------------------------------------------------------------------------------------------------|
| **Translation**      | Converts planning problems into alternative representations, such as constraint satisfaction problems. This approach may offer advantages in terms of efficiency, feasibility, and simplicity. |

---

## Positioning of Planning Classes 

The positioning of planning classes is defined by two dimensions: capability and evolution of use. The capability dimension represents the degree to which a planning system can perform complex tasks, ranging from basic functionalities to advanced, fully integrated planning operations. The evolution of use dimension reflects the system's potential to develop and adapt over time, from experimental and prototyping phases to widespread deployment in critical applications. Together, these dimensions provide a framework for understanding how different planning functionalities progress in complexity and real-world applicability.



---
