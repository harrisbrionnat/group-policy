


<h3
    <b> Set up an account lockout policy using Group Policy</b>
  </h3>
  <br>
  <br>
Navigate to the Group Policy Management Console. Right click Start click 'Run' type gpmc.msc. Right click the domain and click 'Create a GPO in this domain, and Link it here. Name the GPO 'Account Lockout Policy'.
   <p>
<img src="https://imgur.com/vcmFdwD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Right clock the GPO and select 'Edit. On the GP Management Editor, go to <b>Computer Configuration</b>---> <b>Policies</b>---><b>Windows Settings</b>--><b>Security Settings</b>---><b>Account Policies</b>---><b>Account Lockout Policy</b>. Go to 'Account lockout Threshold' and set it to 3. Attempt to login to a domain account 4 times with an incorrect password to see if the lockout policy has taken effect.
 <p>
<img src="https://imgur.com/ZGe9nrj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
