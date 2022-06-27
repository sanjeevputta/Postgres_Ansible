# Postgres_Ansible

*For this first we need one Host VM.
*In that VM Need to install Docker.
*and need to configer ansble and dependency's.

//And need to Go Playbook path in VM
 >>Need to Deploy this Postgress_container.yml using "ansible-playbook Postgress_container.yml"
 >> Here it will create Potgres container for the first step.
 >> and the DB Name as PG_Container.
 >> And next step it will connect to DB as given Cred.
 >> After accessing it will restart the Postgres.

// And the Next step of this is Creing DB back up for Db.
 >>First step is Every 3 hours this task will run.
 >>time stamp for DB_backup
 >>this step creating Back up Directory.
 >>Taking backup of Database
 >>Fetching backup from the server and placing into Destination.
 >>And the file extention in .gz
