# SIEM-Development-Chart
The SIEM Development Chart is a comprehensive architectural blueprint designed to guide the deployment, management, and continuous evolution of a Security Information and Event Management (SIEM) ecosystem. While originally conceived before the advent of SOAR (Security Orchestration, Automation, and Response), the framework’s core tenets—telemetry integrity, procedural documentation, and role-based oversight— drive the standard for excellence in continuos improvement for both deployment and maintenace. 

The framework is not a linear checklist, but a modular lifecycle. It recognizes that while an organization may not require every single document or sub-process to achieve an "initial operating capability," the consideration of these entities is what separates a high-fidelity security control from a noisy, unmanaged data lake. While this chart was originally designed for SIEM, the chart can easily fit other security controls. 

# Considerations
Just like any other security control, Just as threats evolve, the SIEM must be a "living" entity. The circular nature of the chart reflects the Plan-Do-Check-Act (PDCA) cycle. A security control that is not continuously tuned becomes a liability. By implementing the framework's entities, organizations create a repeatable loop where incident post-mortems and threat research naturally feed back into the detection logic, ensuring the SIEM, or any other control, matures alongside the adversary.
## Separation of Duties and Governance
A critical consideration for the framework is the mitigation of "Key Person Risk" and the establishment of objective oversight. The Trinity of Roles: Even in small teams, the framework works well with a three-pillar responsibility model:
* The Implementer (Engineer): Focuses on technical configuration, data ingestion, and regex/parsing.
* The User (Analyst): Consumes the alerts, validates the signal, and provides feedback on noise.
* The Approver (Architect/Manager): Ensures the detection logic aligns with business risk and compliance requirements.

One person should never be the developer, approver, and maintainer. Without this separation, "blind spots" are often introduced into the system. I think, however, most people already know that already. 

I still may write the book that inspired the creation of this chart I am just unsure if there is an interest. Instead, I decided to release this to the world. hope you find it useful


*Kenneth Ray*
