# Password
Password Strength Evaluation - README

This project contains a set of sample passwords evaluated for strength using an entropy-based approximation and common heuristics. Files:
⦁	password_strength_results.csv : CSV table with computed entropy estimates and estimated average crack times under different attacker capabilities.
⦁	report.md : Detailed report summarizing methods, findings, best practices, and tips.
Notes:
⦁	Entropy is estimated with E = L * log2(R) where L is length and R is estimated character pool size.
⦁	Entropy is adjusted down if common dictionary words are present (heuristic).
⦁	These are estimates and not absolute guarantees. Don't submit your real passwords to unknown websites.
