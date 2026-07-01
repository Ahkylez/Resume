<link rel="stylesheet" href="styles.css">

# Isaic Cruse  
<p style="text-align: center;">
    <span id="location"></span> | P: <span id="phone"></span> | 
    <a href="mailto:isaiccruse28@gmail.com">isaiccruse28@gmail.com</a> | 
    <a href="https://github.com/Ahkylez">https://github.com/Ahkylez</a> | 
    <a href="http://www.linkedin.com/in/isaic-cruse">http://www.linkedin.com/in/isaic-cruse</a>
</p>


<script src="config.js"></script>
<script>
    if (typeof config !== 'undefined') {
        document.getElementById('location').innerText = config.LOCATION || "Remote / California";
        document.getElementById('phone').innerText = config.PHONE || "[Hidden]";
    } else {
        document.getElementById('location').innerText = "California";
        document.getElementById('phone').innerText = "[upon request]";
    }
</script>
---

* Applied Mathematics undergraduate (3.6 GPA) specializing in operations research, mathematical modeling, and optimization.
* First-author of a conference-submitted paper where I designed a portfolio optimizer that generated a 12.75% return, outperforming the baseline.
* Built automated Python data-scraping pipelines and match-engine at Ellerra while advising startup founders.
* Selected as a CAMP Scholar to build a numerical solvers for partial differential equations.

## **EDUCATION**

---

<p class="item-header"><strong>University of California, Merced | B.S. in Applied Mathematics (CS Emphasis) | GPA: 3.6</strong> <span>Expected May 2027</span></p>

**Honors & Awards:** CAMP Scholar, UC LEADS Graduate Preparation Funding, Wishek Family Endowed Scholarship (2026–2027), Dean's Honor List (2)

**Relevant Coursework:** Mathematical Modeling, Probability & Statistics, Linear Algebra & Differential Equations, Numerical Analysis, Data Structures, Advanced Programming, Algorithm Design & Analysis, Complex Variables, Linear Analysis 

## **RESEARCH EXPERIENCE**

---

<p class="item-header"><strong>Undergraduate Research – Stochastic Programming & Generative Modeling</strong> <span>Merced, CA</span></p>
<p class="item-header">Mentor: Prof. Roummel F. Marcia<span>Oct 2025 – Present</span></p>

* **Conference Paper - Submitted:** Authored "Hybrid Time-Causal Variational Autoencoders with Vine Copula for Scenario Generation in Portfolio Optimization." Tested the generative model over a 52-week out-of-sample backtest, achieving a 12.75% total return vs. 10.20% for the baseline.
* **C++ / Python Optimizer:** Engineered a two-stage stochastic portfolio optimizer using C++ (via Google OR-Tools) as the high-performance math engine and Python for automated data processing, scenario generation, and risk analysis.
* **Scenario Generation Modeling:** Implemented generative machine learning models to simulate realistic financial market scenarios, effectively fixing correlation issues and lowering portfolio risk metrics (95% CVaR) to 5.47% (vs. 6.07% baseline).
* **Risk-Adjusted Performance:** Achieved a 0.739 Sharpe and 1.250 Sortino ratio (outperforming the 0.593 / 0.839 baselines) while decreasing annualized volatility to 18.79%.
* **Backtesting Infrastructure:** Built a dynamic, 52-week rolling-window testing framework incorporating weekly rebalancing and variable transaction costs to simulate realistic asset management on an initial $100,000 fund.
* **Scientific Communication:** Selected to present complex technical research methodologies and financial engineering models at the Undergraduate Research Opportunity Center (UROC).

<p class="item-header"><strong>CAMP Scholar | UROC Research Scholar</strong> <span>Merced, CA</span></p>
<p class="item-header">Mentor: Prof. Juan Meza<span>June 2026 – Present</span></p>

* **Comparative Solver Development:** Programming two distinct numerical frameworks in MATLAB, an Augmented Lagrangian solver and a Least Squares solver to evaluate their performance on non-linear partial differential equations.
* **Benchmarking & Analysis:** Constructing a testing framework using classic mathematical benchmark problems to compare both solvers across iterations and numerical accuracy.
* **Academic & Research Training:** Completing formal research training focused on rigorous scientific literature review, implementation, and technical writing.
* **Scientific Presentation:** Synthesized the underlying methodologies and architectural designs into a research poster to present findings at the upcoming undergraduate research symposium.
## **WORK EXPERIENCE**

---

<p class="item-header"><strong>ELLERRA</strong> <span>Palo Alto, CA (Remote)</span></p>
<p class="item-header">Financial Analyst<span>June 2026 – Present</span></p>

* **Automated Sourcing Pipelines:** Built Python web-scraping scripts to programmatically extract, clean, and structure high-fidelity data on venture capital and angel investors, establishing a centralized investor database.
* **Feature Encoding & Matching:** Engineered a feature-encoding pipeline for the core matching engine, transforming qualitative startup attributes and investor mandates into clean data representations to improve match accuracy.
* **Algorithmic Asset Matching:** Developed a multi-variable matching framework using scoring criteria to align startup profiles (industry, stage, capital needs) with historical investor portfolio data and active investment criteria.
* **Founder Discovery Calls:** Conducted technical discovery and consultation calls with early-stage startup founders to analyze their capital structures, translating qualitative client needs into clear engine parameters and product features.

<p class="item-header"><strong>UNIVERSITY OF CALIFORNIA, MERCED</strong> <span>Merced, CA</span></p>
<p class="item-header">Learning Assistant - Calculus<span>Aug 2024 – Present</span></p>

* **Technical Mentorship:** Mentored and coached over 1,000 students by translating abstract mathematical theories into practical, step-by-step problem-solving techniques.
* **Collaborative Instruction:** Facilitated high-engagement review sessions, coordinating closely with faculty to identify and target common student conceptual bottlenecks.
* **Communication & Leadership:** Developed strong technical communication skills by presenting complex calculus concepts clearly and adaptably to individuals with varying technical baselines.

## **PROJECTS**

---

<p class="item-header"><strong>Quantitative Risk & MPT Engine | <i>Python, streamlit, Pandas, Numpy</i></strong><span>2025</span></p>

* Analytics Dashboard: Developed a Streamlit app for Modern Portfolio Theory (MPT) asset allocation.    
* Risk Attribution: Engineered modular libraries for automated multi-asset covariance estimation and downside risk metrics.


## **ADDITIONAL**

---

**Skills:** Python (PyTorch, scikit-learn, pandas, NumPy, Streamlit, Jupyter, Matplotlib, SciPy), LaTeX, git, CVXPY, HIGHS/LP solver, SQL, Google OR-Tools MP Solver, Vim, Postgres, supabase