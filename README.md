# Automated snapshots of EBS volumes

*1. Create a role and attach the inline policy which is given in repo - policy.json*<br>

*2. Create the lambda function using python as runtime and attach the role created in the previous step*<br>

*3. Use the lambda function provided in the repo - volume-snapshot.py*<br>

*4. This function will check for any snapshot is already created for a volume if it is created already this function will delete the old version of the snapshot to create the new one. if no snapshot is created yet it will create the new one*<br>

*We can see from the below snap these were the snapshots created at 15:29*<br>

![Alt text](./images/pre-snap.png)

*New version of the snapshot*

![Alt text](./images/snap.png)


