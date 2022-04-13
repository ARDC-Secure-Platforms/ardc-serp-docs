Monash SeRP

Training Manual

# Contents {#contents .TOC-Heading}

[[1 introduction]{.smallcaps} [2](#introduction)](#introduction)

[[2 key features & benefits]{.smallcaps}
[2](#key-features-benefits)](#key-features-benefits)

[[3 terms of use]{.smallcaps} [3](#terms-of-use)](#terms-of-use)

[[4 getting started]{.smallcaps}
[3](#getting-started)](#getting-started)

[[5 analytical environment]{.smallcaps}
[5](#_Toc88133671)](#_Toc88133671)

[[6 security 3 portal]{.smallcaps} [22](#_Toc88133672)](#_Toc88133672)

[[7 sub-licensee support]{.smallcaps}
[29](#_Toc88133673)](#_Toc88133673)

## [1 introduction]{.smallcaps}

Monash Secure eResearch Platform (SeRP) is a secure environment for
sharing research data for collaboration and analysis, within the control
and governance of the data custodian. Monash SeRP allows the Data
custodian or the delegated project manager (Data Custodian) to have
visibility and control over how their data is being used by other
approved researchers.

Onboarding a project/registry is simple and straightforward. The project
owner places a request to create a project. A consultant will then be in
touch to discuss the requirements and create the project.

Once a project is established and a dataset uploaded, a Data Custodian
can allocate controlled access to this dataset, provide computing power
and approved analytical tools to approved researchers, manage the
controls of the environment including restricting access to the
internet, restricting the importing of other data, authorise all
removals of data and audit the usage of data and compute resources.

## [2 key features & benefits ]{.smallcaps}

**2.1 FEATURES & BENEFITS**

-   Secure remote access to your research data.

-   Fully controlled environment

-   Regularly updated software packages to assist you in your data
    analysis

-   Accessible using most modern web browsers and mobile devices

-   Hosted on NeCTAR Research Cloud (Local Monash Instance)

-   Dedicated Support Website

**\
**

**\
**

**2.2 AVAILABLE APPLICATIONS**

Applications are delivered dynamically and are assigned to the user upon
login.

Currently, the following applications are provided:

-   SPSS

-   Stata

-   SAS

-   R Studio

-   MatLab

-   Notepad++

-   Python

-   Microsoft Office applications

Additional applications can be installed upon request (subject to
licencing).

Please submit any requests to <serp-support@monash.edu>

## [3 terms of use]{.smallcaps}

**\
**Use of the Monash SeRP is subject to Monash University's Information
Technology Acceptable Use Policy and Information Technology Acceptable
Use Procedure. Found
[here](https://www.monash.edu/__data/assets/pdf_file/0009/1092699/Information-Technology-Acceptable-Use-Policy.pdf).

If you have any queries, please contact the Monash SeRP Helpdesk:
<serp-support@monash.edu>

## [4 getting started]{.smallcaps}

**4.1 ACCOUNT ACTIVATION**\
To activate your Monash account, follow the steps in the link below. We
recommend that you read all the instructions in this section before
beginning these steps:

<https://monash.edu/esolutions/accounts-passwords/activate>

**Note:** Monash accounts require a strong password. For guidance on
creating a strong password, see article
<https://mon.clients.squiz.net/esolutions-site/accounts-passwords/strong-passwords>

**\
**

**Your Multi-Factor Authentication options:**

If you have a smartphone, you can use either the Okta Verify app
(recommended) or Google Authenticator for MFA. If you don't have a
smartphone, or don't wish to use your smartphone for MFA, you can
request a USB device (YubiKey or a U2F). You can also use your own U2F
security key.

** **![https://lh3.googleusercontent.com/NBpl9SC6-NeyP4uIHVQJ5fm53go1CrjLDcN68lp1vkUdkDGa-3rvklcImd3lRO-Xtkofrla-vclcR0B8U0t_3WNfc6TqFrnKDKkqAGb4Otzu9Yo7DOciyU94zB8Zl5vYp3-idJY](media/image1.png){width="6.268055555555556in"
height="3.86665791776028in"}

For further information on Multi-Factor Authentication, see\
<https://mon.clients.squiz.net/esolutions-site/accounts-passwords/multi-factor-authentication>

After successful activation, if you select "continue", a login screen
will appear. It is not necessary to login at this point, as Monash SeRP
is accessed from a [Virtual Private Network
(VPN)](https://docs.google.com/document/d/1aXnDKNy6sA_bqxNFaWkxsG11O8dmEc8T/edit#heading=h.r7d3qd1oj97z)
and a [secure
portal](https://docs.google.com/document/d/1aXnDKNy6sA_bqxNFaWkxsG11O8dmEc8T/edit#heading=h.8u6ad8hxquk),
and these steps are outlined below.  However, if you wish to view your
Monash account and access your Monash email, use your Monash ID, e.g.
ext-jsmith to login at this point. You do not need to use the full email
address, eg. ext-jsmith@monash.edu

**Troubleshooting**

If you experience issues activating your account, contact Monash SeRP
Support Desk:\
<serp-support@monash.edu>

**\
**

**\
4.2 MONASH VPN**

A VPN is a virtual private network which allows you to access Monash
services. A VPN connection is compulsory while accessing the SeRP
environment. Monash utilises a VPN client called 'CISCO AnyConnect'.\
\
Download CISCO AnyConnect using the instructions available at
[https://vpn.monash.edu](https://vpn.monash.edu/) 

Detailed guidance about Cisco AnyConnect and the Monash Virtual Private
Network (VPN) can be found at
<https://www.monash.edu/esolutions/network/vpn>*[\
\
]{.smallcaps}*[]{#_Toc88133671 .anchor}[\
5 analytical environment]{.smallcaps}

**\
\
5.1 LOGGING INTO MONASH SERP**

**Requirements**

-   Internet Browser - Monash SeRP can be accessed through any modern
    internet browser. We recommend Microsoft Edge or Google Chrome.

-   Your Monash user account must be activated, see "Activating your
    account" section.

1\. Log in to the Monash VPN using your Monash ID (username) and
password

Open the CISCO AnyConnect application, then click Connect

![https://www.monash.edu/\_\_data/assets/image/0004/1510429/vpn-mfa-1.png](media/image2.png){width="3.15625in"
height="1.4895833333333333in"}

2\. Login with your Monash username, not your email address.

Your username will be similar to: jsmith, jsmi0001 or ext-jsmith.

![okta screen grab](media/image3.png){width="2.9583333333333335in"
height="1.9479166666666667in"}

3\. You will be prompted to authenticate using multifactor
authentication (MFA).

Select either Option 1 or Option 2.

Option 1: Enter verification code from your Okta App, then click OK.

Option 2: Approve push notification on your Okta App.

![https://www.monash.edu/\_\_data/assets/image/0015/1510431/vpn-mfa-3.png](media/image4.png){width="2.6770833333333335in"
height="2.21875in"}

4\. Click Accept to complete your login to the VPN

![https://www.monash.edu/\_\_data/assets/image/0017/1510433/vpn-mfa-5.png](media/image5.png){width="3.3490562117235347in"
height="1.79791447944007in"}

![https://www.monash.edu/\_\_data/assets/image/0018/1510434/vpn-mfa-6.png](media/image6.png){width="3.348611111111111in"
height="1.5908103674540683in"}

5\. Open a web browser and go to the Monash SeRP web portal

[https://serp-web.erc.monash.edu/\
](https://serp-web.erc.monash.edu/)

6\. You will be directed to enter your Monash ID and password to see the
Monash SeRP Launch Portal where you will see your available project(s)
listed and several options:

![https://lh6.googleusercontent.com/Ie4stqgZnw-SBm53OxsiayEUxMb1elCJdOk9vVS97WHA19oG1L-YbtK42rUPkdd2weQUsCzujCXVELUZUzY9wFo8oIh0dXls5B85qcD8mtpSdBye2UddrHdp_IAPNg](media/image7.png){width="6.056603237095363in"
height="2.2323720472440947in"}

7\. Click Launch Platform

9\. You will be redirected to the Monash Okta login page.\
\
Please enter your Monash email address (ie. ext-jsmith@monash.edu) and
password and follow authentication prompts on your screen and secondary
smart device.\
![https://lh5.googleusercontent.com/lLMTr-L66UtHrUqqlxmU6mLlFwddXUrY5Onw55ohY1egU5UbQ9jR0dTJOk8mAW9RSNoFDn0Mmq7B6zOTxDe0EVZyza_fIprth5GLb1STba2xeNISCP_fZLHHz-BFDw](media/image8.png){width="1.7867465004374454in"
height="2.877357830271216in"}

10\. A pool of available Virtual Machines will be listed.

Click Connect on any available machine to start the remote connection

![https://lh6.googleusercontent.com/jKzOA2Vg-xGRjhDyaqqpKX5MQzEJQEjs4JbZz6zyf36mCEjDZNdeeXZoAcaWbL_IxhdpNSyA8B39ysi23Lt4GJUsw0RceCpVmMA1EtKPpVwwBy0W6p0RZCWrAAG9XVUD-gRN86s](media/image9.png){width="3.3645833333333335in"
height="1.09375in"}

11\. Click OK

![https://lh5.googleusercontent.com/oc94vlRu6RhPBlbGbysiQAZ4YN-V1Q9zGP3J1hXoB4mxdjJ6fYkU4E_2xhlmEWw3wt-m1xkUVcd0kst0N8UqoTQKbCJ-b0DYC75RQNG72R-IgX0sKXaEqOIgzNDAbEo9esWVg0E](media/image10.png){width="3.272222222222222in"
height="1.246107830271216in"}

12\. Once you\'ve selected a Virtual Machine you will be prompted to
re-enter your Monash ID and password.\
![https://lh3.googleusercontent.com/-scAC7VaKxFPrp2QIG-PPCX34Kjx8oftI4vkohvjeJYXmBjuMcKu04UfSSL8MP2O_6fpw_T1ulJVSjV6kNYOIQ1y3R1cREk9I31GEs4AFN4O1VP6KxCjgyCIP89Jig](media/image11.png){width="3.272222222222222in"
height="1.8299201662292213in"}\
\
13. Congratulations, you are now logged in!

Upon first time log in, it may take a minute to load your personal
desktop.

To sign-out of the environment, click the 'Windows' button on the lower
left of the screen. This will

load a menu screen, click on your name in top right corner of screen and
click 'sign-out'.

**5.2 PROJECT DATA - P DRIVE\
\
**1. To access your research data folders, you must be logged into the
Monash SeRP Analytical Environment and click on the 'File Explorer' icon
in the bottom left of screen.

![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51000786985/original/0wsi\_\_zUp-faNzLSTFrbUAjQp3aDSS-5RA.png?1552966419](media/image12.png){width="0.5520833333333334in"
height="0.46875in"}

2\. The project data is available on the P: drive.

Accessing the P drive will show you a list of available project folders.
You will only be able to see the project folders that you have been
approved to access.

![](media/image13.png){width="6.065902230971129in"
height="3.9798665791776027in"}**\
**

**\
**

**5.3 PERSONAL WORKSPACE - U DRIVE\
**1. Your own reference documents, scripts or research outputs should be
saved to the U drive\
\
2. You may also save data to the P drive, but this will be dependent on
the permissions you have been allocated for the project. If you are
unsure where you should save data, please check with your Data Custodian
or Project Lead.\
\
3. It is important that you do not save data to any of the 'My
documents' folder or desktop. There is no guarantee the same machine
portal will be available to you the next time you log in. The 'My
Documents' folder is a component of a user's profile and is unique to
each user.\
\
**5.4 SAVING FILES TO THE DESKTOP**

1\. It is recommended that you do not save any files to the desktop of
the analytical machine.

2\. Any files saved to the desktop will be saved only to the users
profile on that particular machine. The 'desktop' folder is a component
of a user's profile and is unique to each user.

3\. This is not ideal as the user cannot be guaranteed to access the
same machine again in future.

4\. All files should be saved to either the P drive or U drive.\
\
**5.5 ANALYSIS APPLICATIONS\
\
**If you require additional packages to be installed for any of the
below applications, please submit your request to
<serp-support@monash.edu>. All requests should be submitted by the
delegated Data Custodian or Project Lead. **\
\
\
STATA\
**STATA is a general-purpose statistical software package for data
manipulation, visualization, statistics, and automated reporting. STATA
is available with a large list of preinstalled packages. A full list is
available
[here](https://monasheresearch.freshdesk.com/support/solutions/articles/51000207824-packages-for-stata).\
To check within STATA, use the command: *-ado-*

**R and R Studio\
**R is a programming language and free software environment for
statistical computing and graphics supported by the R Core Team and the
R Foundation for Statistical Computing. It is widely used among
statisticians and researchers for developing statistical software and
data analysis\
R and R Studio are available with a large list of preinstalled packages.
A full list is available
[here](https://monasheresearch.freshdesk.com/support/solutions/articles/51000096072-packages-for-r).\
To check within R, use the command: *installed.packages()\
*

**Anaconda / Python\
**Anaconda is a distribution of the Python and R programming languages
for scientific computing, that aims to simplify package management and
deployment.\
Anaconda is available with a base environment with preinstalled
packages. A full list is available
[here](https://monasheresearch.freshdesk.com/support/solutions/articles/51000207370-python-anaconda).\
For detailed instructions on creating and managing Anaconda
environments, please see
[here](https://monasheresearch.freshdesk.com/support/solutions/articles/51000207370-python-anaconda).

**SPSS**

SPSS v27 is available on Monash SeRP

-   R Plug-In has been installed

-   Python Plug-In has been installed

-   Propensity Score Matching bundle has been installed

When opening SPSS, please ensure R and Python locations have been set
correctly. Once setup correct, you will be able to use SPSS with
Python/R as normal.

[SPSS - Python Setup]{.underline}

1\. Go to Edit \> Options \> File Locations

2\. Ensure Python 2.7 location is set to C:\\ProgramFiles\\Python27 and
Python 3 Location is set to Installed with IBM SPSS Statistics\
![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51009661399/original/8NwYwkm9C3piAfOKEZQCW7yyxuVFVF36Bw.png?1606443939](media/image14.png){width="6.208333333333333in"
height="1.7882370953630795in"}\
\
[SPSS - R Setup]{.underline}

1\. Go to Extensions \> R3.6 Configuration

2\. Ensure R 3.6 home directory is set to C:\\ProgramFiles\\R\\R-3.6.1\
\
![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51009661398/original/yZld0FMAmfRZZqDqxWD6bmAMfnrSc0gKBA.png?1606443938](media/image15.png){width="3.9433967629046367in"
height="1.6712095363079615in"}\
\
[\
SPSS SUMMARY]{.underline}

For SPSS v27 the Propensity Score Matching option is available under
Data \> Propensity Score Matching

![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51009661468/original/PsGDIDK1CLEJz8MDnA2xSq3fvS0prv-Yrg.png?1606443983](media/image16.png){width="5.770833333333333in"
height="3.760990813648294in"}

FUZZY is also available.\
![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51009661566/original/ulCxOabheSkcrI9OAJwgL8_A2yzrWR95Lg.png?1606444043](media/image17.png){width="5.157617016622922in"
height="1.5520833333333333in"}

**5.6 File in Process\
**This process should be used by the Data Custodian to ingress project
files such as datasets, data dictionaries, scripts and other supporting
project documentation.

End-Users can import supporting project documentation and scripts for
data analysis.\
\
1. To import a file into the SeRP environment, load the SeRP user
portal:

<https://serp-web.erc.monash.edu/>

Reminder: SeRP access is only available via Monash VPN. For detailed log
in instructions, see here.

2\. Once you have accessed the SeRP portal, click \'File In Requests\'
icon as show below.\
\
![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51000787579/original/ChwdK7A6BAMAwJqkgoj81Ke7B0wQe18Y2g.png?1552969884](media/image18.png){width="4.645833333333333in"
height="1.2967115048118985in"}\
3. You can now drag and drop your file in requests into the Files area.

Click \'Upload Files\' when finished. Files will be automatically
approved.\
\
![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51000787601/original/bnqzhhxhbINGIvuJrkczLHE7Bu7WvHgcFg.png?1552969955](media/image19.png){width="5.395833333333333in"
height="3.141573709536308in"}\
\
4. To retrieve your file from within the SeRP environment, go back to
the main portal page by clicking on the Monash University logo.

![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51019035988/original/YAnbvnhpV60nNO60vO8qyTyYuk60qDPUdw.png?1623316629](media/image20.png){width="5.614583333333333in"
height="2.6482491251093614in"}

Click Launch Platform, then connect to a virtual machine.

![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51019036002/original/sM5XGQcG8GdvPRqFV0SrYsLKl49pHtqUKQ.png?1623316663](media/image21.png){width="2.7395833333333335in"
height="2.5700546806649167in"}

5\. Once connected and the virtual environment has loaded, select the
desktop icon \'SeRP Egress\'

![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51018051546/original/NcGPvF-pR-mkhtCaOopRWbu0q663BTtZmQ.png?1622017174](media/image22.png){width="0.8020833333333334in"
height="0.8020833333333334in"}\
\
You will be prompted for your log in details, please use your Monash ID
and password.

6\. Click Retrieve Files In\
![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51019036036/original/K0D7kdwGy73AMraHhSbcuBTY3oak4OKcNw.png?1623316721](media/image23.png){width="5.479166666666667in"
height="2.698557524059493in"}\
\
7. A list will display of all available file uploads. Select the \'eye\'
icon to view your file.\
\
![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51000794002/original/I594FKMzo6MU0t9SpdDrlsrWQYnv7jWs4w.png?1553055909](media/image24.png){width="6.416666666666667in"
height="1.7432950568678915in"}\
\
8. Click the download icon to download your file within the SeRP
environment.\
![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51000794031/original/5JmllqEcv0nhsTJFll_gEKV-ivnw1b2zQg.png?1553056050](media/image25.png){width="5.65625in"
height="1.6557950568678914in"}\
\
9. Your file(s) has now been imported into the SeRP environment and will
be available on the U: Drive.\
\
10. Transfer the files from the U: drive to the P: drive to allow all
appropriate project researchers to access the data.

**5.7 FILE IN PROCESS FOR LARGE DATASETS\
**1. There is no file size limit for data ingress using the File In
Process described above.

2\. Alternative methods are available using SFTP or datasets can be
uploaded to an SQL Database.

3\. Please contact <serp-support@monash.edu> for assistance an advice
using these alternate methods.\
\
**\
5.8 FILE OUT PROCESS\
**1. File Out requests are submitted from within the Monash SeRP virtual
desktop environment, using the SeRP Egress desktop shortcut.

![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51016362631/original/BCjblzZat9fJ4A14UTrH_aDIKq7MVbXv1g.png?1619569197](media/image26.png){width="6.171776027996501in"
height="3.0520833333333335in"}

Please see the user guide, **LOGGING IN TO MONASH SERP** user guide for
detailed steps accessing the Monash SeRP analytical environment.

2\. Once you have accessed the Monash SeRP virtual desktop environment,
double-click the SeRP Egress desktop shortcut.

![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51016363060/original/djtvkRMAcjAOlhPOBGLy6FLZqIKxsoG7AQ.png?1619569395](media/image27.png){width="0.8854166666666666in"
height="0.78125in"}

You will be prompted for your log in details again, please use your
Monash ID and password.

3\. Once the SeRP Egress Portal has loaded, click Request File(s) Out

![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51000794157/original/zyF581Ft9WqYb7Ye0vcArWibCbPHYqBeYA.png?1553056549](media/image28.png){width="6.1715277777777775in"
height="1.888830927384077in"}

4\. Drop your file(s) into the relevant area and complete the form
questions. Then click Send Request.

![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51000794226/original/jMvOulvWVx4g3qfLQuShXdj5UQ6RvGsTNA.png?1553056605](media/image29.png){width="5.322916666666667in"
height="1.6630632108486438in"}

![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51000794244/original/vNXvkYlA8Hpoo1opGJQePtO-D969ye0MMA.png?1553056697](media/image30.png){width="5.260416666666667in"
height="3.3440430883639545in"}

5\. Please allow two working days for the review process. When the
review has been completed, you will be sent another email notification
containing instructions on how to retrieve the file(s).

If you have not received an email with instructions on how to retrieve
your file(s) please contact your project co-ordinator or data custodian.

The following steps are to be completed once your File Out Request has
been approved for retrieval from the Monash SeRP environment.

6\. Navigate to the Monash SeRP User Portal at
https://serp-web.erc.monash.edu/ (do not select launch platform).

7\. Select File Out Requests

![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51000794305/original/fsdDjn-lCDcqo9R95Kv561ZvtsPTDNlqzw.png?1553056856](media/image31.png){width="5.489583333333333in"
height="1.532212379702537in"}

8\. A list of previous File Out requests will be displayed. Click the
\'eye\' icon to view your approved file.

![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51000794319/original/vugoMKC32Phg9rfsr8ehB4OcEIjsXxDU4A.png?1553056914](media/image32.png){width="5.625in"
height="1.2331955380577428in"}

9\. Click the download icon to download your approved file. The file
will now be saved to your local computer.

![https://s3-ap-southeast-2.amazonaws.com/aus-cdn.freshdesk.com/data/helpdesk/attachments/production/51000797423/original/\_BE_UMBvUrUpElVUvs5JZxjjGCigJ_OtjQ.png?1553126049](media/image33.png){width="5.791666666666667in"
height="1.8698468941382327in"}
