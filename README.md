# Data Analyst for Finance
### Optimizing Branch Performance Analyzing Loan Disbursements and Efficiency at DQLab Finance
________________________________________________________
##### Background
1. DQLab Finance has established branches in various locations since its founding in January 2020. Despite being less than a year old, DQLab Finance has consistently provided financial assistance to the community and has been expanding each month by opening new branches.
2. With numerous branches already in operation, it becomes essential to monitor the performance of each branch. 
3. Within each branch, there are agents responsible for identifying and documenting prospective partners who intend to apply for loans with DQLab Finance. Once approved, these agents are also responsible for disbursing funds to the approved partners.

##### Tables in Data
1. loan_id: The table contains unique IDs
2. tanggal_cair: Disbursement dates
3. cabang: Agent work locations
4. agen: The field officer responsible for disbursement
5. amount: The disbursed amount

##### Summary & Recommendation
1. When evaluating branch performance, we should not only focus on the total_amount but also consider how long the branch has been established, allowing for a more comprehensive analysis. 
2. From the previous exploration, it can be observed that the performance of each branch is influenced by the number of working days and loan disbursement. Therefore, to enhance performance, we can improve the agents' efficiency to increase monthly loan disbursements.

### The Investor Investment Process
##### Background
1. DQLab Finance is a peer-to-peer lending company, relying on investors for potential borrowers. 
2. Each prospective borrower applying for a loan will have their loan uploaded to the marketplace. Registered investors can then choose loans that align with their preferences

##### Tables in Data
1. loan_id: Unique ID of the loan uploaded to the marketplace, unique ID of the registered investor, activities performed by the investor, and changes in the loan status
2. Investor_id: Unique ID of the registered investor
3. Nama_event: activities performed by the investor and loan status changes
4. Created_at: Time the event occurred

##### Summary & Recommendation
1. In general, DQLab Finance shows positive development with fluctuations occurring due to specific dates, influenced by external factors such as salary disbursement. Overall, 5% of the total monthly registered investors will make investments, with the majority occurring within the first 30 days after registration, and only a small portion in the second month. The chances of conversion in the following months are very slim. Therefore, it is crucial to ensure a smooth investor journey in the first month to encourage further conversions in DQLab Finance.
2. Next, it is essential to examine the continuity of investments in the subsequent months. Generally, 30% of investors will reinvest in the following month. In February, the conversion rate was good at 7.57%, with a high number of conversions. However, the retention was only 16% of those who invested, and in the next month, it was only half of the previous months. It's possible that the observed trends are linked to the pandemic, so need a deeper analysis.
