

# Templates Directory

This directory contains all **model templates** used in the project.
Each template encapsulates the core logic and behavior of a specific system component and is designed to be modular, reusable, and extendable.

The templates here form the backbone of the simulation/modeling framework and are integrated by the central controller during execution.



## Directory Overview

The `FSM_templates/` folder includes logic templates for:

* **Vehicles**
* **Pedestrians**
* **Traffic Lights**
* **Emergency Vehicles**
* **Central Controller**

Each template focuses on defining:

* State transitions
* Interaction rules
* Control logic
* System constraints

This separation ensures clarity, scalability, and ease of collaboration among team members.



## Group Member Contributions

Although all group members contributed across multiple components, the table below highlights the **major contributions** made by each member.

| **Member**             | **Major Contribution**                                        |
| ---------------------- | ------------------------------------------------------------- |
| **Dhaval Bothra**      | Modelling Vehicle logic and Central Controller templates      |
| **Kandarp Kalavadiya** | Modelling Pedestrian logic templates and document preparation |
| **Rachit Soni**        | Modelling Traffic Light and Emergency Vehicle logic templates |
| **Ujwal Keshava**      | Modelling Traffic Light and Emergency Vehicle logic templates |
| **Girish Mundra**      | Modelling Vehicle logic and Central Controller templates      |



## Contribution Guidelines

* Each template should remain **self-contained**
* Avoid hard-coding parameters that may be configured globally
* Follow consistent naming conventions across templates




## Notes

* This directory is intended strictly for **template definitions**
* Supporting utilities or helper functions should reside outside this folder
* Documentation updates should reflect changes made to template logic

