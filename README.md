# glovo-support-analytics
Agent performance and CSAT analysis for a support team. Synthetic dataset based on real operations structure
# Glovo Support Team — Performance Analysis

Analysis of support agent performance over 30 days based on 
real call center operations structure.

# Business Questions
Who are the top performers by CSAT and ticket volume?
How many agents are below the 80% CSAT target?
Is there a correlation between ticket volume and quality?
What does daily team productivity look like?

# Key Findings
26,999 tickets processed over 30 days by 15 agents
Team average CSAT: 75.1% — below the 80% target
10 out of 15 agents did not meet the CSAT target
Top performer: Rasul B. — 94.3% CSAT, 2,322 tickets
High volume ≠ high quality (confirmed by scatter analysis)

# Recommendation
Pair low-CSAT agents with top performers (Rasul B., Ainur T.)
for mentoring. Priority: quality over speed.

# Tools
Python (pandas, numpy, matplotlib, seaborn)
SQL (SQLite)
Google Colab

# Files
- `glovo_analysis.ipynb` — full analysis notebook
- `glovo_performance.png` — performance dashboard
