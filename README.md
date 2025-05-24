# car-dealership-management

Overview
  
  The Car Dealership Management System is a comprehensive application designed to manage various aspects of a car dealership. This system allows users to manage inventory, track car types, handle employee information, and monitor car imports and exports. The application is built using Python and utilizes a graphical user interface (GUI) for user interaction.

Features

  --> Inventory Management: Keep track of available cars, their quantities, and worth.
  
  --> Car Types: Manage different types of cars available in the dealership.
  
  --> Employee Management: Store and manage employee details.
  
  --> Import and Export Tracking: Monitor cars that are imported and exported from the dealership.
  
  --> Used Cars Management: Keep records of used cars available for sale.
  
  --> New Arrivals: Track newly arrived cars and their quantities.
  
  --> Rental Cars: Manage rental car information and pricing.
  
  --> Data Visualization: Generate visual representations of data using charts and graphs.
  
  
File Structure
  The project consists of several files and folders, each serving a specific purpose:
  1. MultipleFiles/
     This directory contains all the necessary files for the application.
       --> branches.csv:
           -> Description: Contains information about the branches of the dealership.
           -> Fields: BranchID, Location, Manager.

       --> car_types.csv:
           -> Description: Lists the different types of cars available.
           -> Fields: TypeID, TypeName.

       --> exported_cars.csv:
           -> Description: Records details of cars that have been exported.
           -> Fields: CarID, CarName, ExportDate, Quantity.

       --> imported_cars.csv:
           -> Description: Contains information about cars that have been imported.
           -> Fields: CarID, CarName, ImportDate, Quantity.

       --> inventory.csv:
           -> Description: Maintains the inventory of cars available for sale.
           -> Fields: CarID, CarName, Quantity.

       --> newly_arrived.csv:
           -> Description: Tracks newly arrived cars and their quantities.
           -> Fields: CarID, CarName, ArrivalDate, Quantity.

       --> rental_cars.csv:
           -> Description: Contains information about cars available for rent.
           -> Fields: RentalID, CarName, RentalPricePerDay.

       --> used_cars.csv:
           -> Description: Records details of used cars available for sale.
           -> Fields: CarID, CarName, Year, Mileage, Quantity.

       --> worth_of_cars.csv:
           -> Description: Contains information about the worth of cars in the inventory.
           -> Fields: CarID, CarName, Worth, Quantity.

       --> employees.csv:
           -> Description: Stores information about employees working at the dealership.
           -> Fields: EmployeeID, Name, Position.

       --> Car Mangement GUI.png:
           -> Description: A visual representation of the GUI layout for the application.

       --> car_images.jpg:
           -> Description: Background image used in the GUI.

       --> final_cps.py:
           -> Description: The main Python script that runs the application. It includes the GUI implementation, data handling, and various functionalities such as displaying, inserting, updating, and deleting                              records.

Technologies Used
--> Python: The primary programming language used for developing the application.
--> Tkinter: A standard GUI toolkit for Python, used for creating the graphical user interface.
--> CSV: Used for data storage and management in a tabular format.
--> PIL/Pillow: A Python Imaging Library used for image processing.
--> Matplotlib: A plotting library used for data visualization.
--> Tabulate: A library for formatting tabular data in a visually appealing way.
--> tkcalendar: A library for adding calendar widgets to the GUI.

Installation
--> Clone the repository:
    -> bash
        git clone https://github.com/yourusername/car-dealership-management.git

--> Navigate to the project directory:
    -> bash
        cd car-dealership-management

--> Install the required libraries:
    -> bash
        pip install -r requirements.txt

--> Run the application:
    -> bash
        python final_cps.py

Usage
--> Launch the application to access the main menu.
--> Use the buttons to navigate through different functionalities such as displaying data, inserting new records, updating existing records, and deleting records.
--> Visualize data through various plots and charts.

Contributing
--> Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.
