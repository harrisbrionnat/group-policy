


<h3
    <b> Set up an account lockout policy using Group Policy</b>
  </h3>
  <br>
  <br>
Navigate to the Group Policy Management Console. Right click Start click 'Run' type gpmc.msc. Click the domain and expand, Right click  'Group Policy Objects'. Click 'New'. Type Account-Lockout. Righ-click the group policy and click 'edit'--><b>Computer Configuration</b>--> <b>Windows Configuration</b>--><b>Security Settings</b>---><b>Account Policies</b>--><b>>Account Lockout Policies</b>. 
<img src="https://imgur.com/rLU3f6i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Go to 'Account lockout Threshold' and set it to 3. Attempt to login to a domain account 4 times with an incorrect password to see if the lockout policy has taken effect.
 <p>
<img src="https://imgur.com/JDtMP5Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://imgur.com/gG08Ht8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
