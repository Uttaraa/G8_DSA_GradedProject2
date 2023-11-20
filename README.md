<H1>G8_DSA_GradedProject2</H1>

DSA-Graded Project2-Group 8 (IITR-FSD 2023 August Batch)

THIS ASSIGNMENT COMPLIES OF TWO PROGRAMS NAMELY:
<ul>
<li><H3><a href ="https://github.com/Uttaraa/G8_DSA_GradedProject2/tree/main/G8_DSA_GradedProject2/src/com/greatlearning/skyscraper">SKYSCRAPER</a></H3></li>

<li><H3><a href ="https://github.com/Uttaraa/G8_DSA_GradedProject2/tree/main/G8_DSA_GradedProject2/src/com/greatlearning/transaction">TRANSACTION_BST</a></H3></li>
</ul>

The guidelines provided in problem statement and further details of both the programs are as follows:

## <ins> SKYSCRAPER </ins>
This assignment demonstrates a program that will help to analyze the construction process and validate the given coditions of a skyscraper building, to avoid manual work and errors.
Implemented using basic concepts of Data Structure and Algorithms(DSA).
<br>
<br>
This program is for A chief architect, who is working on building a skyscraper, in Mumbai. The construction is in such a way that the floors will be constructed in other factories and they will be assembled. All the sizes will be distinct.
<br><br>
<b>The skyscraper needs to be constructed in N days with the following conditions :</b>
<br>
a)	Every day a floor is constructed in a separate factory of distinct size.
<br>
b)	The floor with the larger size must be placed at the bottom of the building.
<br>
c)	The floor with the smaller size must be placed at the top of the building.
<br>
<br>
<ins>Note</ins>: A floor cannot be assembled in the building until all floors larger in size are placed.
Architect wants us to build a small program that will help him analyze the construction process, to avoid manual work and errors.
<br>
### <ins>Additional Information</ins>
<b>The following conditions are fulfilled as mentioned in assignment </b>
<ul>
<br><li>1)	Can use any inbuilt java function/s to implement the above functionalities</li>
<br><li>2)	Can choose any DataStructure(Stack, Queue, LinkedList) to implement the above functionality.</li>
</ul>
<br>
The program initially takes number of DAYS as input from the operator then takes the size of the floors as input and saves it in an array, this helps to compare the size of floors on each day. If invalid size of the floor is enterred the operator will get a message of the same and can continue with correct size of floors,otherwise the program will dispalay the size of floors which can be assembled on respective day.
<br>
<br>

## <ins> TRANSACTION_BST </ins>
This assignment demonstrates a program for a scenerio where I am working in an MNC, which manages the Transactions, where only BST is used as a Data Structure. The company stores all the data of transactions in BST such that the tree is always a complete BST.
<br>
A new business requirement has arrived where the BST should not contain any left node.
<br>
I am required to modify the existing BST and display the node values present in ascending order.
<br>
<br>
<b>PROGRAM INFORMATION</b>
This program's package consist of two classes namely:
<br>
<a href="https://github.com/Uttaraa/G8_DSA_GradedProject2/blob/main/G8_DSA_GradedProject2/src/com/greatlearning/transaction/Transaction_BST.java">Transaction_BST</a>
<br>
<a href="https://github.com/Uttaraa/G8_DSA_GradedProject2/blob/main/G8_DSA_GradedProject2/src/com/greatlearning/transaction/TransactionDriver.java">TransactionDriver</a>
<br><br>
Here in Transaction_BST class we the Binary Search Tree is converted into into a Skewed Tree and the values are hard coded as given in problem statement. Whereas TransactionDriver class works as the driver class for the program.
<br>
### <ins>Additional Information</ins>
Given values to hardcode given in problem statement are as follows: <br>
     Main tree = new Main(); <br>
     tree.node = new Node(50); <br>
     tree.node.left = new Node(30); <br>
     tree.node.right = new Node(60); <br>
     tree.node.left.left = new Node(10); <br>
     tree.node.right.left= new Node(55); <br> 
     <br>
And the desired **output** is as follows:
<br>
**10 30 50 55 60**

<H6><ins>Technology</ins></H6>
<b>Java</b>
