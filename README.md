# OPTIMISE YOUR MINECRAFT SERVER WITH USING DATABASE FOR PLUGINS

This guide will focus on the part of using databases in plugins to optimise minecraft server for faster performance

## What database does pterodactyl panel use

Pterodactyl panel supports both MySQL and MariaDB which are popular among using relational database management systems. 
The database schema is designed to accommodate various datat ypes related to server management such as accounts, resouce usage, other configurations.

## Lets learn about MySQL & MariaDB

Before going deep into the stuff its always good to know about what thesse database do.

### MYSQL
It is an open-source relational database managment system developed by oracle corporation. It is widely used for web applications andonline transction processing.

Features:
SQL Support: MySQL supports structured query language for database management,  making it easy to read, write & delete data.

Performance: It is known for its speed and reliablity, making it suitable for high-traffic applications.

Scalability: MySQL can handle large databases and is capable of scaling hrizontally with clustering and replication features.

Security: Offers robust security features, including user authentication and access control.

Common Use Cases:
Opten used in web applications, online transaction systems & data warehousing.

### MARIADB

MariaDB is a fork of MySQL, created by the original developers of MySQL. It is fully open-source and aims to maintain compatibility with MySQL while offering additional features.

Feature:
Capatibility: MariaDB is desgined to be drop-in replacment for MySQL, meaning applications that work with MySQL can typically switch to MariaDB without modification.

Storage Engines: MariaDB includes additional storage engines for improved performance and flexibility.

Performance Improvements: It includes optimizations for queries, indexing & data processing that can lead to daster performance in certain scenerios.

advanced features: MariaDB offers features like dybamic columns, virtual columns * enchanced replication options. 

Now we know what both database do lets start with the real deal which is why should we use database for minecraft plugins