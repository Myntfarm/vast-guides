# vast-guides
step by step guides for common issues i run into in the vast community discord

# Retrieve Files from Vast Instace
## Easy method - SCP

- Open a SCP client - IE [WinSCP](https://winscp.net/eng/index.php)
- Select Protocal: SCP
- Enter your Vast instance IP and an open port that will accept SSH
- user: root
- Then click on advanced to bring up the menu to upload your ssh key
![image](https://user-images.githubusercontent.com/96462665/228139965-c4f729bd-83e5-4653-84ac-41768c5106f0.png)
- Click on Authentication > click allow agent forwarding > point to your ssh key which the program is expecting in .ppk format (PUTTY)
![image](https://user-images.githubusercontent.com/96462665/228139313-f726164e-4f3d-4a12-8b9d-9b1996d4ad74.png)
