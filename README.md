# Analyzing-File-Based-Viruses-Using-VirusTotal
Analyzing potential indicators to determine the type of attack

Description: Virus Total is a free online service that analyzes files and URLs to identify potential malware. Virus Total combines 70 antivirus scanners and URL/domain blacklisting services along with other tools to identify malware. A wide range of files can be submitted to VirusTotal for examination, such as user data files and documents, executable programs, PDFs, and images. One of the uses of Virus Total is to provide a “second opinion” on a file or URL that may have been flagged as suspicious by other scanning software. In this project, you use VirusTotal to scan a file and a URL.
1.	First view several viruses from 20 years ago and observe their benign but annoying impact. Open your web browser and enter the url archive.org/details/malwaremuseum&tab=collection (if you are no longer able to access the site through the web address, use a search engine to search for “Malware Museum”).
   <img width="442" height="174" alt="image" src="https://github.com/user-attachments/assets/9d32422c-0b5f-41b0-a53f-d457ff72a7a1" />
    
2.	All of the viruses have been rendered ineffective and will not harm a computer. click several of the viruses and notice what they do.
 
<img width="468" height="218" alt="image" src="https://github.com/user-attachments/assets/54ccb93e-a26a-4368-93e3-14a611daea49" />
<img width="468" height="265" alt="image" src="https://github.com/user-attachments/assets/4865f9b4-84a1-4bbc-b043-fbe3a1bac501" />

 
3.	When finished, close your web browser.
4.	Use Microsoft Word to create a document that contains the preceding paragraph description about VirusTotal. Save the document as VirusTotal.docx.
 <img width="450" height="116" alt="image" src="https://github.com/user-attachments/assets/0aaae36f-0ef8-45b1-a714-fc26e09ba548" />

5.	Exit Word.
6.	Open your web browser and enter the URL www.virustotal.com (if you are no longer able to access the site through the web address, use a search engine to search for “Virus Total”).
<img width="468" height="176" alt="image" src="https://github.com/user-attachments/assets/4f501a4c-5ad4-4fab-9168-e93fcec1935b" />
 
7.	If necessary, click the File tab.
8.	Click Choose File.
 <img width="468" height="167" alt="image" src="https://github.com/user-attachments/assets/ab54ab4a-c45d-4210-b992-b3c1501cec45" />

9.	Navigate to the location of VirusTotal.docx and click Open.
<img width="432" height="223" alt="image" src="https://github.com/user-attachments/assets/2dec00e2-8242-4b37-867f-7c2551e71009" />

10.	Click Confirm upload.
11.	Wait until the upload and analysis are completed.
12.	Scroll through the list of antivirus (AV) vendors that have been polled regarding this file. A green checkmark means no malware was detected.
       
<img width="468" height="279" alt="image" src="https://github.com/user-attachments/assets/f4f8baa0-fdb9-4487-a1e6-2617e538cfe9" />

13.	Click the DETAILS tab and read through the analysis.
 <img width="468" height="235" alt="image" src="https://github.com/user-attachments/assets/9fd67c3d-ed30-42e0-a9cc-9e41ed1d55cd" />
  <img width="468" height="279" alt="image" src="https://github.com/user-attachments/assets/f7337e01-856d-4222-a30c-0ae40695dcaf" />
   
 
14.	Use your browser’s back button to return to the Virus Total home page.
15.	Now you will analyze a website. Click URL.
 <img width="468" height="166" alt="image" src="https://github.com/user-attachments/assets/3dec5bca-0917-45bd-8b7f-24a35710f600" />

16.	Enter the url of your school, place of employment, or another site with which you are familiar.
 <img width="468" height="192" alt="image" src="https://github.com/user-attachments/assets/c152ebb7-6a16-44b3-b148-feb7c8d070e0" />

17.	Wait until the analysis is completed.
 <img width="468" height="177" alt="image" src="https://github.com/user-attachments/assets/60e436f5-59f2-4709-b2e1-373f744c9e7e" />

18.	Click the DETAILS tab and read through the analysis.
 <img width="468" height="194" alt="image" src="https://github.com/user-attachments/assets/1c7cf463-3246-4fff-a24c-2c01562bc5f5" />


19.	Click scroll through the list of vendor analysis. do any of these sites indicate Unrated site or Malware site? 
 <img width="430" height="152" alt="image" src="https://github.com/user-attachments/assets/c6844165-59ed-458f-ab7b-df132df46c5d" />

20.	How could VirusTotal be useful to users? how could it be useful to security researchers? Could it also be used by attackers to test their own malware before distributing it to ensure that it does not trigger an AV alert? What should be the protections against this?

•	VirusTotal can assist in detecting malicious content as well as identifying false positives, which are normal and harmless items that have been flagged as malicious by one or more scanners. VirusTotal is an internet-based tool for inspecting uploaded files. Scanning is used to detect viruses and malware. Furthermore, the tool can scan URLs or domains for viruses. The content is scanned by 70 antivirus scanners. As a result, users should scan for potential infections that antivirus software may have missed.
•	VirusTotal is useful for security researchers because it allows them to inspect the security of files. 
•	Attackers frequently abuse the virus scanning tool. Because they are modifying their own attacks through viruses, they must test them before distributing them to ensure that malwares are successfully launched in the targeted systems. These tools will help them ensure that their malicious file or link is not detected by detection software. Using the virustotal tool to test it will allow their product to pass undetected.
•	The software has the potential to be misused. Attackers may take advantage of the tool in order to gain access to the virus models contained in the uploaded files. In this case, security policies should be put in place to prevent them from uploading files in order to confirm the virus forms that are available. As a result, they may abuse it.
21.	Close all windows.


## Project 3-2: analyze Virus File Using VirusTotal—part 2 

Objective: Analyze potential indicators to determine the type of attack.
Description: What happens when VirusTotal detects a file-based virus? In this project, you will download a file that has a “signature” of a file-based virus into a sandbox in order to upload it to VirusTotal. 
1. Open your web browser.
<img width="468" height="162" alt="image" src="https://github.com/user-attachments/assets/9bac14d4-a361-4e55-a6c7-4adfd5b58b27" />

 
2. Enter the URL www.eicar.org/?page_id=3950.
 <img width="468" height="216" alt="image" src="https://github.com/user-attachments/assets/1e2b0395-76bf-4a6a-82e6-646e5b794126" />

3. Scroll down to Download area using the standard protocol http.
 <img width="410" height="316" alt="image" src="https://github.com/user-attachments/assets/6b41369d-6806-4f4c-9ef2-d15a810a6092" />

4. Click eicar.com to start the download.
 <img width="467" height="151" alt="image" src="https://github.com/user-attachments/assets/6df4a1d4-8fe8-4538-824e-0571fe95766c" />

5. Your antimalware software on your personal computer should immediately flag this file as malicious and not allow you to download it. because it cannot (and should not) be downloaded on your regular computer, you will instead want to use the Windows sandbox or VMware sandbox you created in Module 1.
 <img width="416" height="244" alt="image" src="https://github.com/user-attachments/assets/7367eba0-1dd9-4700-a2fe-c8c7ca40f1a4" />
 <img width="468" height="71" alt="image" src="https://github.com/user-attachments/assets/2bd496ca-6634-4180-8a8f-41aea07fc9e7" />

6. If you are using the Windows sandbox, click Start, scroll down to Windows sandbox, and then click Windows Sandbox.
7. First you will turn off the security protections in Windows sandbox. Click Start and then Windows Security.
8. Click the three horizontal lines at the left of the screen to display the menu options.
9. Click App & browser control.
10. For each of the categories, click the Off button to turn off security. remember this will only impact the security within the Windows sandbox and will have no impact on the underlying computer.
11. Open Internet explorer in the Windows sandbox.
12. Enter the URL www.eicar.org/?page_id=3950.
13. Scroll down to Download area using the standard protocol http.
14. Click eicar.com to start the download.
15. The antimalware software within Windows sandbox will now allow the file to be downloaded into the sandbox.
16.Open another tab on the Internet explorer web browser in the Windows sandbox and enter the URL www.virustotal.com (if you are no longer able to access the site through the web address, use a search engine to search for “Virus Total”).
17. If necessary, click the File tab.
18. Click Choose File.
19. Navigate to the location of eicar.com and click Open.
20. Click Confirm upload.
21. Wait until the upload and analysis are completed.
22. scroll through the list of AV vendors that have been polled regarding this file. A green checkmark means no malware was detected.
23. Click the DETAILS tab and read through the analysis.
24. Close the Windows Sandbox. This will delete the eicar.com file and reset the security settings to normal.
    
As Observed and practiced manually in Lab and as unable to download and install Windows Sandbox on Operating system Windows 10.
