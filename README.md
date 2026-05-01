I’m developing an AI-assisted analysis tool for learners in embedded systems and RF engineering. The goal is to address common challenges in engineering education, such as fragmented learning materials, high comprehension costs, and the lack of systematic guidance during the design process.

In real-world courses and projects (e.g., microcontroller development and RF circuit design), students often need to consult a large number of English datasheets, research papers, and technical documents, and perform multiple rounds of understanding and organization. This process is usually time-consuming and inefficient. Therefore, I am building an “Engineering Learning Assistant Agent” based on large language models to support interactive analysis of complex technical content.

The core workflow of the system is as follows:

* Users input questions or upload technical materials (such as chip datasheets, lab reports, or design documents)
* The system parses long texts and performs structured understanding
* It supports multi-turn reasoning based on context (e.g., parameter calculation, principle explanation, and design suggestions)
* It outputs summaries or assists in generating design ideas (such as circuit schemes or code frameworks)

In implementation, I currently use a “long-context + multi-turn dialogue” approach, allowing the model to continuously track the same engineering task. For example, in an LNA design task, the system performs iterative analysis of parameters, S-parameter interpretation, and matching network design across multiple interaction rounds.
