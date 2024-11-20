**Name: BHANUSRI G**
**Company : CODTECH IT SOLUTIONS PVT.LTD**
**ID : CT08DS9625**
**Domain : Software Development**
**Duration : 10 Nov 2024 - 10 Dec 2024**

**Task 2 --- Health and Fitness Tracker**

**Introduction**

    The Health and Fitness Tracker is a simple Java console application that helps users monitor their daily fitness goals. The program allows users to log the number of steps walked, calorie intake, and water consumption, providing a summary of their fitness data during the session.

**Features**

Update Steps: Log the number of steps walked during the day.
Update Calories: Record daily calorie intake.
Update Water Intake: Track water consumption in milliliters.
View Summary: Display the total fitness data logged in the session.
Exit: Exit the application gracefully.

**Technologies Used**

Programming Language: Java
IDE: Any Java IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans)
Execution Environment: Console Application
Code Explanation
Main Functionalities
The program uses a FitnessData class to store and manage fitness data for the session. Below are the main features:
steps: Tracks the total steps walked.
calories: Tracks the total calorie intake.
waterIntake: Tracks the total water consumed in milliliters.
Methods:
updateSteps: Adds steps to the total count.
updateCalories: Adds calories to the total count.
updateWater: Adds water intake to the total count.
displaySummary: Prints a summary of all logged data.

**Menu Interface:**
    A user-friendly menu allows users to log data and view a summary of their fitness activity.
    
**Code Snippet**

System.out.println("\nHealth and Fitness Tracker");
System.out.println("1. Update Steps");
System.out.println("2. Update Calories");
System.out.println("3. Update Water Intake");
System.out.println("4. View Summary");
System.out.println("5. Exit");
System.out.print("Enter your choice: ");
choice = scanner.nextInt();
This snippet shows how the program presents the menu options to the user.

**How to Run**
Clone or download the repository.
Open the code in a Java IDE (e.g., IntelliJ IDEA, Eclipse).
Compile and run the program.
Use the menu options to log and view fitness data.

**Sample Output**

Health and Fitness Tracker
1. Update Steps
2. Update Calories
3. Update Water Intake
4. View Summary
5. Exit
Enter your choice: 1
Enter steps walked: 3000
Steps updated!

Enter your choice: 4
Fitness Summary:
Steps Walked: 3000
Calories Consumed: 0
Water Intake: 0 ml
Possible Enhancements
Save fitness data permanently using file handling or a database.
Add tracking for additional metrics such as weight, sleep hours, and exercises.
Integrate a graphical user interface (GUI) for better usability.
Include a progress tracker for fitness goals.

**Conclusion**

The Health and Fitness Tracker is a beginner-friendly Java application demonstrating the basics of programming, including object-oriented design, user interaction, and data manipulation. It serves as an excellent foundation for building more advanced health monitoring systems.
