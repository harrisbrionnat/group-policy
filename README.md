### Set up an Account Lockout Policy Using Group Policy

Navigate to the Group Policy Management Console. Right-click **Start**, click **Run**, and type `gpmc.msc`. Click the domain and expand it. Right-click **Group Policy Objects**, then click **New**. Name it `Account-Lockout`. Right-click the new group policy and select **Edit** → **Computer Configuration** → **Windows Configuration** → **Security Settings** → **Account Policies** → **Account Lockout Policies**.
<p align="center">
  <img src="https://imgur.com/rLU3f6i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Go to **Account Lockout Threshold** and set it to **3**. Attempt to log in to a domain account **4 times** with an incorrect password to see if the lockout policy has taken effect.
<p align="center">
  <img src="https://imgur.com/JDtMP5Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p align="center">
  <img src="https://imgur.com/gG08Ht8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
