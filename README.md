This Program is designed to calculate Total Marks and CGPA (Cumulative Grade Point Average) for multiple students, considering both core and additional subjects. The program allows the user to input marks for core subjects (CIE, ETE, TW) and additional subjects, validate input values, calculate total marks, and compute CGPA on a scale of 10 for each student. It then displays the individual results and summarizes the academic performance for all students.

##Key Features:
Core and Additional Subjects:
Core subjects have marks distributed across CIE, ETE, and TW.
Additional subjects have marks with different maximum scores.
Input Validation:
The program ensures that the entered marks for each evaluation category are within the valid range.
If invalid marks are entered, the program prompts the user to re-enter the data.
Marks and CGPA Calculation:
Total marks are calculated by summing up the individual marks from all evaluation categories.
CGPA is calculated using a fixed formula based on the total marks obtained and the total credits for both core and additional subjects.
Multi-student Support:
The program can handle data for multiple students, processing each student's input individually and calculating their results.
Detailed Output:
The program displays subject-wise marks, total marks, and CGPA for each student.
After processing all students, it summarizes the results in a final report.
Implementation Details
Constants for Configuration: The program uses predefined constants to manage the number of subjects, maximum marks for different evaluation components, and the allowed sizes for subject names, student names, and roll numbers.
Function to Calculate Marks and CGPA: The calculatemarks function computes the total marks and CGPA for each student based on their input. It sums the marks from all subjects, calculates the total, and computes the CGPA.
Function for Core Subject Marks Input: The inputCoreSubjects function prompts the user to input marks for CIE tools, ETE, and TW for each core subject. It ensures that the entered marks fall within valid ranges.
Function for Additional Subject Marks Input: The inputAdditionalSubjects function collects marks for additional subjects and validates them based on the subject's maximum allowed marks.
Main Program Logic: The main function handles the flow of the program. It first asks for the number of students, then processes each student by collecting their data and calculating their marks and CGPA. After processing all students, it displays a summary of results for each student.
Input and Output: The program uses scanf to collect input data and printf to display results. It asks for subject names, marks for different components, and then shows the total marks and CGPA for each student.
Error Handling: The program includes checks for invalid input. If the number of students is non-positive, or if any mark input is outside the valid range, appropriate error messages are displayed, and the user is prompted to correct their input.
This program allows the input, validation, and calculation of academic results for multiple students, including their core and additional subjects. It is structured to handle a flexible number of students, compute their total marks and CGPA based on predefined evaluation categories, and output detailed and summarized results for all students.
