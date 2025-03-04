## User Authentication Module
This module (`auth.py`) allows users to register and log in.

**Features:**
- Register new users
- Log in with a username and password

**Example Usage:**
```python
from auth import Auth
auth = Auth()
auth.register("user", "password")
auth.login("user", "password")
