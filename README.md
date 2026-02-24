# CreatingSnapshots

Creating Snapshots in AWS

Using the create snapshot wiszard it's easy to create a snapshot of volumes within a cloud environment.  
 
<img width="975" height="477" alt="image" src="https://github.com/user-attachments/assets/30581716-ce7c-46ec-9e8c-ad62a17d3af4" />

Simple process to follow and create and could see what volumes were created.
 
<img width="1063" height="402" alt="image" src="https://github.com/user-attachments/assets/592f8da3-b8ff-4e84-b3f9-d13665fc1fdb" />

I’m going to add the users into the sudo file with no password using the sudo visudo command. Then I’m going to add the users under ec2-user which was the first accounted created when I first created the E2 instance.
 
<img width="975" height="266" alt="image" src="https://github.com/user-attachments/assets/3481cba9-9e1d-4c5a-892d-0c02a19a0705" />

I’m going to make cronjab to shut down the instance every day at 12pm. I would enter us the root user so I would su – into the root user then use the commands to enter the crontab and set the parameters of what I want to accomplish.    

<img width="914" height="1086" alt="image" src="https://github.com/user-attachments/assets/8d0ef60e-882d-4f84-b5fb-b920e708acd3" />

This would shutdown the instances as requested. 

<img width="975" height="79" alt="image" src="https://github.com/user-attachments/assets/3cba0b1c-2b93-4bd3-a302-696f9b3cfc35" />

Going to create a final snapchsot which would include all the changes I have done since the first snapshot I made.
 
<img width="975" height="481" alt="image" src="https://github.com/user-attachments/assets/9ed5e51d-c7ab-4532-9000-616210f28f23" />
