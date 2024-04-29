# Project Summary

This repository focuses on quality assurance for Urban.Routes, a transportation app. It was created during the QA Engineer bootcamp at
TripleTen, where we honed our skills and leveraged various techniques and tools to enhance testing efficiency.

# Project Structure

Mind map: Visual Reference to plan and execute tests comprehensively.

Flowchart: Shows the behavior and interaction for costs and time of "carsharing" option.

Equivalence Class and Boundary Tests: Explore different equivalence classes and boundaries to ensure complete and robust coverage.

Jira Bug Reports: Report and track issues identified during testing: https://willcarneiro.atlassian.net/jira/software/projects/BUG/issues/

Test cases and Checklists: Exploring the interface, functionality, and logic of the application, focusing on the "Payment Method" and "Add Card" pop-ups, the logic behind the "Book" button, and the logic of the Vehicle Reservation feature.

# Tasks
  ### Part 1

* Task 1: Create a Mind Map for the "Add Driver Licence" feature. Analyze the requirements and designs of the "Add Driver Licence"
  feature and present them graphically in the form of a mind map. The mind map is divided into interface and functionality.
  > Files nested in folder Task_1.


* Task 2: Create a flowchart to comprehend the calculation logic behind the cost and duration of the carsharing feature. The application provides information on the journey's cost and duration.
  > Files nested in folder Task_2.

* Task 3: Defining Equivalence Classes and Boundary Values only for the "First Name" and "Last Name" Input Fields in the Driver Licence Form.
  > Files nested in folder Task_3.

* Task 4: Write the test cases based on the test values within the equivalence classes. It doesn't need to be written other cases now, as the requirements may still change, rendering the values useless in that case. The test cases should verify if the logic for calculating the time and cost of a journey is correct. Two formulas used to calculate the time and cost:
  | Calculation | Description |
  | ----------- | ----------- |
  | Time (T)    | Distance (S) / Speed (V) at the departure time |
  | Cost        | Time (T) of the trip * price per minute |

   > Files nested in folder Task_4.

### Part 2
> Enviroments: <br>
   _Google Chrome, screen resolution 800x600_ <br>
   _Firefox, screen resolution 1920x1080_

* Task 5: Prepare the test documentation for the layout of the reservation form. Create a checklist for the "Reservation form" layout.
  > Files nested in folder Task_5.<br>
  > _Note: The carsharing designs in Figma cannot be displayed due to copyright reasons._



* Task 6: Create a checklist to assess the functionality of both the "Payment Method" and "Add Card" screens, utilizing partitioning of equivalence classes and analysis of boundary values. Include both positive and negative test cases. Could be tested only in one enviroment.
  > Files nested in folder Task_6.

* Task 7: Prepare test cases for the "Reserve" button including positive and negative tests. Refer to the "Reserve Button" section in the requirements.
  > Files nested in folder Task_7.





 

