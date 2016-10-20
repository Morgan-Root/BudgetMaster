# __Software Requirements Specification__

### __for__

# __BudgetMaster__

#### __Version 1.0 approved__

### __Prepared by Grant Hardy, Ross Thompson, Jason Williams, Adrian Colon, Chris Ross, Morgan Root__

### __LSU__

### __October 21, 2016__

<br><br>

### __Table of Contents__

#### __Table of Contents__
#### __Revision History__

#### __1. Introduction__
  1. Purpose
  2. Document Conventions
  3. Intended Audience and Reading Suggestions
  4. Product Scope
  5. References

#### __2. Overall Description__
  1. Product Perspective 
  2. Product Functions
  3. User Classes and Characteristics
  4. Operating Environment
  5. Design and Implementation Constraints
  6. User Documentation
  7. Assumptions and Dependencies

#### __3. External Interface Requirements__
  1. User Interfaces
  2. Hardware Interfaces
  3. Software Interfaces
  4. Communications Interfaces

#### __4. System Features__
  1. Add Income
  2. Add Expense

#### __5. Other Nonfunctional Requirements__
  1. Performance Requirements
  2. Safety Requirements
  3. Security Requirements
  4. Software Quality Attributes
  5. Business Rules

#### __6. Other Requirements__
#### __Appendix A: Glossary__
#### __Appendix B: Analysis Models__
#### __Appendix C: To Be Determined List__

<br><br>

### __Revision History__
| Name          | Date              | Reason For Changes  | Version |
| ------------- |:-----------------:|:-------------------:| -------:|
| Initial Draft | October 17, 2016  |                     | 0.1     |
|               |                   |                     |         |

<br><br>

### __1.   Introduction__
#### __1.1   Purpose__
  The product is a budgeting Android application that allows users to easily keep track of budgets and 
    day-to-day spending. Users may enter their monthly income and divide it into smaller expense 
    categories (e.g. entertainment, gas, groceries, etc.). The application will provide an 
    intuitive user interface and goals/tips to encourage users to keep track of their spending.


#### __1.2   Document Conventions__
This document will be following all conventions required in the IEEE Std 830-1998. Boldface will represent the title of each section in this document. 

#### __1.3   Intended Audience and Reading Suggestions__
Readers that may benefit from this document include (but are not limited to):
- Developers
  - To better understand the goals, use cases, and specifications of this project
- Project Managers
  - To familiarize themselves with the requirements and scope of this project
- Marketing Staff
  - To examine features that may make this software system more profitable
- Users/Testers
  - To gain knowledge on all aspects of this software system that may be useful to a daily user
- Document Writers
  - To fully understand any feature that would otherwise be unclear based on code

#### __1.4   Product Scope__
BudgetMaster is an Android application that will be compatible on all versions past Android 5.0. BudgetMaster will allow its users to log all incomes and expenses and project the monthly available income on its main screen. BudgetMaster aims to be a frequently used application that encourages the management of finances on a daily basis. 

#### __1.5   References__
* [Material Design by Google](https://material.google.com/)
* [SQL for Android](https://developer.android.com/reference/android/database/sqlite/SQLiteDatabase.html)
* [Android API](https://developer.android.com/reference/packages.html)


<br>

### __2.   Overall Description__ 
#### __2.1   Product Perspective__

This system will be a mobile application that allows users to make and track their budget; it will also include a database that allows the storage of data of the budget.
<br>
The database and the mobile application will need to interact in order for the user of the app to see and track what money has been spent in prior entries. Whenever the user makes an entry into the mobile application, the database will then update its information about the user's current budget. If the user wants to see past entries in the mobile application, the database will have to provide the application with that information so that the application can then show the user the information about the budget requested. So, the mobile application will be able to both access and modify data of the database. The database will be embedded in the mobile application in order for the user to access the database easily.


#### __2.2   Product Functions__

#### __2.3   User Classes and Characteristics__

#### __2.4   Operating Environment__

#### __2.5   Design and Implementation Constraints__

#### __2.6   User Documentation__

#### __2.7   Assumptions and Dependencies__

<br>


### __3.   External Interface Requirements__ 
#### __3.1   User Interfaces__

#### __3.2   Hardware Interfaces__

#### __3.3   Software Interfaces__

#### __3.4   Communications Interfaces__

<br>


### __4.   System Features__ 
#### __4.1   Add Income__

    4.1.1 User adds an amount that increases total spendable income - High Priority
    
    4.1.2 Stimulus/Response Sequences

    4.1.3 Functional Requirements
    
#### __4.2   Add Expense__

<br>

### __5.   Other Nonfunctional Requirements__ 
#### __5.1   Performance Requirements__

#### __5.2   Safety Requirements__

#### __5.3   Security Requirements__

#### __5.4   Software Quality Attributes__
    5.4.1 Maintainability and Extendability
    
    5.4.2 Reliability 
    
    5.4.3 Usability
    
#### __5.5   Business Rules__ 

<br>

### __6.   Other Requirements__

### __Appendix A: Glossary__

### __Appendix B: Analysis Models__

### __Appendix C: To Be Determined List__


