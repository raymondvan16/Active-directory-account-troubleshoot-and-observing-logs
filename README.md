<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Account troubleshoot and observing logs with Active Directory.(Active Directory)</h1>
In this repo, we will be going over how to deal with account lockouts, enabling and disabling accounts, and lastly observing logs.


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- Group Policy Management Console (GPMC)

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>Account Lockouts.</h2>
Dealing with Account Lockouts
Get logged into dc-1
Pick a random user account you created previously
Attempt to log in with it 10 times with a bad password
Attempt to log in with it 6 times with a bad password

Observe that the account has been locked out within Active Directory
Unlock the account
Reset the password
Attempt to login with it

  
<h2>Enabling and Disabling Accounts.</h2>
Disable the same account in Active Directory
Attempt to login with it, observe the error message
Re-enable the account and attempt to login with it.

<h2>Observing Logs.</h2>
Observe the logs in the Domain Controller as shown.
Observe the logs on the client Machine as shown.

<br>End of Lab.</br>
