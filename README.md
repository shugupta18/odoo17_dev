
#  Odoo (17) 
## custom_addons

```python
# venv is present
```

```sql
-- use postgres (user)
CREATE DATABASE your_database_name;
CREATE USER your_user WITH PASSWORD 'your_password';
GRANT ALL PRIVILEGES ON DATABASE your_database_name TO your_user;
-- inside the your_database_name db
GRANT ALL PRIVILEGES ON SCHEMA public TO your_user;
```

