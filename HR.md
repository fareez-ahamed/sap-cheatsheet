**PA Tcodes** PA20, PA30, PA40
**OM Tcodes** PP01, PPOME
**Payroll** PC_PAYRESULT

#Beneifits Infotypes
167-Health Plans
168-Insurance Plans
169-Savings Plans
170-Flexible Spending Accounts
(Annual Payment)

#Reading Payroll Data
Call CU_READ_RGDIR
Pass PERNR and SEQNR, Cluster ID to PYXX_READ_PAYROLL_RESULT
Cluster ID for US - RU

#Common FM's
HR_READ_INFOTYPE, HR_INFOTYPE_OPERATION
RH_READ_INFTY, RH_GET_LEADER, RH_CUT_INFTY

#Infotypes
0000 - Actions
0001 - Org Assignment
0002 - Personal Data
0003 - Payroll Status
0006 - Address
0008 - Basic Pay
0009 - Bank Account
0014 - Recurring Payment/Deduction
0015 - Additional Payment
0021 - Dependents
0105 - Communications
0267 - Off Cycle Payment
1001 - Relationships
