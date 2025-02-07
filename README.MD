# FIREBASE 2.5 DOCKER CONTAINER

## Setup
1. Copy the <yourdatabase.fdb> fixture to the `./data` directory.
2. copy the `.sample-env` to `.env` and fill in the desired values
3. Build the docker image `docker compose build firebird`
4. Start the server `docker compose up firebird`

## Connect

- Port: 3050
- Username: SYSDBA
- Password: ISC_PASSWORD value that you sent in your .env file
- Database: /firebird/data/<yourdatabase.fdb>


