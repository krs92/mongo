# mongo important scripts

Here I will be updating different scripts for mongodb 

This is used for taking backups, creating authentication in docker and such things


# 1. Automating MongoDB Backups


 In order to automate the backup of databases in MongoDB, we'll need to create a shell script that can be run in a Linux cron job. So pick a directory and let's create the script. You can use whatever file editor you choose, I typically use vim. Modify the contents below then copy and paste them to the new file you created.

save in .sh file and chmod +x /home/YourDirectory/mongo_backups.sh

we have a cleanup command that will delete backup files older than 3 days


# 2. Create MongoDb docker with auth 


