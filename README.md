# User-Configuration-Manager

### Table of Contents
- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Concepts Used](#concepts-used)
- [Features](#features)
- [Project Requirements](#project-requirements)
- [Key Learning Outcome](#key-learning-outcome)
- [Real World Application](#real-world-application)


### Project Overview
This project is a simple Python-based system that allows users to manage application settings such as theme, language, and notifications. The system supports adding, updating, deleting, and viewing user settings using Python functions and dictionaries. The project was completed as part of the Python Certification on [FreeCodeCamp](https://www.freecodecamp.org/learn/python-v9/lab-user-configuration-manager/build-a-user-configuration-manager).


### Project Objective
The goal of this project is to build a basic configuration manager that:
- Stores user settings in a dictionary
- Allows dynamic updates to settings
- Handles errors for duplicate or missing keys
- Displays settings in a user-friendly format


### Concepts Used
This project makes use of the following:
- Python dictionaries (data storage)
- Tuples (structured input)
- Functions and parameters
- Conditional statements (if, else)
- String formatting (f-strings)
- Data validation and error handling


### Features
1. Add Settings
   - Adds a new key-value pair to the settings dictionary
   - Converts input to lowercase
   - Prevents duplicate keys
  
2. Update Setting
   - Updates the value of an existing setting
   - Returns an error if the setting does not exist
  
3. Delete Setting
   - Removes a setting from the dictionary
   - Handles cases where the key does not exist
  
4. View Settings
   - Displays all settings in a clean format
   - Returns a message if no settings exist
  

### Project Requirements
The following requirements were implemented based on the project instructions:
- Define four functions:
  - add_setting(settings, setting)
  - update_setting(settings, setting)
  - delete_setting(settings, key)
  - view_settings(settings)
 
1. add_setting Function
   - Converts key and value to lowercase
   - Checks if key already exists
   - Adds new setting if key does not exist
   - Returns appropriate success/error messages
  
2. update_setting Function
   - Converts key and value to lowercase
   - Updates existing key
   - Returns error if key does not exist
  
3. delete_setting Function
   - Converts key to lowercase
   - Deletes key if it exists
   - Returns error if key is not found
  
4. view_settings Function
   - Returns "No settings available." if empty
   - Displays all settings with capitalized keys
   - Formats output neatly with line breaks
  

### Key Learning Outcome
This project helped reinforce:
- How data flows from input (tuple) → processing → storage (dictionary)
- How to design reusable functions
- How real-world systems manage user configurations


### Real-World Application
This type of system is commonly used in:
- Mobile app settings
- Web application user preferences
- Dashboard customization in data analytics tools
- Software configuration management systems


