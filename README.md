# bioportapp

## Config

Open the config file and adjust the values.

### SD
user: your username

password: your password

database: the database name 

isNewDatabase: should be set to True if the above mentioned is a new database. (with capital T)

port: the port to connect with your stardog server

### ONT
list: python format list with the acronyms of the ontologies to download

graphUriBase: the base URI (ex, urn:dev:, rdfal:develop:, stardog:context:urn:)

### BP
apikey: your Bioportal API key


Be careful not to corrupt an existing databases as it will load the triples without asking.
