# MyCake-CMS

This is an CMS backend application. Strapi provides much higher level abstraction, such that developer only need to define what types and data should be exist. This project uses PostgreSQL as main database and storing data from API.

Do be careful as the default API gateway is public, consider the privacy of your data before publicly available. You can set the API gateway into **authenticated**, instead of **public**.

Before running the Strapi CMS, make sure that your local PostgreSQL is set up and have correct host, port, username, password, privilege (access to CRUD), and the database itself. Otherwise, Strapi will throw error.
