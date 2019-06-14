# Json-Parse-for-SQL-Server-version-below-2016
because there's no native function on sql server version below 2016

# How to Use
Show all Json Data :
`select * from dbo.parseJSON(<JSONObject>)`

Show spesific Json Data :
`select StringValue from dbo.parseJSON(<JSONObject>) WHERE NAME = '<DataName>'`
