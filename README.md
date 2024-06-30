# What was the problem you were solving in the projects for this course?

The problem was to develop a program that manages course information, including course numbers, names, and prerequisites, and allows users to interact with this data through a menu-driven interface. The solution needed to efficiently handle tasks like reading data from a file, validating prerequisites, searching for specific courses, and displaying course information.

# How did you approach the problem? Consider why data structures are important to understand.

I approached the problem by:
1. Defining the course structure using a struct to encapsulate course information.
2. Implementing functions to read data from a file, parse lines into course objects, and validate prerequisites.
3. Exploring different data structures (vector, hash table, and tree) to manage the courses, evaluating their advantages and disadvantages.
4. Using a menu-driven interface to interact with the data.

Understanding data structures is crucial as they directly impact the efficiency of the program. Choosing the appropriate data structure ensures optimal performance for operations like insertion, search, and validation.

# How did you overcome any roadblocks you encountered while going through the activities or project?

Roadblocks and solutions included:
1. **File Reading Issues**: Ensured proper error handling to manage file I/O operations.
2. **Data Validation**: Developed a robust validation function to check prerequisites, ensuring all courses referenced as prerequisites existed.
3. **Efficiency Concerns**: Evaluated and implemented different data structures (vector, hash table, tree) to improve the performance of various operations.
4. **Complexity Management**: Broke down the problem into smaller functions to make the code modular and manageable.

# How has your work on this project expanded your approach to designing software and developing programs?

This project expanded my approach by:
1. Highlighting the importance of choosing the right data structure based on the problem requirements.
2. Emphasizing the need for modular design, breaking down the problem into smaller, manageable functions.
3. Enhancing my ability to write efficient and scalable code by considering both time and space complexities.
4. Reinforcing the practice of thorough validation and error handling to ensure robustness.

# How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?

My work evolved by:
1. **Maintainability**: Writing modular functions with clear responsibilities, making it easier to update and maintain the code.
2. **Readability**: Following consistent coding standards and using meaningful variable and function names to enhance code readability.
3. **Adaptability**: Designing the program to be flexible, allowing easy modifications to accommodate changes in requirements or data structures.
4. **Documentation**: Including comments and documentation to explain the purpose and functionality of different parts of the code, aiding future developers in understanding and maintaining the codebase.


# What was the problem you were solving in the projects for this course?

The problem was to create a course planner program in C++ that can read course data from a file, store it in an appropriate data structure, and provide functionalities to display all courses in alphanumeric order and show detailed information about a specific course, including its prerequisites.

# How did you approach the problem? Consider why data structures are important to understand.

I approached the problem by:
1. Designing a `Course` class to encapsulate the course information.
2. Using a `map` data structure to store the courses, with the course ID as the key and the `Course` object as the value.
3. Implementing functions to load the data from a file, print the list of courses in order, and display information about a specific course.
4. Creating a menu-driven interface to interact with the user and provide the required functionalities.

Data structures are important because they define the way data is organized, stored, and accessed in memory. Choosing the right data structure ensures efficient performance for operations like insertion, search, and retrieval, which is crucial for the responsiveness and scalability of the program.

# How did you overcome any roadblocks you encountered while going through the activities or project?

Roadblocks and solutions included:
1. **File I/O Handling**: Initially faced issues with file handling. Solved this by ensuring proper error checking and using `ifstream` for reading files.
2. **Data Parsing**: Encountered difficulties in parsing lines correctly. Addressed this by using `stringstream` to split lines based on commas and handle multiple prerequisites.
3. **Data Storage and Retrieval**: Needed to choose an efficient way to store and retrieve course data. Opted for a `map` data structure for its O(1) average time complexity for lookups.

# How has your work on this project expanded your approach to designing software and developing programs?

This project expanded my approach by:
1. Emphasizing the importance of modular design, where each function has a single responsibility, making the code more organized and easier to manage.
2. Highlighting the need for thorough testing and validation, especially when handling file I/O and user input.
3. Reinforcing the practice of using appropriate data structures to optimize the performance and efficiency of the program.
4. Encouraging the use of clear and concise documentation to explain the purpose and functionality of different parts of the code.

# How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?

My work evolved by:
1. **Maintainability**: Writing clean, modular functions with clear responsibilities, making it easier to update and maintain the codebase.
2. **Readability**: Following consistent coding standards and using descriptive variable and function names to enhance code readability.
3. **Adaptability**: Designing the program to be flexible, allowing for easy modifications to accommodate new requirements or changes in data structure.
4. **Error Handling**: Implementing robust error handling to manage unexpected situations gracefully, improving the program's reliability.
5. **User Interaction**: Developing a user-friendly menu-driven interface to ensure smooth and intuitive user interaction with the program.
