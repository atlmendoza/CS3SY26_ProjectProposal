# CS3SY26_ProjectProposal by Aline Teresa Mendoza from CS Unit of PSHS


## Project Proposal Template:
### Project Title or Name of the Application	: PennyWise
### Section			   	      : 9-Cesium 2030
### Group Members			    : Cs04 - CASISON, Mary Thiadelle | Cs05 - CASTRO, Zoe Asiel | Cs30 - VERGARA, Jaime
### Date (Proposal Date)  : Nov 13, 2026

### Project Description:

- Managing personal finances can be challenging, especially for individuals who struggle with effective management and budgeting. Without a proper way to keep track of expenses, people may risk overspending beyond their budget and/or have difficulty remembering where their money actually goes. This is where our project comes in. It will be designed with younger audiences in mind, being simple and incredibly easy to understand, as young people are only just learning to manage their budgets. 

- Put simply, the program will allow an account owner to manage their money by taking a monetary unit (eg. their paycheck or monthly allowance) and allocating it to different places (eg. savings, leisure, essential bills, etc.) so they can keep track of their spendings. It also lets them keep track of online subscriptions by syncing with their browser and email, so they can see if they are losing any money to subscriptions they no longer need. A list of the classes involved is as follows:

### Full Explanation of Classes

1. Account
2. Plus Account
3. Pro Account
4. Subscription
5. Monetary Unit
6. Allocation Destination

### Accounts
Pro accounts inherit from plus accounts, and plus accounts inherit from basic accounts. They all have usernames, passwords, and current total budgets that can be altered using methods, and the higher tiers have additional features such as more access to customized spending goals (beyond the basics), viewing how their expenses have evolved over time, and access to artificial intelligence-based features that give them customized budget suggestions. The base account can start a free trial of one of the higher-tier accounts, getting access to their perks for a temporary period of time. All accounts can also accept money units, instantiate allocation destinations within themselves, distribute money throughout these destinations, and other things, all done through methods.

Attributes:
 - name
 - password (private)
 - subscription list
 - destination list
 - current budget

Methods:
 - Getters and setters for name and password
 - Show subscription list
 - Show destination list
 - Create destination
 - Start a free trial of a higher tier
 - Allocate money
 - Delete account

### Subscriptions
Subscriptions are instantiated by the user, representative of a subscription based online that they are currently paying for. The account can generate a list of all of these subscriptions, showing the user how much they are paying for each one. 

Attributes:
 - id
 - business / service
 - fee

Methods:
 - Getter and setter for id
 - Getter for business/service name
 - Delete subscription

### Monetary Unit
Represents a unit of money, like a user's paycheck for a week or allowance for a month. Can be used by the account to be allocated to different destinations within their account. They are instantiated within accounts, and can only exist within that account (composition relationship). 

Attributes:
 - name
 - amount
 - currency

Methods:
 - getters and setters for name, account, and currency
 - delete unit

### Allocation Destination
A place where the user can allocate the money provided by a monetary unit. Think of it like a box where a user can place their money in order to spend it on something specific in the future. For example, there could be a box for their savings, a box for their important bills, a box for their leisure spending, etc. They are instantiated within accounts, and can only exist within that account (composition relationship). 

Attributes:
 - name
 - id
 - amount of money
 - budget percentage (calculated based on total money and amount of money within destination) 

Methods: 
 - getters and setters for name, id, and amount of money
 - delete destination


As previously stated, the specific target audience for our application will be younger people (teens and young adults) that are only beginning to learn how to handle large amounts of money. They need a way to learn these essential budgeting skills without an app that will overwhelm them with loads of different features or advanced concepts. Our aim for our project is to make budgeting as simple as possible, so it can stand out from other budgeting apps as the most straightforward and best for a younger demographic.

The description is then followed by the class diagram, depicting clearly what was described.

**Sample class Diagram from https://static.visual-paradigm.com/web/images/tutorials/class-diagram-tutorial/01-class-diagram-example.png:**

<img width="1544" height="886" alt="image" src="https://github.com/user-attachments/assets/2420c881-3b32-4b3b-8457-4ed13382c1fd" />


![Sample Diagram](https://static.visual-paradigm.com/web/images/tutorials/class-diagram-tutorial/01-class-diagram-example.png)

### Goals:

Describe the long term outcomes of your project followed by a couple of objectives to meet the goals stated in this paragraph

- Objective 1: Provide a simple, clean, and user-friendly way to manage personal funds and budgeting to an identified target demographic of teens and young adults that want to effectively handle money
- Objective 2: Train ourselves in the principles of collaborative coding and object-oriented programming
- Objective 3: Demonstrate how Computer Science 3 concepts and knowledge can solve real-life, everyday problems 

[Click here for Rubrics and Sample projects](https://docs.google.com/document/d/1xKd1CqK6DcNWS2_oJPBNtY5n3I3Hqiw8FY3W295Iqfk/edit?usp=sharing)

### Note: Information presented here is for the project proposal only, and is subject to change. It may or may not fully reflect the final product.
