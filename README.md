# Optimizing Branch Performance Analyzing Loan Disbursements and Efficiency at DQLab Finance
________________________________________________________
## Background
1. DQLab Finance has established branches in various locations since its founding in January 2020. Despite being less than a year old, DQLab Finance has consistently provided financial assistance to the community and has been expanding each month by opening new branches.
2. With numerous branches already in operation, it becomes essential to monitor the performance of each branch. 
3. Within each branch, there are agents responsible for identifying and documenting prospective partners who intend to apply for loans with DQLab Finance. Once approved, these agents are also responsible for disbursing funds to the approved partners.

## Tables in Data
1. loan_id: The table contains unique IDs
2. tanggal_cair: Disbursement dates
3. cabang: Agent work locations
4. agen: The field officer responsible for disbursement
5. amount: The disbursed amount

## Summary & Recommendation
1. When evaluating branch performance, we should not only focus on the total_amount but also consider how long the branch has been established, allowing for a more comprehensive analysis. 
2. From the previous exploration, it can be observed that the performance of each branch is influenced by the number of working days and loan disbursement. Therefore, to enhance performance, we can improve the agents' efficiency to increase monthly loan disbursements.
