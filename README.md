This project demonstrates a producer-consumer management system using gRPC, allowing interaction between producers and consumers.

#Database set up
Database name : grpc
-- Create the 'users' table
CREATE TABLE users (
  username VARCHAR(255),
  password VARCHAR(255)
);

-- Create the 'profiles' table
CREATE TABLE profiles (
  username VARCHAR(255),
  firstname VARCHAR(255),
  lastname VARCHAR(255),
  email VARCHAR(255),
  city VARCHAR(255)
);
