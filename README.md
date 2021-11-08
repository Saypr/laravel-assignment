# Saypr Laravel Assignment

Welcome to Saypr's Laravel test.

### Sharing the code

Please upload your code to GitHub.

### Assignment Details

Project to manage companies and their employees. A mini CRM.

- Basic level authentication
- Use seeders to create users. (One for basic user and one for admin user)
- Admin users can create, list, delete companies
- Basic users shouldn't be able to create, list, delete companies (use middleware)
- CRUD functionality for companies and employees
- Use migrations to create tables
- Store companies logos in storage/app/public folder and make them accessible from public
- Use basic Laravel resource controllers
- Use Laravel's Request classes for validation
- Companies table:
  - id
  - name (required)
  - email
  - logo (minimum 100x100)
  - website
- Employees table:
  - id
  - company_id (foreign key to companies)
  - first_name (required)
  - last_name (required)
  - email

### Deadline

**Deadline for submission:** 2 days

### What are we looking for?

- Ability to start a new project
- Understanding of how middlewares work
- Understanding of how request classes work
- Understanding of how seeders work
- Clean code