# Experiment-05
# Aim:Study of Dictionary in Python
## Theory:
A dictionary is a collection which is ordered*, changeable and do not allow duplicates. Dictionary items are presented in key:value pairs, where the key acts as a unique identifier for its associated value. Because keys must be unique, providing a duplicate key will simply overwrite the existing value.
To manage this data, you can use the len() function to find the total number of pairs, or use .keys() and .values() to view the specific labels and data stored within. For safe data retrieval, the .get() method is used to access a value without risking a crash if the key is missing, while the .pop() method allows you to remove and return a specific item. If the dictionary contains numerical values, you can even use max() to find the highest value or key.
## Algorithm:
A: Update Product Price
    1)Initialize the dictionary "product" with names as keys and prices as values.
    2)Display the "product" dictionary to show the "Original price".
    3)Update the value of a specific key using the syntax product["Book"] = "55 Rupees".
    4)Display the updated product dictionary.
B: Search Student Marks
    1)Initialize the dictionary "student" with names and marks.
    2)Input a string from the user and store it in the variable name.
    3)Search for the name in the "student" dictionary using the student.get(name,"Student not found" command.
    4)Output the mark if the name exists; otherwise, return the default message "Student not found".
c)User Login Validation
    1)Initialize the dictionary "users" with usernames as keys and passwords as values.
    2)Input data from the user for variables username and password.
    3)Validate by checking if users.get(username) matches the entered password.
    4)If they match, Display "Login successful".
       Else, Display "Invalid username or password".
d)Find Highest Scorer
    1)Initialize the dictionary "student" with student names and their respective marks.
    2)Identify the key with the highest value using max(student, key=student.get) and store it in the variable topper.
    3)Access the score of the topper using the syntax student[topper].
    4)Display the name of the topper and their corresponding marks.
    Dictionaries are used to store data values in key:value pairs. A dictionary is a collection which is ordered*, changeable and does not allow duplicates.  
### Conclusion:
Hence dictionary was implemented in python and operations were done on them.
