# 📊 Fabric Patterns Cheatsheet

# Piping Into Fabric

## Piping

- Connects output of one command to input of another
- Allows chaining multiple commands for complex operations
- Uses vertical bar symbol "|" between commands
- Enables efficient data processing and manipulation

## Windows
```Powershell
### From Clipboard
 Get-Clipboard | fabric --pattern analyze_claims

### From File
type article.txt | fabric --pattern analyze_claims

### From your your own text
echo "Explain the concept of artificial intelligence" | fabric --pattern ai

### From Youtube Transcript

yt --transcript https://youtube.com/watch?v=uXs-zPc63kM | fabric --stream --pattern extract_wisdom
```
## Mac

```bash
### From Clipboard
 pbpaste | fabric --pattern analyze_claims

### From File
cat article.txt | fabric --pattern analyze_claims

### From your your own text
echo "Explain the concept of artificial intelligence" | fabric --pattern ai

### From Youtube Transcript
yt --transcript https://youtube.com/watch?v=uXs-zPc63kM | fabric --stream --pattern extract_wisdom
```
# Pattern Sections

## 🔍 Analysis Patterns

| Pattern | Description | Windows Command | Mac/Linux Command |
|---------|-------------|-----------------|-------------------|
| 🧠 analyze_answers | Evaluates learner responses | `type answers.txt \| fabric --pattern analyze_answers` | `cat answers.txt \| fabric --pattern analyze_answers` |
| ⚖️ analyze_claims | Fact-checks and rates claims | `type article.txt \| fabric --pattern analyze_claims` | `cat article.txt \| fabric --pattern analyze_claims` |
| 🗣️ analyze_debate | Analyzes debate transcripts | `type debate_transcript.txt \| fabric --pattern analyze_debate` | `cat debate_transcript.txt \| fabric --pattern analyze_debate` |
| 🛡️ analyze_incident | Summarizes security breaches | `type incident_report.txt \| fabric --pattern analyze_incident` | `cat incident_report.txt \| fabric --pattern analyze_incident` |
| 📊 analyze_logs | Identifies server log patterns | `type server_log.txt \| fabric --pattern analyze_logs` | `cat server_log.txt \| fabric --pattern analyze_logs` |
| 🦠 analyze_malware | Examines malware behavior | `type malware_report.txt \| fabric --pattern analyze_malware` | `cat malware_report.txt \| fabric --pattern analyze_malware` |
| 📑 analyze_paper | Evaluates research papers | `type research_paper.txt \| fabric --pattern analyze_paper` | `cat research_paper.txt \| fabric --pattern analyze_paper` |
| 💡 analyze_patent | Assesses patent applications | `type patent_application.txt \| fabric --pattern analyze_patent` | `cat patent_application.txt \| fabric --pattern analyze_patent` |
| 🧘 analyze_personality | Performs psychological analysis | `type character_description.txt \| fabric --pattern analyze_personality` | `cat character_description.txt \| fabric --pattern analyze_personality` |
| 🎤 analyze_presentation | Critiques presentations | `type presentation_transcript.txt \| fabric --pattern analyze_presentation` | `cat presentation_transcript.txt \| fabric --pattern analyze_presentation` |
| ✍️ analyze_prose | Evaluates writing quality | `type essay.txt \| fabric --pattern analyze_prose` | `cat essay.txt \| fabric --pattern analyze_prose` |
| 📊 analyze_prose_json | Structured writing analysis | `type article.txt \| fabric --pattern analyze_prose_json` | `cat article.txt \| fabric --pattern analyze_prose_json` |
| 📚 analyze_prose_pinker | Applies Pinker's principles | `type essay.txt \| fabric --pattern analyze_prose_pinker` | `cat essay.txt \| fabric --pattern analyze_prose_pinker` |
| 🕯️ analyze_spiritual_text | Compares spiritual texts | `type spiritual_text.txt \| fabric --pattern analyze_spiritual_text` | `cat spiritual_text.txt \| fabric --pattern analyze_spiritual_text` |
| 🛡️ analyze_threat_report | Extracts cybersecurity insights | `type threat_report.txt \| fabric --pattern analyze_threat_report` | `cat threat_report.txt \| fabric --pattern analyze_threat_report` |
| 📈 analyze_threat_report_trends | Identifies security trends | `type multiple_threat_reports.txt \| fabric --pattern analyze_threat_report_trends` | `cat multiple_threat_reports.txt \| fabric --pattern analyze_threat_report_trends` |

## 📝 Summarization Patterns

| Pattern | Description | Windows Command | Mac/Linux Command |
|---------|-------------|-----------------|-------------------|
| 5️⃣ create_5_sentence_summary | Multi-level summaries | `type long_article.txt \| fabric --pattern create_5_sentence_summary` | `cat long_article.txt \| fabric --pattern create_5_sentence_summary` |
| 🔤 create_micro_summary | Brief, structured summaries | `type long_article.txt \| fabric --pattern create_micro_summary` | `cat long_article.txt \| fabric --pattern create_micro_summary` |
| 📋 create_summary | Comprehensive summaries | `type long_document.txt \| fabric --pattern create_summary` | `cat long_document.txt \| fabric --pattern create_summary` |
| 📚 summarize | General-purpose summarization | `type long_article.txt \| fabric --pattern summarize` | `cat long_article.txt \| fabric --pattern summarize` |
| 🗣️ summarize_debate | Debate analysis and summary | `type debate_transcript.txt \| fabric --pattern summarize_debate` | `cat debate_transcript.txt \| fabric --pattern summarize_debate` |
| 🐙 summarize_git_changes | GitHub project updates | `git log --since="1 week ago" --oneline \| fabric --pattern summarize_git_changes` | `git log --since="1 week ago" --oneline \| fabric --pattern summarize_git_changes` |
| 🔄 summarize_git_diff | Git diff summaries | `git diff \| fabric --pattern summarize_git_diff` | `git diff \| fabric --pattern summarize_git_diff` |
| 📰 summarize_newsletter | Extracts key newsletter content | `type newsletter.txt \| fabric --pattern summarize_newsletter` | `cat newsletter.txt \| fabric --pattern summarize_newsletter` |
| 📄 summarize_paper | Summarizes academic papers | `type academic_paper.txt \| fabric --pattern summarize_paper` | `cat academic_paper.txt \| fabric --pattern summarize_paper` |
| 🔍 summarize_pattern | Summarizes AI chat prompts | `type ai_prompt.txt \| fabric --pattern summarize_pattern` | `cat ai_prompt.txt \| fabric --pattern summarize_pattern` |
| 🔀 summarize_pull-requests | Summarizes code contributions | `git log --merges --first-parent main --pretty=format:"%s" \| fabric --pattern summarize_pull-requests` | `git log --merges --first-parent main --pretty=format:"%s" \| fabric --pattern summarize_pull-requests` |
| 🎲 summarize_rpg_session | Summarizes role-playing game sessions | `type rpg_session_notes.txt \| fabric --pattern summarize_rpg_session` | `cat rpg_session_notes.txt \| fabric --pattern summarize_rpg_session` |

## 🎨 Creation Patterns

| Pattern | Description | Windows Command | Mac/Linux Command |
|---------|-------------|-----------------|-------------------|
| 📄 create_academic_paper | Generates research papers | `echo "Climate change effects" \| fabric --pattern create_academic_paper` | `echo "Climate change effects" \| fabric --pattern create_academic_paper` |
| 💼 create_ai_jobs_analysis | AI impact on job market | `type job_market_report.txt \| fabric --pattern create_ai_jobs_analysis` | `cat job_market_report.txt \| fabric --pattern create_ai_jobs_analysis` |
| 💬 create_aphorisms | Generates thought-provoking sayings | `echo "Success and failure" \| fabric --pattern create_aphorisms` | `echo "Success and failure" \| fabric --pattern create_aphorisms` |
| 🎨 create_art_prompt | Creates AI art instructions | `echo "Futuristic cityscape" \| fabric --pattern create_art_prompt` | `echo "Futuristic cityscape" \| fabric --pattern create_art_prompt` |
| 🖼️ create_better_frame | Explores perspective framing | `echo "Reframe failure concept" \| fabric --pattern create_better_frame` | `echo "Reframe failure concept" \| fabric --pattern create_better_frame` |
| 💻 create_coding_project | Generates project structures | `echo "Todo list app" \| fabric --pattern create_coding_project` | `echo "Todo list app" \| fabric --pattern create_coding_project` |
| 🔧 create_command | Creates tool command lines | `echo "Port scan using nmap" \| fabric --pattern create_command` | `echo "Port scan using nmap" \| fabric --pattern create_command` |
| 🛡️ create_cyber_summary | Cybersecurity threat summaries | `type cyber_threat_report.txt \| fabric --pattern create_cyber_summary` | `cat cyber_threat_report.txt \| fabric --pattern create_cyber_summary` |
| 🔄 create_git_diff_commit | Guides Git operations | `echo "Show changes since last commit" \| fabric --pattern create_git_diff_commit` | `echo "Show changes since last commit" \| fabric --pattern create_git_diff_commit` |
| 🧭 create_idea_compass | Structured idea exploration | `echo "Explore sustainable urban development" \| fabric --pattern create_idea_compass` | `echo "Explore sustainable urban development" \| fabric --pattern create_idea_compass` |
| 🕸️ create_investigation_visualization | Creates investigation diagrams | `type investigation_data.txt \| fabric --pattern create_investigation_visualization` | `cat investigation_data.txt \| fabric --pattern create_investigation_visualization` |
| 🎤 create_keynote | Develops presentation outlines | `echo "Future of AI" \| fabric --pattern create_keynote` | `echo "Future of AI" \| fabric --pattern create_keynote` |
| 🎨 create_logo | Generates minimalist logo concepts | `echo "Tech startup 'Quantum Leap'" \| fabric --pattern create_logo` | `echo "Tech startup 'Quantum Leap'" \| fabric --pattern create_logo` |
| 🗺️ create_markmap_visualization | Creates mind maps | `type complex_concept.txt \| fabric --pattern create_markmap_visualization` | `cat complex_concept.txt \| fabric --pattern create_markmap_visualization` |
| 📊 create_mermaid_visualization | Generates Mermaid diagrams | `echo "Visualize software development lifecycle" \| fabric --pattern create_mermaid_visualization` | `echo "Visualize software development lifecycle" \| fabric --pattern create_mermaid_visualization` |
| 🌐 create_network_threat_landscape | Analyzes network security risks | `type network_scan_results.txt \| fabric --pattern create_network_threat_landscape` | `cat network_scan_results.txt \| fabric --pattern create_network_threat_landscape` |
| 🎭 create_npc | Generates D&D character profiles | `echo "Create a mysterious elven merchant NPC" \| fabric --pattern create_npc` | `echo "Create a mysterious elven merchant NPC" \| fabric --pattern create_npc` |
| 🧩 create_pattern | Develops new AI prompts | `echo "Create a pattern for analyzing customer feedback" \| fabric --pattern create_pattern` | `echo "Create a pattern for analyzing customer feedback" \| fabric --pattern create_pattern` |
| 📝 create_quiz | Generates educational assessments | `echo "Create a quiz on basic algebra concepts" \| fabric --pattern create_quiz` | `echo "Create a quiz on basic algebra concepts" \| fabric --pattern create_quiz` |
| 📚 create_reading_plan | Designs personalized reading lists | `echo "Create a reading plan for classical philosophy" \| fabric --pattern create_reading_plan` | `echo "Create a reading plan for classical philosophy" \| fabric --pattern create_reading_plan` |
| 🔍 create_report_finding | Creates security finding reports | `echo "SQL Injection vulnerability in login form" \| fabric --pattern create_report_finding` | `echo "SQL Injection vulnerability in login form" \| fabric --pattern create_report_finding` |
| 🛡️ create_security_update | Generates security newsletter content | `type recent_security_news.txt \| fabric --pattern create_security_update` | `cat recent_security_news.txt \| fabric --pattern create_security_update` |
| 🎬 create_show_intro | Writes podcast introductions | `type podcast_transcript.txt \| fabric --pattern create_show_intro` | `cat podcast_transcript.txt \| fabric --pattern create_show_intro` |
| 🛡️ create_stride_threat_model | Creates STRIDE threat models | `type system_design.txt \| fabric --pattern create_stride_threat_model` | `cat system_design.txt \| fabric --pattern create_stride_threat_model` |
| 🔒 create_threat_model | Develops comprehensive threat models | `echo "Create a threat model for a small business office" \| fabric --pattern create_threat_model` | `echo "Create a threat model for a small business office" \| fabric --pattern create_threat_model` |
| 🔍 create_threat_scenarios | Identifies potential security threats | `echo "Identify threats for a cloud-based financial application" \| fabric --pattern create_threat_scenarios` | `echo "Identify threats for a cloud-based financial application" \| fabric --pattern create_threat_scenarios` |
| 🔄 create_upgrade_pack | Extracts system improvement insights | `type system_analysis.txt \| fabric --pattern create_upgrade_pack` | `cat system_analysis.txt \| fabric --pattern create_upgrade_pack` |
| 🎬 create_video_chapters | Extracts video content structure | `type video_transcript.txt \| fabric --pattern create_video_chapters` | `cat video_transcript.txt \| fabric --pattern create_video_chapters` |
| 🖼️ create_visualization | Creates ASCII art visualizations | `echo "Visualize circular economy concept" \| fabric --pattern create_visualization` | `echo "Visualize circular economy concept" \| fabric --pattern create_visualization` |

## 🔍 Extraction Patterns

| Pattern | Description | Windows Command | Mac/Linux Command |
|---------|-------------|-----------------|-------------------|
| 🧠 extract_algorithm_update_recommendations | Process improvement suggestions | `type algorithm_description.txt \| fabric --pattern extract_algorithm_update_recommendations` | `cat algorithm_description.txt \| fabric --pattern extract_algorithm_update_recommendations` |
| 📚 extract_article_wisdom | Key insights from articles | `type article.txt \| fabric --pattern extract_article_wisdom` | `cat article.txt \| fabric --pattern extract_article_wisdom` |
| 📖 extract_book_ideas | Summarizes book concepts | `type book_content.txt \| fabric --pattern extract_book_ideas` | `cat book_content.txt \| fabric --pattern extract_book_ideas` |
| 📝 extract_book_recommendations | Extracts practical advice | `type book_content.txt \| fabric --pattern extract_book_recommendations` | `cat book_content.txt \| fabric --pattern extract_book_recommendations` |
| 💡 extract_business_ideas | Generates business concepts | `type business_brainstorm.txt \| fabric --pattern extract_business_ideas` | `cat business_brainstorm.txt \| fabric --pattern extract_business_ideas` |
| ❗ extract_extraordinary_claims | Identifies unusual assertions | `type conversation_transcript.txt \| fabric --pattern extract_extraordinary_claims` | `cat conversation_transcript.txt \| fabric --pattern extract_extraordinary_claims` |
| 💡 extract_ideas | Extracts insightful ideas | `type philosophical_text.txt \| fabric --pattern extract_ideas` | `cat philosophical_text.txt \| fabric --pattern extract_ideas` |
| 🧠 extract_insights | Extracts complex insights | `type complex_article.txt \| fabric --pattern extract_insights` | `cat complex_article.txt \| fabric --pattern extract_insights` |
| 🎯 extract_main_idea | Identifies core concepts | `type article.txt \| fabric --pattern extract_main_idea` | `cat article.txt \| fabric --pattern extract_main_idea` |
| 🔍 extract_patterns | Analyzes recurring themes | `type data_observations.txt \| fabric --pattern extract_patterns` | `cat data_observations.txt \| fabric --pattern extract_patterns` |
| 🔬 extract_poc | Extracts proof of concept URLs | `type security_report.txt \| fabric --pattern extract_poc` | `cat security_report.txt \| fabric --pattern extract_poc` |
| 🔮 extract_predictions | Organizes future forecasts | `type future_trends_article.txt \| fabric --pattern extract_predictions` | `cat future_trends_article.txt \| fabric --pattern extract_predictions` |
| ❓ extract_questions | Analyzes question effectiveness | `type interview_transcript.txt \| fabric --pattern extract_questions` | `cat interview_transcript.txt \| fabric --pattern extract_questions` |
| 📝 extract_recommendations | Condenses actionable advice | `type advisory_report.txt \| fabric --pattern extract_recommendations` | `cat advisory_report.txt \| fabric --pattern extract_recommendations` |
| 📚 extract_references | Compiles content references | `type academic_paper.txt \| fabric --pattern extract_references` | `cat academic_paper.txt \| fabric --pattern extract_references` |
| 🎵 extract_song_meaning | Interprets song lyrics | `echo "Analyze 'Imagine' by John Lennon" \| fabric --pattern extract_song_meaning` | `echo "Analyze 'Imagine' by John Lennon" \| fabric --pattern extract_song_meaning` |
| 💼 extract_sponsors | Identifies potential sponsors | `type podcast_transcript.txt \| fabric --pattern extract_sponsors` | `cat podcast_transcript.txt \| fabric --pattern extract_sponsors` |
| 🎥 extract_videoid | Extracts video IDs from URLs | `echo "https://www.youtube.com/watch?v=dQw4w9WgXcQ" \| fabric --pattern extract_videoid` | `echo "https://www.youtube.com/watch?v=dQw4w9WgXcQ" \| fabric --pattern extract_videoid` |
| 🧠 extract_wisdom | Extracts key insights and ideas | `type long_article.txt \| fabric --pattern extract_wisdom` | `cat long_article.txt \| fabric --pattern extract_wisdom` |
| 🤖 extract_wisdom_agents | Complex insight extraction | `type philosophical_essay.txt \| fabric --pattern extract_wisdom_agents` | `cat philosophical_essay.txt \| fabric --pattern extract_wisdom_agents` |
| 📚 extract_wisdom_dm | Synthesizes valuable content | `type motivational_speech.txt \| fabric --pattern extract_wisdom_dm` | `cat motivational_speech.txt \| fabric --pattern extract_wisdom_dm` |
| 💡 extract_wisdom_nometa | Organizes insightful content | `type philosophical_text.txt \| fabric --pattern extract_wisdom_nometa` | `cat philosophical_text.txt \| fabric --pattern extract_wisdom_nometa` |

## 🔧 Improvement Patterns

| Pattern | Description | Windows Command | Mac/Linux Command |
|---------|-------------|-----------------|-------------------|
| 📚 improve_academic_writing | Enhances scholarly texts | `type academic_paper_draft.txt \| fabric --pattern improve_academic_writing` | `cat academic_paper_draft.txt \| fabric --pattern improve_academic_writing` |
| 🤖 improve_prompt | Refines AI prompts | `echo "Write a detective story" \| fabric --pattern improve_prompt` | `echo "Write a detective story" \| fabric --pattern improve_prompt` |
| 📊 improve_report_finding | Enhances security reports | `type security_finding.txt \| fabric --pattern improve_report_finding` | `cat security_finding.txt \| fabric --pattern improve_report_finding` |
| ✍️ improve_writing | General writing enhancement | `type draft_article.txt \| fabric --pattern improve_writing` | `cat draft_article.txt \| fabric --pattern improve_writing` |

## 🏆 Evaluation Patterns

| Pattern | Description | Windows Command | Mac/Linux Command |
|---------|-------------|-----------------|-------------------|
| 🕵️ find_hidden_message | Uncovers subtle intentions | `type political_speech.txt \| fabric --pattern find_hidden_message` | `cat political_speech.txt \| fabric --pattern find_hidden_message` |
| 🧠 find_logical_fallacies | Identifies reasoning flaws | `type debate_transcript.txt \| fabric --pattern find_logical_fallacies` | `cat debate_transcript.txt \| fabric --pattern find_logical_fallacies` |
| 🌟 get_wow_per_minute | Evaluates content impact | `type presentation_transcript.txt \| fabric --pattern get_wow_per_minute` | `cat presentation_transcript.txt \| fabric --pattern get_wow_per_minute` |
| 🏷️ label_and_rate | Categorizes and scores content | `type article.txt \| fabric --pattern label_and_rate` | `cat article.txt \| fabric --pattern label_and_rate` |
| 🤖 rate_ai_response | Evaluates AI-generated content | `type ai_response.txt \| fabric --pattern rate_ai_response` | `cat ai_response.txt \| fabric --pattern rate_ai_response` |
| 📊 rate_ai_result | Assesses AI output quality | `type ai_generated_content.txt \| fabric --pattern rate_ai_result` | `cat ai_generated_content.txt \| fabric --pattern rate_ai_result` |
| 📝 rate_content | Evaluates content quality | `type article.txt \| fabric --pattern rate_content` | `cat article.txt \| fabric --pattern rate_content` |
| 💎 rate_value | Assesses collaborative work value | `echo "Rate the value of this collaborative project" \| fabric --pattern rate_value` | `echo "Rate the value of this collaborative project" \| fabric --pattern rate_value` |

## 🧩 Miscellaneous Patterns

| Pattern | Description | Windows Command | Mac/Linux Command |
|---------|-------------|-----------------|-------------------|
| 🏃‍♂️ agility_story | Generates Agile user stories | `echo "Create a user login feature" \| fabric --pattern agility_story` | `echo "Create a user login feature" \| fabric --pattern agility_story` |
| 🤖 ai | Summarizes with insightful bullet points | `echo "Explain artificial intelligence" \| fabric --pattern ai` | `echo "Explain artificial intelligence" \| fabric --pattern ai` |
| 💼 answer_interview_question | Generates interview responses | `echo "Explain polymorphism in OOP" \| fabric --pattern answer_interview_question` | `echo "Explain polymorphism in OOP" \| fabric --pattern answer_interview_question` |
| 🔒 ask_secure_by_design_questions | Security-focused project questions | `type project_description.txt \| fabric --pattern ask_secure_by_design_questions` | `cat project_description.txt \| fabric --pattern ask_secure_by_design_questions` |
| 🧠 capture_thinkers_work | Summarizes philosophical ideas | `echo "Summarize Immanuel Kant's work" \| fabric --pattern capture_thinkers_work` | `echo "Summarize Immanuel Kant's work" \| fabric --pattern capture_thinkers_work` |
| ✅ check_agreement | Analyzes contracts for issues | `type contract.txt \| fabric --pattern check_agreement` | `cat contract.txt \| fabric --pattern check_agreement` |
| 🧹 clean_text | Improves text formatting | `type messy_text.txt \| fabric --pattern clean_text` | `cat messy_text.txt \| fabric --pattern clean_text` |
| 💻 coding_master | Explains coding concepts | `echo "Explain object-oriented programming" \| fabric --pattern coding_master` | `echo "Explain object-oriented programming" \| fabric --pattern coding_master` |
| 🔄 compare_and_contrast | Compares items or concepts | `echo "Compare Python, Java, and C++" \| fabric --pattern compare_and_contrast` | `echo "Compare Python, Java, and C++" \| fabric --pattern compare_and_contrast` |
| 🔍 explain_code | Analyzes and explains code | `type complex_code.py \| fabric --pattern explain_code` | `cat complex_code.py \| fabric --pattern explain_code` |
| 📚 explain_docs | Improves tool documentation | `type tool_usage.txt \| fabric --pattern explain_docs` | `cat tool_usage.txt \| fabric --pattern explain_docs` |
| 🧩 explain_project | Summarizes project documentation | `type project_docs.md \| fabric --pattern explain_project` | `cat project_docs.md \| fabric --pattern explain_project` |
| 📖 explain_terms | Creates glossaries for complex terms | `type technical_article.txt \| fabric --pattern explain_terms` | `cat technical_article.txt \| fabric --pattern explain_terms` |
| 📺 get_youtube_rss | Generates YouTube RSS URLs | `echo "https://www.youtube.com/channel/UC-lHJZR3Gqxm24_Vd_AJ5Yw" \| fabric --pattern get_youtube_rss` | `echo "https://www.youtube.com/channel/UC-lHJZR3Gqxm24_Vd_AJ5Yw" \| fabric --pattern get_youtube_rss` |
| 📜 official_pattern_template | Template for psychological assessments | `type personal_history.txt \| fabric --pattern official_pattern_template` | `cat personal_history.txt \| fabric --pattern official_pattern_template` |
| 🧠 philocapsulate | Summarizes philosophical teachings | `echo "Summarize Plato's philosophy" \| fabric --pattern philocapsulate` | `echo "Summarize Plato's philosophy" \| fabric --pattern philocapsulate` |
| 🧘 provide_guidance | Offers psychological advice | `echo "How to overcome public speaking fear?" \| fabric --pattern provide_guidance` | `echo "How to overcome public speaking fear?" \| fabric --pattern provide_guidance` |
| 🔍 raw_query | Produces optimal responses to queries | `echo "Impact of AI on modern society" \| fabric --pattern raw_query` | `echo "Impact of AI on modern society" \| fabric --pattern raw_query` |
| 🎵 recommend_artists | Creates personalized music schedules | `echo "I like techno and house music" \| fabric --pattern recommend_artists` | `echo "I like techno and house music" \| fabric --pattern recommend_artists` |
| 🗺️ show_fabric_options_markmap | Visualizes Fabric functionalities | `fabric --pattern show_fabric_options_markmap` | `fabric --pattern show_fabric_options_markmap` |
| 💡 suggest | Recommends Fabric commands | `echo "I want to summarize a long article" \| fabric --pattern suggest` | `echo "I want to summarize a long article" \| fabric --pattern suggest` |
| 🃏 to_flashcards | Creates Anki flashcards | `type study_material.txt \| fabric --pattern to_flashcards` | `cat study_material.txt \| fabric --pattern to_flashcards` |
| 🐦 tweet | Guides tweet creation | `echo "Create a tweet about a new tech product launch" \| fabric --pattern tweet` | `echo "Create a tweet about a new tech product launch" \| fabric --pattern tweet` |
| 📝 write_essay | Generates essays in Paul Graham's style | `echo "Write an essay on the future of work" \| fabric --pattern write_essay` | `echo "Write an essay on the future of work" \| fabric --pattern write_essay` |
| 🔬 write_micro_essay | Creates concise, impactful essays | `echo "Write about the importance of critical thinking" \| fabric --pattern write_micro_essay` | `echo "Write about the importance of critical thinking" \| fabric --pattern write_micro_essay` |
| 🛡️ write_nuclei_template_rule | Creates Nuclei security templates | `echo "Create a template for SQL injection detection" \| fabric --pattern write_nuclei_template_rule` | `echo "Create a template for SQL injection detection" \| fabric --pattern write_nuclei_template_rule` |
| 🔀 write_pull-request | Drafts pull request descriptions | `git diff main..feature-branch \| fabric --pattern write_pull-request` | `git diff main..feature-branch \| fabric --pattern write_pull-request` |
| 🔍 write_semgrep_rule | Creates Semgrep security rules | `echo "Detect hardcoded API keys in Python" \| fabric --pattern write_semgrep_rule` | `echo "Detect hardcoded API keys in Python" \| fabric --pattern write_semgrep_rule` |
