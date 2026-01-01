

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