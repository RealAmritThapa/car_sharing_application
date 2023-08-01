# Car Sharing Application
Car Rental Management System

This Car Rental Management System is a C++ program that allows users to manage car and user data in a car rental application. The program defines a class hierarchy for cars, including Electric, Utility, and Sport classes, with each class inheriting from the Cars class. The Cars class is a subclass of the Host class, which represents the host user account. The program also includes data structures like arrays and circular linked lists to store car and renter information.

Features<br />
Car Class Hierarchy: The Cars class hierarchy includes base class Cars with general car information and derived classes Electric, Utility, and Sport with additional attributes specific to each car type.
<br />Host User Accounts: The program manages host user accounts through the Host_accounts class, which allows users to save, display, and check account credentials.
<br />Car Data Management: The Arr class handles an array of car nodes, enabling users to insert, display, and remove car information based on car IDs.
<br />Renter Data Management: The Cll class manages a circular linked list of renter nodes, allowing users to insert, display, fetch, and remove renter information.
# How to use<br />
git clone [url] <br />
cd car_sharing_application<br />
g++ *.cpp -o car_sharing_app<br />
./car_sharing_app<br />

