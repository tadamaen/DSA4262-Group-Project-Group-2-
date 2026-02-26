# DSA4262 Group Project AY25/26 Semester 2 (Group 2)

This project investigates depression among students at the National University of Singapore (NUS) through a multi-layered data analysis approach. Our goal is to better understand depression prevalence, identify key contributing factors and explore how counselling session intervals may influence recovery trajectories. By integrating structured data (eg. survey-based depression scores, demographic attributes, counselling timelines) with unstructured raw text from students/patients experiencing depressive symptoms, we aim to generate actionable insights that can support evidence-based mental health interventions within the university.

Our solution prioritizes early detection and continuous monitoring as the core mechanism for reducing depression risk among students at the National University of Singapore. Rather than focusing primarily on reactive counselling, we design a preventive system that identifies at-risk individuals earlier and more systematically.

#### 1. Regular Check-Ins with Intelligent Screening (Primary Focus)

The foundation of our solution is a system of regular mental health check-ins using brief validated screening tools such as the PHQ-2, enhanced with dynamic follow-up questioning powered by large language models (LLMs). These adaptive prompts allow the system to probe deeper when risk signals are detected while remaining lightweight and non-intrusive for students. Responses collected through these check-ins are analyzed using textual classification models to detect linguistic markers of distress, escalating symptoms or crisis indicators. By combining structured scores (PHQ-2) with unstructured text analysis, the system can flag students who may require timely intervention. This proactive, data-driven triaging mechanism is the central pillar of our platform.

#### 2. Counsellor Communication Interface (Secondary Support Layer)

For students flagged as higher risk, the platform provides counsellors with the ability to initiate secure chat-based communication. This may include administering more comprehensive assessments such as the PHQ-9, conducting structured lines of questioning or engaging in therapeutic conversations when appropriate. However, this component is designed as a support layer rather than the primary focus of the system. Our emphasis remains on early detection and intelligent screening, with direct counselling interactions serving as a responsive extension when necessary.

#### 3. Counsellor Dashboard and Monitoring Tools

On the counsellors’ end, the platform includes a dashboard that aggregates risk signals, symptom trends and engagement metrics. This interface enables professionals to monitor flagged cases, track changes in mental health indicators over time and prioritize outreach based on urgency levels. Through visualization and structured summaries, the dashboard supports more informed decision-making, better workload management and data-driven intervention planning, ultimately enhancing the effectiveness and scalability of student mental health support services.
