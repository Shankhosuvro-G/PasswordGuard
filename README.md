# PasswordGuard

Fortifypass is a Python library for evaluating password strength and estimating cracking time.

## Features

- Assess password strength based on length, character sets, and common patterns.
- Estimate the time required to crack a password using brute-force methods.
- Enhance security measures in applications by ensuring stronger passwords.

## Installation

You can install PasswordGuard using pip:

```bash
pip install passwordguard
```

## Usage  
from passwordguard import calculate_password_strength, calculate_cracking_time  
password = "MyStrongPassword123!"  
strength = calculate_password_strength(password)  
cracking_time = calculate_cracking_time(password)  
print(f"Password: {password}")  
print(f"Strength: {strength}")  
print(f"Estimated cracking time: {cracking_time}")  

## License
This project is licensed under the MIT License - see the LICENSE file for details.
