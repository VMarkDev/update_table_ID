# Update_table_ID
<code>
* SET @newid=0;
* UPDATE tablename SET primary_key_id=(@newid:=@newid+1) ORDER BY primary_key_id;
</code>
