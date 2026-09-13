# Activity-audit

**EXPERIMENT 05 AUDITING CLOUD ACTIVITY USING AWS CLOUDTRAIL**

**NAME: Yaazhini. V**

**REG.NO :212225220124**

**Objective**

To audit and monitor cloud activity in AWS using AWS CloudTrail by viewing and analyzing recorded AWS events and identifying important audit information such as user identity, event name, event time, AWS service, region, and operation status.

**1. Requirements**

•	AWS Account 

•	Web Browser 

•	Internet Connection 

•	Amazon S3 access 

•	AWS CloudTrail 

**PART A — ACCESS AWS CLOUDTRAIL**

Step 1: Login to AWS

1.	Open the AWS Management Console.

2.	Sign in using your AWS account. 

3.	In the AWS search bar, type CloudTrail. 

4.	Select AWS CloudTrail.

<img width="1037" height="492" alt="image" src="https://github.com/user-attachments/assets/6e5c1827-5b20-45fc-955c-9fbb241901e9" />

**Step 2: Open Event History**

1.	In the CloudTrail navigation menu, select Event history. 

2.	CloudTrail displays recent AWS activity. 

3.	Review the available events. 

The Event History page may display information such as:

•	Event time 

•	Username 

•	Event name 

•	Event source 

•	Resource type 

•	Resource name 

<img width="1907" height="797" alt="642637485-c2ca942d-014f-4ea8-a47e-5cf2fd3d8e98" src="https://github.com/user-attachments/assets/9fdeab72-9563-4c1a-ad6e-ed6c0db51318" />

**PART B — ANALYZE A CLOUDTRAIL EVENT**

Step 3: Select an Event

1.	From the Event History list, select an S3-related event. 

2.	Click the event to open its details. 

3.	Examine the event information and the event record/JSON. 

For this experiment, a CreateBucket event can be used.

Step 4: Analyze the CreateBucket Event

The CreateBucket event indicates that an Amazon S3 bucket creation operation occurred.

Record the following information:

<img width="687" height="562" alt="642638124-450cdaa6-5839-4b33-a42f-cb691712bde8" src="https://github.com/user-attachments/assets/c183d4be-2fc2-4268-88c9-b4424a631100" />

Meaning of important fields 

<img width="1145" height="490" alt="642638602-b3f7d99d-6c11-4264-b530-3a94d4f0bdee" src="https://github.com/user-attachments/assets/effdade8-d76f-49bc-ac5f-c6750196bae3" />

<img width="1027" height="477" alt="image" src="https://github.com/user-attachments/assets/9071365c-c81c-4d4c-ad62-79748c3a5c2d" />

**PART C — IDENTIFY ANOTHER CLOUDTRAIL EVENT**

Step 5: Select Another Event

1.	Return to CloudTrail → Event history. 

2.	Select another event. 

3.	Open its details.

4.	Record the important fields.

For example, an event such as:

AutomatedDefaultVpcCreation

may be present.

This event is associated with Amazon EC2.

Step 6: Analyze the Second Event

Record:

<img width="685" height="557" alt="642639785-b452acc4-afa9-46af-a783-9231560256a0" src="https://github.com/user-attachments/assets/ad6dd1fc-3440-4e94-a4cf-346664169d92" />

<img width="1042" height="482" alt="image" src="https://github.com/user-attachments/assets/ad0d02ef-5392-4b38-b6d5-6358a5a16daa" />

**PART D — COMPARE THE EVENTS**

Step 7: Prepare the Audit Comparison

Compare the two CloudTrail events.

<img width="1146" height="532" alt="image" src="https://github.com/user-attachments/assets/d782b36a-0e37-41ec-8fa4-bfe3de1dcf35" />

**PART E — SECURITY AUDIT ANALYSIS**

Step 8: Identify Who, What, When and Where

For each event, identify:

**WHO?**

Who or which identity performed/generated the activity?

**WHAT?**

What AWS operation was performed?

**WHEN?**

At what date and time did the activity occur?

**WHERE?**

In which AWS Region did the activity occur?

**RESULT?**

Was the operation successful or did it generate an error?

**Step 9: Prepare the Final Audit Table**

<img width="1215" height="237" alt="image" src="https://github.com/user-attachments/assets/b041b43d-fe30-42c6-a28f-73c0ad67a02a" />

**RESULT**

The cloud activities in AWS were successfully audited using AWS CloudTrail Event History. Different AWS events were examined based on event time, user identity, event name, event source, AWS Region, read-only status, and error status. The experiment demonstrated how AWS CloudTrail provides an audit trail for monitoring, accountability, and investigation of cloud activities.



