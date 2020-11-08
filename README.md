# pollu-check



Tables. 

Customer info : 
1. Name 
2. Number 
3. Car Registration No
4. Plan 
5. Timestamp 
6. Date Added (Derived from timestamp) 
7. Retail Number (Derived from retail user id)
8. Amount Bill

Retail_Agent : 
1. Name 
2. Number 
3. Retail Location Number

Retail Location Index
1. State 
2. City 
3. Number 




Use Cases. 

a) Enter Customer Info. :: MAJOR (Done when billing. Added by Retail_agent.) 
b) Create Retail_Agent (Only SuperAdmin. Hardcode in the Application.)
c) Add Retail Location Index row. 






Class Daigram. 
Classes -> Customer , RetailAgent

Global Variables : 
  list<Customers>
Global Functions : 
  GetUpComingCustomers(int days)
  InsertCustomerIntoDB()
  DecompileCustomers()
  PopulateCustomers()
  
  
Class Customer : 
  Methods : Constructor , Decompile

Class RetailAgent (singleton class - to be hardcoded for each customer) : 



