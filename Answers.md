# Class Design and Implementation Case

#### A large company with locations in different cities has taken an OOP approach in creating an administration program that manages all aspects of its business. These aspects include:
#### ·the sale of all the different products that the company manages
#### ·the salaries for managers, office staff and sales personnel.


#### 1.(a) By making use of an example from the above scenario, distinguish between a class and an instantiation of a class. (3 points)
> A class is a blueprint or template that defines the properties and behaviors of objects. An instantiation of a class, also known as an object, is a specific instance created based on that class.

#### The different modules in the program each open a graphical user interface (GUI). Each GUI has a similar design but contains differences specific to each module.

#### (b) By giving two examples, explain how the principles of inheritance can be incorporated into the design of this administration program. (4 points)
>Examples of incorporating inheritance in the administration program design could be:
>Having a base class for GUI design with common features, and deriving specific GUI classes for each module with additional unique features.
>Creating a base class for employee salaries and deriving subclasses for managers, office staff, and sales personnel, inheriting the common salary functionality.

#### (c) Describe how the use of libraries can facilitate the development of programs like this company’s administration program. (3 points)
> The use of libraries can facilitate development by providing pre-built code modules that offer specific functionalities. These libraries save time and effort as developers can leverage existing code rather than starting from scratch. It promotes code reuse, improves efficiency, and allows developers to focus on the core aspects of the program.

#### 2. The company employs several sales personnel to sell its products to different retailers. Each branch of the company keeps track of its own sales with a suite of programs that include the two classes SalesPerson and Sales.

#### Each instance variable is initialized when a SalesPerson object is instantiated.
#### (a) Complete the constructor public SalesPerson(String id), from the SalesPerson class. (2 points)
>![image](https://github.com/RandomKings/forum-oop/assets/127679190/5ef0867b-9800-4f2c-b11a-3f03c3cf1ee8)

#### (b) Explain why accessor methods are necessary for the SalesPerson class. (3 points)
> Accessor methods are necessary in the SalesPerson class to access the private instance variables (such as id, salesHistory) from outside the class. They allow other parts of the program to retrieve the values of these variables, providing necessary information and encapsulation.

#### (c) (i) Construct unified modelling language (UML) diagrams to clearly show the relationship between the SalesPerson and Sales classes.
Note: There is no need to include mutator or accessor methods or a constructor. (4 points)

//uml digrrammmm

#### (c) (ii) Outline a negative effect that a future change in the design of the Sales object might have on this suite of programs. (2 points)
>A negative effect of future changes in the Sales object's design could be the need to modify the SalesPerson class as it relies on the structure and attributes of the Sales class. Any changes to the Sales object may require corresponding updates in the SalesPerson class, leading to potential errors or inconsistencies if not properly handled.

#### (d) State the output after running this code. (4 points)
>102
2
2550.4
1300.0

#### (e) Construct the method calcTotalSales(), in the SalesPerson class that calculates the total value of the sales for a specific SalesPerson object. (5 points)
>![image](https://github.com/RandomKings/forum-oop/assets/127679190/667dd6e5-e2c2-4024-b883-68095ff56b09)

#### The salesPeople array contains 100 instantiated objects. The company wishes to reward the salesperson whose sales have the largest total value.
(f) By making use of any previously written methods, construct the method highest(), that returns the ID of the salesperson whose sales have the largest total value. (5 points)
>
