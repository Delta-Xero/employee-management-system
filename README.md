# Employee Management System

A simple Python project that demonstrates Object-Oriented Programming (OOP) concepts by modeling an employee management system.

## Features

- Create employees with a name and level
- Automatic base salary assignment
- Property decorators (`@property`)
- Getters and setters
- Input validation
- Prevent invalid promotions
- Prevent demotions
- Prevent selecting the same level
- Custom exceptions with informative messages
- String representation using `__str__` and `__repr__`

## Employee Levels

| Level | Base Salary |
|--------|------------:|
| Trainee | $1000 |
| Junior | $2000 |
| Mid-level | $3000 |
| Senior | $4000 |

## Concepts Demonstrated

- Classes and Objects
- Encapsulation
- Properties
- Getters & Setters
- Validation
- Exception Handling
- Class Attributes
- Instance Attributes
- Special Methods (`__str__`, `__repr__`)
- Object-Oriented Programming (OOP)

## Example

```python
charlie = Employee("Charlie Brown", "trainee")

print(charlie)

charlie.level = "junior"

print(charlie.salary)
```

Output

```
'name' updated to 'Charlie Brown'.
'Charlie Brown' promoted to 'trainee'.
Salary updated to $1000.
Charlie Brown: trainee
'Charlie Brown' promoted to 'junior'.
```

