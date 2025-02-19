User Creation
User-Class-Methods

This Python project implements a User Management System with classes for managing users, generating user IDs, passwords, and emails.

Classes Overview

User Class
Represents a user with attributes like `user_id`, `name`, `surname`, `email`, `password`, and `birthday`. Methods include:
- `get_details()` – Returns formatted user details.
- `get_age()` – Calculates and returns user's age.

UserService Class
Manages users with methods to:
- `add_user(user)`
- `find_user(user_id)`
- `delete_user(user_id)`
- `update_user(user_id, user_update)`
- `get_number()` – Returns the total number of users.

UserUtil Class
Provides utility methods:
- `generate_user_id()`
- `generate_password()`
- `is_strong_password(password)`
- `generate_email(name, surname, domain)`
- `validate_email(email)`
Sample Input/Output

