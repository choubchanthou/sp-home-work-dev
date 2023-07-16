# Usage
Step 1: `git clone https://github.com/choubchanthou/sp-home-work-dev.git` 
Step 2: pull submodule `git submodule update --init --recursive`
Step 3: `docker-compose up`
Step 4: init db `docker exec -ti db /opt/mssql-tools/bin/sqlcmd -S localhost -U sa -P Bitc!1234! -d master -i db-init.sql`