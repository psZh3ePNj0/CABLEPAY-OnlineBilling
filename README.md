<h5><b><i>Note to Reader: Where permissable - the source code will readily be provided. There are cases where IP | Copyright factors apply. In those cases the source code cannot be published without the StakeHolders consent. Thank you for your understanding.</b></i></h5>
<br/>

<h1>CABLEPAY: Online Billing Portal (Collaborative) </h1>
<br/>



<h2>Description</h2>
<b>A FullStack Online Portal Solution allowing Cable Customers to View and Pay their Billing online:</b>
<br/>
<br/>
<br/>

<p align="center">
<b>Hierchy:</b> <br/>
<img src="https://github.com/psZh3ePNj0/OnlineBilling/blob/main/OnlineBilling-CoreFunctions.jpg" height="80%" width="80%" alt="OnlineBilling Flow"/>
<br />
<br />


<h2>Languages, Utilities and Dependencies </h2>

- Lasso Programming Language and Lasso Studio 6.0.4 IDE
- Java Programming Language and Eclipse IDE
- Java Database Connectivity Drivers (JDBC)
- Java Service Wrapper (Installs Java Based applications as a Windows Service)  
- SQL: Oracle (8.0.5.1.0) and MSSQL 2000
- Oracle SQL Developer and MSSQL 2000 SQL Studio
<br/>
<br/>


<h2>Environments Used </h2>

- Windows Server 2000 with IIS 5.0 and Lasso Professional 6.0.4 
- Windows Server 2000 with MSSQL Server 2000 and Sun JRE with Virtual Machine (1.4.2_16)
- Oracle Database Server 8i Enterprise Edition [8.0.5.1.0] AIX 4

<br/>
<br/>



<h2>FrontEnd Component: Billing Feature Set</h2>

<p align="center">
<b>Welcome:</b> <br/>
<img src="https://github.com/psZh3ePNj0/OnlineBilling/blob/main/OnlineBilling-Welcome-Logout.jpg" height="80%" width="80%" alt="OnlineBilling Flow"/>
<br />
<br />
</p>


<p align="center">
<b>My Profile:</b> <br/>
<img src="https://github.com/psZh3ePNj0/OnlineBilling/blob/main/OnlineBilling-Profile.jpg" height="80%" width="80%" alt="OnlineBilling Flow"/>
<br />
<br />


<p align="center">
<b>My Statement:</b>  <br/>
<img src="https://github.com/psZh3ePNj0/OnlineBilling/blob/main/OnlineBilling-Statement.jpg" height="80%" width="80%" alt="OnlineBilling Flow"/>
<br />
<br />


<p align="center">
<b>Payment Centre:</b> <br/>
<img src="https://github.com/psZh3ePNj0/OnlineBilling/blob/main/OnlineBilling-PaymentCentre.jpg" height="80%" width="80%" alt="OnlineBilling Flow"/>
<br />
<br />

<p align="center">
<b>Contact Us:</b>  <br/>
<img src="https://github.com/psZh3ePNj0/OnlineBilling/blob/main/OnlineBilling-ContactUs.jpg" height="80%" width="80%" alt="OnlineBilling Flow"/>
<br />
<br />

</p>
<br />


<h2>MiddleWare Component: Billing Feature Set</h2>

- CablePay Acct Actv Module and CablePay Instruct Module are CablePay’s middle-tier Java-based components. They compose an integral part of the CablePay Billing Portal solution. 

- CablePay Acct Actv Module ensure that the frontend web component of CablePay application can easily and efficiently retrieve critical data from the backend database in order that it provides customers with My Profile and My Statement viewing services. 

-  CablePay Instruct Module efficiently obtains the payment instructions and credit card info submitted by the CablePay customer through the frontend Web application. It quickly relays this info for payment and credit card processing, thus providing the means and service for customers to pay their bills 


<p align="center">
<b>Modules -> NT Serves:</b>  <br/>
<img src="https://github.com/psZh3ePNj0/OnlineBilling/blob/main/OnlineBilling-Services.jpg" height="80%" width="80%" alt="OnlineBilling Flow"/>
<br />
<br />
  


<br />

<h2>BackEnd Component: Billing Feature Set</h2>
<br />

- The backend (database[s] and their objects) form the final tier component of CablePay.
- The backend Database elemets follow best design / practice features of the rdms databases involve featuring key elements such as:
  - Encryption
  - Modularity
  - Optimisation
    
- Database Objects involved:
  - Stored Procedures
  - Functions
  - Sequences
  - Triggers
  - Indexes
  - Views
  - Synonyms 

<br />
<br />

<h2>Documentation References / Additional Components</h2>

- <b>[CablePay FrontEnd](https://github.com/psZh3ePNj0/OnlineBilling/blob/main/CablePay_Front_GITHUB.docx)</b>
- <b>[CablePay Middletier](https://github.com/psZh3ePNj0/OnlineBilling/blob/main/CablePay_Modules_GITGUB.docx)</b>
<br />


<h2>Core Development Team</h2
                           
  - <b>Christophe Cartwright (MiddleWare Java / BackEnd Database Development)</b>
  - <b>Clint Roberts (FrontEnd Lasso / Web Development)</b>
  - <b>Martin Smith (BackEnd Database Development / Database Administration)</b>
<br/>





<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
