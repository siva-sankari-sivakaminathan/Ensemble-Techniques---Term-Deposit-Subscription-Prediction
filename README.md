**Goal**

Using the data collected from existing customers, build a model that will help the marketing
team identify potential customers who are relatively more likely to subscribe term deposit
and thus increase their hit ratio. 

**Attribute information**

**Input variables:**

Bank client data:

1. age: Continuous feature
2. job: Type of job (management, technician, entrepreneur, blue-collar, etc.)
3. marital: marital status (married, single, divorced)
4. education: education level (primary, secondary, tertiary)
5. default: has credit in default?
6. housing: has housing loan?
7. loan: has personal loan?
8. balance in account
Related to previous contact:
9. contact: contact communication type
10. month: last contact month of year
11. day: last contact day of the month
12. duration: last contact duration, in seconds*
    
Other attributes:
14. campaign: number of contacts performed during this campaign and for this
client
15. pdays: number of days that passed by after the client was last contacted from a
previous campaign (-1 tells us the person has not been contacted or contact
period is beyond 900 days)
16. previous: number of contacts performed before this campaign and for this
client
17. poutcome: outcome of the previous marketing campaign

**Output variable (desired target):**
18. Target: Tell us has the client subscribed a term deposit. (Yes, No)
