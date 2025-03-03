<h1>Digital Forensics Data Analysis Group Project - Cal Poly Pomona</h1>

<h2>Description</h2>
This project consists of using digital forensics tools to analyze a sector by sectore clone of a hard drive in efforts to locate any evidence that will assist in prosecuting offenses against a suspect named Elvis. These offenses include counterfeiting U.S. currency, counterfeiting U.S. passports, theft of credit card information, and other illegal activities. The project is guided by 15 questions that help target specific pieces of evidence to search for.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Autopsy</b> 
- <b>Windows Registry</b>
- <b>Timeline Tool</b>
- <b>Log Analysis</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program walk-through:</h2>

<b>Part 1</b>
<br />
  
Question 1: Use FTK to create a new case called Lab1. Then add the ID THEFT1.E01image with all processing options except a SHA1hash. 
<br/>

Question 2: Locate the evidence that can assist in prosecuting the following offenses:<br/>
a. Counterfeiting U.S. Currency<br/>
b. Counterfeiting U.S. Passports<br/>
c. Theft of Credit Card Information
<br/>

Question 3: If possible, ascertain if Elvis has any upcoming travel plans. 
<br/>

Question 4: Bookmark and document findings including the registry file analysis in your case report.
<br />

<b>Part 2</b>
<br />

Question 1: Police suspect that Elvis was in possession of illegal MP3 files obtained from an RIAA sting operation. How can you determine if Elvis possessed any of the following files?
<br/>

Question 2: Several paper documents were recovered in Elvis’ locker. Document analysis has begun. What printer was Elvis using?
<br/>

Question 3: Elvis maintained a POP e-mail account with the IRS fake-ID site. Provide evidence of this account as well as the password Elvis was using to access that account. Add this key to the report.
<br/>

Question 4: What was Elvis’ Internet Explorer homepage?
<br/>

Question 5: What was the last location that Elvis downloaded something from using Internet Explorer?
<br/>

Question 6: Add the following to your report:<br/>
a. Internet Explorer Typed URLs<br/>
b. Recent Documents<br/>
c. Run MRU list information<br/>
d. Last visited MRU information<br/>
e. Open Saved MRU information (Open With or Save as Dialog)
<br/>

Question 7: Generate a report based on NTUSER.DAT file. 
<br/>

Question 8: Answer the following questions using the SYSTEM file. <br/>
a. Elvis is known to transport illicit files on portable storage devices. The Pomona PD has several portable storage devices in their possession from Elvis’ school locker. Can you give them any information that can help them determine if Elvis has connected to these portable storage devices?<br/>
b. Elvis’ computer has been attempting to hack several Salt Lake City credit card sites. The event logs continually show a reference to KAL as an incoming computer name. Look for information that supports this and list a location that could be used to corroborate it.
<br/>

Question 9: Generate a report based on the System file. 
<br/>

Question 10: Even though Elvis had his SAM file on this thumb drive, document when Elvis last logged on to his machine using the SAM file. His machine account name is ID THEFT DUDE. Generate a report. 
<br/>
<br/>
Question 11: Generate a report based on the SAM file.
<br/>

<h2>Main Findings</h2>

- Conducted comprehensive forensic analysis of a disk image using Autopsy, focusing on extracting critical evidence in cases of identity theft, credit card fraud, and counterfeit document production.
- Performed file system exploration, recovering deleted and carved files from unallocated space to identify evidence of illegal activity, including counterfeit U.S. currency, counterfeit IDs, and stolen credit card information.
- Tagged and organized evidence by categorizing files related to specific criminal activities, generating detailed forensic reports to support legal investigations.
- Analyzed Internet Explorer’s registry entries to uncover potential travel plans, browsing history, and evidence of fraudulent activity, including accessing phishing sites and fake IDs.
- Investigated the NTUSER.DAT and SYSTEM files to retrieve valuable metadata, identifying user behavior, email addresses associated with identity theft, and forensic evidence from device connections.
- Applied keyword search techniques and the Timeline tool to locate illicit MP3 files, determine printer usage, and recover password data from encrypted email accounts.
- Generated comprehensive reports based on registry analysis, recent document access, and user activity, contributing to successful evidence presentation.
- Applied filtering and timeline tools to track file creation, modification, and deletion events, including analyzing allocated and deleted graphics for investigative insights.

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
