﻿# iti-python-lab4

<h1 align="center">
  <br>
  <a href=""><img src="https://www.iti.gov.eg/assets/images/iti-logo.png" alt="ITI" width="200"></a>
  <br>
  ITI
  <br>
</h1>

<h4 align="center">This code defines multiple classes that model a scenario of an office, its employees and the cars they use.
.</h4>


![screenshot](https://www.filepicker.io/api/file/BFMMlbcQvml9HSqXcvNp)
---------------------------------------------------------------
## How to run
---------------------------------------------------------------
pip install virtualenv
----------------------------------------------------------------
virtualenv my_env_name
----------------------------------------------------------------
virtualenv my_env_name to create a new environment
----------------------------------------------------------------
source my_env_name/bin/activate to activate the new environment
----------------------------------------------------------------
python main.py
----------------------------------------------------------------
## Key Features

---------------------------------------------------------------
This code defines multiple classes that model a scenario of an office, its employees and the cars they use.

    Class Person defines the basic properties and actions of a person:
        name
        money
        mood (happy, tired, lazy)
        healthRate
        sleep (modifies mood based on number of hours slept)
        eat (modifies healthRate based on number of meals eaten)
        buy (deducts the cost of items from money)

    Class Employee inherits from class Person and adds additional properties and actions specific to an employee:
        id
        car
        email
        salary
        distanceToWork
        work (modifies mood based on number of hours worked)
        send_mail (saves an email in a text file)
        email and salary have setters to enforce validation (email must end with .com, salary must be >= 1000)
        healthRate has a setter to enforce validation (healthRate must be between 0 to 100)

    Class Car defines the basic properties and actions of a car:
        name
        fuelRate
        velocity
        run (modifies fuelRate based on distance traveled and velocity)
        stop (updates velocity to 0)
        refuel (increases fuelRate)

    Class Office models an office and its employees:
        employeesNum (keeps track of number of employees)
        name
        employees (list of employees)
        get_all_employees (returns the list of employees)
        get_employee (returns the employee with the specified id)
        hire (adds an employee to the list of employees)
        fire (removes an employee from the list of employees)
        deduct (deducts a specified amount from an employee's salary)
        reward (increases an employee's salary by a specified amount).
---------------------------------------------------------------



## Created BY

[![Bedaba Edward](https://avatars.githubusercontent.com/u/21156712?v=4)](https://github.com/bedaba)

[Bedaba Edward ](https://github.com/bedaba) 

## [License](https://github.com/bedaba/iti-python-lab3/blob/main/LICENSE)

MIT

---
