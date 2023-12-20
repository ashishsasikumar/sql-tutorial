
# SQL Insert Examples

To insert users into the user table we use SQL like:  
Note replace the values marked in <{}> with real data

```sql
INSERT INTO `tus`.`user`
(`username`, `email`, `password`, `create_time`, `firstname`, `lastname`)
VALUES
(
<{username: }>,
<{email: }>,
<{password: }>,
<{create_time: CURRENT_TIMESTAMP}>,
<{firstname: }>,
<{lastname: }>);
```

```sql
INSERT INTO `tus`.`user` (`username`, `email`, `password`, `firstname`, `lastname`) VALUES
('john.doe', 'john.doe@tus.ie', 'password', 'John', 'Doe'),
('jane.smith', 'jane.smith@tus.ie', 'password', 'Jane', 'Smith'),
('bob.johnson', 'bob.johnson@tus.ie', 'password', 'Bob', 'Johnson'),
('alice.williams', 'alice.williams@tus.ie', 'password', 'Alice', 'Williams'),
('charlie.brown', 'charlie.brown@tus.ie', 'password', 'Charlie', 'Brown');
```