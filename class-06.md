# Class 06 Reading Notes

## Understanding the Problem Domain is the Hardest Part of Programming
What this means is having a clear understanding of the objective of the assignment is critical. Once you understand the problem you are trying to solve. 
### Tips
- talk to the client and really make sure you have a clear understanding of the question you are trying to solve before you start to code
- break the problem up into bits. This allows you to narrow your focus.

### JavaScript - Object Literals
Objects group together variables and functions to create a model. It has its own terminology:
- variables are called properties (i.e. about the object)
- functions are methods (i.e. tasks)

### Creating an Object using Literal Notation:
```
- var ballardLibrary = {
    name: BallardLibraryBooks,
    totalBooks: 100,
    checkedOutBooks: 60,

    checkAvailableBooks: function(){
        return this.totalBooks - this.checkedOutBooks;
    }
};
```

### JavaScript Ch 5 - Document Object Model
- Makes a model of the HTML page using a DOM tree
- Accesses and changes the page using the Application Programming Interface (API)
- Various types of nodes: document node, element nodes, attribute nodes, text nodes. 
- Can access element nodes to make changes to the page using DOM queries.
- DOM queries can return a single element or a NodeList
-Two ways to select a node element from a NodeList:
1. item() method
1. array syntax

- Can also loop through each node on a node list


