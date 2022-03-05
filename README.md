# Lending-Club-Case-Study
## EDA- Loan Default
Lending-Club-Case-Study case study aims to understand the driving factors (or driver variables) behind loan default, that is, the variables which are strong indicators of default.

### Business Objective
	1.Consumer attributes and loan attributes influence the tendency of default.
	2.Company wants to use driving factors (or driver variables) behind loan default for performing portfolio and risk assessment.
	3.With this application one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.
	
### Data Understanding
Data in raw share has 39717 rows and 111 columns.

Just by browsing the data we understand that there are many columns that are completely null and there many columns that are irrelevant so will be removed after analysing.

**** Some of the key columns that are relevant for this analysis are: ****
1. Loan_amnt
2. Term
3. Int_rate
4. Grade
5. Emp_length
6. Annual_inc
7. Loan status
8. Addr_state
8. Loan Month
9. Loan State

### Conclusions:

	1.Loan has more number of defaults as term of loan increases, so prefer to give short term loans.
	2.% of default increases by 25%(Grade A vs Grade G) as the grade of the person decreases.
	3 % default in NE state is 40% more than other states, Hence, we should be more vigilant in giving home_improvement loans in NE state where income < 50000.
	4.Default ratio is 8% high if person has derogatory public record.
	5.Borrower with bankruptcies record have 8% high percentage of charged off.
	6.Most of the loan is granted in Q4 (Dec,Nov, and Oct) and default ratio is also high for these months. So don't put sales pressure to disburse loans 

**** For more insights, refer to presentation.****





