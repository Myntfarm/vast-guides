# vast-guides
step by step guides for common issues i run into in the vast community discord

# Retrieve Files from Vast Instace
## Easy method - SCP

- Open a SCP client - IE [WinSCP](https://winscp.net/eng/index.php)
- Select Protocal: SCP
- Enter your Vast instance IP and an open port that will accept SSH
- user: root
- Then click on advanced to bring up the menu to upload your ssh key
- ![image](https://user-images.githubusercontent.com/96462665/228139965-c4f729bd-83e5-4653-84ac-41768c5106f0.png)
- Click on Authentication > click allow agent forwarding > point to your ssh key which the program is expecting in .ppk format (PUTTY)
- ![image](https://user-images.githubusercontent.com/96462665/228139313-f726164e-4f3d-4a12-8b9d-9b1996d4ad74.png)

# Safely take your machine offline
- Navigate to your [machine page](https://cloud.vast.ai/host/machines/) and Unlist.
- ![image](https://user-images.githubusercontent.com/96462665/228146043-92b04ce6-ebff-4b65-9ec9-9ef4c6fa79ed.png)
- Now update and change the expiration date. you Ideally want to schedule down time about once a month.
- ideally you want to give your client as much time as possible i normaly find that 7 days is generaly more than enough
- once you set your expiration date and the date passes you may still see instances stored on your machine
- IE. ![image](https://user-images.githubusercontent.com/96462665/228149028-3fe57fc0-42b5-4f0e-8ff3-614f5213636f.png)
- **YOU MUST WAIT UNTIL THERE ARE NO STORED INSTANCES TO AVOID REPUTATION LOSS**
- IE. ![image](https://user-images.githubusercontent.com/96462665/228149346-aa0c23f3-0d49-4e15-bc1b-c595e3ada8d5.png)
- I have noticed that normally after a day or 2 of a user not being able to start their instance (because it is delisted) most users will tranfers their data to a new instance
- Once there are no running processes (epiration date takes care of this) and once all stored instances have been removed you can safely offline your machine
