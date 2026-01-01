# AI Learning Plan: From Novice to "Decent" (6-9 Months, Flexible 1+ Hour/Day)

As a COBOL/Python programmer with DB exposure, this plan builds on your strengths for **AI-accelerated coding**—focusing on tools like GitHub Copilot in VS Code to speed up data analysis and generate business proposals (e.g., auto-drafting insights from CSVs). "Decent" = Building/deploying simple models, prompting AI for 2x faster code, and creating end-to-end workflows (data → model → Markdown summary).

## Key Principles
- **Daily Structure**: 20-30 min theory (videos/readings), 30-40+ min hands-on (Copilot-assisted coding in VS Code/Jupyter).
- **Tools**: VS Code + GitHub Copilot (or Codeium free alt), Anaconda for env, Kaggle for datasets, GitHub for versioning.
- **Flex Time**: Core ~1 hour; stretch to 2-3 on high-energy days. Accelerate if you finish early.
- **Tracking**: Weekly check-ins here—what clicked? Snags? I'll adapt.
- **Resources**: Free (Coursera audits, fast.ai, Handbook online). Business datasets (e.g., Superstore Sales for proposal mocks).
- **Endgame**: Prompt Copilot: "Analyze sales CSV, build regression, output proposal Markdown."

## Phases Overview

| Phase | Weeks | Focus | Goals | Hours (Core) |
|-------|-------|-------|-------|--------------|
| **1: Python for Data/AI** | 1-4 | NumPy/Pandas + Viz | Data wrangling like enhanced DB ops; Copilot for snippets. | ~28 |
| **2: ML Foundations** | 5-12 | Supervised ML (scikit-learn) | Train/tune models; auto-gen code for classification. | ~56 |
| **3: Deep Learning Basics** | 13-20 | Neural nets (PyTorch) | Image/text models; transfer learning for quick prototypes. | ~56 |
| **4: Practice & Integration** | 21-24 | Projects/Deployment | End-to-end proposals; Streamlit apps with AI insights. | ~28 |
| **5: Polish (Optional)** | 25-36 | Advanced/Specialize | NLP/time-series; COBOL code analyzer project. | ~84 |

## Detailed Week 1: NumPy + Copilot Kickoff (Jan 1-7, Core ~7 Hours; Stretch ~14)
**Goal**: NumPy fluency for array ops (vectorized DB-like math). Business tie: Crunch Superstore Sales CSV → Proposal stats (e.g., "Regional avg: $X").

**Dataset Setup**: Download [Superstore Sales CSV](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting) (~10k rows: sales/profits). Open in VS Code (Jupyter ext for notebooks).

**Copilot Tips**: Comment prompts (e.g., `# Filter sales > 1000`) → Tab to accept → Run/tweak.

### Daily Breakdown
- **Day 1 (Jan 1): Setup & Array Basics**  
  - **Core (1 hr)**: Skim [Handbook Ch. 2.1](https://jakevdp.github.io/PythonDataScienceHandbook/02.00-introduction-to-numpy.html) (20 min). In `day1_numpy.py`: Import `numpy as np`; prompt Copilot for sample sales array → Compute mean. Load CSV 'Sales' column → Avg output.  
  - **Quick Win**: "Avg sales: $261.96".  
  - **Stretch**: `# Add 10% tax function` → Apply/save CSV.

- **Day 2 (Jan 2): Shapes & Reshaping**  
  - **Core**: Handbook Ch. 2.2 (20 min). `# Reshape 1D to 2D (e.g., 5x20)` on Superstore snippet → Check `.shape`.  
  - **Stretch**: `# Stack sales/profit arrays` (like DB append).

- **Day 3 (Jan 3): Indexing & Slicing**  
  - **Core**: Ch. 2.3 (20 min). `# Slice rows 10:20`; `# Filter sales > 500` → Top 50 sales extract.  
  - **Stretch**: Boolean for "profitable" (profit > 0).

- **Day 4 (Jan 4): Advanced Indexing**  
  - **Core**: Fancy indexing (20 min). `# Multi-condition: sales > 200 & region == 'West'`.  
  - **Stretch**: `# Matplotlib plot of sliced sales`.

- **Day 5 (Jan 5): Broadcasting**  
  - **Core**: Ch. 2.5 (20 min). `# Add 0.1 discount scalar` → No loops!  
  - **Stretch**: `# Profit margins (profit / sales)`.

- **Day 6 (Jan 6): UFuncs & Aggregates**  
  - **Core**: Ch. 2.6-2.7 (20 min). `# np.sum by column` (regional totals).  
  - **Stretch**: `# Sales-quantity correlation`.

- **Day 7 (Jan 7): Review & Mini-Project**  
  - **Core**: Revisit (30 min); Project (30 min): `week1_summary.py` – Copilot: `# Load CSV → NumPy stats by category → Markdown table`. Commit to GitHub.  
  - **Reflection**: Best Copilot save?  
  - **Stretch**: Share code here for review.

## Challenges & Fixes
- **Burnout**: Fun dataset swap (e.g., Pokémon).  
- **Plateaus**: Kaggle beginner notebooks.  
- **Milestones**: Week 4: Clean/explore dataset in <30 min. Month 3: 80% model accuracy.