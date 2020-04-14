# Home-docker-syslog-setup
<p>Setting up syslog in my home:</p>
<ul>
 <li>The host machine is Ubuntu 18.04.4 LTS </li>
 <li>The entire system is hosted on Docker</li>
 <li>Uses three separate containers</li> 
  <ul>
   <li>Syslog-ng</li>
   <li>Splunk Forwarder</li>
   <li>Splunk Indexer</li>
  </ul> 
</ul>
<i>The original idea was pulled from: <a href=https://splunk.paloaltonetworks.com/universal-forwarder.html>Palo Alto Syslog Guide</a>.</i>

 <p>A lot of modifications had to be made...</p>
