# Webshop-backend
This is the backend of a webshop that was made for Delaware as a student project.

The corresponding frontend can be found [here](https://github.com/LaurensDM/Webshop-frontend)

## Technologies

The main technologies used in this project are:
  - Yarn
  - KoaJS
  - KnexJS
  - Multer
  - Jsonwebtoken
  - MySql
  - socket.io

## Summary

This backend is a RESTFUL API using koajs as a nodejs framework.

These are the several api endpoints:

  - /api/category
  - /api/company
  - /api/delivery
  - /api/health
  - /api/notifications
  - /api/order
  - /api/packaging
  - /api/product
  - /api/user

Authorization and authentication is configured with jsonwebtokens. Passwords are saved as a salted hash in the database using sha256 protocol.

Connection with the MySQL database and queries are executed using knexjs.

A socket is running to periodically fetch and send notification data to the frontend. 
