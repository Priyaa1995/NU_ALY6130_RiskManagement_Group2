Course: ALY6130 - Risk Management Analytics
Institution: Northeastern University, Vancouver
Instructor: Professor Abeba Nigussie Turi
Group 2:Md Maniur Rahman, Rahul Reddy Basani
Term B: Winter 2026
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
About this Project:
This project applies risk management frameworks to a live, in-progress Merger and Acquisition transaction [EQB Inc.'s acquisition of PC Financial from Loblaw Companies Limited.]

The Deal:
On December 3, 2025, EQB Inc. parent of EQ Bank and Canada's seventh-largest bank, announced a definitive agreement to acquire PC Financial from Loblaw for approximately $800 million in cash and shares.
The deal expands EQB's customer base from 761,000 to nearly 3.5 million, adds $5.8 billion in assets, and includes a 12-year exclusive partnership with the PC Optimum loyalty program  which has over 17.5 million active members. 
Closing is expected by end of 2026, pending approval from Canada's Minister of Finance and clearance under the Competition Act.

SWOT Summary:
Strengths: Both banks run on the same core platform (Temenos), reducing integration risk. EQB holds a strong CET1 ratio of 13.3% and gains exclusive access to the PC Optimum loyalty ecosystem.
Weaknesses: EQB has no prior experience managing a credit card portfolio. A recent restructuring in Q4 2025 including layoffs and $92M in charges added financial pressure during integration. 
            Scaling to 3.5 million customers strains existing security infrastructure.
Opportunities: ~90% of PC Financial's credit card holders do not hold a deposit account, creating a significant cross-sell pipeline.  
               EQB also gains an omnichannel presence through 2,500+ Loblaw store locations for the first time.
Threats: EQB now competes directly against Canada's Big Six banks and fintechs in an unfamiliar market segment. System integration creates elevated cybersecurity exposure, and heavy reliance on Loblaw 
         as a strategic partner introduces concentration risk.

Risk Register:
We came up with 2 negatives and 1 positive risks
Negative 1: Cybersecurity breach -during system integration /data migration vulnerabilities
Negative 2: Delay in approval -disrupts integration timelines and increases holding costs
Positive 1: Cross sell opportunities-expanding customer base - for GIC/ mortgage /deposit account

Full Risk Assessment:
Building on the Assignment 2 Risk Register foundation, this phase expanded the risks to 40 (37 negative, 3 positive) covering the full scope of the EQB/PC Financial integrationv- from cybersecurity and regulatory exposure to operational, financial, and strategic risks. Each risk was scored using the specific scale and categorized as High, Medium, or Low priority. A Random Forest classifier was also applied to validate the priority classifications programmatically across all 40 risks.
ParameterValues
Likelihood 1, 3, 5, 7, 9
Impact 1, 2, 4, 6, 8, 9
Risk Score = L × I
Thresholds --> High ≥ 45 | Medium 21 – 44 | Low ≤ 20

Quantitative Risk Analysis:
This phase applied quantitative methods to five priority risks selected from the Assignment risk register /risk log. Two techniques were used: Indicators & Warnings (I&W) Analysis and Monte Carlo Simulation.

The I&W analysis identified measurable leading indicators (early warning signals) for each risk, assigned probability values on a 0–1 scale, and calculated Expected Monetary Value (EMV = Probability × Cost Impact).
All financial estimates were anchored to EQB's disclosed figures - $800M deal price, $105M integration budget, and $30M annual synergy target.

The Monte Carlo simulation ran 10,000 iterations per risk using PERT-based 3-point estimates (Optimistic / Most Likely / Pessimistic)



Frameworks & Regulators Referenced:
COSO ERM 2017
ISO 31000:2018
OSFI B-10 (Third-Party Risk), OSFI B-13 (Technology & Cyber Risk)
PIPEDA / Bill C-27
FCAC, OPC

-------------Final Deliverables----------------
ALY6130_Group2_SignatureAssessmentReport_Final
ALY6130_Group2_EQB_PC FInancials_RT&RP.xlsx
ALY6130_RiskRegisterAnalysis_Assignment3_Group2.ipynb 
ALY6130_Group2_MonteCarlo_Final.ipynb 
ALY6130_Group2_RiskAnalytics_Statistical.ipynb
