# Portfolio Construction — Random Matrix Theory & Bayesian Shrinkage

Asset-selection model for a CHF 574k private portfolio, built under real-world constraints:
tax-frozen legacy holdings, long-only, all risk measured in Swiss francs.

**Approach 1 — RMT-denoised covariance.** Marchenko–Pastur eigenvalue analysis with an iteratively
fitted noise bulk, clone consolidation for near-duplicate funds and a constrained minimum-variance solution.

**Approach 2 — Bayesian mean shrinkage with turnover control.** Per-asset conjugate posteriors under
a common prior, EWMA covariance, posterior-predictive scenarios with antithetic sampling, and a
CVaR program with an L1 turnover penalty and a return floor. 


