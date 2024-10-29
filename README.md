# PixisAirGroupProject2024

(https://docs.google.com/document/d/1z0B2JLGt0uxJ_2OBZEYjfV0gKKUkCEFoAiaqSQL1TPc/edit)

There should be a button that brings up a listing of all employees. - Connor

There should be a button that list all jobs and a description of the jobs (Pamela)

There should be a button that allows a user to an ENTER flight number and see a list of the staff on the flight. Thomas

There should be a button that allows a user to select a region and see the employees in the region.(Jacey)

There should be a button that allows a user to select an employee by number and determine the state the employee lives in.(Jacey)

Add or update an Employee to the Employee table. - Connor

Add or update a City and State and Zip Code to the Zip Code table - Thomas

Add or update a Customer to the Customer Table (Pamela)

Add or update an Airplane to the Airplane table.(Jacey)

Add or update an Airport to the Airport table (Jacey)

Library == #FLIGHT2024 

Employee Table = #EMPLOYEE

Zip Code Table = #ZIPCODE

Airplane table = #AIRPLANE

Airport table = #AIRPORT

If you sign into your AS400 green screen then type in the command STRSQL and then enter “select * from flight2024/airport” all the fields in the airport table will be shown. Have shown the physical files PF below. The files or tables we will use are #BOLD.

Object Type Library Attribute Text

ACCTPERIOD *FILE FLIGHT2024 PF Accting Period Begin And En ACP001 *FILE FLIGHT2024 PF Acme Work File - No key

***AIRPLANE *FILE FLIGHT2024 PF Flight - Airplanes***

***AIRPORT *FILE FLIGHT2024 PF Flight - List of Airports***

BOAT_TYPE2 *FILE FLIGHT2024 PF
CARS *FILE FLIGHT2024 PF
CARSLF *FILE FLIGHT2024 LF
CLUBMEMBER *FILE FLIGHT2024 PF Mastering IBM i - Chapter 1 COUNTRY *FILE FLIGHT2024 PF Flight - List of Countries
CREW *FILE FLIGHT2024 PF
CREW1 *FILE FLIGHT2024 PF

Object Type Library Attribute Text

CSCSTP *FILE FLIGHT2024 PF Customer Master File for Co CSORDP *FILE FLIGHT2024 PF CloudServices247 Inc. Order CSSUPP *FILE FLIGHT2024 PF Supplier File for CloudServ CURRENCY *FILE FLIGHT2024 PF Currency Exchange Rates
CUSTOMER *FILE FLIGHT2024 PF Flight - Customers who book DANCE *FILE FLIGHT2024 PF
EMAILSENT *FILE FLIGHT2024 PF Emails Sent Table
EMPHRLYPAY *FILE FLIGHT2024 PF Pyxis Global Hourly Employe

***EMPLOYEE *FILE FLIGHT2024 PF Employee Table***

EMPPF *FILE FLIGHT2024 PF Early Chapter Employee File EMPWORKORD *FILE FLIGHT2024 PF Employee Work Order Table
EVFEVENT *FILE FLIGHT2024 PF
FLIGHT *FILE FLIGHT2024 PF Scheduled flights Table
FLIGHTHIST *FILE FLIGHT2024 PF Flight History
FLIGHTPROD *FILE FLIGHT2024 PF Overview Of FLIGHTPROD Rela GTCLSP *FILE FLIGHT2024 PF GTC - Call Transaction File GTCPAYP *FILE FLIGHT2024 PF GTC - Payments Transaction
GTCSTP *FILE FLIGHT2024 PF GTC - Customer Master File
JOBTYPE *FILE FLIGHT2024 PF Reference table of Employee JUNK *FILE FLIGHT2024 PF junk
MAINTLOG *FILE FLIGHT2024 PF Maintenance Log Table
MWC001P *FILE FLIGHT2024 PF Meter Reading File

 Object           Type           Library          Attribute      Text 
                   
 MYTABLE      *FILE      FLIGHT2024    PF          This is a test table        
 ORDERPART *FILE     FLIGHT2024    PF          Airplane Parts on Order     
 PARTS            *FILE     FLIGHT2024    PF          Upload data 8-17-15         
 PRICECODE  *FILE     FLIGHT2024    PF          Ticket price codes and mult 
 PYXISMAINT  *FILE     FLIGHT2024    LF                                      
 REGION          *FILE     FLIGHT2024    PF          Flight - Region for Employe 
 RESCODE       *FILE    FLIGHT2024    PF          Total Pricing Codes for Pyx 
 RESHIST         *FILE    FLIGHT2024    PF          Reservation History Table   
 RESHISTOLD  *FILE    FLIGHT2024    PF          Reservation History Table   
 RESRVTN         *FILE   FLIGHT2024    PF          Flight - Reservations booke 
 RGNAIRPORT  *FILE    FLIGHT2024    PF          Region Airport Relationship 
 ROUTE             *FILE    FLIGHT2024    PF          Flight - Flight Routes      
 ROUTE2           *FILE    FLIGHT2024    PF          Flight - Flight Routes      
 RPG24SPRIN   *FILE    FLIGHT2024    PF                                      
 SA0703D           *FILE    FLIGHT2024    DSPF     Display for Chapter 07 Exer 
 STAFFSCHED  *FILE    FLIGHT2024    PF          Flight Schedule of Staff Ta 
 STATUS             *FILE    FLIGHT2024    PF          Flight Status Reference Tab 
 SUPPLIER         *FILE    FLIGHT2024    PF          Suppliers (SUP/SU)          
 SYSCHKCST     *FILE    FLIGHT2024    LF          SQL catalog view            
 SYSCOLUMNS  *FILE    FLIGHT2024    LF          SQL catalog view            
 SYSCST             *FILE    FLIGHT2024    LF          SQL catalog view            
 SYSCSTCOL      *FILE    FLIGHT2024    LF          SQL catalog view            
 TASKPARTS       *FILE    FLIGHT2024    PF                                      
 TASKS                *FILE    FLIGHT2024    PF          Flight - Tasks for Work Ord 
 TEMPS                *FILE    FLIGHT2024    PF                                      
  WORKORDER    *FILE   FLIGHT2024    PF          Flight - Work orders for pl 
  WUCRSDSP       *FILE    FLIGHT2024    PF          Wibaux University Course De 
  WUCRSP            *FILE    FLIGHT2024    PF          Wibaux University Course Fi 
  WUENRLP          *FILE    FLIGHT2024    PF          Wibaux University - Current 
  Object         Type        Library          Attribute       Text                        
  WUINPAY      *FILE     FLIGHT2024  PF          Wibaux University Instructo 
  WUINSTP      *FILE     FLIGHT2024  PF          Wibaux University Instructo 
  WULOANP     *FILE     FLIGHT2024  PF          Wibaux University Faculty C 
  WUSCTP       *FILE     FLIGHT2024  PF          Wibaux University Current S 
  WUSTDP       *FILE     FLIGHT2024  PF          Wibaux University Student M 

  ***ZIPCODE       *FILE     FLIGHT2024  PF          Zip Codes Table For Airline***

  ZIPPF            *FILE      FLIGHT2024  PF          Mastering IBM i Zipcode dat
