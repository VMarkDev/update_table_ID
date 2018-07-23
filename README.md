# Update_table_ID

* You can edit the ID of a table and update numerically and increase +1

SET @newid=0;

UPDATE tablename SET primary_key_id=(@newid:=@newid+1) ORDER BY primary_key_id;
