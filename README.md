# CreatingSnapshots

Creating Snapshots in AWS

Using the create snapchot wiszard its easy to create a snapshot of volumes within the cloud environment.  
 
![Image](https://github.com/user-attachments/assets/12b339a5-a71a-4b86-a748-20b324a12103)

Simple process to follow and create and could see what volumes were created.
 
![Image](https://github.com/user-attachments/assets/d1833284-c9d4-4710-983c-26cd93aa8ee7)


I’m going to add the users into the sudo file with no password using the sudo visudo command. Then I’m going to add the users under ec2-user which was the first accounted created when I first created the E2 instance.
 
![Image](https://github.com/user-attachments/assets/301cfc49-11f3-4e17-9c31-9a9713c51965)




I’m going to make cronjab to shut down the instance every day at 12pm. I would enter us the root user so I would su – into the root user then use the commands to enter the crontab and set the parameters of what I want to accomplish.    

![Image](https://github.com/user-attachments/assets/e2f700db-2124-4855-aadb-8de2433a56bb)


This would shutdown the instances as requested. 

 ![Image](https://github.com/user-attachments/assets/00c32f8d-df73-4745-a61b-4655353ffa04)

Going to create a final snapchsot which would include all the changes I have done since the first snapshot I made.
 
![Image](https://github.com/user-attachments/assets/bdf0a337-d467-441a-8470-2066678bbbb1)
