<h1>Identification of the type of attack</h1>
<p style="font-size: 15px;">Upon analyzing the Wire shark log of HTTP and TCP traffic, it was observed that requests were being made via the transport layer protocol to initiate a TCP handshake from an unidentified IP address outside employee’s subnet address.</br> Although the IP address could potentially belong to a customer, the nature of the requests exhibited abnormal behaviour. Even after establishing a connection, the suspected IP address continued to send multiple SYN packets over TCP to the web server. These packets originated from a single source IP address and were numerous, indicating a classic SYN flood Denial of Service Attack.</p>

<div align="center">
  <img src="Picture3.png" alt="Project Image">
</div>
