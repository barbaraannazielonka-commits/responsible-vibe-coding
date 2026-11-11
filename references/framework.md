# Supplied framework — source reference

Created by Barbara Anna Zielonka, based on *The Vibe-Code of Ethics*.

Source: THE VIBE-CODE OF ETHICS(1).docx, supplied by its creator. Retained as source material, not independently verified current legal guidance. Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/); see `../LICENSE.md`.

## Contents
- Introduction and responsibility (1)
- Pedagogy and purpose (2–4)
- Privacy and student rights (5–8)
- Security and runtime AI (9–10)
- Inclusion and dignity (11–13)
- Assessment, transparency and intellectual property (14–16)
- Testing, failure and documentation (17–19)
- Governance, sharing and maintenance (20–22)
- Readiness gates (23)
- Practical risk classification (24; table follows source text)
- Creator commitment (25) and further reading

THE VIBE-CODE OF ETHICS
A Responsible Creation Framework for Educators Building AI-Powered Educational Tools

1. A NEW RESPONSIBILITY: FROM EDUCATOR TO TECHNOLOGY CREATOR
Artificial intelligence has changed who can create software.
With the help of AI tools/coding assistants, teachers can now build websites, applications, educational games, simulations, interactive learning environments, assessment tools and AI-powered assistants without having extensive programming experience.
This creates extraordinary opportunities for educational innovation. Teachers can respond directly to classroom needs, experiment with new learning experiences and create resources that traditional educational technology providers might never develop.
However, the ability to create software does not automatically provide the knowledge required to develop it safely.
When educators build tools for students, they take on responsibilities that extend beyond writing instructions for an AI coding assistant. They become responsible for considering the pedagogical, ethical, legal, technical and social consequences of the products they create.
A tool that works is not necessarily a tool that is safe.
A tool that is engaging is not necessarily a tool that supports learning.
A tool that is free is not necessarily a tool that protects privacy.
A tool that uses AI is not necessarily intelligent, accurate or fair.
The Vibe-Code of Ethics establishes principles that should guide educators throughout the entire development lifecycle, from the first idea to deployment, evaluation and eventual retirement of an educational tool.
Who is this framework for?
Teachers building websites, applications and interactive learning resources.
Educators experimenting with AI-powered learning assistants and agents.
Teachers creating simulations, educational games and virtual environments.
School leaders evaluating teacher-developed digital resources.
Educational innovators sharing their creations with other schools.
Anyone using AI coding platforms to develop tools that students or colleagues will use.
The fundamental principle
The best educational technology is the technology that serves a clearly identified educational purpose while respecting the rights, safety, dignity and needs of its users.

PART I. PEDAGOGY AND PURPOSE
2. START WITH PEDAGOGY, NOT TECHNOLOGY
Before opening an AI coding assistant, ask yourself why the tool needs to exist.
Vibe coding makes it tempting to start with an exciting idea, an attractive interface or an interesting AI feature. However, educational design should begin with a learning need rather than a technological possibility.
Consider the following questions:
The educational purpose
What specific learning problem am I trying to address?
What do students currently struggle with?
What learning experience am I trying to improve?
Is there evidence that this type of intervention could support the intended learning?
Does the tool address a genuine need or simply introduce another digital distraction?
Curriculum alignment
Which curriculum objectives does the tool support?
Does it develop subject-specific knowledge, skills or competencies?
Is it appropriate for the students' educational level?
Does it support progression rather than simply provide entertainment?
Can students transfer what they learn to other contexts?
The role of technology
Is technology necessary?
Could a discussion, printed resource, practical activity or teacher-led explanation achieve the same objective?
Does the technology make something possible that would otherwise be difficult?
Does it increase meaningful student participation?
The role of the teacher
Does the tool strengthen the teacher's pedagogical role?
Does it allow teachers to make professional decisions?
Does it complement classroom interaction rather than replace it?
Can teachers adapt its use to different learning situations?
The pedagogical test
Before development, complete this sentence:
I am building this tool because it will help students __________ by providing __________, which supports the learning objective __________.
If you cannot complete this sentence clearly, reconsider the project before writing code.
3. DESIGN FOR LEARNING, NOT JUST ENGAGEMENT
Educational tools should be designed around established principles of learning and instruction.
Consider:
Cognitive load
Avoid unnecessary animations, decorations and competing visual elements.
Present information in manageable sections.
Introduce complex tasks gradually.
Avoid overwhelming students with too many options.
Provide appropriate scaffolding and worked examples.
Active learning
Require students to think, make decisions, explain and apply knowledge.
Include opportunities for retrieval practice.
Encourage students to construct their own understanding.
Avoid turning learning into passive interaction with a screen.
Scaffolding and differentiation
Offer different levels of difficulty.
Provide hints without immediately revealing answers.
Allow students to progress at an appropriate pace.
Include additional explanations where needed.
Avoid assuming that all students have identical prior knowledge.
Feedback
Make feedback specific, constructive and actionable.
Explain why an answer is incorrect.
Provide opportunities to revise and improve.
Distinguish between formative feedback and formal assessment.
Avoid feedback that labels students or makes unsupported judgments about their abilities.
Metacognition
Encourage students to reflect on their learning strategies.
Ask students to explain their reasoning.
Include opportunities for self-assessment.
Help students identify what they understand and what they still need to practise.
A useful rule: Every feature should have a pedagogical justification. If a feature does not contribute meaningfully to learning, accessibility, usability or safety, consider removing it.
4. PROTECT STUDENT AGENCY AND HUMAN AGENCY
Educational technology should empower learners rather than make decisions on their behalf.
Students should remain active participants in their learning.
Do not design tools that encourage students to follow AI-generated answers without thinking.
Avoid systems that complete important intellectual work for students.
Make it possible to question, challenge and verify AI-generated feedback.
Give students opportunities to make choices and explain their reasoning.
Do not present AI recommendations as unquestionable facts.
Preserve opportunities for independent thinking and productive struggle.
Teachers must also remain in control of pedagogical decisions.
AI can assist with content generation, feedback and differentiation, but it should not independently determine students' educational opportunities, progression or achievement.

PART II. PRIVACY, DATA PROTECTION AND STUDENT RIGHTS
5. COLLECT AS LITTLE DATA AS POSSIBLE
The safest educational tool is often the one that does not need to know who the student is.
Before developing a tool, identify exactly what information it collects, why it collects it and where it goes.
Understand the different types of information
Personal data
Names and surnames.
Email addresses.
Student identification numbers.
IP addresses and identifiable device information.
Login information and account identifiers.
Individual activity histories.
Potentially sensitive educational information
Grades and assessment results.
Learning difficulties and support needs.
Special educational arrangements.
Attendance and behavioural information.
Individual feedback and performance records.
Information about students' family circumstances.
Particularly sensitive information
Health information.
Disability-related information.
Psychological assessments.
Information revealing religious beliefs or other protected characteristics.
Information can become personal data even when it appears anonymous. For example, a combination of class, age, responses and timestamps might make an individual student identifiable.
The data minimisation principle
Do not request student names unless necessary.
Do not collect email addresses to personalise an experience.
Do not store individual answers when immediate feedback is sufficient.
Do not collect behavioural information without a clearly justified purpose.
Avoid unnecessary tracking, analytics and profiling.
Do not use student data for unrelated experiments.
Never assume that removing names automatically makes a dataset anonymous.
Ask yourself:
Could this tool deliver the same educational benefit without collecting this information?
If the answer is yes, do not collect it.
6. KNOW WHERE STUDENT DATA GOES
A common mistake in vibe coding is assuming that information entered into an application stays inside that application.
It may not.
A simple application can involve several external services:
The hosting platform.
A database provider.
An authentication service.
An analytics provider.
An AI model provider.
An external API.
A file storage service.
Third-party scripts and libraries.
Each connection can introduce additional data processing and security responsibilities.
Questions every educator should investigate
Where is the application hosted?
Where are submitted answers stored?
Does the application communicate with external servers?
Does it send information to an AI model?
Which company operates that AI model?
Are prompts or uploaded files retained?
Can submitted information be used to improve or train AI models?
Are third-party cookies or tracking technologies used?
Are data transferred outside the European Economic Area?
How long is information retained?
Can information be permanently deleted?
Who can access the information?
What happens when the project is discontinued?
Do not rely solely on what the coding assistant tells you. Inspect the actual services, configurations, privacy policies and technical architecture.
Important distinction: no login does not mean no data collection
A tool may not require student accounts and may still process IP addresses, browser information, device identifiers, cookies, free-text responses or other personal information.
A no-login design is often preferable, but it is not automatically GDPR-compliant.
7. RESPECT GDPR AND YOUR SCHOOL'S DATA PROTECTION RULES
If you work in a Norwegian school, GDPR and the Norwegian Personal Data Act are central considerations.
A teacher should never independently decide that a new application is approved for processing student information simply because it is useful for teaching.
In Norway, Utdanningsdirektoratet advises schools to use secure solutions that have been approved and assessed by the school owner.
Before using a new tool with students:
Consult school management and the responsible school owner.
Contact the Data Protection Officer (DPO/personvernombud) when appropriate.
Establish whether personal data is processed.
Identify the purpose and legal basis for processing.
Determine who acts as data controller and whether a processor agreement is necessary.
Check whether data processing agreements cover all relevant providers.
Establish appropriate retention and deletion arrangements.
Consider whether a Data Protection Impact Assessment (DPIA) is required.
Provide appropriate information to students and, where relevant, parents or guardians.
A DPIA is particularly important when processing is likely to result in high risks to individuals' rights and freedoms.
Potential warning signs include:
Processing information about vulnerable individuals.
Monitoring student behaviour.
Profiling students.
Processing sensitive information.
Introducing innovative technologies with significant privacy implications.
Combining several datasets.
Do not confuse a teacher's ability to publish an application with the school's authority to approve it for educational use.
8. PROTECT STUDENT IDENTITIES AND CONFIDENTIALITY
Never use real student information when experimenting with AI coding platforms.
Do not paste the following into AI coding assistants or unapproved external services:
Student names.
Grades.
Written assignments containing identifiable information.
Individual feedback.
Special educational needs documentation.
Health information.
Screenshots containing student information.
School records or internal documents.
Login credentials or confidential school communications.
Use fictional examples and synthetic datasets during development and testing.
For example, instead of asking an AI coding assistant to build a feedback application using actual student submissions, provide it with fictional texts written specifically for testing.
Remember that the development process itself can expose information, even if the finished application does not collect it.

PART III. SECURITY AND TECHNICAL RESPONSIBILITY
9. NEVER TRUST AI-GENERATED CODE WITHOUT REVIEW
AI-generated code can contain vulnerabilities, outdated dependencies, insecure configurations and incorrect assumptions.
A working demonstration does not establish that an application is secure.
Educators who vibe code should understand that AI-generated software needs human review and technical testing.
Essential security practices
Protect credentials
Never place API keys in publicly accessible frontend code.
Never upload passwords or secrets to public repositories.
Use appropriate environment variables and server-side secret management.
Rotate exposed credentials immediately.
Avoid sharing development screenshots that reveal secrets.
Protect databases
Use authentication where required.
Apply server-side authorisation checks.
Implement appropriate access controls.
Ensure students cannot access another student's records.
Do not rely on hidden buttons or frontend restrictions for security.
Check database access policies and permissions.
Test that unauthorised users cannot read, change or delete information.
Protect the application
Validate inputs on the server as well as the client.
Sanitize user-generated content before displaying it.
Avoid executing untrusted code.
Use secure communication through HTTPS.
Review third-party packages and dependencies.
Keep frameworks and libraries updated.
Use appropriate protection against automated abuse and excessive requests.
Establish backups and recovery procedures where information is stored.
Protect development environments
Use private repositories when appropriate.
Review what is published before making a repository public.
Do not expose configuration files containing secrets.
Separate development and production environments.
Remove test accounts and test data before deployment.
A particularly important rule
Never assume that a feature is secure because the AI coding assistant says it has implemented security measures.
Ask a qualified technical person to review sensitive systems, particularly those involving accounts, databases, student records or external AI services.
10. UNDERSTAND THE RISKS OF AI-POWERED FEATURES
Adding an AI chatbot, feedback assistant or intelligent agent introduces additional risks.
AI-powered features may:
Generate inaccurate information.
Produce biased or discriminatory responses.
Invent sources or references.
Reveal information included in prompts or connected data.
Be manipulated by malicious instructions.
Generate inappropriate content.
Misinterpret students' questions.
Produce different answers to similar questions.
Make unsupported claims about student performance.
Specific risks to investigate
Prompt injection
A student or external document may contain instructions designed to manipulate an AI model into ignoring its original instructions.
For example, an AI learning assistant that processes uploaded documents might encounter instructions hidden inside those documents.
Treat student input, uploaded files and retrieved online content as untrusted information.
Sensitive information disclosure
AI systems may expose information that should remain confidential if prompts, connected databases or application permissions are poorly designed.
Never rely on a system prompt as a security boundary.
Excessive agency
An AI agent with permission to access databases, send emails, modify records or perform other actions can cause harm if it is manipulated or makes an incorrect decision.
Give AI systems only the minimum permissions required.
Require human approval before consequential actions.
Hallucinations and misinformation
AI-generated explanations, feedback, historical facts and references must be checked.
Do not allow students to mistake confident language for verified knowledge.
Uncontrolled usage and costs
AI APIs may generate unexpected costs if usage is unrestricted.
Consider rate limits, usage quotas, monitoring and clear stopping conditions.
Design safer AI features
Give AI a clearly defined and limited role.
Use trusted, verified educational content where possible.
Clearly identify AI-generated responses.
Include appropriate content boundaries.
Provide a way to report inappropriate outputs.
Test responses to challenging and unexpected questions.
Avoid giving AI access to unnecessary personal information.
Do not allow AI to make consequential educational decisions independently.

PART IV. FAIRNESS, INCLUSION AND ACCESSIBILITY
11. DESIGN FOR ALL LEARNERS
An educational tool should not create unnecessary barriers for students.
A visually impressive application may still be inaccessible to students with visual, hearing, motor, cognitive or learning differences.
Consider accessibility from the beginning rather than treating it as a final design improvement.
Accessibility checklist
Visual accessibility
Use sufficient colour contrast.
Do not communicate meaning through colour alone.
Allow text resizing.
Use readable fonts and appropriate spacing.
Avoid flashing content and unnecessary visual effects.
Provide meaningful alternative text for important images.
Navigation
Make the application usable with a keyboard.
Provide visible focus indicators.
Use clear navigation and consistent layouts.
Ensure buttons have descriptive labels.
Avoid unnecessary time limits.
Provide clear instructions and error messages.

Cognitive accessibility
Use plain and understandable language.
Break complicated tasks into manageable steps.
Avoid excessive instructions on one screen.
Offer examples and visual support.
Allow students to pause and return when appropriate.
Multimedia accessibility
Provide captions for videos.
Include transcripts where appropriate.
Do not rely exclusively on audio instructions.
Provide alternatives for activities requiring particular sensory abilities.
Use WCAG 2.2 Level AA as a practical accessibility target, while checking the applicable Norwegian requirements for universal design.
Automated accessibility checkers are useful, but they cannot replace testing with real users.
12. IDENTIFY AND REDUCE BIAS
AI-generated applications may unintentionally reproduce stereotypes or discriminatory assumptions.
Bias can enter through:
Training data.
AI-generated educational content.
Examples and scenarios.
Language models.
Assessment criteria.
Images and character representations.
The assumptions built into the original prompt.
Ask:
Are different genders represented fairly?
Do examples reflect different cultures and backgrounds?
Does the tool assume that all students have the same experiences?
Could its feedback disadvantage students using different varieties of English?
Does it unfairly penalise students with disabilities?
Are its recommendations based on relevant educational evidence?
Does it make assumptions about students' abilities based on limited information?
Test the tool with diverse fictional scenarios.
Do not allow AI-generated profiling or predictions to define a student's potential.
13. RESPECT STUDENT DIGNITY AND PSYCHOLOGICAL SAFETY
Technology should support students without embarrassing, labelling or unnecessarily exposing them.
Avoid:
Public leaderboards that reveal individual weaknesses.
Competitive ranking systems that create unnecessary pressure.
AI-generated labels such as weak, lazy or unintelligent.
Feedback that humiliates students.
Unnecessary monitoring of student activity.
Systems that compare students without a pedagogical reason.
Features that encourage students to disclose personal or emotional information unnecessarily.
Consider how a student might feel when using the tool, particularly if they are anxious, have additional learning needs or struggle with confidence.
Provide alternatives when a digital activity requires speaking, appearing on camera or sharing personal information.

PART V. ASSESSMENT, TRANSPARENCY AND ACADEMIC INTEGRITY
14. DO NOT CONFUSE AUTOMATED FEEDBACK WITH TEACHER ASSESSMENT
AI can support formative assessment, but it should not automatically become an authority on student achievement.
AI-generated assessment may be inconsistent, inaccurate or biased.
A language-learning application, for example, might incorrectly penalise a valid alternative expression or fail to recognise a student's reasoning.
Therefore:
Explain the purpose and limitations of automated feedback.
Do not use unvalidated AI scores as final grades.
Do not let AI independently determine progression or access to opportunities.
Give students opportunities to question and discuss feedback.
Allow teachers to review important assessment decisions.
Validate scoring systems against appropriate educational criteria.
Avoid presenting automated estimates as objective measurements of ability.
If a tool records student performance, establish who can see the information, how it is used and how long it is retained.
15. BE TRANSPARENT ABOUT AI
Students should understand when AI is involved in their learning experience.
Make it clear:
Whether the application uses AI.
Which features are AI-powered.
What information students submit.
Whether information is sent to an external AI provider.
Whether responses are generated automatically.
What the limitations of the AI are.
Whether student submissions are stored.
Who is responsible for reviewing important feedback.
Never disguise an AI system as a human teacher or imply that an automated response has been personally reviewed when it has not.
16. RESPECT COPYRIGHT AND INTELLECTUAL PROPERTY
AI-generated code and content do not automatically give educators unrestricted rights to everything included in an application.
Consider:
Copyrighted texts and books.
Commercial images and illustrations.
Music and sound recordings.
Videos and other media.
Educational resources from publishers.
Fonts and icons.
Third-party code and software libraries.
AI-generated images and text.
Before using material, check the relevant licence and terms of use.
Use appropriately licensed resources, public-domain materials or original content.
Check whether third-party software libraries permit your intended use.
Give appropriate attribution where required.
Do not upload copyrighted educational materials to external AI services without checking whether the use is permitted.
If you publish an application, include a clear credits and licensing section where appropriate.

PART VI. DEVELOPMENT, TESTING AND DEPLOYMENT
17. TEST BEFORE STUDENTS TEST
Students should not become the first group to discover serious flaws in a newly created application.
Developers should follow a staged process.
Stage 1: Prototype
Build using fictional content.
Avoid real student data.
Test the main learning activity.
Check basic navigation and functionality.
Keep the initial version simple.
Stage 2: Technical review
Inspect the generated code.
Check external connections and dependencies.
Review authentication and database permissions.
Verify that API keys and secrets are protected.
Test input validation.
Check mobile and desktop functionality.
Run security and accessibility checks.
Stage 3: Pedagogical review
Check alignment with learning objectives.
Verify educational content.
Test feedback and instructions.
Check difficulty levels.
Consider the needs of different learners.
Identify unintended learning consequences.
Stage 4: Controlled pilot
Only after appropriate school approval, consider a small, supervised pilot.
Explain the purpose of the tool.
Provide clear instructions.
Avoid unnecessary personal data.
Observe how students interact with it.
Gather feedback.
Identify technical and pedagogical problems.
Make improvements before wider use.
Stage 5: Deployment
Deploy only when the appropriate people have approved the tool and the relevant risks have been addressed.
Stage 6: Continuous evaluation
A tool is never permanently finished.
Monitor:
Technical reliability.
Security updates.
Accessibility.
Accuracy of content.
Student experience.
Educational value.
Changes in third-party services.
Changes in privacy policies and legal requirements.
18. CREATE A PLAN FOR FAILURE
What happens if the application stops working during a lesson?
What happens if a database is accidentally exposed?
What happens if an AI assistant produces inappropriate feedback?
What happens if a student submits personal information?
Before deployment, establish a response plan.
Minimum incident response plan
Stop using the affected tool if student safety or data protection may be compromised.
Restrict access or disable the affected functionality.
Preserve relevant evidence without unnecessarily copying or sharing personal data.
Inform the appropriate school management, IT/security contact and DPO.
Follow the school's incident-reporting procedures.
Allow the responsible organisation to assess notification obligations, including any GDPR breach reporting requirements.
Identify the cause and implement corrective measures.
Do not restart the service until the responsible people consider it safe.
A personal data breach may require notification to the supervisory authority within 72 hours of awareness, subject to GDPR requirements. This is the responsibility of the controller, not an individual teacher acting independently.
19. DOCUMENT WHAT YOU BUILD
Educational tools should not become mysterious applications that only their original creators understand.
Create a simple documentation file for each project.
Include:
Application name and purpose.
Intended users and age group.
Learning objectives.
Main features.
AI services and external integrations.
Hosting provider.
Data collected and processed.
Storage arrangements.
Authentication requirements.
Security measures.
Accessibility considerations.
Known limitations.
Testing completed.
Approval status.
Contact person responsible for maintenance.
Date of last review.
Documentation is particularly important when tools are shared with colleagues or transferred to another teacher.

PART VII. GOVERNANCE AND PROFESSIONAL RESPONSIBILITY
20. RESPECT THE SCHOOL'S AUTHORITY AND POLICIES
A teacher can create a tool independently, but that does not mean the teacher can independently authorise its use in the school's educational environment.
School owners and school leaders have responsibilities concerning procurement, information security, data protection and approved digital services.
Before deploying a tool:
Check the school's acceptable-use policies.
Consult the responsible IT department.
Consult the DPO when necessary.
Clarify whether the tool requires formal approval.
Establish whether a data processing agreement is needed.
Check whether the hosting arrangement is acceptable.
Determine whether the tool can be accessed on school devices.
Clarify who will maintain the application.
Establish who is responsible if something goes wrong.
Sharing a public link does not remove these responsibilities.
21. BE RESPONSIBLE WHEN SHARING YOUR CREATIONS
Educators often share their applications through GitHub, Netlify, Cloudflare Pages, Google AI Studio and other platforms.
Open sharing can support professional collaboration, but it also increases responsibility.
When publishing an educational tool:
State that it is an educator-developed resource.
Describe its intended educational purpose.
Identify the intended age group.
Explain whether AI is used.
Provide a privacy notice where appropriate.
Explain what data the application processes.
Identify relevant third-party services.
State known limitations.
Provide a way to report problems.
Include a version number and last-updated date.
Make clear whether the tool has been formally approved for school use.
Never imply that a resource is school-approved, GDPR-compliant or security-certified unless that status has actually been established.
A disclaimer does not replace appropriate technical and organisational safeguards.


22. TAKE RESPONSIBILITY FOR MAINTENANCE
Publishing an application creates an ongoing responsibility, especially when students continue using it.
Ask yourself:
Who maintains the application?
Who checks for security vulnerabilities?
Who updates dependencies?
Who pays for external services?
What happens if a free hosting plan changes?
What happens if an AI provider changes its model or pricing?
What happens if an API stops working?
Who can disable the application?
Can data be exported or deleted?
What happens when the original creator leaves the school?
If you cannot answer these questions, reconsider whether the application should be deployed as a long-term school resource.

PART VIII. THE EDUCATOR'S PRE-DEPLOYMENT CHECKLIST
23. THE RESPONSIBLE VIBE-CODING GATE
Before allowing students to use an application, work through the following checklist.
A. Pedagogical readiness
I have identified an educational need.
The application supports clearly defined learning objectives.
Its features have pedagogical justifications.
It promotes active learning and student thinking.
Feedback is educationally meaningful.
I have considered alternative, non-digital approaches.
The application is appropriate for the intended age group.

B. Privacy and data protection
I know what information the application collects.
I have minimised data collection.
I understand where information is stored.
I have identified all external services.
I have checked relevant privacy policies.
I have not entered real student information into unapproved development services.
I have consulted the appropriate school authorities.
Required privacy assessments and agreements have been addressed.
Retention and deletion arrangements are understood.
C. Security
API keys and credentials are protected.
No confidential information is exposed in public repositories.
Database permissions have been checked.
Authentication and authorisation are implemented appropriately.
User input is validated.
External dependencies have been reviewed.
AI features have been tested for misuse.
Unauthorised access has been tested.
A response plan exists for technical or security incidents.
D. AI responsibility
AI-generated information has been verified.
AI limitations are communicated clearly.
Students understand when they are interacting with AI.
The AI has limited permissions.
Prompt injection and inappropriate output risks have been considered.
AI does not make consequential educational decisions independently.
External AI processing has been appropriately assessed.
E. Accessibility and inclusion
Text is readable.
Colour contrast is sufficient.
Navigation is keyboard-accessible.
Images have appropriate alternatives.
Multimedia has captions or transcripts where appropriate.
The application does not unnecessarily disadvantage students with additional needs.
I have tested the application on different devices.
Alternative ways of participating are available.
F. Assessment and student rights
Automated feedback is not presented as infallible.
Important assessment decisions remain under appropriate human oversight.
Students know what happens to their submissions.
The application does not unnecessarily monitor or rank students.
Students can report problems.
Appropriate alternatives are available.
G. Deployment and maintenance
The relevant school approval has been obtained.
Testing has been completed.
Documentation is available.
A responsible maintainer has been identified.
A plan exists for technical failure.
There is a process for reviewing and updating the tool.
There is a plan for discontinuing the tool safely.
Important: This checklist is a development aid, not a certification of legal compliance or a substitute for formal school approval.



PART IX. A PRACTICAL RISK CLASSIFICATION
24. NOT ALL EDUCATIONAL TOOLS HAVE THE SAME LEVEL OF RISK
The complexity of an application should influence the level of review it receives.
This is an indicative practical classification, not an official legal risk taxonomy.
A simple application can become high-risk because of the information it processes or the decisions it supports.

PART X. THE ETHICAL VIBE-CODING PROMISE
25. OUR COMMITMENT AS EDUCATOR-CREATORS
As educators who use AI to create digital tools, we recognise that technology gives us new opportunities and new responsibilities.
We commit to:
Putting pedagogy first. We build to address real learning needs, not simply to experiment with technology.
Protecting students. We treat student privacy, security and dignity as non-negotiable priorities.
Minimising data. We collect only what is necessary and avoid unnecessary monitoring.
Taking responsibility. We do not assume that AI-generated code is correct, secure or legally compliant.
Keeping humans in control. We preserve professional judgement and meaningful human oversight.
Designing for inclusion. We consider accessibility, different learning needs and diverse student experiences.
Being transparent. We explain how our tools work, what information they process and where their limitations lie.
Respecting intellectual property. We use content, code and resources responsibly.
Testing before deployment. We review, challenge and evaluate our applications before students use them.
Learning continuously. We update our knowledge, review our tools and respond to emerging risks.
Collaborating responsibly. We involve colleagues, school leaders and relevant specialists when decisions exceed our expertise.
Knowing when not to build. We recognise that some educational problems require human relationships, professional expertise or institutional solutions rather than another application.

FINAL THOUGHT: THE FUTURE BELONGS TO RESPONSIBLE CREATORS
Vibe coding has opened the door for teachers to become creators rather than simply consumers of educational technology.
This is an important shift.
Teachers understand their students, their subjects, their classrooms and the everyday challenges of learning. They can identify problems that technology developers might overlook and create solutions that are grounded in actual educational practice.
But creativity must be accompanied by responsibility.
We should not measure our success by the number of applications we build, the sophistication of our code or the number of AI features we integrate.
We should measure it by the educational value we create, the barriers we remove, the learning opportunities we expand and the trust we preserve.

RECOMMENDED REFERENCE FRAMEWORKS AND FURTHER READING
The following sources provide a starting point for educators who want to investigate the legal, pedagogical and technical responsibilities of building educational applications.
Norwegian educational and privacy guidance
Utdanningsdirektoratet – Advice on AI in schools: https://www.udir.no/kvalitet-og-kompetanse/digitalisering-skole/kunstig-intelligens-i-skolen/rad-om-kunstig-intelligens-skolen/
Utdanningsdirektoratet – Privacy considerations when using AI: https://www.udir.no/kvalitet-og-kompetanse/digitalisering-skole/kunstig-intelligens-i-skolen/personvern-ki/
Utdanningsdirektoratet – How schools can use AI safely: https://www.udir.no/kvalitet-og-kompetanse/digitalisering-skole/kunstig-intelligens-i-skolen/eksempler-fra-praksis/
Datatilsynet – Digital learning tools and privacy: https://www.datatilsynet.no/personvern-pa-ulike-omrader/skole-barn-unge/bruk-av-digitale-hjelpemidler/
Datatilsynet – Privacy findings concerning free online services in schools: https://www.datatilsynet.no/aktuelt/aktuelle-nyheter-2026/personvern-i-skolen--funn-om-gratis-nettjenester/
Datatilsynet – Data Protection Impact Assessments (DPIA): https://www.datatilsynet.no/rettigheter-og-plikter/virksomhetenes-plikter/vurdering-av-personvernkonsekvenser/
International technical and ethical frameworks
OWASP – Top 10 for Large Language Model Applications (2026): https://github.com/GenAI-Security-Project/GenAI-LLM-Top10
W3C – Web Content Accessibility Guidelines (WCAG): https://www.w3.org/WAI/standards-guidelines/wcag/
European Union – Artificial Intelligence Act: https://eur-lex.europa.eu/eli/reg/2024/1689/oj
Norwegian National Security Authority (NSM) – ICT Security Principles: https://nsm.no/advice-and-guidance/publications/nsm-ict-security-principles
A note on legal interpretation: This framework is an educational and professional responsibility guide, not legal advice or a certification. Legal obligations depend on the actual application, its users, data processing, intended purpose and deployment context. Check current Norwegian requirements, applicable GDPR provisions and the implementation and applicability of the EU AI Act before deployment. School owners and their designated specialists must make the relevant formal decisions.

Risk level | Examples | Recommended approach
Lower risk | Static vocabulary games, public information websites, simple interactive quizzes without data storage | Review content, accessibility, external connections and school policies
Moderate risk | Student-submitted answers, saved progress, feedback dashboards, user accounts | Conduct a more detailed privacy and security assessment; seek school approval
Higher risk | AI chatbots processing student input, databases containing student records, behavioural tracking, automated performance analysis | Formal review by appropriate school authorities, privacy and security specialists, and assessment of DPIA requirements
Very high risk | AI making consequential decisions about grades, progression, admissions, student profiling or access to opportunities | Do not deploy independently; require specialist legal, pedagogical and technical review