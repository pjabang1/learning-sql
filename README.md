# SQL Tutorial

This SQL tutorial involve creating a databate to manage and report transaction for a container business. We will use the MySQL database management system to structure and store data.

## MySQL 

## Sequel Pro

- To go access sequel pro, go to applications.
- Once opened, enter '127.0.0.1' as host and 'root' as username

## Tutorials

- https://www.w3schools.com/sql/

### Create Database 

```create database gaica;```

### Create Tables 

Think about models in your business example 

### Containers
```
CREATE TABLE containers (
    ContainerId int,
    ContainerName varchar(255),
    LoadDate DATE,
    DepartureDate DATE,
    ArrivalDate DATE,
    Cost decimal(10,2)
);
```

### Items

### Joins

```
select ItemName, ItemQuantity, sum(s.`Quantity`) AS SoldQuantity, ItemQuantity-sum(s.`Quantity`) AS Remaining
from items i
LEFT JOIN sales s ON i.`ItemId` = s.`ItemId` 
GROUP BY 
ItemName, ItemQuantity;
```

- containers : id, name, leave_date, arrival_date
- inventory : 
- inventory_types : 

### Insert Data

### Select Data

#### SQL Joins

### Update Data

### Delete Data

### Apache Nifi Certification



# Python Tutorial

- Example : http://cdn.visualbi.com/wp-content/uploads/tableau-sales-kpi-performance-3-country-analysis.png

# Tableau Tutorial 
