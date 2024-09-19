# Fabric Pattern Wiki

## Table of Contents

<details>
<summary>A-C</summary>

1. [agility_story](#agility_story)
2. [ai](#ai)
3. [analyze_answers](#analyze_answers)
4. [analyze_claims](#analyze_claims)
5. [analyze_debate](#analyze_debate)
6. [analyze_incident](#analyze_incident)
7. [analyze_logs](#analyze_logs)
8. [analyze_malware](#analyze_malware)
9. [analyze_paper](#analyze_paper)
10. [analyze_patent](#analyze_patent)
11. [analyze_personality](#analyze_personality)
12. [analyze_presentation](#analyze_presentation)
13. [analyze_prose](#analyze_prose)
14. [analyze_prose_json](#analyze_prose_json)
15. [analyze_prose_pinker](#analyze_prose_pinker)
16. [analyze_spiritual_text](#analyze_spiritual_text)
17. [analyze_tech_impact](#analyze_tech_impact)
18. [analyze_threat_report](#analyze_threat_report)
19. [analyze_threat_report_trends](#analyze_threat_report_trends)
20. [answer_interview_question](#answer_interview_question)
21. [ask_secure_by_design_questions](#ask_secure_by_design_questions)
22. [capture_thinkers_work](#capture_thinkers_work)
23. [check_agreement](#check_agreement)
24. [clean_text](#clean_text)
25. [coding_master](#coding_master)
26. [compare_and_contrast](#compare_and_contrast)
27. [create_5_sentence_summary](#create_5_sentence_summary)
28. [create_academic_paper](#create_academic_paper)
29. [create_ai_jobs_analysis](#create_ai_jobs_analysis)
30. [create_aphorisms](#create_aphorisms)
31. [create_art_prompt](#create_art_prompt)
32. [create_better_frame](#create_better_frame)
33. [create_coding_project](#create_coding_project)
34. [create_command](#create_command)
35. [create_cyber_summary](#create_cyber_summary)

</details>

<details>
<summary>D-I</summary>

36. [create_git_diff_commit](#create_git_diff_commit)
37. [create_idea_compass](#create_idea_compass)
38. [create_investigation_visualization](#create_investigation_visualization)
39. [create_keynote](#create_keynote)
40. [create_logo](#create_logo)
41. [create_markmap_visualization](#create_markmap_visualization)
42. [create_mermaid_visualization](#create_mermaid_visualization)
43. [create_micro_summary](#create_micro_summary)
44. [create_network_threat_landscape](#create_network_threat_landscape)
45. [create_npc](#create_npc)
46. [create_pattern](#create_pattern)
47. [create_quiz](#create_quiz)
48. [create_reading_plan](#create_reading_plan)
49. [create_report_finding](#create_report_finding)
50. [create_security_update](#create_security_update)
51. [create_show_intro](#create_show_intro)
52. [create_stride_threat_model](#create_stride_threat_model)
53. [create_summary](#create_summary)
54. [create_threat_model](#create_threat_model)
55. [create_threat_scenarios](#create_threat_scenarios)
56. [create_upgrade_pack](#create_upgrade_pack)
57. [create_video_chapters](#create_video_chapters)
58. [create_visualization](#create_visualization)
59. [explain_code](#explain_code)
60. [explain_docs](#explain_docs)
61. [explain_project](#explain_project)
62. [explain_terms](#explain_terms)
63. [extract_algorithm_update_recommendations](#extract_algorithm_update_recommendations)
64. [extract_article_wisdom](#extract_article_wisdom)
65. [extract_book_ideas](#extract_book_ideas)
66. [extract_book_recommendations](#extract_book_recommendations)
67. [extract_business_ideas](#extract_business_ideas)
68. [extract_extraordinary_claims](#extract_extraordinary_claims)
69. [extract_ideas](#extract_ideas)
70. [extract_insights](#extract_insights)
71. [extract_main_idea](#extract_main_idea)
72. [extract_patterns](#extract_patterns)
73. [extract_poc](#extract_poc)
74. [extract_predictions](#extract_predictions)
75. [extract_questions](#extract_questions)
76. [extract_recommendations](#extract_recommendations)
77. [extract_references](#extract_references)
78. [extract_song_meaning](#extract_song_meaning)
79. [extract_sponsors](#extract_sponsors)
80. [extract_videoid](#extract_videoid)
81. [extract_wisdom](#extract_wisdom)
82. [extract_wisdom_agents](#extract_wisdom_agents)
83. [extract_wisdom_dm](#extract_wisdom_dm)
84. [extract_wisdom_nometa](#extract_wisdom_nometa)
85. [find_hidden_message](#find_hidden_message)
86. [find_logical_fallacies](#find_logical_fallacies)
87. [get_wow_per_minute](#get_wow_per_minute)
88. [get_youtube_rss](#get_youtube_rss)
89. [improve_academic_writing](#improve_academic_writing)
90. [improve_prompt](#improve_prompt)
91. [improve_report_finding](#improve_report_finding)
92. [improve_writing](#improve_writing)

</details>

<details>
<summary>L-Z</summary>

93. [label_and_rate](#label_and_rate)
94. [official_pattern_template](#official_pattern_template)
95. [philocapsulate](#philocapsulate)
96. [provide_guidance](#provide_guidance)
97. [rate_ai_response](#rate_ai_response)
98. [rate_ai_result](#rate_ai_result)
99. [rate_content](#rate_content)
100. [rate_value](#rate_value)
101. [raw_query](#raw_query)
102. [recommend_artists](#recommend_artists)
103. [show_fabric_options_markmap](#show_fabric_options_markmap)
104. [suggest](#suggest)
105. [summarize](#summarize)
106. [summarize_debate](#summarize_debate)
107. [summarize_git_changes](#summarize_git_changes)
108. [summarize_git_diff](#summarize_git_diff)
109. [summarize_micro](#summarize_micro)
110. [summarize_newsletter](#summarize_newsletter)
111. [summarize_paper](#summarize_paper)
112. [summarize_pattern](#summarize_pattern)
113. [summarize_pull-requests](#summarize_pull-requests)
114. [summarize_rpg_session](#summarize_rpg_session)
115. [to_flashcards](#to_flashcards)
116. [tweet](#tweet)
117. [write_essay](#write_essay)
118. [write_micro_essay](#write_micro_essay)
119. [write_nuclei_template_rule](#write_nuclei_template_rule)
120. [write_pull-request](#write_pull-request)
121. [write_semgrep_rule](#write_semgrep_rule)

</details>


## agility_story

### Overview
The `agility_story` pattern generates user stories and acceptance criteria for specified topics, focusing on Agile framework principles.

### Use Cases
- Creating user stories for software development projects
- Defining acceptance criteria for new features
- Structuring project requirements in an Agile format

### Examples

Windows:
```
echo "Create a user login feature" | fabric --pattern agility_story
```

macOS/Linux:
```
echo "Create a user login feature" | fabric --pattern agility_story
```

Output will be in JSON format, detailing the topic, user story, and acceptance criteria.

## ai

### Overview
The `ai` pattern summarizes and responds to questions with insightful bullet points, creating a mental model for deeper understanding.

### Use Cases
- Quickly summarizing complex topics
- Generating concise answers to questions
- Creating brief overviews of subjects

### Examples

Windows:
```
echo "Explain the concept of artificial intelligence" | fabric --pattern ai
```

macOS/Linux:
```
echo "Explain the concept of artificial intelligence" | fabric --pattern ai
```

Output will consist of 3-5 concise bullet points, each limited to 10 words.

## analyze_answers

### Overview
The `analyze_answers` pattern evaluates the correctness of answers provided by learners to questions generated by a complementary quiz creation pattern.

### Use Cases
- Assessing student understanding of learning objectives
- Identifying areas needing further study
- Providing feedback on quiz responses

### Examples

Windows:
```
type answers.txt | fabric --pattern analyze_answers
```

macOS/Linux:
```
cat answers.txt | fabric --pattern analyze_answers
```

Output will be an analysis of the learner's answers, indicating their grasp of the subject matter.

## analyze_claims

### Overview
The `analyze_claims` pattern analyzes and rates truth claims in input, providing evidence for and against, along with a balanced view.

### Use Cases
- Fact-checking articles or statements
- Evaluating the credibility of claims
- Providing a balanced analysis of controversial topics

### Examples

Windows:
```
type article.txt | fabric --pattern analyze_claims
```

macOS/Linux:
```
cat article.txt | fabric --pattern analyze_claims
```

Output includes a summary, evidence, refutations, logical fallacies, ratings, labels, and an overall score and analysis.

## analyze_debate

### Overview
The `analyze_debate` pattern analyzes debate transcripts to help users understand different viewpoints and broaden their perspectives.

### Use Cases
- Summarizing political debates
- Analyzing academic discussions
- Evaluating argument quality in debates

### Examples

Windows:
```
type debate_transcript.txt | fabric --pattern analyze_debate
```

macOS/Linux:
```
cat debate_transcript.txt | fabric --pattern analyze_debate
```

Output includes scores, participant emotionality, argument summaries with sources, and lists of agreements, disagreements, misunderstandings, learnings, and takeaways.

## analyze_incident

### Overview
The `analyze_incident` pattern summarizes cybersecurity breach articles by extracting key information efficiently, focusing on conciseness and organization.

### Use Cases
- Quickly understanding cybersecurity incidents
- Extracting key details from security breach reports
- Organizing incident information for analysis

### Examples

Windows:
```
type incident_report.txt | fabric --pattern analyze_incident
```

macOS/Linux:
```
cat incident_report.txt | fabric --pattern analyze_incident
```

Output is a structured summary with specific details about the cybersecurity incident, including attack methods, vulnerabilities, and recommendations for prevention.

## analyze_logs

### Overview
The `analyze_logs` pattern analyzes server log files to identify patterns, anomalies, and potential issues, aiming to enhance server reliability and performance.

### Use Cases
- Troubleshooting server issues
- Identifying security threats from log data
- Optimizing server performance

### Examples

Windows:
```
type server_log.txt | fabric --pattern analyze_logs
```

macOS/Linux:
```
cat server_log.txt | fabric --pattern analyze_logs
```

Output includes a detailed examination of log entries, assessment of operational reliability, identification of recurring issues, and recommendations for improvements.

## analyze_malware

### Overview
The `analyze_malware` pattern analyzes malware across various platforms, focusing on extracting indicators of compromise and detailed malware behavior.

### Use Cases
- Malware detection and analysis
- Identifying potential threats in software
- Understanding malware behavior and impact

### Examples

Windows:
```
type malware_report.txt | fabric --pattern analyze_malware
```

macOS/Linux:
```
cat malware_report.txt | fabric --pattern analyze_malware
```

Output includes a summary of findings, potential indicators of compromise, Mitre ATT&CK techniques, pivoting advice, detection strategies, suggested Yara rules, additional references, and technical recommendations.

## analyze_paper

### Overview
The `analyze_paper` pattern analyzes research papers to determine their main findings, scientific rigor, and quality.

### Use Cases
- Evaluating academic research papers
- Summarizing scientific findings
- Assessing the quality of research methodologies

### Examples

Windows:
```
type research_paper.txt | fabric --pattern analyze_paper
```

macOS/Linux:
```
cat research_paper.txt | fabric --pattern analyze_paper
```

Output includes a summary, author details, findings, study quality, and a final grade with explanations.

## analyze_patent

### Overview
The `analyze_patent` pattern outlines the role and responsibilities of a patent examiner, emphasizing the importance of technical and legal expertise in evaluating patents.

### Use Cases
- Evaluating patent applications
- Understanding the core ideas of inventions
- Assessing the novelty and inventive step of patents

### Examples

Windows:
```
type patent_application.txt | fabric --pattern analyze_patent
```

macOS/Linux:
```
cat patent_application.txt | fabric --pattern analyze_patent
```

Output involves detailed analysis and documentation in specific sections, using bullet points for clarity.

## analyze_personality

### Overview
The `analyze_personality` pattern performs in-depth psychological analysis on the main individual in the provided input.

### Use Cases
- Character analysis in literature
- Psychological profiling
- Understanding personality traits from written content

### Examples

Windows:
```
type character_description.txt | fabric --pattern analyze_personality
```

macOS/Linux:
```
cat character_description.txt | fabric --pattern analyze_personality
```

Output includes a concise psychological profile summary and detailed supporting points.

## analyze_presentation

### Overview
The `analyze_presentation` pattern analyzes and critiques presentations, focusing on content, speaker's psychology, and the difference between stated and actual goals.

### Use Cases
- Evaluating public speaking performances
- Analyzing presentation effectiveness
- Providing feedback on presentation content and delivery

### Examples

Windows:
```
type presentation_transcript.txt | fabric --pattern analyze_presentation
```

macOS/Linux:
```
cat presentation_transcript.txt | fabric --pattern analyze_presentation
```

Output includes scores and summaries for ideas, selflessness, and entertainment, plus an overall analysis.

## analyze_prose

### Overview
The `analyze_prose` pattern evaluates the quality of writing by assessing its novelty, clarity, and prose, and provides improvement recommendations.

### Use Cases
- Evaluating written content for quality
- Providing feedback on writing style
- Identifying areas for improvement in prose

### Examples

Windows:
```
type essay.txt | fabric --pattern analyze_prose
```

macOS/Linux:
```
cat essay.txt | fabric --pattern analyze_prose
```

Output includes ratings and concise improvement tips for various aspects of the writing.

## analyze_prose_json

### Overview
The `analyze_prose_json` pattern evaluates the quality of writing and content, providing ratings and recommendations for improvement based on novelty, clarity, and overall messaging.

### Use Cases
- Detailed analysis of written content
- Generating structured feedback on writing
- Evaluating content for freshness and originality

### Examples

Windows:
```
type article.txt | fabric --pattern analyze_prose_json
```

macOS/Linux:
```
cat article.txt | fabric --pattern analyze_prose_json
```

Output is a JSON object summarizing evaluations and recommendations for the analyzed text.

## analyze_prose_pinker

### Overview
The `analyze_prose_pinker` pattern evaluates prose based on Steven Pinker's writing principles, identifying its current style and recommending improvements for clarity and engagement.

### Use Cases
- Improving writing style based on Pinker's principles
- Analyzing adherence to specific writing guidelines
- Enhancing clarity and engagement in prose

### Examples

Windows:
```
type essay.txt | fabric --pattern analyze_prose_pinker
```

macOS/Linux:
```
cat essay.txt | fabric --pattern analyze_prose_pinker
```

Output includes a detailed analysis of the prose's style, strengths, weaknesses, and specific examples of both effective and ineffective writing elements.

## analyze_spiritual_text

### Overview
The `analyze_spiritual_text` pattern analyzes spiritual texts to highlight surprising claims and contrasts them with the King James Bible.

### Use Cases
- Comparative analysis of religious texts
- Identifying unique claims in spiritual writings
- Contrasting different religious
[Continuing from where the previous artifact left off...]

## analyze_threat_report

### Overview
The `analyze_threat_report` pattern instructs a super-intelligent cybersecurity expert to analyze and extract key insights from cybersecurity threat reports.

### Use Cases
- Summarizing cybersecurity threat reports
- Extracting key trends and statistics from security analyses
- Generating actionable recommendations from threat data

### Examples

Windows:
```
type threat_report.txt | fabric --pattern analyze_threat_report
```

macOS/Linux:
```
cat threat_report.txt | fabric --pattern analyze_threat_report
```

Output includes a one-sentence summary, trends, statistics, quotes, references, and recommendations from the report, all formatted in plain language without repetition.

## analyze_threat_report_trends

### Overview
The `analyze_threat_report_trends` pattern analyzes cybersecurity threat reports to identify up to 50 unique, surprising, and insightful trends.

### Use Cases
- Identifying emerging cybersecurity trends
- Extracting key insights from multiple threat reports
- Providing a comprehensive overview of current threat landscapes

### Examples

Windows:
```
type multiple_threat_reports.txt | fabric --pattern analyze_threat_report_trends
```

macOS/Linux:
```
cat multiple_threat_reports.txt | fabric --pattern analyze_threat_report_trends
```

Output is a list of trends without repetition or formatting embellishments, focusing on new and interesting information.

## answer_interview_question

### Overview
The `answer_interview_question` pattern generates tailored responses to technical interview questions, aiming for a casual yet insightful tone.

### Use Cases
- Preparing for technical interviews
- Practicing interview responses
- Generating example answers for interview prep materials

### Examples

Windows:
```
echo "Explain the concept of polymorphism in object-oriented programming" | fabric --pattern answer_interview_question
```

macOS/Linux:
```
echo "Explain the concept of polymorphism in object-oriented programming" | fabric --pattern answer_interview_question
```

Output is structured as first-person responses, including context, main explanation, alternative approach, and evidence-based conclusion.

## ask_secure_by_design_questions

### Overview
The `ask_secure_by_design_questions` pattern generates a comprehensive set of security-focused questions tailored to the fundamental design of a specific project.

### Use Cases
- Conducting security assessments of project designs
- Identifying potential security vulnerabilities in early stages
- Generating security-focused requirements for new projects

### Examples

Windows:
```
type project_description.txt | fabric --pattern ask_secure_by_design_questions
```

macOS/Linux:
```
cat project_description.txt | fabric --pattern ask_secure_by_design_questions
```

Output includes a summary and a detailed list of security questions organized by themes.

## capture_thinkers_work

### Overview
The `capture_thinkers_work` pattern summarizes teachings and philosophies of notable individuals or philosophical schools, providing detailed templates on their backgrounds, ideas, and applications.

### Use Cases
- Summarizing philosophical concepts
- Creating educational materials on thinkers and their ideas
- Analyzing the impact of philosophical schools of thought

### Examples

Windows:
```
echo "Summarize the work of Immanuel Kant" | fabric --pattern capture_thinkers_work
```

macOS/Linux:
```
echo "Summarize the work of Immanuel Kant" | fabric --pattern capture_thinkers_work
```

Output includes encapsulations, background information, schools of thought, impactful ideas, primary teachings, works, quotes, applications, and life advice.

## check_agreement

### Overview
The `check_agreement` pattern outlines a process for analyzing contracts and agreements to identify potential issues or "gotchas."

### Use Cases
- Reviewing legal documents for potential issues
- Analyzing contracts for hidden clauses or problems
- Summarizing key points of agreements

### Examples

Windows:
```
type contract.txt | fabric --pattern check_agreement
```

macOS/Linux:
```
cat contract.txt | fabric --pattern check_agreement
```

Output includes a concise summary, detailed callouts, categorized issues, and recommended responses in Markdown format.

## clean_text

### Overview
The `clean_text` pattern summarizes and corrects formatting issues in text without altering the content.

### Use Cases
- Improving readability of poorly formatted text
- Preparing text for further processing or analysis
- Cleaning up raw data for presentation

### Examples

Windows:
```
type messy_text.txt | fabric --pattern clean_text
```

macOS/Linux:
```
cat messy_text.txt | fabric --pattern clean_text
```

Output is a clean, well-formatted version of the original text with improved readability.

## coding_master

### Overview
The `coding_master` pattern explains coding concepts or languages to beginners, using examples from reputable sources and illustrating points with formatted code.

### Use Cases
- Creating educational content for coding beginners
- Explaining complex programming concepts simply
- Generating code examples for tutorials

### Examples

Windows:
```
echo "Explain object-oriented programming" | fabric --pattern coding_master
```

macOS/Linux:
```
echo "Explain object-oriented programming" | fabric --pattern coding_master
```

Output includes markdown-formatted code and structured lists of ideas, recommendations, habits, facts, and insights, adhering to specific word counts.

## compare_and_contrast

### Overview
The `compare_and_contrast` pattern compares and contrasts a list of items, focusing on their differences and similarities.

### Use Cases
- Analyzing differences between products or concepts
- Creating comparative studies
- Generating comparison tables for research or presentations

### Examples

Windows:
```
echo "Compare and contrast Python, Java, and C++" | fabric --pattern compare_and_contrast
```

macOS/Linux:
```
echo "Compare and contrast Python, Java, and C++" | fabric --pattern compare_and_contrast
```

Output is a structured comparison in table format, highlighting similarities and differences across various aspects of the compared items.

## create_5_sentence_summary

### Overview
The `create_5_sentence_summary` pattern generates concise summaries or answers at five decreasing levels of depth.

### Use Cases
- Creating multi-level summaries of complex topics
- Generating elevator pitches of varying lengths
- Simplifying complex ideas for different audience levels

### Examples

Windows:
```
type long_article.txt | fabric --pattern create_5_sentence_summary
```

macOS/Linux:
```
cat long_article.txt | fabric --pattern create_5_sentence_summary
```

Output is a structured list capturing the essence in 5, 4, 3, 2, and 1 word(s).

## create_academic_paper

### Overview
The `create_academic_paper` pattern produces high-quality, authoritative LaTeX academic papers with clear concept explanations.

### Use Cases
- Generating academic paper templates
- Creating formatted research papers
- Producing professional-looking scientific documents

### Examples

Windows:
```
echo "Write a paper on the effects of climate change" | fabric --pattern create_academic_paper
```

macOS/Linux:
```
echo "Write a paper on the effects of climate change" | fabric --pattern create_academic_paper
```

Output is LaTeX code formatted in a two-column layout with a header and footer.

## create_ai_jobs_analysis

### Overview
The `create_ai_jobs_analysis` pattern analyzes job reports to identify roles least and most vulnerable to automation, offering strategies for enhancing job security.

### Use Cases
- Assessing the impact of AI on job markets
- Planning career strategies in the age of automation
- Analyzing workforce trends related to AI and automation

### Examples

Windows:
```
type job_market_report.txt | fabric --pattern create_ai_jobs_analysis
```

macOS/Linux:
```
cat job_market_report.txt | fabric --pattern create_ai_jobs_analysis
```

Output includes a detailed analysis and recommendations for resilience against automation in various job categories.

## create_aphorisms

### Overview
The `create_aphorisms` pattern generates a list of 20 aphorisms related to the given topic(s), ensuring variety in their beginnings.

### Use Cases
- Creating inspirational quotes for presentations
- Generating thought-provoking statements for writing
- Producing content for social media posts

### Examples

Windows:
```
echo "Success and failure" | fabric --pattern create_aphorisms
```

macOS/Linux:
```
echo "Success and failure" | fabric --pattern create_aphorisms
```

Output includes each aphorism followed by the name of the person who said it (sourced from real individuals).

## create_art_prompt

### Overview
The `create_art_prompt` pattern guides an expert artist in conceptualizing and instructing AI to create art that perfectly encapsulates a given concept.

### Use Cases
- Generating prompts for AI art creation
- Describing visual concepts for artists
- Creating detailed visual descriptions for creative projects

### Examples

Windows:
```
echo "A futuristic cityscape at sunset" | fabric --pattern create_art_prompt
```

macOS/Linux:
```
echo "A futuristic cityscape at sunset" | fabric --pattern create_art_prompt
```

Output is a 100-word description that instructs the AI on what to create, including how the art should evoke feelings and suggest style through examples.

## create_better_frame

### Overview
The `create_better_frame` pattern explores the concept of framing as a way to construct and interpret reality through different lenses, emphasizing the power of perspective in shaping one's experience of the world.

### Use Cases
- Developing new perspectives on complex issues
- Creating content for personal development workshops
- Generating ideas for cognitive reframing exercises

### Examples

Windows:
```
echo "Reframe the concept of failure" | fabric --pattern create_better_frame
```

macOS/Linux:
```
echo "Reframe the concept of failure" | fabric --pattern create_better_frame
```

Output is an essay-like exploration of different frames and perspectives on the given topic, illustrating how changing frames can lead to different outcomes and perceptions.

## create_coding_project

### Overview
The `create_coding_project` pattern generates wireframes and starter code for coding projects based on user ideas.

### Use Cases
- Kickstarting new software development projects
- Creating project outlines for coding tutorials
- Generating initial code structures for applications

### Examples

Windows:
```
echo "Create a todo list app with user authentication" | fabric --pattern create_coding_project
```

macOS/Linux:
```
echo "Create a todo list app with user authentication" | fabric --pattern create_coding_project
```

Output includes project summaries, structured directories, and initial code setups.

## create_command

### Overview
The `create_command` pattern generates specific command lines for various penetration testing tools based on a brief description of the desired outcome.

### Use Cases
- Assisting in penetration testing activities
- Generating complex command-line instructions
- Creating examples for cybersecurity training materials

### Examples

Windows:
```
echo "Perform a port scan on 192.168.1.1 using nmap" | fabric --pattern create_command
```

macOS/Linux:
```
echo "Perform a port scan on 192.168.1.1 using nmap" | fabric --pattern create_command
```

Output is a precise command that aligns with the user's objectives for the specified tool.

## create_cyber_summary

### Overview
The `create_cyber_summary` pattern creates a comprehensive summary of cybersecurity threats, vulnerabilities, incidents, and malware for a technical audience.

### Use Cases
- Summarizing cybersecurity reports
- Creating briefings on current cyber threats
- Compiling information for security awareness training

### Examples

Windows:
```
type cyber_threat_report.txt | fabric --pattern create_cyber_summary
```

macOS/Linux:
```
cat cyber_threat_report.txt | fabric --pattern create_cyber_summary
```

Output includes a concise summary and categorized lists of cybersecurity issues.

## create_git_diff_commit

### Overview
The `create_git_diff_commit` pattern guides the creation of Nuclei templates for cybersecurity applications, focusing on generating precise and efficient scanning templates for various protocols.

### Use Cases
- Guiding developers through Git operations
- Creating tutorials on Git usage
- Generating explanations for version control processes

### Examples

Windows:
```
echo "Show changes since last commit and current repo state" | fabric --pattern create_git_diff_commit
```

macOS/Linux:
```
echo "Show changes since last commit and current repo state" | fabric --pattern create_git_diff_commit
```

Output is a guide on executing these Git commands with explanations.

## create_idea_compass

### Overview
The `create_idea_compass` pattern guides users in developing a structured exploration of ideas through a detailed template.

### Use Cases
- Brainstorming and idea development
- Structuring complex concepts for presentations
- Creating comprehensive outlines for research papers

### Examples

Windows:
```
echo "Explore the idea of sustainable urban development" | fabric --pattern create_idea_compass
```

macOS/Linux:
```
echo "Explore the idea of sustainable urban development" | fabric --pattern create_idea_compass
```

Output is a comprehensive summary with related ideas, evidence, and sources organized in a structured format.

## create_investigation_visualization

### Overview
The `create_investigation_visualization` pattern creates detailed GraphViz visualizations to illustrate complex intelligence investigations and data insights.

### Use Cases
- Visualizing complex data relationships
- Creating graphical representations of investigations
- Generating network diagrams for analysis

### Examples

Windows:
```
type investigation_data.txt | fabric --pattern create_investigation_visualization
```

macOS/Linux:
```
cat investigation_data.txt | fabric --pattern create_investigation_visualization
```

Output includes a comprehensive diagram and analytical conclusions with a certainty rating.

## create_keynote

### Overview
The `create_keynote` pattern guides in creating TED-quality keynote presentations from provided input, focusing on narrative flow and practical takeaways.

### Use Cases
- Developing engaging presentation outlines
- Creating structure for public speaking engagements
- Generating content for keynote addresses

### Examples

Windows:
```
echo "Create a keynote on the future of artificial intelligence" | fabric --pattern create_keynote
```

macOS/Linux:
```
echo "Create a keynote on the future of artificial intelligence" | fabric --pattern create_keynote
```

Output includes a story flow, the final takeaway, and a detailed slide deck presentation.

## create_logo

### Overview
The `create_logo` pattern generates simple, minimalist company logos based on provided input, focusing on elegance and impact without text.

### Use Cases
- Generating logo concepts for branding projects
- Creating minimalist design ideas
- Producing prompts for AI image generators

### Examples

Windows:
```
echo "Create a logo for a tech startup named 'Quantum Leap'" | fabric --pattern create_logo
```

macOS/Linux:
```
echo "Create a logo for a tech startup named 'Quantum Leap'" | fabric --pattern create_logo
```

Output is a prompt for an AI image generator to create a simple, vector graphic logo.

## create_markmap_visualization

### Overview
The `create_markmap_visualization` pattern transforms complex ideas into visual formats using MarkMap syntax for easy understanding.

### Use Cases
- Creating mind maps from complex data
- Visualizing hierarchical information
- Generating interactive diagrams for presentations

### Examples

Windows:
```
type complex_concept.txt | fabric --pattern create_markmap_visualization
```

macOS/Linux:
```
cat complex_concept.txt | fabric --pattern create_markmap_visualization
```

Output is a MarkMap syntax diagram that visually communicates the core ideas.

## create_mermaid_visualization

### Overview
The `create_mermaid_visualization` pattern transforms complex ideas into simplified Mermaid (Markdown) visual diagrams.

### Use Cases
- Creating flowcharts from text descriptions
- Visualizing processes or algorithms
- Generating diagrams for documentation

### Examples

Windows:
```
echo "Visualize the software development lifecycle" | fabric --pattern create_mermaid_visualization
```

macOS/Linux:
```
echo "Visualize the software development lifecycle" | fabric --pattern create_mermaid_visualization
```

Output is a Mermaid syntax diagram accompanied by a concise visual explanation.

## create_micro_summary

### Overview
The `create_micro_summary` pattern summarizes content into a Markdown formatted summary, focusing on brevity and clarity.

### Use Cases
- Creating quick summaries of long articles
- Generating concise overviews for reports
- Producing
[Continuing from where the previous content left off...]

## create_micro_summary

### Overview
The `create_micro_summary` pattern summarizes content into a Markdown formatted summary, focusing on brevity and clarity.

### Use Cases
- Creating quick summaries of long articles
- Generating concise overviews for reports
- Producing brief content for social media posts

### Examples

Windows:
```
type long_article.txt | fabric --pattern create_micro_summary
```

macOS/Linux:
```
cat long_article.txt | fabric --pattern create_micro_summary
```

Output includes a one-sentence summary, main points, and key takeaways, each adhering to strict word limits.

## create_network_threat_landscape

### Overview
The `create_network_threat_landscape` pattern analyzes open ports and services from network scans to identify security risks and provide recommendations.

### Use Cases
- Assessing network security posture
- Identifying potential vulnerabilities in IT infrastructure
- Creating security reports for organizations

### Examples

Windows:
```
type network_scan_results.txt | fabric --pattern create_network_threat_landscape
```

macOS/Linux:
```
cat network_scan_results.txt | fabric --pattern create_network_threat_landscape
```

Output is a markdown formatted threat report with sections on description, risk, recommendations, a concise summary, trends, and quotes from the analysis.

## create_npc

### Overview
The `create_npc` pattern generates detailed NPCs (Non-Player Characters) for D&D 5th edition, incorporating a wide range of characteristics from background to appearance.

### Use Cases
- Creating diverse characters for role-playing games
- Generating NPCs for storytelling and world-building
- Assisting Dungeon Masters in campaign preparation

### Examples

Windows:
```
echo "Create a mysterious elven merchant NPC" | fabric --pattern create_npc
```

macOS/Linux:
```
echo "Create a mysterious elven merchant NPC" | fabric --pattern create_npc
```

Output is a comprehensive character profile suitable for gameplay, including backstory, traits, and goals.

## create_pattern

### Overview
The `create_pattern` pattern is designed to interpret and respond to LLM/AI prompts with structured outputs, specializing in organizing and analyzing prompts to produce responses that adhere to specific instructions and formatting requirements.

### Use Cases
- Developing new AI prompts
- Structuring complex AI tasks
- Creating templates for AI-generated content

### Examples

Windows:
```
echo "Create a pattern for analyzing customer feedback" | fabric --pattern create_pattern
```

macOS/Linux:
```
echo "Create a pattern for analyzing customer feedback" | fabric --pattern create_pattern
```

Output is a structured AI prompt with clear instructions and formatting guidelines.

## create_quiz

### Overview
The `create_quiz` pattern generates questions for reviewing learning objectives based on provided subject and objectives.

### Use Cases
- Creating educational assessments
- Generating review materials for students
- Developing quiz content for learning platforms

### Examples

Windows:
```
echo "Create a quiz on basic algebra concepts" | fabric --pattern create_quiz
```

macOS/Linux:
```
echo "Create a quiz on basic algebra concepts" | fabric --pattern create_quiz
```

Output consists of questions aimed at helping students review key concepts related to the specified subject and learning objectives.

## create_reading_plan

### Overview
The `create_reading_plan` pattern designs a tailored three-phase reading plan based on user input, focusing on an author or specific guidance.

### Use Cases
- Developing personalized reading lists
- Creating structured learning paths through literature
- Generating book recommendations for specific topics or authors

### Examples

Windows:
```
echo "Create a reading plan for understanding classical philosophy" | fabric --pattern create_reading_plan
```

macOS/Linux:
```
echo "Create a reading plan for understanding classical philosophy" | fabric --pattern create_reading_plan
```

Output includes a concise plan summary and categorized reading lists with reasons for each selection.

## create_report_finding

### Overview
The `create_report_finding` pattern instructs the creation of a detailed markdown security finding report, incorporating sections like Description, Risk, Recommendations, and others, based on a vulnerability title and explanation provided by the user.

### Use Cases
- Generating security assessment reports
- Documenting vulnerabilities in systems
- Creating standardized cybersecurity findings

### Examples

Windows:
```
echo "SQL Injection vulnerability in login form" | fabric --pattern create_report_finding
```

macOS/Linux:
```
echo "SQL Injection vulnerability in login form" | fabric --pattern create_report_finding
```

Output is a comprehensive report with specific sections, focusing on clarity, insightfulness, and relevance to cybersecurity assessment.

## create_security_update

### Overview
The `create_security_update` pattern instructs on creating concise security updates for newsletters, focusing on cybersecurity developments, threats, advisories, and new vulnerabilities.

### Use Cases
- Generating content for security newsletters
- Summarizing recent cybersecurity threats
- Creating brief security advisories

### Examples

Windows:
```
type recent_security_news.txt | fabric --pattern create_security_update
```

macOS/Linux:
```
cat recent_security_news.txt | fabric --pattern create_security_update
```

Output includes structured sections with short descriptions and relevant details, aiming to inform readers about the latest security concerns efficiently.

## create_show_intro

### Overview
The `create_show_intro` pattern creates compelling short intros for podcasts, focusing on the most interesting aspects of the show.

### Use Cases
- Writing podcast introductions
- Creating engaging openings for video content
- Summarizing key points for audio or video shows

### Examples

Windows:
```
type podcast_transcript.txt | fabric --pattern create_show_intro
```

macOS/Linux:
```
cat podcast_transcript.txt | fabric --pattern create_show_intro
```

Output is a structured intro that teases the conversation's main points, designed to capture audience interest.

## create_stride_threat_model

### Overview
The `create_stride_threat_model` pattern instructs on creating a detailed threat model using the STRIDE per element methodology for a given system design document.

### Use Cases
- Conducting threat modeling for software systems
- Identifying potential security threats in system designs
- Creating comprehensive security assessments

### Examples

Windows:
```
type system_design.txt | fabric --pattern create_stride_threat_model
```

macOS/Linux:
```
cat system_design.txt | fabric --pattern create_stride_threat_model
```

Output is a comprehensive table listing threats, their components, mitigation strategies, and risk assessments based on the STRIDE methodology.

## create_summary

### Overview
The `create_summary` pattern summarizes content into a structured Markdown format, focusing on brevity and clarity.

### Use Cases
- Condensing long articles or reports
- Creating quick overviews of complex topics
- Generating executive summaries

### Examples

Windows:
```
type long_document.txt | fabric --pattern create_summary
```

macOS/Linux:
```
cat long_document.txt | fabric --pattern create_summary
```

Output is organized into specific sections for easy reference, including a concise summary, main points, and key takeaways.

## create_threat_model

### Overview
The `create_threat_model` pattern outlines a comprehensive approach to everyday threat modeling, emphasizing its application beyond technical defenses to include personal and physical security scenarios.

### Use Cases
- Developing security strategies for various scenarios
- Assessing risks in personal and professional contexts
- Creating comprehensive threat assessments

### Examples

Windows:
```
echo "Create a threat model for a small business office" | fabric --pattern create_threat_model
```

macOS/Linux:
```
echo "Create a threat model for a small business office" | fabric --pattern create_threat_model
```

Output involves creating threat models for various scenarios, highlighting realistic defenses, and guiding individuals towards logical security decisions through structured analysis.

## create_threat_scenarios

### Overview
The `create_threat_scenarios` pattern seeks to identify and prioritize potential threats to a given system or situation, using a narrative-based, simple threat modeling approach.

### Use Cases
- Developing realistic security scenarios
- Prioritizing security measures based on threat likelihood
- Creating training materials for security awareness

### Examples

Windows:
```
echo "Identify threats for a cloud-based financial application" | fabric --pattern create_threat_scenarios
```

macOS/Linux:
```
echo "Identify threats for a cloud-based financial application" | fabric --pattern create_threat_scenarios
```

Output includes a list of prioritized threat scenarios, an analysis of the threat model, recommended controls, a narrative analysis, and a concise conclusion.

## create_upgrade_pack

### Overview
The `create_upgrade_pack` pattern extracts and organizes insights on world models and task algorithms from provided content.

### Use Cases
- Developing improvement strategies for systems or processes
- Creating actionable insights from complex data
- Generating upgrade recommendations for software or workflows

### Examples

Windows:
```
type system_analysis.txt | fabric --pattern create_upgrade_pack
```

macOS/Linux:
```
cat system_analysis.txt | fabric --pattern create_upgrade_pack
```

Output includes concise, actionable bullet points under relevant categories, focusing on beliefs about the world and optimal task execution strategies.

## create_video_chapters

### Overview
The `create_video_chapters` pattern extracts and organizes the most engaging topics from a transcript with corresponding timestamps.

### Use Cases
- Creating chapter markers for long videos
- Summarizing key points of video content
- Generating content outlines for video descriptions

### Examples

Windows:
```
type video_transcript.txt | fabric --pattern create_video_chapters
```

macOS/Linux:
```
cat video_transcript.txt | fabric --pattern create_video_chapters
```

Output is a list of topics with their timestamps in a sequential format, highlighting key moments and subjects.

## create_visualization

### Overview
The `create_visualization` pattern transforms complex ideas into simplified ASCII art visualizations.

### Use Cases
- Creating simple visual representations of concepts
- Generating ASCII diagrams for text-based documentation
- Illustrating ideas in a format suitable for text-only environments

### Examples

Windows:
```
echo "Visualize the concept of circular economy" | fabric --pattern create_visualization
```

macOS/Linux:
```
echo "Visualize the concept of circular economy" | fabric --pattern create_visualization
```

Output is a detailed ASCII art representation accompanied by a concise visual explanation.

## explain_code

### Overview
The `explain_code` pattern analyzes and explains code, security tool outputs, or configuration texts, tailoring the explanation to the type of input.

### Use Cases
- Providing code explanations for learners
- Interpreting complex configuration files
- Explaining security tool outputs

### Examples

Windows:
```
type complex_code.py | fabric --pattern explain_code
```

macOS/Linux:
```
cat complex_code.py | fabric --pattern explain_code
```

Output is a detailed explanation or answer in designated sections, clarifying the function, implications, or settings based on the input's nature.

## explain_docs

### Overview
The `explain_docs` pattern transforms input about tool usage into improved, structured documentation.

### Use Cases
- Creating user-friendly documentation for software tools
- Improving existing technical documentation
- Generating clear usage instructions for complex systems

### Examples

Windows:
```
type tool_usage.txt | fabric --pattern explain_docs
```

macOS/Linux:
```
cat tool_usage.txt | fabric --pattern explain_docs
```

Output includes an overview, usage syntax, common use cases, and key features of the tool, presented in a clear and structured format.

## explain_project

### Overview
The `explain_project` pattern summarizes project documentation into a concise, user and developer-focused summary, highlighting its purpose, problem addressed, approach, installation, usage, and examples.

### Use Cases
- Creating project overviews for README files
- Summarizing complex projects for quick understanding
- Generating documentation for open-source projects

### Examples

Windows:
```
type project_docs.md | fabric --pattern explain_project
```

macOS/Linux:
```
cat project_docs.md | fabric --pattern explain_project
```

Output includes a project overview, problem it addresses, approach to solving the problem, and practical steps for installation and usage.

## explain_terms

### Overview
The `explain_terms` pattern produces a glossary of advanced terms found in specific content, including definitions and analogies.

### Use Cases
- Creating glossaries for technical documents
- Explaining complex terminology in educational materials
- Generating explanations for industry-specific jargon

### Examples

Windows:
```
type technical_article.txt | fabric --pattern explain_terms
```

macOS/Linux:
```
cat technical_article.txt | fabric --pattern explain_terms
```

Output is a list of terms with explanations and analogies in a structured Markdown format, focusing on obscure or complex terms.

## extract_algorithm_update_recommendations

### Overview
The `extract_algorithm_update_recommendations` pattern analyzes input to provide concise recommendations for improving processes.

### Use Cases
- Generating improvement suggestions for algorithms
- Extracting actionable advice from process descriptions
- Creating quick optimization tips for workflows

### Examples

Windows:
```
type algorithm_description.txt | fabric --pattern extract_algorithm_update_recommendations
```

macOS/Linux:
```
cat algorithm_description.txt | fabric --pattern extract_algorithm_update_recommendations
```

Output consists of a bulleted list of up to three brief suggestions for improvement.

## extract_article_wisdom

### Overview
The `extract_article_wisdom` pattern extracts key insights and valuable information from textual content, focusing on ideas, quotes, habits, and references.

### Use Cases
- Summarizing key points from articles or papers
- Extracting quotable content from long texts
- Identifying actionable insights from written material

### Examples

Windows:
```
type article.txt | fabric --pattern extract_article_wisdom
```

macOS/Linux:
```
cat article.txt | fabric --pattern extract_article_wisdom
```

Output includes summarized ideas, notable quotes, referenced materials, and habits worth adopting from the content.

## extract_book_ideas

### Overview
The `extract_book_ideas` pattern summarizes a book's key content by extracting 50 to 100 of its most interesting ideas.

### Use Cases
- Creating concise book summaries
- Extracting main concepts from lengthy texts
- Generating discussion points for book clubs or classes

### Examples

Windows:
```
type book_content.txt | fabric --pattern extract_book_ideas
```

macOS/Linux:
```
cat book_content.txt | fabric --pattern extract_book_ideas
```

Output is a concise list of bulleted ideas, limited to 20 words each, prioritized by interest and insightfulness.

## extract_book_recommendations

### Overview
The `extract_book_recommendations` pattern summarizes a book's key content by extracting 50 to 100 of its most practical recommendations, prioritizing the most impactful advice.

### Use Cases
- Creating actionable summaries of self-help books
- Extracting key advice from business or personal development literature
- Generating lists of practical tips from informational texts

### Examples

Windows:
```
type book_content.txt | fabric --pattern extract_book_recommendations
```

macOS/Linux:
```
cat book_content.txt | fabric --pattern extract_book_recommendations
```

Output is formatted as an instructive, bullet-pointed list, limited to 20 words each, focusing on the most impactful and practical advice.

## extract_business_ideas

### Overview
The `extract_business_ideas` pattern outlines a process for identifying and elaborating on innovative business ideas.

### Use Cases
- Brainstorming new business concepts
- Refining existing business ideas
- Generating potential startup proposals

### Examples

Windows:
```
type business_brainstorm.txt | fabric --pattern extract_business_ideas
```

macOS/Linux:
```
cat business_brainstorm.txt | fabric --pattern extract_business_ideas
```

Output includes two sections: a list of extracted ideas and a detailed elaboration on the top ten ideas, ensuring uniqueness and differentiation.

## extract_extraordinary_claims

### Overview
The `extract_extraordinary_claims` pattern identifies and lists extraordinary claims from conversations, focusing on those rejected by the scientific community or based on misinformation.

### Use Cases
- Fact-checking discussions or debates
- Identifying potential misinformation in conversations
- Analyzing content for extraordinary or unsubstantiated claims

### Examples

Windows:
```
type conversation_transcript.txt | fabric --pattern extract_extraordinary_claims
```

macOS/Linux:
```
cat conversation_transcript.txt | fabric --pattern extract_extraordinary_claims
```

Output is a detailed list of quotes, ranging from 50 to 100, showcasing claims

[Continuing from where the previous content left off...]

## extract_extraordinary_claims

[Content for this section was already provided in the previous part.]

## extract_ideas

### Overview
The `extract_ideas` pattern extracts and condenses insightful ideas from text into 15-word bullet points focusing on life's purpose and human progress.

### Use Cases
- Summarizing key ideas from philosophical texts
- Extracting core concepts from motivational content
- Creating concise lists of thought-provoking ideas

### Examples

Windows:
```
type philosophical_text.txt | fabric --pattern extract_ideas
```

macOS/Linux:
```
cat philosophical_text.txt | fabric --pattern extract_ideas
```

Output consists of a list of concise, thought-provoking ideas related to life's purpose and human progress.

## extract_insights

### Overview
The `extract_insights` pattern extracts and condenses complex insights from text on profound topics into 15-word bullet points.

### Use Cases
- Summarizing complex academic or philosophical texts
- Extracting key insights from research papers
- Creating concise summaries of thought leadership content

### Examples

Windows:
```
type complex_article.txt | fabric --pattern extract_insights
```

macOS/Linux:
```
cat complex_article.txt | fabric --pattern extract_insights
```

Output is a concise list of abstracted, insightful bullets related to human and technological advancement.

## extract_main_idea

### Overview
The `extract_main_idea` pattern extracts and highlights the most crucial or intriguing idea from any given content.

### Use Cases
- Identifying the core concept of an article or speech
- Summarizing the main point of a discussion
- Creating headlines or taglines from longer content

### Examples

Windows:
```
type article.txt | fabric --pattern extract_main_idea
```

macOS/Linux:
```
cat article.txt | fabric --pattern extract_main_idea
```

Output includes a concise main idea and a recommendation based on that idea.

## extract_patterns

### Overview
The `extract_patterns` pattern guides in identifying and analyzing recurring, surprising, or insightful patterns from a collection of ideas, data, or observations.

### Use Cases
- Analyzing trends in large datasets
- Identifying recurring themes in qualitative research
- Extracting insights for business strategy or scientific research

### Examples

Windows:
```
type data_observations.txt | fabric --pattern extract_patterns
```

macOS/Linux:
```
cat data_observations.txt | fabric --pattern extract_patterns
```

Output includes a detailed summary of patterns, an explanation of their selection and significance, and actionable advice based on these insights.

## extract_poc

### Overview
The `extract_poc` pattern analyzes security or bug bounty reports to extract and provide proof of concept URLs for validating vulnerabilities.

### Use Cases
- Verifying reported security vulnerabilities
- Extracting actionable information from bug reports
- Preparing for security testing based on reported issues

### Examples

Windows:
```
type security_report.txt | fabric --pattern extract_poc
```

macOS/Linux:
```
cat security_report.txt | fabric --pattern extract_poc
```

Output includes the URL with a specific command to execute it, like using curl or python, for direct verification of reported vulnerabilities.

## extract_predictions

### Overview
The `extract_predictions` pattern extracts and organizes predictions from content into a structured format.

### Use Cases
- Analyzing future trends from expert opinions
- Summarizing forecasts in research papers or articles
- Creating structured lists of predictions for various fields

### Examples

Windows:
```
type future_trends_article.txt | fabric --pattern extract_predictions
```

macOS/Linux:
```
cat future_trends_article.txt | fabric --pattern extract_predictions
```

Output includes a bulleted list and a detailed table of these predictions, including timelines, confidence levels, and verification methods.

## extract_questions

### Overview
The `extract_questions` pattern extracts questions from content and analyzes their effectiveness in eliciting high-quality responses.

### Use Cases
- Improving interview question sets
- Analyzing the quality of survey questions
- Extracting discussion prompts from educational materials

### Examples

Windows:
```
type interview_transcript.txt | fabric --pattern extract_questions
```

macOS/Linux:
```
cat interview_transcript.txt | fabric --pattern extract_questions
```

Output includes a list of questions, an analysis of their strengths, and recommendations for interviewers.

## extract_recommendations

### Overview
The `extract_recommendations` pattern extracts and condenses recommendations from content into a concise list.

### Use Cases
- Summarizing key takeaways from advisory reports
- Creating action item lists from long documents
- Extracting practical advice from self-help or business books

### Examples

Windows:
```
type advisory_report.txt | fabric --pattern extract_recommendations
```

macOS/Linux:
```
cat advisory_report.txt | fabric --pattern extract_recommendations
```

Output is a bulleted list of up to 20 brief recommendations extracted from the given material.

## extract_references

### Overview
The `extract_references` pattern extracts references to various forms of cultural and educational content from provided text.

### Use Cases
- Compiling bibliographies from academic papers
- Creating reading lists from lectures or talks
- Identifying cultural references in literary works

### Examples

Windows:
```
type academic_paper.txt | fabric --pattern extract_references
```

macOS/Linux:
```
cat academic_paper.txt | fabric --pattern extract_references
```

Output is a bulleted list of up to 20 references, each summarized in no more than 15 words.

## extract_song_meaning

### Overview
The `extract_song_meaning` pattern analyzes and interprets the meaning of songs based on extensive research and lyric examination.

### Use Cases
- Analyzing lyrics for literature classes
- Creating content for music blogs or reviews
- Developing interpretations for music appreciation

### Examples

Windows:
```
echo "Analyze 'Imagine' by John Lennon" | fabric --pattern extract_song_meaning
```

macOS/Linux:
```
echo "Analyze 'Imagine' by John Lennon" | fabric --pattern extract_song_meaning
```

Output includes a summary sentence, detailed meaning in bullet points, and evidence supporting the interpretation.

## extract_sponsors

### Overview
The `extract_sponsors` pattern identifies and distinguishes between official and potential sponsors from transcripts.

### Use Cases
- Analyzing podcast or video content for sponsorship information
- Identifying potential sponsorship opportunities from events
- Verifying official sponsors mentioned in content

### Examples

Windows:
```
type podcast_transcript.txt | fabric --pattern extract_sponsors
```

macOS/Linux:
```
cat podcast_transcript.txt | fabric --pattern extract_sponsors
```

Output lists official sponsors and potential sponsors based on their mention in the content.

## extract_videoid

### Overview
The `extract_videoid` pattern extracts video IDs from URLs for use in other applications.

### Use Cases
- Parsing video URLs for embedding or sharing
- Extracting video identifiers for API requests
- Automating video link processing

### Examples

Windows:
```
echo "https://www.youtube.com/watch?v=dQw4w9WgXcQ" | fabric --pattern extract_videoid
```

macOS/Linux:
```
echo "https://www.youtube.com/watch?v=dQw4w9WgXcQ" | fabric --pattern extract_videoid
```

Output is solely the video ID, with no additional information or errors included.

## extract_wisdom

### Overview
The `extract_wisdom` pattern extracts key insights, ideas, quotes, habits, and references from textual content to address the issue of information overload and the challenge of retaining knowledge.

### Use Cases
- Creating concise summaries of lengthy articles or books
- Extracting key points from lectures or talks
- Generating study guides or review materials

### Examples

Windows:
```
type long_article.txt | fabric --pattern extract_wisdom
```

macOS/Linux:
```
cat long_article.txt | fabric --pattern extract_wisdom
```

Output includes summarized ideas, notable quotes, relevant habits, and useful references, all aimed at enhancing understanding and retention.

## extract_wisdom_agents

### Overview
The `extract_wisdom_agents` pattern outlines a complex process for extracting insights from text content, focusing on themes like the meaning of life and technology's impact on humanity.

### Use Cases
- Analyzing philosophical or futuristic texts
- Extracting multi-faceted insights from complex writings
- Creating comprehensive summaries of thought-provoking content

### Examples

Windows:
```
type philosophical_essay.txt | fabric --pattern extract_wisdom_agents
```

macOS/Linux:
```
cat philosophical_essay.txt | fabric --pattern extract_wisdom_agents
```

Output includes structured sections filled with concise, insightful entries derived from the input material, covering summaries, ideas, insights, quotes, habits, facts, references, and recommendations.

## extract_wisdom_dm

### Overview
The `extract_wisdom_dm` pattern extracts and synthesizes valuable content from input text, focusing on insights related to life's purpose and human advancement.

### Use Cases
- Summarizing self-help or personal development content
- Extracting key ideas from motivational speeches or writings
- Creating condensed wisdom from lengthy philosophical texts

### Examples

Windows:
```
type motivational_speech.txt | fabric --pattern extract_wisdom_dm
```

macOS/Linux:
```
cat motivational_speech.txt | fabric --pattern extract_wisdom_dm
```

Output includes summaries, ideas, insights, and other categorized information for deep understanding and practical application.

## extract_wisdom_nometa

### Overview
The `extract_wisdom_nometa` pattern guides the extraction and organization of insightful content from text, focusing on life's purpose, human flourishing, and technology's impact.

### Use Cases
- Creating comprehensive summaries of philosophical texts
- Extracting actionable insights from complex writings
- Generating structured content for personal development materials

### Examples

Windows:
```
type philosophical_text.txt | fabric --pattern extract_wisdom_nometa
```

macOS/Linux:
```
cat philosophical_text.txt | fabric --pattern extract_wisdom_nometa
```

Output includes structured sections for summaries, ideas, insights, quotes, habits, facts, recommendations, and references, each with specific content and formatting requirements.

## find_hidden_message

### Overview
The `find_hidden_message` pattern analyzes political messages to reveal overt and hidden intentions.

### Use Cases
- Analyzing political speeches for underlying messages
- Uncovering hidden agendas in public statements
- Studying propaganda techniques in communications

### Examples

Windows:
```
type political_speech.txt | fabric --pattern find_hidden_message
```

macOS/Linux:
```
cat political_speech.txt | fabric --pattern find_hidden_message
```

Output includes overt messages, hidden cynical messages, supporting arguments, desired audience actions, and analyses from cynical to favorable perspectives.

## find_logical_fallacies

### Overview
The `find_logical_fallacies` pattern identifies and categorizes various fallacies in arguments or texts.

### Use Cases
- Analyzing debates or arguments for logical flaws
- Improving critical thinking skills
- Evaluating the validity of arguments in written content

### Examples

Windows:
```
type debate_transcript.txt | fabric --pattern find_logical_fallacies
```

macOS/Linux:
```
cat debate_transcript.txt | fabric --pattern find_logical_fallacies
```

Output is a list of identified fallacies with brief explanations of each.

## get_wow_per_minute

### Overview
The `get_wow_per_minute` pattern evaluates the density of wow-factor in content by analyzing its surprise, novelty, insight, value, and wisdom.

### Use Cases
- Assessing the engagement potential of content
- Evaluating the quality of educational or entertainment material
- Analyzing the impact of presentations or speeches

### Examples

Windows:
```
type presentation_transcript.txt | fabric --pattern get_wow_per_minute
```

macOS/Linux:
```
cat presentation_transcript.txt | fabric --pattern get_wow_per_minute
```

Output is a JSON report detailing scores and explanations for each wow-factor component and overall wow-factor per minute.

## get_youtube_rss

### Overview
The `get_youtube_rss` pattern generates RSS URLs for YouTube channels based on given channel IDs or URLs.

### Use Cases
- Creating RSS feeds for YouTube channels
- Automating YouTube channel monitoring
- Integrating YouTube content into RSS readers

### Examples

Windows:
```
echo "https://www.youtube.com/channel/UC-lHJZR3Gqxm24_Vd_AJ5Yw" | fabric --pattern get_youtube_rss
```

macOS/Linux:
```
echo "https://www.youtube.com/channel/UC-lHJZR3Gqxm24_Vd_AJ5Yw" | fabric --pattern get_youtube_rss
```

Output is solely the RSS URL for the specified YouTube channel.

## improve_academic_writing

### Overview
The `improve_academic_writing` pattern aims to enhance the quality of text for academic purposes.

### Use Cases
- Refining academic papers or essays
- Improving clarity and coherence in research writing
- Enhancing the overall quality of scholarly texts

### Examples

Windows:
```
type academic_paper_draft.txt | fabric --pattern improve_academic_writing
```

macOS/Linux:
```
cat academic_paper_draft.txt | fabric --pattern improve_academic_writing
```

Output is a professionally refined text with a list of applied corrections, focusing on grammar, clarity, coherence, and academic tone.

## improve_prompt

### Overview
The `improve_prompt` pattern enhances LLM/AI prompts by applying expert prompt writing techniques to achieve better results.

### Use Cases
- Refining AI prompts for better outputs
- Optimizing instructions for language models
- Improving the effectiveness of AI interactions

### Examples

Windows:
```
echo "Write a story about a detective" | fabric --pattern improve_prompt
```

macOS/Linux:
```
echo "Write a story about a detective" | fabric --pattern improve_prompt
```

Output is an improved version of the original prompt, optimized for clarity and effectiveness in AI interactions.

## improve_report_finding

### Overview
The `improve_report_finding` pattern creates an improved security finding report from a penetration test, detailing the finding, risk, recommendations, references, a concise summary, and insightful quotes.

### Use Cases
- Enhancing penetration test reports
- Improving clarity and depth of security findings
- Creating more comprehensive cybersecurity documentation

### Examples

Windows:
```
type security_finding.txt | fabric --pattern improve_report_finding
```

macOS/Linux:
```
cat security_finding.txt | fabric --pattern improve_report_finding
```

Output is a comprehensive, markdown-formatted report covering various sections including title, description, risk, recommendations, references, and quotes, aiming for clarity and depth in reporting.

## improve_writing

### Overview
The `improve_writing` pattern refines input text for enhanced clarity, coherence, grammar, and style.

### Use Cases
- Enhancing the quality of written content
- Improving readability and coherence of texts
- Correcting grammar and style issues in writing

### Examples

Windows:
```
type draft_article.txt | fabric --pattern improve_writing
```

macOS/Linux:
```
cat draft_article.txt | fabric --pattern improve_writing
```

Output is a grammatically correct and stylistically improved version of the text, preserving the original meaning.

## label_and_rate

### Overview
The `label_and_rate` pattern evaluates and categorizes content based on its relevance to specific human-centric themes, then assigns a tiered rating and a numerical quality score.

### Use Cases
- Categorizing and rating content for relevance
- Assessing the quality of articles or papers
- Creating structured evaluations of written material

### Examples

Windows:
```
type article.txt | fabric --pattern label_and_rate
```

macOS/Linux:
```
cat article.txt | fabric --pattern label_and_rate
```

Output is a structured JSON object detailing the content summary, labels, rating, and quality score with explanations.

## official_pattern_template

### Overview
The `official_pattern_template` pattern outlines a complex process for diagnosing and addressing psychological issues based on a person's background and behaviors.

### Use Cases
- Creating templates for psychological assessments
- Developing structured approaches to behavioral analysis
- Generating comprehensive personality profiles

### Examples

Windows:
```
type personal_history.txt | fabric --pattern official_pattern_template
```

macOS/Linux:
```
cat personal_history.txt | fabric --
```

[Continuing from where the previous content left off...]

## official_pattern_template

[Content for this section was already provided in the previous part.]

## philocapsulate

### Overview
The `philocapsulate` pattern summarizes teachings of philosophers or philosophies, providing detailed templates on their background, encapsulated philosophy, school, teachings, works, quotes, application, and life advice.

### Use Cases
- Creating comprehensive summaries of philosophical ideas
- Developing educational materials on philosophers and their works
- Generating structured overviews of philosophical schools of thought

### Examples

Windows:
```
echo "Summarize the philosophy of Immanuel Kant" | fabric --pattern philocapsulate
```

macOS/Linux:
```
echo "Summarize the philosophy of Immanuel Kant" | fabric --pattern philocapsulate
```

Output includes structured information for educational or analytical purposes, covering various aspects of the philosopher's life and work.

## provide_guidance

### Overview
The `provide_guidance` pattern provides comprehensive psychological advice tailored to the individual's specific question and context.

### Use Cases
- Offering personalized psychological advice
- Generating self-help recommendations
- Providing structured guidance for personal development

### Examples

Windows:
```
echo "How can I overcome my fear of public speaking?" | fabric --pattern provide_guidance
```

macOS/Linux:
```
echo "How can I overcome my fear of public speaking?" | fabric --pattern provide_guidance
```

Output includes a concise analysis, detailed scientific rationale, actionable recommendations, Esther Perel's perspective, self-reflection prompts, possible clinical diagnoses, and a summary, all aimed at fostering self-awareness and positive change.

## rate_ai_response

### Overview
The `rate_ai_response` pattern evaluates the quality of AI responses against the benchmark of human experts, assigning a letter grade and score.

### Use Cases
- Assessing the performance of AI models
- Comparing AI outputs to human expert standards
- Evaluating the quality of AI-generated content

### Examples

Windows:
```
type ai_response.txt | fabric --pattern rate_ai_response
```

macOS/Linux:
```
cat ai_response.txt | fabric --pattern rate_ai_response
```

Output includes a detailed justification for the assigned grade, highlighting specific strengths and weaknesses of the AI's response.

## rate_ai_result

### Overview
The `rate_ai_result` pattern evaluates the quality of AI-generated content based on construction, quality, and spirit.

### Use Cases
- Assessing AI-generated content for various applications
- Providing feedback on AI model outputs
- Comparing different AI models or versions

### Examples

Windows:
```
type ai_generated_content.txt | fabric --pattern rate_ai_result
```

macOS/Linux:
```
cat ai_generated_content.txt | fabric --pattern rate_ai_result
```

Output is a final score out of 100, with deductions detailed for each category (construction, quality, and spirit).

## rate_content

### Overview
The `rate_content` pattern evaluates content by labeling it with relevant single-word descriptors, rating its quality based on idea quantity and thematic alignment, and scoring it on a scale from 1 to 100.

### Use Cases
- Evaluating articles or blog posts for quality and relevance
- Assessing academic papers or research content
- Rating user-generated content for online platforms

### Examples

Windows:
```
type article.txt | fabric --pattern rate_content
```

macOS/Linux:
```
cat article.txt | fabric --pattern rate_content
```

Output includes a list of labels, a tiered rating with an explanation, and an overall quality score with justification.

## rate_value

### Overview
The `rate_value` pattern acknowledges the collaborative effort behind its creation, inspired by notable figures in information theory and viral content creation.

### Use Cases
- Attributing credit for collaborative work
- Recognizing influences in content creation
- Highlighting the theoretical foundations of a project

### Examples

Windows:
```
echo "Rate the value of this collaborative project" | fabric --pattern rate_value
```

macOS/Linux:
```
echo "Rate the value of this collaborative project" | fabric --pattern rate_value
```

Output is an attribution of credit, highlighting the fusion of theoretical foundations and modern digital strategies.

## raw_query

### Overview
The `raw_query` pattern produces the best possible output by thoroughly analyzing and understanding the input.

### Use Cases
- Generating open-ended responses to complex queries
- Providing detailed analysis of user inputs
- Creating comprehensive answers to broad questions

### Examples

Windows:
```
echo "Explain the impact of artificial intelligence on modern society" | fabric --pattern raw_query
```

macOS/Linux:
```
echo "Explain the impact of artificial intelligence on modern society" | fabric --pattern raw_query
```

Output is an optimal response tailored to the inferred desires of the input provider, based on deep analysis of the query.

## recommend_artists

### Overview
The `recommend_artists` pattern recommends a personalized festival schedule featuring artists similar to the user's preferences in EDM genres and artists.

### Use Cases
- Creating personalized music festival schedules
- Recommending new artists based on user preferences
- Generating customized event itineraries

### Examples

Windows:
```
echo "I like techno and house music, especially artists like Carl Cox and Amelie Lens" | fabric --pattern recommend_artists
```

macOS/Linux:
```
echo "I like techno and house music, especially artists like Carl Cox and Amelie Lens" | fabric --pattern recommend_artists
```

Output is a detailed schedule organized by day, set time, stage, and artist, optimized for the user's enjoyment based on their music preferences.

## show_fabric_options_markmap

### Overview
The `show_fabric_options_markmap` pattern creates a visual representation of the functionalities provided by the Fabric project, focusing on augmenting human capabilities with AI.

### Use Cases
- Visualizing the capabilities of the Fabric project
- Creating an overview of AI augmentation functionalities
- Generating a mind map of AI-assisted human capabilities

### Examples

Windows:
```
fabric --pattern show_fabric_options_markmap
```

macOS/Linux:
```
fabric --pattern show_fabric_options_markmap
```

Output is comprehensive Markmap code detailing the functionality map of Fabric, breaking down capabilities into categories like summarization, analysis, and more.

## suggest

### Overview
The `suggest` pattern analyzes user input to suggest appropriate fabric commands or patterns, enhancing the tool's functionality.

### Use Cases
- Assisting users in finding the right Fabric command
- Recommending appropriate patterns for specific tasks
- Improving user experience with the Fabric tool

### Examples

Windows:
```
echo "I want to summarize a long article" | fabric --pattern suggest
```

macOS/Linux:
```
echo "I want to summarize a long article" | fabric --pattern suggest
```

Output includes command suggestions, explanations, and instructions for new patterns if needed.

## summarize

### Overview
The `summarize` pattern summarizes content into a structured Markdown format, focusing on brevity and clarity.

### Use Cases
- Condensing long articles or reports
- Creating quick overviews of complex topics
- Generating executive summaries

### Examples

Windows:
```
type long_article.txt | fabric --pattern summarize
```

macOS/Linux:
```
cat long_article.txt | fabric --pattern summarize
```

Output includes a one-sentence summary, main points, and key takeaways, adhering to specified word limits.

## summarize_debate

### Overview
The `summarize_debate` pattern analyzes debates to identify and summarize the primary disagreements, arguments, and evidence that could change participants' minds.

### Use Cases
- Summarizing political or academic debates
- Analyzing arguments in discussions or forums
- Creating concise overviews of complex debates

### Examples

Windows:
```
type debate_transcript.txt | fabric --pattern summarize_debate
```

macOS/Linux:
```
cat debate_transcript.txt | fabric --pattern summarize_debate
```

Output includes structured summaries and analyses of each party's position and evidence, along with predictions of potential outcomes.

## summarize_git_changes

### Overview
The `summarize_git_changes` pattern summarizes major changes and upgrades in a GitHub project over the past week.

### Use Cases
- Creating weekly project update reports
- Summarizing recent changes in open-source projects
- Generating changelog entries for software updates

### Examples

Windows:
```
git log --since="1 week ago" --oneline | fabric --pattern summarize_git_changes
```

macOS/Linux:
```
git log --since="1 week ago" --oneline | fabric --pattern summarize_git_changes
```

Output includes a 20-word introduction and excitedly written update bullets highlighting key changes.

## summarize_git_diff

### Overview
The `summarize_git_diff` pattern analyzes Git diffs to summarize major changes and upgrades.

### Use Cases
- Summarizing code changes for pull requests
- Creating concise commit messages
- Generating changelog entries from Git diffs

### Examples

Windows:
```
git diff | fabric --pattern summarize_git_diff
```

macOS/Linux:
```
git diff | fabric --pattern summarize_git_diff
```

Output includes a 100-character intro sentence using conventional commits format and concise bullet points for feature changes and updates.

## summarize_micro

### Overview
The `summarize_micro` pattern summarizes content into a structured Markdown format with concise, bullet-pointed summaries and takeaways.

### Use Cases
- Creating quick summaries of articles or reports
- Generating brief overviews for presentations
- Producing concise content for social media or newsletters

### Examples

Windows:
```
type article.txt | fabric --pattern summarize_micro
```

macOS/Linux:
```
cat article.txt | fabric --pattern summarize_micro
```

Output includes a one-sentence summary and lists of main points and takeaways in a concise format.

## summarize_newsletter

### Overview
The `summarize_newsletter` pattern extracts and organizes key content from newsletters, focusing on the most meaningful, interesting, and useful information.

### Use Cases
- Creating quick digests of lengthy newsletters
- Extracting key points from industry updates
- Generating concise summaries of email newsletters

### Examples

Windows:
```
type newsletter.txt | fabric --pattern summarize_newsletter
```

macOS/Linux:
```
cat newsletter.txt | fabric --pattern summarize_newsletter
```

Output includes sections for a brief summary, detailed content points, author opinions, mentioned tools and companies, and recommended follow-ups in a structured Markdown format.

## summarize_paper

### Overview
The `summarize_paper` pattern summarizes academic papers by extracting key sections such as title, authors, main goals, and more from the provided text.

### Use Cases
- Creating quick overviews of research papers
- Generating abstracts or summaries for academic work
- Assisting in literature reviews by summarizing multiple papers

### Examples

Windows:
```
type academic_paper.txt | fabric --pattern summarize_paper
```

macOS/Linux:
```
cat academic_paper.txt | fabric --pattern summarize_paper
```

Output is a detailed summary covering various dimensions of the research, including methodology, distinctive features, and experimental outcomes.

## summarize_pattern

### Overview
The `summarize_pattern` pattern instructs on summarizing AI chat prompts into concise paragraphs.

### Use Cases
- Creating brief descriptions of AI prompts
- Summarizing the purpose and approach of AI patterns
- Generating concise explanations of AI task instructions

### Examples

Windows:
```
type ai_prompt.txt | fabric --pattern summarize_pattern
```

macOS/Linux:
```
cat ai_prompt.txt | fabric --pattern summarize_pattern
```

Output is a structured summary highlighting the prompt's purpose, approach, and anticipated results, using active voice and present tense for clarity.

## summarize_pull-requests

### Overview
The `summarize_pull-requests` pattern summarizes pull requests for a coding project, focusing on the types of changes made.

### Use Cases
- Creating summaries of recent code contributions
- Generating overview reports for project managers
- Summarizing development activity for team meetings

### Examples

Windows:
```
git log --merges --first-parent main --pretty=format:"%s" | fabric --pattern summarize_pull-requests
```

macOS/Linux:
```
git log --merges --first-parent main --pretty=format:"%s" | fabric --pattern summarize_pull-requests
```

Output includes a concise overview and specific examples of pull requests, rewritten for clarity.

## summarize_rpg_session

### Overview
The `summarize_rpg_session` pattern outlines the process for summarizing in-person role-playing game sessions, focusing on key events, combat details, character development, and worldbuilding.

### Use Cases
- Creating session summaries for role-playing game groups
- Documenting campaign progress for long-term RPG stories
- Generating recap material for players between sessions

### Examples

Windows:
```
type rpg_session_notes.txt | fabric --pattern summarize_rpg_session
```

macOS/Linux:
```
cat rpg_session_notes.txt | fabric --pattern summarize_rpg_session
```

Output includes a comprehensive overview of the session's storyline, character interactions, and significant moments, tailored for both players and observers.

## to_flashcards

### Overview
The `to_flashcards` pattern creates Anki cards from texts following specific principles to ensure simplicity, optimized wording, and no reliance on external context.

### Use Cases
- Generating study materials from textbooks or lecture notes
- Creating flashcards for language learning
- Developing quiz questions for educational content

### Examples

Windows:
```
type study_material.txt | fabric --pattern to_flashcards
```

macOS/Linux:
```
cat study_material.txt | fabric --pattern to_flashcards
```

Output is a set of questions and answers formatted as a CSV table, optimized for learning efficiency and comprehension.

## tweet

### Overview
The `tweet` pattern guides users on crafting engaging tweets with emojis, focusing on Twitter's basics and content creation strategies.

### Use Cases
- Crafting effective social media posts
- Learning to use emojis in tweets effectively
- Developing engaging Twitter content strategies

### Examples

Windows:
```
echo "Create a tweet about a new tech product launch" | fabric --pattern tweet
```

macOS/Linux:
```
echo "Create a tweet about a new tech product launch" | fabric --pattern tweet
```

Output is a comprehensive guide for creating appealing tweets with emojis, including strategy and examples.

## write_essay

### Overview
The `write_essay` pattern is designed to write an essay in the style of Paul Graham, focusing on the essence and approach of writing concise, clear, and illuminating essays on any given topic.

### Use Cases
- Generating thought-provoking essays on various topics
- Creating content for blogs or opinion pieces
- Developing writing samples in a specific style

### Examples

Windows:
```
echo "Write an essay on the future of work" | fabric --pattern write_essay
```

macOS/Linux:
```
echo "Write an essay on the future of work" | fabric --pattern write_essay
```

Output is an essay written in Paul Graham's style, focusing on clarity, conciseness, and insightful analysis of the given topic.

## write_micro_essay

### Overview
The `write_micro_essay` pattern is designed to write an essay in the style of Paul Graham, focusing on the essence of simplicity in conveying complex ideas.

### Use Cases
- Creating concise, impactful essays on complex topics
- Generating brief but insightful content for social media
- Developing short-form thought leadership pieces

### Examples

Windows:
```
echo "Write a micro essay on the importance of critical thinking" | fabric --pattern write_micro_essay
```

macOS/Linux:
```
echo "Write a micro essay on the importance of critical thinking" | fabric --pattern write_micro_essay
```

Output is a brief, focused essay that conveys complex ideas in a simple, Paul Graham-inspired style.

## write_nuclei_template_rule

### Overview
The `write_nuclei_template_rule` pattern guides the creation of Nuclei templates for cybersecurity applications, focusing on generating precise and efficient scanning templates for various protocols.

### Use Cases
- Developing custom security scanning templates
- Creating rules for vulnerability detection
- Enhancing cybersecurity assessment tools

### Examples

Windows:
```
echo "Create a Nuclei template for detecting SQL injection vulnerabilities" | fabric --pattern write_nuclei_template_rule
```

macOS/Linux:
```
echo "Create a Nuclei template for detecting SQL injection vulnerabilities" | fabric --pattern write_
```
[Continuing from where the previous content left off...]

## write_nuclei_template_rule

### Overview
The `write_nuclei_template_rule` pattern guides the creation of Nuclei templates for cybersecurity applications, focusing on generating precise and efficient scanning templates for various protocols.

### Use Cases
- Developing custom security scanning templates
- Creating rules for vulnerability detection
- Enhancing cybersecurity assessment tools

### Examples

Windows:
```
echo "Create a Nuclei template for detecting SQL injection vulnerabilities" | fabric --pattern write_nuclei_template_rule
```

macOS/Linux:
```
echo "Create a Nuclei template for detecting SQL injection vulnerabilities" | fabric --pattern write_nuclei_template_rule
```

Output is a well-structured YAML Nuclei template that adheres to best practices in template creation, including handling dynamic data extraction and ensuring accurate vulnerability detection.

## write_pull-request

### Overview
The `write_pull-request` pattern instructs on drafting a detailed pull request (PR) description based on the output of a `git diff` command, focusing on identifying and explaining code changes.

### Use Cases
- Creating comprehensive pull request descriptions
- Documenting code changes for review processes
- Improving collaboration in software development workflows

### Examples

Windows:
```
git diff main..feature-branch | fabric --pattern write_pull-request
```

macOS/Linux:
```
git diff main..feature-branch | fabric --pattern write_pull-request
```

Output is a structured PR description in markdown, covering a summary of changes, reasons, impacts, and testing plans in clear language.

## write_semgrep_rule

### Overview
The `write_semgrep_rule` pattern requests the creation of a Semgrep rule to detect a specific vulnerability pattern in code, based on provided context and examples.

### Use Cases
- Developing custom static analysis rules
- Creating security-focused code scanning rules
- Enhancing code quality checks in development pipelines

### Examples

Windows:
```
echo "Create a Semgrep rule to detect hardcoded API keys in Python code" | fabric --pattern write_semgrep_rule
```

macOS/Linux:
```
echo "Create a Semgrep rule to detect hardcoded API keys in Python code" | fabric --pattern write_semgrep_rule
```

Output is a well-structured Semgrep rule that aligns with the syntax and guidelines detailed in the context, capable of identifying the vulnerability across different scenarios.