FROM mongo:5
COPY *.js /docker-entrypoint-initdb.d/

#This variable allows you to specify the name of a database to be used 
#for creation scripts in /docker-entrypoint-initdb.d/*.js (see Initializing a fresh instance below). 
#MongoDB is fundamentally designed for "create on first use", so if you do not insert data with your
# JavaScript files, then no database is created.