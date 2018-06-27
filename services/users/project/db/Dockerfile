FROM postgres

# run create.sql on init
# this extends the official postgres image by adding sql file
# to the /docker-entrypoint-initdb.d directory
# that direcotry executes on init (I guess)
ADD create.sql /docker-entrypoint-initdb.d
