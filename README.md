## MySQL_notes ##
### Query to counting number of tables of a Database in MySQL?? ###
`SELECT COUNT(*) FROM information_schema.tables WHERE table_schema = 'Database name';`
