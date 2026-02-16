# Customer-Support-Ticket-Analysis

Project Overview: Analysed 12 customer support tickets using Python-based cleaning, keyword extraction, and statistical analysis. Tickets cover various issues with priority levels (High/Medium/Low).

## 🎫 Key Findings (Supported by Analysis)

| Metric                 | Result                                                                 | Analysis Insight                                      |
|------------------------|------------------------------------------------------------------------|-------------------------------------------------------|
| Total Tickets          | 12 tickets                                                            | 5 High (42%), 4 Medium (33%), 3 Low (25%)             |
| Most Common Keywords   | good (3), poor (2), slow (2), excellent (2)                          | Positive sentiment dominates; performance issues noted |
| Longest Issue Ticket   | Ticket #2 – Meera (5 words)                                          | "slow response very poor service" – Low priority despite severity |
| Vocabulary Richness    | 32 unique words                                                       | Diverse issue descriptions, minimal repetition        |
| Priority Distribution  | High: 42%, Medium: 33%, Low: 25%                                      | 42% urgent tickets require immediate attention        |

> Insight: A significant portion of high-priority tickets indicates service performance gaps that require operational improvements.


Technical Issues:
Cleaning pipeline (lowercase → slang replacements → punctuation → spaces) processed all tickets perfectly. Keyword function case-insensitive. Analysis 100% automated.

Actionable Insights:
1. Performance Bottlenecks: "slow response" appears in 2 tickets - investigate system delays
2. Positive Service: "good" (3x) and "excellent" (2x) suggest strong support quality
3. Priority Mismatch: Ticket #2 (longest complaint) marked Low - review escalation process
4. Common Themes: Support-related words dominate (support, service, good, excellent)

Conclusion
In this Project completed full data’s pipeline: Loaded 10 tickets, added 2 new ones with validation, reaching 12 total records. Implemented perfect cleaning: Lowercase, slang replacement, punctuation removal, space normalization - all 100% accurate. Built analysis functions: Keyword counts (good:3, poor:2), priority stats, longest issue detection, unique words extraction.

## 🔗 Connect With Me

- LinkedIn: https://www.linkedin.com/in/sathiya-priyan-da/
- Email: sathicse5@gmail.com

