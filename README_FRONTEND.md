
## Docker compose up

1. `docker compose up` run it in new terminal
2. Install python packages `python -m pip install -r requirements.txt`
3. Check if psql is installed if not install it `sudo apt update -y && sudo apt install postgresql-client-common postgresql-client-14 -y`.
4. Connect to postgres `psql -h postgres -U postgres`
5. `CREATE USER utodos WITH PASSWORD 'utodos';`
6. `CREATE DATABASE utodos WITH OWNER 'utodos';`
7. Launch frontend `python main.py`
8. Open and play with UI
9. Connect to postgres again and change database to utodos.
10. Use commands \l, \dt, etc 
11. Use \? and \h => Check SQL and psql commands

