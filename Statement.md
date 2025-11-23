PROJECT STATEMENT

Project Title: Personal Expense Tracker System

1. Problem Statement
In the life of a student or a young professional, financial management often gets ignored. The big costs, like tuition or rent, are easy to see. The small daily costs such, as snacks, travel fares, stationery and subscriptions, add up. Financial management suffers when those small costs pile up and cause a budget shortfall at the end of the month.
The core issues identified are:
Memory Fallacy: Relying on mental notes to track spending is unreliable and prone to forgetfulness.
Manual Tedium: I notice that physical notebooks are often not, at hand when the transaction happens. Physical notebooks lead to data gaps.
Complexity of Existing Solutions:
I have found that most expense tracking apps you can find in the market focus, on devices. Expense tracking apps often fill the screen with ads. Expense tracking apps often ask for permissions such as linking a bank account. Many users feel uneasy, about those permissions.
From my experience there is no lightweight desktop tool, for users who spend most of their time at a computer. Users want the simple offline lightweight desktop tool to let them type quickly with the keyboard. Users do not want to use a interface. The simple offline lightweight desktop tool does not exist.

2. Scope of the Project
The scope of the project is to build a Desktop Console Application using Python that works as a diary. The system will use the ideas of data management (CRUD. Create, Read, Update, Delete). The system will also use file persistence.

In-Scope:
Developing a Command Line Interface (CLI) for user interaction.
Implementing a robust backend using Python’s standard libraries.
I have found that using the CSV (Comma Separated Values) files, for data storage is reliable. The CSV (Comma Separated Values) files are simple.
Providing basic analytical capabilities (summation and categorization).

Out-of-Scope (for this version):
Graphical User Interface (GUI) elements (buttons/windows).
Integration with online banking APIs or cloud storage.
I notice that the system only supports a user. Multi‑user authentication is unnecessary.
Multi-currency support.

3. Target Users
The main audience, for this software includes:
University Students have the pocket money. University Students need to track campus expenses such, as food, printouts and transport.
Freelancers/Developers: I see Freelancers/Developers spend hours on the desktop. I see Freelancers/Developers prefer command-line tools that fit the workflow. Freelancers/Developers avoid switching devices.
Privacy-Conscious Users: the people who want to track their finances. Privacy-Conscious Users do not want to share the data, with third‑party apps or cloud services.

4. High-Level Features
I have built the system. The system will have the following functions:
Expense Logging:
A streamlined input interface to record Product Name, Category (e.g., Food, Travel), Price, and Date.
Automated Persistence (Auto-Save):
The system writes data to the disk (expenses.csv) after each entry. The system writes the data automatically. The system stops data loss if power fails or program terminates.
Expense Management:
View: Display a tabulated list of all past expenses.
Edit: Let users correct fields. For example fix a price. Users do not need to re‑enter the record.
Delete: Delete the duplicate entries using an ID system.
Search & Retrieval:
A function to look up specific transaction IDs to verify past spending.
Financial Analytics:
A reporting feature that calculates the Total Expenditure and provides a Category-wise Breakdown, helping users identify their highest spending areas.
