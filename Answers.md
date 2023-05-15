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
> The use of libraries can facilitate development by providing pre-built code modules that offer specific functionalities. These libraries save time and effort as developers can leverage existing code rather than starting from scratch. It promotes code reuse, >improves efficiency, and allows developers to focus on the core aspects of the program.

#### 2. The company employs several sales personnel to sell its products to different retailers. Each branch of the company keeps track of its own sales with a suite of programs that include the two classes SalesPerson and Sales.

#### Each instance variable is initialized when a SalesPerson object is instantiated.
#### (a) Complete the constructor public SalesPerson(String id), from the SalesPerson class. (2 points)
>![image](https://github.com/RandomKings/forum-oop/assets/127679190/5ef0867b-9800-4f2c-b11a-3f03c3cf1ee8)

