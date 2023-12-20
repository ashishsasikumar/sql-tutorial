
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