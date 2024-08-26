# Incident-Response-and-Forensics-Autopsy

## Personal Project Report: Investigating an Employee Data Leak Using Autopsy
Introduction.

In this project, I investigated a case where an employee was suspected of leaking private company data. The investigation involved analyzing artifacts from a disk image using the Autopsy digital forensics tool. The goal was to uncover evidence that would either confirm or refute the suspicion. This report details my findings, the steps I took during the investigation, and the lessons I learned.
Task 2: Workflow Overview and Case Analysis

### 1. What is the file extension of the Autopsy files?

    Answer: .aut

### Task 3: Data Sources

#### 1. What is the disk image name of the “e01” format?

    Answer: EnCase

### Task 5: The User Interface I

#### 1. Expand the “Data Sources” option; what is the number of available sources?

![image](https://github.com/user-attachments/assets/108c8d81-838e-48cb-93a5-6c79731e0d6a)

    Answer: 4

#### 2. What is the number of the detected “Removed” files?

![image](https://github.com/user-attachments/assets/c263c940-c53d-428d-a592-80611bf2c198)

    Answer: 10

#### 3. What is the filename found under the “Interesting Files” section?

![image](https://github.com/user-attachments/assets/684a53dd-8c27-46e0-bc5a-0bdb7f7c6c3c)

    Answer: googledrivesync.exe

### Task 6: The User Interface II

#### 1. What is the full name of the operating system version?

![image](https://github.com/user-attachments/assets/efc9cb55-e941-4dda-81fe-fdbae9bafe07)

    Answer: Windows 7 Ultimate Service Pack 1

#### 2. What percentage of the drive are documents?

![image](https://github.com/user-attachments/assets/184546dd-6c45-474f-bd1b-b3dd4f342baf)



    Answer: 40.8%

#### 3. Generate an HTML report as shown in the task and view the “Case Summary” section. What is the job number of the “Interesting Files Identifier” module?

![image](https://github.com/user-attachments/assets/ab829d7a-fa8f-4862-b3e7-ad900b8305f2)

![image](https://github.com/user-attachments/assets/3d0ca5ed-9459-4a0d-89da-1c06cca90834)

![image](https://github.com/user-attachments/assets/b0b0bb4e-71ad-46ca-b0c7-fd6987c7be52)

    Answer: 10

### Task 7: Data Analysis

Mini Scenario: An employee was suspected of leaking company data. A disk image was retrieved from the machine. I was assigned to perform the initial analysis to determine if there was any evidence of data leakage. Based on my findings, further actions would be taken.

#### 1. What is the name of an installed program with the version number of 6.2.0.2962?

![image](https://github.com/user-attachments/assets/ba229817-da60-4842-8608-f54a4336e220)

![image](https://github.com/user-attachments/assets/bd66234e-9b79-4661-8aae-a3cb7d511d7a)

    Answer: Eraser.

#### 2. A user has a Password Hint. What is the value?

![image](https://github.com/user-attachments/assets/42394303-6654-400c-b63e-2f8de94fef9f)

    Answer: IAMAN

#### 3. Numerous SECRET files were accessed from a network drive. What was the IP address?

![image](https://github.com/user-attachments/assets/1bc29cd4-f200-48f8-9536-17e73f631a59)

![image](https://github.com/user-attachments/assets/87c5af5a-09da-4313-9835-83465140488d)

    Answer: 10.11.11.128

#### 4. What web search term has the most entries?

![image](https://github.com/user-attachments/assets/8b0da429-6996-43a0-85a8-ee8e1b30da63)

![image](https://github.com/user-attachments/assets/2cb640fd-d2f4-4bcb-a78c-aec79326563c)

    Answer: information leakage cases.

#### 5. What was the web search conducted on 3/25/2015 21:46:44?

![image](https://github.com/user-attachments/assets/600b8422-58fc-4796-9b2b-225bbcdda3e3)

    Answer: anti-forensic tools

#### 6. What MD5 hash value of the binary is listed as an Interesting File?

![image](https://github.com/user-attachments/assets/2107d0c4-416c-4ec9-a50a-8639d641881e)

![image](https://github.com/user-attachments/assets/b63fac70-eb84-4342-a7c3-afdad46161fa)

    Answer: fe18b02e890f7a789c576be8abccdc99

#### 7. What self-assuring message did the ‘Informant’ write for himself on a Sticky Note?

![image](https://github.com/user-attachments/assets/da876720-244a-462e-abac-70be5d64d3eb)

![image](https://github.com/user-attachments/assets/3b7a6bf6-f907-4633-bf24-693aa3c32276)

    Answer: Tomorrow… Everything will be OK…

### Task 8: Visualization Tools

#### 1. Using the Timeline, how many results were there on 2015–01–12?

![image](https://github.com/user-attachments/assets/c56423e5-2a42-44bf-9e8c-0dfa41cfe774)

![image](https://github.com/user-attachments/assets/3c72f697-c37c-42ec-b819-ad98a8e640fe)

![image](https://github.com/user-attachments/assets/7087c03b-aa7b-4f51-8cf3-d196aa6e2482)

![image](https://github.com/user-attachments/assets/971f2301-552b-413f-842d-dd358589861e)

    Answer: 46

#### 2. The majority of file events occurred on what date?

![image](https://github.com/user-attachments/assets/8ca8de29-fc37-44fd-bf67-308c9dc22ef8)

![image](https://github.com/user-attachments/assets/bd85b1f0-971a-4ef8-af17-fa80a3f65afa)

![image](https://github.com/user-attachments/assets/6c9c18a1-93cc-400c-9c1f-4eb48a73b08e)

![image](https://github.com/user-attachments/assets/577dff92-b8ab-42cc-b3c5-8faae791e452)

![image](https://github.com/user-attachments/assets/1f65f93c-cb04-4bd3-bcba-b7a0f5caa9b0)

    Answer: March 25, 2015

### Conclusion

The investigation into the suspected employee provided significant insights into the use of Autopsy for digital forensics. Through detailed analysis of the disk image, I was able to uncover various artifacts, including the use of a secure network drive to access SECRET files, suspicious web searches related to anti-forensic tools, and the presence of a program called Eraser, which could be used to securely delete files. These findings suggest that the employee may have been involved in data leakage activities.
Experience Gained

### Forensic Investigation: 

I gained hands-on experience in conducting a forensic investigation using Autopsy, from analyzing disk images to uncovering key evidence.
Data Analysis: I improved my skills in analyzing digital artifacts, such as web search histories, file removals, and installed programs, which are crucial in digital forensics.
Problem Solving: The challenges I faced, especially in locating specific artifacts and generating reports, honed my problem-solving abilities and underscored the importance of persistence and attention to detail in forensic investigations.

### Benefits

 Enhanced Skills: This project significantly enhanced my digital forensics skills, especially in the use of Autopsy for investigating disk images and analyzing complex data sets.
 Practical Experience: By working on a realistic scenario, I gained practical experience that will be invaluable in my career as a cybersecurity analyst.
 Critical Thinking: The need to think critically and solve problems under pressure has prepared me for real-world challenges in the field of digital forensics.

This project has brought me closer to completing the SOC Level 1 path, and I am eager to apply the knowledge and skills gained to future investigations and challenges.
