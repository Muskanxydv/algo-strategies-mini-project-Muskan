# Media Analytics & Content Optimization Strategies
**Course:** Analysis and Design of Algorithms (ADA)
**Project:** Lab Experiment - 1
**Developer:** Muskan

## 📌 Problem Context
In the era of massive media libraries and streaming platforms, managing content metadata and optimizing user watch-lists is a high-stakes challenge. This project implements core algorithmic paradigms to solve problems within a media ecosystem, such as sorting massive anime/manhwa databases, optimizing binge-watch schedules, and managing local storage for offline downloads.

## 🧠 Algorithmic Strategies
This project explores three core paradigms applied to digital media and fandom data:

1. **Divide and Conquer:** Applied through QuickSort and MergeSort to handle large-scale metadata sorting of series by popularity, ratings, or chapter release dates.
2. **Greedy Algorithms:** Utilized for Activity Selection to help users maximize the number of episodes they can watch in a limited timeframe without overlaps.
3. **Dynamic Programming:** Essential for the 0/1 Knapsack problem (optimizing high-quality downloads within a phone's storage limit) and finding the shortest binge-path through interconnected spin-offs.

## 🛠️ Setup & Usage
### Prerequisites
* Python: ≥ 3.10 with venv
* Libraries: matplotlib, numpy, memory_profiler, jupyter, time

### Installation
1. Create a private repository: `algo-strategies-mini-project-Muskan`
2. Initialize the environment:
   python -m venv .venv
   source .venv/bin/activate  (On Windows: .venv\Scripts\activate)
3. Install dependencies:
   pip install matplotlib numpy memory_profiler jupyterlab

### Usage
Launch the Jupyter Notebook to explore the algorithmic simulations:
jupyter lab notebooks/media_strategy_notebook.ipynb

## 📊 Summary Comparison Table
| Task | Algorithm | Strategy | Complexity | Fandom Application |
| :--- | :--- | :--- | :--- | :--- |
| Database Sort | QuickSort | D&C | O(n log n) | Ranking Manhwa/Anime |
| Watch Schedule | Activity Selection | Greedy | O(n log n) | Binge-watching efficiency |
| Content Offline | 0/1 Knapsack | DP | O(n * W) | Storage Optimization |
| Series Path | Min Path Cost | DP | O(m * n) | Episode Progression |

---
**Final Submission Tag:** v1.0-submission
