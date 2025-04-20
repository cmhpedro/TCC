# ArchHypo Tooling - Enabling Practical Hypothesis Engineering for Software Architecture

## The Problem and Relevance

Software architecture design is a critical yet complex process, often hindered by uncertainties regarding requirements and potential solutions. While agile methodologies have successfully introduced practices like Test-Driven Development and refactoring, they often lack well-recognized and agreed-upon approaches for architectural design. Frequently, the most common approach is letting the architecture "emerge" over the project life, leading mature teams to develop their methods while newer teams struggle. This lack of established practice means architectural changes remain challenging within agile contexts, often necessitating significant upfront design that contradicts core agile principles.

Furthermore, existing methods frequently rely heavily on experienced architects' tacit knowledge, lacking sufficient support for less experienced practitioners and robust evaluation mechanisms. Souza et al.'s systematic mapping study [1] highlighted these gaps, noting that about a third of analyzed architectural derivation approaches lack tool support, and over half lack explicit evaluation methods. This points to a clear need for tools to aid architects, suggesting patterns and supporting decision-making to reduce dependency on seasoned experts.

Hypothesis Engineering offers a philosophical approach to managing uncertainty by treating assumptions as testable hypotheses. Building on this, ArchHypo provides a theoretical framework specifically for handling architectural uncertainties. It involves identifying architectural hypotheses, assessing their impact and uncertainty level, and creating technical plans to manage them.

However, Silva et al. empirical research on ArchHypo [2] demonstrated benefits like better collaboration and a structured approach to architectural work and revealed significant adoption challenges. Participants found the technique hard to learn, particularly in mapping risks, specifying hypotheses, and defining action plans. This study highlighted a strong need for better guidance and, crucially, **tool support to manage hypotheses and execute action plans**, which could lessen team dependency on architects.

Therefore, while Hypothesis Engineering provides the philosophy and ArchHypo the framework, a practical, accessible tool is missing to implement this approach in real-world software development effectively. This capstone proposes the development of such a tool.

## Capstone Project Goals

The primary goal of this capstone project is to design and develop a software tool that operationalizes the ArchHypo framework, focusing on supporting architectural decision-making under uncertainty. This tool aims to bridge the gap between the theoretical ArchHypo framework and its practical application by addressing the documented needs for better hypothesis management and action plan execution support.

Specific objectives include:

1. **Develop an ArchHypo Tool**: Create a software application that allows teams to:
    - Explicitly document and manage architectural hypotheses.
    - Assess hypotheses based on impact and uncertainty levels.
    - Define and track technical action plans associated with each hypothesis.
    - Visualize the status and evolution of hypotheses and their plans over time.
2. **Ensure Modularity and Integrability**: Design the tool with a modular architecture, enabling it to be:
    - Used as a standalone application.
    - Integrated with existing developer portals or project management platforms (e.g., Backstage)  through APIs or plugins, facilitating seamless adoption into diverse development workflows.
3. **Address Learning Curve Challenges**: Incorporate features aimed at simplifying the adoption of ArchHypo, such as:
    - Templates or guidance for hypothesis specification.
    - Suggestions or patterns for common technical plan actions based on hypothesis characteristics (allowing for creative solutions).

By achieving these goals, this capstone will provide a tangible solution to the identified gap in tool support for managing architectural uncertainty, making the benefits of the ArchHypo framework more accessible to software development teams.

## References

1. E. Souza, A. Moreira, and M. Goulão, "Deriving architectural models from requirements specifications: A systematic mapping study," Information and Software Technology, vol. 109. Elsevier BV, pp. 26–39, May 2019. doi: 10.1016/j.infsof.2019.01.004.

2. K. Silva, J. Melegati, F. Silveira, X. Wang, M. Ferreira, and E. Guerra, "ArchHypo: Managing Software Architecture Uncertainty Using Hypotheses Engineering," IEEE Transactions on Software Engineering, vol. 51, no. 2. Institute of Electrical and Electronics Engineers (IEEE), pp. 430–448, Feb. 2025. doi: 10.1109/tse.2024.3520477.

3. K. Silva, J. Melegati, X. Wang, M. Ferreira, and E. Guerra, "Using Hypotheses to Manage Technical Uncertainty and Architecture Evolution in a Software Start-up," IEEE Software, vol. 41, no. 4. Institute of Electrical and Electronics Engineers (IEEE), pp. 7–13, Jul. 2024. doi: 10.1109/ms.2024.3383628.
