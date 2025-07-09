# Cloud_computing_
( https://chatgpt.com/share/6869e4e8-6c50-800d-8441-e9e6d31db1ab)
For S3 Bucket creation if we want to give permission its called so we can give policies if we own the s3 bucket for eg in this screenshot we impliement one policy  ![image](https://github.com/user-attachments/assets/decf15c1-26d9-442e-afdb-ce2253ba0abd) the star*(astrich) mean complete access to the bucekt.the object we want particular object access.
Using S3 Bucket Can i host static website on this Yes we can![image](https://github.com/user-attachments/assets/4b699aae-867d-4c53-8e90-0e163c694b41)
Here we can upload html file 

![image](https://github.com/user-attachments/assets/14893e55-1852-4f52-b170-832b04315449)
So we are getting 404 not found because we did not have data in index.html file so we need to upload the file so we will get output.
Now come to the root user we can able to give other user some permisson using IAM and also we can make some group if they are using same services.![image](https://github.com/user-attachments/assets/8d3f3b6f-8091-4848-b385-86c3a8d28e60)
![image](https://github.com/user-attachments/assets/c1908b0b-164b-4593-a82e-6ccab8738d53)


Amazon CloudWatch --![image](https://github.com/user-attachments/assets/5b1f289e-f84c-4a91-ae6b-c8200ac51dd6)

Cloudwatch is basically a monitoring tool.
first we need to create a alarm and select the metrics in that we need to select cpu utilization![image](https://github.com/user-attachments/assets/45015a07-a1c2-4cb3-9758-2bee6d4cada0)
Then go to ec2 then preinstance ![image](https://github.com/user-attachments/assets/0236260f-b662-44b6-b390-09e25efc8869)
![image](https://github.com/user-attachments/assets/52ed2259-ecc1-4b47-a416-479b1f04d4e1)
So whenever the cpu utilization is greater than or equaltt to 90%  ![image](https://github.com/user-attachments/assets/a0650530-e1f0-4c31-b519-40d7961b5619)
![image](https://github.com/user-attachments/assets/70c7c222-588f-40be-ab7a-78625597342f) We need mostly inalarm mettrics thing
The notification will recive if it hapend ![image](https://github.com/user-attachments/assets/01bc29e0-ece2-4280-abf9-957a9e7f6152)
it will notify to the customer if it crosses 90% to customers![image](https://github.com/user-attachments/assets/690dc682-6603-4bac-a747-55a6ca540793)

After this we have machine learning services as well There are some three amount of Services AmazonTrextract![image](https://github.com/user-attachments/assets/99b3150d-d892-4ddb-b558-72de6af3f279) Texttract whenever you getting date from scanned document in those case we can start extracting the data from any document we can extract that Automating with maching learning modules.
,AmazonTranscribe,AmazonTranslate

AmazonTextract ![image](https://github.com/user-attachments/assets/1de3e4ad-7be5-4310-8f14-5dcd3d5ce806)

AmazonTranscribe- like speaking yourself ![image](https://github.com/user-attachments/assets/6ba77b6f-ab29-4d2f-bb5c-53ebc9c145a6)
AmazonTranslate - Whatever the text we have we caan convet that![image](https://github.com/user-attachments/assets/72b13e89-177a-4040-8748-c226cf5ecb36)

Cloud Computing - 7 July
Databases Topic SQL & NOSQL Databases
IN
![image](https://github.com/user-attachments/assets/e92b13f0-da1b-412e-961f-48e86dd87466)
![image](https://github.com/user-attachments/assets/0acba91c-9263-4c6d-9fec-c52328ff9ef4)
![image](https://github.com/user-attachments/assets/c6c81ccd-088c-46d7-93b0-673bd71375f3)

![image](https://github.com/user-attachments/assets/b5a33421-a2c3-432c-8042-f9a41a646d46)
![image](https://github.com/user-attachments/assets/d9bbca1a-ac03-480b-9c78-20ff0c25b5a6)

![image](https://github.com/user-attachments/assets/810f229d-e31d-4b94-91e1-3739e2168a40)
![image](https://github.com/user-attachments/assets/7f6205a1-4d28-4d9b-93c5-47eef63ca6ef)
![image](https://github.com/user-attachments/assets/41a45262-8a0e-4170-b806-24883d3762e7)
![image](https://github.com/user-attachments/assets/2500432c-0bdb-46e5-90f9-9bddc1b2b035)
![image](https://github.com/user-attachments/assets/ecadb445-2807-48a2-8072-cbd86e85d4b0)
![image](https://github.com/user-attachments/assets/b1a7a645-06bb-456f-9236-b2fbf7d20a91)


------2nd session same class 


![image](https://github.com/user-attachments/assets/8a04feb9-f8f9-4145-96ee-bdfe44f87276)

Creating of mongoDB

![image](https://github.com/user-attachments/assets/d509f46c-f7d3-4aa0-87b1-1e351ac9502c)

In MongoDB what is the use of creating items

![image](https://github.com/user-attachments/assets/cf42301d-f626-4da7-b98d-f1e128597320)
in this we can run all or if we want to run specific we can mention that also for creating tables

So if we want to create global tables ![image](https://github.com/user-attachments/assets/91748455-85ba-4cb4-8349-0a2e1971b4e3) go to replica so we can create different region also available ![image](https://github.com/user-attachments/assets/6dd36d56-411c-4b48-8f13-b2ad3baac944)

Coming to backups so there are two kind of backup ![image](https://github.com/user-attachments/assets/1f07701c-6011-495b-9eda-8f0bf4e241ee)
1.Create on-demand Backup 2. Schedule Backup  1. if we click 1st As of now at this moment the backup would be created.2. It is fixed time of amount we will have the particular so we can take backup specific amount of time only we can backup.

Exports and Streams![image](https://github.com/user-attachments/assets/a2193d7f-1c21-42e0-8c3a-9d90c9e23786)
Full Exports means As of now whatever the data is there we can able to create a particular table and we can export all the data at the same time.Incremeental data After full export whatever the data is there we willl be able to send only specific data .
![image](https://github.com/user-attachments/assets/6faab5da-7c47-4371-97eb-cd43f2526503)

To Create SQL Database we need to ![image](https://github.com/user-attachments/assets/baeaa0bc-9299-41c0-b65c-8ad81a5ea432)
![image](https://github.com/user-attachments/assets/36c86962-a4b3-4976-ade1-6987ec4a1b89)
![image](https://github.com/user-attachments/assets/0024f62b-c860-492d-9e89-6799d68276a7) go for free if u want to do\
![image](https://github.com/user-attachments/assets/233394cd-dbee-48b4-8051-2ee4be2ca387)
![image](https://github.com/user-attachments/assets/e025e205-9929-4a35-b902-cf1513cf8256)

Done created sql ![image](https://github.com/user-attachments/assets/86b6b1ef-eb55-44c6-a530-4bc3e4b31b2b)
copy the endpoint ![image](https://github.com/user-attachments/assets/000de181-fcb8-4ce5-822e-20be26f9d735)
USing endpoint we can make a connection with sql![image](https://github.com/user-attachments/assets/cdc701ee-9d57-4f15-afd2-fe1114c55552)
in hostname we need to give endpoint capy nd paste then admin name and password whatever we gave
He told we will discuss vpc and lambda function tommorow
,

Day- 08/07/2025

Lamda Function-  It is a serverless function
So the customer requreiment is there whenever he using the data and store the data in S3 it should automatically the data will save aswell in DB also. SO it wont do automatically we need to use the lamda function to trigger the thing whenever the customer uploading data in S3 the lambda function trigger aswell..
![image](https://github.com/user-attachments/assets/cd6b8602-ffe9-463b-82a2-eb5b18368497)
![image](https://github.com/user-attachments/assets/78818d5e-8007-4ebd-9889-e3788ef885c6)

We creating lambda function through pythong and then we need to make that like we need to display that URL and bind them ![image](https://github.com/user-attachments/assets/93b16ae0-3286-416f-a910-5c995dd8547e) 
The next Service is Simple Notification Service (SNS) - COncept is any doing transaction,upi automatically we get notificatioon from service provider .
  In this We have some terminology ![image](https://github.com/user-attachments/assets/139d067f-5075-4013-a408-446da06d9cf7)
SNS follows PUB/ SUB/ model where we can able to pulish and subscribe.

VPC - Virtual private CLoud -> Where you are creating deticated network for our organization inside the network we can isolate that among the organization
Using this vpc we can created subnet For eg if we have big network we divinding the give small small network

Now we see practical way to create lamda--![image](https://github.com/user-attachments/assets/e337a47f-ed83-4984-b660-aca0513d1c81)
![image](https://github.com/user-attachments/assets/48d3f91d-5038-4bbd-a852-fd4ac8db76da)
RunTime means - In which particula program environment we need to run the program we chosse pythong![image](https://github.com/user-attachments/assets/716a7e9f-8d8f-4ffb-a604-dad14f3c7374)
Created -![image](https://github.com/user-attachments/assets/994a25e7-544d-4253-b653-bdff3127f543)
ARN -Amazon resourse Number, where we can actually have unique number. Throttle - suddenly if we want to stop the function afterwards we can download that.Add Destination - This function is running or not if we want to add the comments we can add the destination on failure what need to do on success what i actually need to do.Add Trigger-  This function want to trigger with which suface we want to inititalize the API Gateway so this function want to trigger with API gateway service aswell. Versions- ![image](https://github.com/user-attachments/assets/cecdca23-66a4-49f5-9fe5-43c45b4775f1)
whenever we write the code we can publish code as well so thats called as publish a new version. Allias -creating a alternative name for our function.Configuration - how much memory we required![image](https://github.com/user-attachments/assets/d5e93b5b-ce40-4e84-81e2-43deae96cf8d) we can edit that how much wee need.![image](https://github.com/user-attachments/assets/b379293a-663d-4e69-812e-f1f5a2e6df13)
Triggers - When we are creating functions automatically they will be able trigger other services aswell
Permissions- We can manage the permission aswell![image](https://github.com/user-attachments/assets/20c5f397-258a-4bfa-b38d-b7d9dcbb5c2c)

![image](https://github.com/user-attachments/assets/194d5d68-e4db-4350-a11e-95cbb215dec7) This is the code for lamda function  if u want to see the output we can select the Test icon.Now go to the test option here we need to create a new even ,name it and save.Now test it,![image](https://github.com/user-attachments/assets/09eaa8be-3f75-4c28-a4bc-abd07e1d4229)
So if you want this ouutput in to open in URL go to ->ADD Trigger ->Select source->API Gateway-> HTTP Gateway ->security should be open _.> now save![image](https://github.com/user-attachments/assets/db7e43c1-8232-41b3-8a82-85a33833971d)
If uou want to check go to the trigger ![image](https://github.com/user-attachments/assets/4a7d2950-79c8-49ff-9ec2-e2d351b12eed) and select URL then u will able to see that output.![image](https://github.com/user-attachments/assets/66974b48-710d-4370-a947-b970e156d2da)

---SNS Services->
![image](https://github.com/user-attachments/assets/0b11a9b5-6191-41be-9d0d-5b719381807c)
![image](https://github.com/user-attachments/assets/5a57bf59-f825-4fad-9a08-f293f5981a3e)
![image](https://github.com/user-attachments/assets/64ecc469-ee4a-4d5c-85d1-7a89a9748070) Here we can create subsciption ![image](https://github.com/user-attachments/assets/897de3ed-7efc-4b1e-9c27-8071253c906e) 
SO if you want to give message to subscriber ![image](https://github.com/user-attachments/assets/ed2564b0-5701-44d6-a96f-641712439b64) --> click snsdemo-->![image](https://github.com/user-attachments/assets/29738959-e1e0-47b5-882a-0d378bf88092) --> here u can mention ![image](https://github.com/user-attachments/assets/2ca313e7-b751-46d7-adb0-01b5e197ec31) Now to go to lambda function and refresh now we can sns functions![image](https://github.com/user-attachments/assets/7c5998bf-9816-4081-90af-66b2e768634b) This is how u mangae subsiber function







