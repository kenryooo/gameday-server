# DB Info

## DB
animal
```sql
CREATE DATABASE `animal`;
```

## Table
- t_animal

### t_animal
| column       | type        | NULL     | memo                      |
|--------------|-------------|----------|---------------------------|
| id           | int         | NOT NULL | Auto Increment            |
| name         | varchar(30) | NOT NULL |                           |
| created_date | datetime    | NOT NULL | Default Current Timestamp |

```sql
CREATE TABLE `t_animal` (
  `id` int NOT NULL AUTO_INCREMENT,
  `name` varchar(30) NOT NULL,
  `created_date` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
  PRIMARY KEY(id)
);
```