<h1>Group Policy Management (GPMC) – Look At The Group Policy Of A Domain</h1>


<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Description</h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
This project goes over how to look at the Group Policy of a Domain using Group Policy Management. Looking at the Group Policy of a domain within the Group Policy Management (GPMC) tool allows administrators to see what the configuration settings are for all users and computers within that domain.
</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Utilities Used</h2>
  
<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
 - <b>Group Policy Management Tool</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
⏹️ Environments Used </h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
- <b>Windows 10 & Windows Server 2016</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
<h2>
⏹️ Project Walk-Through:</h2>
 <br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: Group Policy = the rules of a user group (password length, etc)</b></span>  
<br/><br/>


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: Shows the details of the group policy (how short can a password be, how many sign-in attempts does a user get, etc)</b></span>  
<br/><br/>


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: ***Kevtech IT Support recommends taking a screenshot of this info and saving it so you can quickly get to this info because many workers of the company call and ask about this stuff</b></span>  
<br/><br/><br/><br/>


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	Two ways to get to Group Policy Manager: 1) Through Server Manager  (AND)  2) Windows search: Group Policy Management</b></span>  
<br/><br/>


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>WAY ONE: Use Search Bar at the bottom of Windows Server.  Type: Server Manager.  Click: Tools (top right).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/bi4ZJ4p.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/NKpgmhj.png" height="50%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/u4r4NgY.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Group Policy Management.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/ilN4jay.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/jlN5OsX.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>WAY TWO: Use Search Bar at the bottom of Windows Server  (OR)  Windows OS with RSAT Tools.  Type: Group Policy Management</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/hdtZkWi.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/MjkSSJR.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click  (OR)  Double-Click: The Forest you want to look at.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/914xrDo.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/AIssrUR.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click  (OR)  Double-Click: Domains.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/vEzwWHm.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/WGcFs5a.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click  (OR)  Double-Click: The domain you want.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/NQTJfJh.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/p9Dcwam.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click  OR  Double-Click: Default Domain Policy.  If you get a warning message: Click: OK.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/LvQ5xVX.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/bF7iA3F.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Settings.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/SkTVmFq.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/MZZFmHN.png" height="50%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/M0uQRoQ.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: View all (top right of the big box – small letters).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/Ap20Wit.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/qcF8zm2.png" height="50%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/L7XEeob.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />
