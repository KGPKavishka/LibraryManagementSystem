# Library Management System  

The Library Management System is designed to simplify library operations, making it easier to manage books, members, and publishers, as well as track borrowing and returning transactions. This system ensures a seamless and organized experience for librarians and members alike.  

---

## Key Features  

- **Streamlined Library Operations**  
  Simplify processes like adding, removing, or issuing books, while maintaining accurate records of members and publishers.  

- **Member Services**  
  Allow members to borrow and return books effortlessly, while keeping track of their borrowing history.  

- **Publisher Management**  
  Maintain up-to-date records of publishers and their contact details.  

- **Transaction Management**  
  Track every book loan and return, including issue dates, due dates, and member details.  

- **Role-Based Access**  
  Enable personalized access for members and librarians to perform their specific tasks.  

---

## Key Components  

### 1. Library  
The Library acts as the central hub of the system, managing all resources and activities.  

#### Responsibilities  
- Maintain a collection of books and a list of registered members.  
- Handle tasks like adding, removing, and issuing books.  

#### Features  
- `addBook()`: Add new books to the collection.  
- `removeBook()`: Remove books that are no longer available.  
- `registerMember()`: Register new members in the system.  
- `issueBook()`: Issue books to members for borrowing.  

---

### 2. Book  
Books are the core assets of the library, with detailed information and availability tracking.  

#### Attributes  
- **title**: The name of the book.  
- **author**: The author of the book.  
- **isbn**: Unique identifier for the book.  
- **status**: Availability of the book (e.g., available or borrowed).  

#### Features  
- `viewDetails()`: View detailed information about the book.  
- `checkAvailability()`: Check if the book is available for borrowing.  

---

### 3. Member  
Members represent individuals who borrow books from the library.  

#### Attributes  
- **member_id**: Unique identifier for each member.  
- **name**: Name of the member.  
- **phone_no**: Contact number of the member.  

#### Features  
- `borrowBook()`: Borrow books from the library.  
- `returnBook()`: Return borrowed books to the library.  

---

### 4. Loan  
Loans track borrowing transactions and ensure timely returns.  

#### Attributes  
- **loan_id**: Unique identifier for each loan.  
- **book**: The borrowed book.  
- **member**: The member who borrowed the book.  
- **issue_date**: The date the book was borrowed.  
- **due_date**: The deadline for returning the book.  

#### Features  
- `completeTransaction()`: Finalize borrowing or returning of books.  

---

### 5. User  
Users represent individuals interacting with the system, including both members and staff.  

#### Attributes  
- **user_id**: Unique identifier for each user.  
- **name**: Name of the user.  
- **email**: Email address of the user.  

#### Features  
- `login()`: Log in to access the system.  
- `logout()`: Log out after completing tasks.  

---

### 6. Librarian  
Librarians are specialized users responsible for managing the library’s resources.  

#### Attributes  
- **librarian_id**: Unique identifier for the librarian.  
- **name**: Name of the librarian.  

#### Features  
- `addBook()`: Add new books to the collection.  
- `removeBook()`: Remove books from the library.  
- `manageBooks()`: Oversee the library’s inventory and operations.  

---

### 7. Publisher  
The Publisher class manages information about book publishers.  

#### Attributes  
- **publisher_id**: Unique identifier for the publisher.  
- **name**: Name of the publisher.  
- **contact_info**: Contact details of the publisher.  

#### Features  
- `addPublisher()`: Add new publishers to the system.  
- `updatePublisher()`: Update details of existing publishers.  
- `removePublisher()`: Remove publishers no longer associated with the library.  

---

## Getting Started  

### Prerequisites  
A relational database to store and manage data for books, members, publishers, and loans.
A programming language or framework that supports object-oriented programming (e.g., Java, Python, or C#).
Development tools such as IDEs, version control (Git), and database management software.

### Steps to Set Up  
1. **Set Up the Database**
  -Design tables for key entities: books, members, publishers, and loans.
  -Define primary keys and foreign keys to establish relationships between tables.

2. **Develop Core Functionalities**
  - Implement features to add, update, delete, and retrieve information about books, members,     and publishers.
  - Create functionality for managing loan transactions, including borrowing, returning, and      tracking due dates.

4. **Build the User Interface**
  -Develop a user-friendly interface where users can:
    -Log in securely.
    -Browse available books and their details.
    -Borrow or return books and view loan status.
    -Manage resources like members and publishers.
   
6. **Test and Refine**
  - Conduct rigorous testing to ensure all functionalities work seamlessly.
  - Optimize performance and resolve any bugs or issues.
  - Validate data integrity and user experience for a smooth workflow.

---

With its robust functionality, this Library Management System offers an efficient and organized approach to managing library resources, ensuring a smooth experience for both librarians and members.  

---

## Contributors  

1. 22UG1-0323 | W.G. Kasun Chamika De Mel
2. 22UG1-0281 | Sahan Wijesinghe
3. 22ug1-0472 | K.G. pasindu Kavishka
4.
5.

---
