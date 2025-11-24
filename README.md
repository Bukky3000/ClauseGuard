# ClauseGuard
ClauseGuard is an AI-powered contract risk analyzer designed to help businesses, legal teams, freelancers, and procurement officers quickly identify risky or unusual clauses in contracts. 
Product Summary
 ClauseGuard is an AI-powered system that automatically reviews contracts, identifies risky or unusual clauses, and summarizes findings for legal teams or business users. The system uses NLP to scan uploaded documents and outputs a structured risk report.

2. Problem Statement
Legal teams and businesses spend significant time manually reviewing contracts to detect risks. This process is slow, expensive, repetitive, and prone to human error.

3. Pain Points
- Time-intensive review
- Human error
- Lack of legal expertise
- High cost
- Inconsistency
- Document volume overload

4. Solution Summary
Build an AI system that:
1. Accepts file uploads
2. Extracts text
3. Scans for risky clauses
4. Classifies risks
5. Generates risk reports

5. Product Goals & Metrics
Goals:
- Faster review
- Help non-lawyers
- Reduce review time 60%
- Simple interface

Metrics:
- 80%+ accuracy
- <30 seconds per doc
- 90% user satisfaction

6. Target Users
Primary: SMB owners, freelancers, legal teams
Secondary: Students, nonprofits, government officers

7. User Stories
- As a business owner…
- As a legal intern…
- As a procurement officer…
- As a freelancer…

8. Features & Requirements
Core features:
- File upload
- Text extraction/OCR
- Clause classification
- Risk detection
- Report generation
- Summary section

9. Non-Functional Requirements
- Performance
- Usability
- Reliability
- Security

10. Technical Approach (No-Code)
User → Upload → OCR → AI Analysis → Risk Report

11. Tools & Platforms (Free)
- ChatGPT GPTs or Flowise
- Google Docs OCR
- PDF.co
- Notion/Google Forms/Glitch


Nodes used in flowise 

1. Document loader


-- PDF file 
 Purpose: Upload contracts or receive file from n8n

Settings: “Extract full text”


Node 2: Text Splitter

Purpose: Break contract into manageable chunks



Chunk overlap: 200


Node 3: Embeddings

Use: OpenAI or Free instructor embeddings

Purpose: Convert text into searchable vectors


Node 4: Vector Store

Use: In-memory or ChromaDB

Purpose: Store contract clause chunks for analysis

13. Future Enhancements
- Clause comparison
- Redline suggestions
- Dashboard
- Nigeria-specific model
- Clause library
- Browser extension

14. Success Snapshot
- Working AI tool
- Upload + analyze
- Risk highlight
- Report output
- Demo-ready


