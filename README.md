INTRODUCTION

The Meteor Minds App is a native Android app developed in Kotlin, designed to provide users with a simple and intuitive way to view weekly weather conditions. The app allows users to view the average temperature for the week, as well as detailed information for each day, including minimum and maximum temperatures, and weather conditions.

FEATURES

Splash screen with app logo and navigation options
Main screen displaying average temperature for the week
Detailed view screen displaying daily weather information
Navigation buttons for smooth transitions between screens
Error handling for input errors
Data storage using parallel arrays
Loop calculation for average temperature
USAGE

Launch the app and navigate to the Main screen
View the average temperature for the week
Tap the "Detailed View" button to view daily weather information
Tap the "Back" button to navigate back to the Main screen
Tap the "Clear Input" button to clear user input and re-input data
DEVELOPMENT

The app was developed using Android Studio and Kotlin programming language. The app utilizes parallel arrays for data storage and loop calculation for average temperature.

UTILIZATION OF GITHUB AND GITHUB ACTIONS

The development process of the Meteor Minds App benefited greatly from the use of GitHub and GitHub Actions. Version Control: GitHub served as a central repository for storing and managing the app's source code, allowing multiple developers to collaborate on the project simultaneously. Branching Strategy: Branches were utilized for feature development and bug fixes, enabling parallel development without interfering with the main codebase. Code Review: Pull requests were used for code review, facilitating collaboration and ensuring that changes met quality standards before being merged into the main branch. Continuous Integration: GitHub Actions were implemented for automated testing and building, enhancing the reliability and maintainability of the app. CI pipelines were set up to automatically run tests and generate build artifacts upon each commit, reducing the risk of regressions and ensuring that the app functions as intended

CODE STYLE AND FEATURES The development of the app leverages Kotlin’s object-oriented programming capabilities and the Android development framework (Kotlin, n.d; Android Studio, n.d). The app utilizes several programming concepts to provide a smooth user experience (Kotlin, n.d.).


PSEUDOCODE // IIE, 2024

1. Start

2. Display Splash Screen:
   - Show app name, developer's name, and student number.
   - Display a logo.
   - Provide options to navigate to the Main Screen or exit the app.

3. Main Screen:
   - Display input fields for the user to enter temperature and weather condition for each day of the week.
   - Display a button to input data.
   - Display a button to clear input data.
   - Display a button to view detailed information.
   - Display the average temperature for the week.

4. Detailed View Screen:
   - Display detailed information for each day's temperature and weather condition.
   - Display a button to navigate back to the Main Screen.

5. Input Data:
   a. When the user clicks on the input button:
      - Get input data (temperature and weather condition) from the user.
      - Validate the input data.
      - If input is valid:
         - Store the input data in arrays.
         - Calculate and display the average temperature for the week.
      - If input is not valid:
         - Display an error message.

6. Clear Input Data:
   a. When the user clicks on the clear input button:
      - Clear all input data from the arrays.
      - Reset the average temperature to N/A.

7. View Detailed Information:
   a. When the user clicks on the detailed view button:
      - Navigate to the Detailed View Screen.
      - Pass the input data arrays to the Detailed View Screen.

8. Detailed View:
   - Display detailed information for each day's temperature and weather condition.
   - Display a button to navigate back to the Main Screen.

9. End


REFERENCING LIST:

Kotlin Programming Language. (n.d.). toIntOrNull - Kotlin Programming Language. [Online] Available at: https://kotlinlang.org/api/latest/ivn/stdlib/kotlin.text/to-int-or-null.html. [Accessed 31 Mar. 2024].

Kotlin Programming Language. (n.d.). isNotEmpty - Kotlin Programming Language. [Online] Available at: https://kotlinlang.org/api/latest/ivm/stdlib/kotlin.collections/is-not-empty.html. [Accessed 31 Mar. 2024].

Stack Overflow. (n.d.). Android findViewById() in Custom View. [Online] Available at: https://stackoverflow.com/questions/18508354/android-findviewbyid-in-custom-view. [Accessed 31 Mar. 2024]

Stack Overflow. (n.d.). Clear text in EditText when entered. [Online] Available at: https://stackoverflow.com/questions/5308200/clear-text-in-edittext-when-entered.[Accessed 31 Mar. 2024].

The IIE. (2024). Introduction to Mobile Application Development [IMAD5112/d/p/w] • The Independent Institution of Education: Unpublished [Accessed 31 Mar. 2024].
