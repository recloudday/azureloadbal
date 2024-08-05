<h1>Create a Standard Load Balancer with Azure CLI</h1>

<h2>Description</h2>
In this lab, I successfully created a Standard Load Balancer using the Azure CLI. 
I utilized Azure CloudShell with Bash to set the necessary variables and then created two Network Interface Cards (NICs). 
I prepared a cloud-init.txt file and pasted the required configuration into it, which facilitated the automated creation of virtual machines (VMs) and the load balancer. Once the setup was complete, I used the public IP address provided by the load balancer to test the deployment and verify that the load balancing was functioning correctly.
This lab enhanced my skills in using Azure CLI for infrastructure deployment and demonstrated my ability to automate resource creation and configuration in Azure.<br />


<h2>Concepts and Utilities Used</h2>

- <b>Azure - Load Balancer</b>
- <b>NIC</b>
- <b>Bash</b>
- <b>VM</b>

<h2>Environments Used </h2>

- <b>Azure: CLI</b>
- <b>CloudShell</b>
- <b>Bash</b>

<h2>Environment walk-through:</h2>

<p align="center">
Start CloudShell with Bash and set variables: <br/>
<img src="https://imgur.com/TnpCyH2.png" height="80%" width="80%" alt="Load Balancer Steps"/>
<br />
<br />
Create two NICs:  <br/>
<img src="https://imgur.com/x05A8ha.png" height="80%" width="80%" alt="Load Balancer Steps"/>
<br />
<br />
Create cloud-init.txt and paste config info, save:  <br/>
<img src="https://imgur.com/c7ILQlb.png" height="80%" width="80%" alt="Load Balancer Steps"/>
<br />
<br />
Use code to create VMs and Load balancers, get the public IP address of the load balancer:  <br/>
<img src="https://imgur.com/YKbwyQw.png" height="80%" width="80%" alt="Load Balancer Steps"/>
<br />
<br />
Test public IP:  <br/>
<img src="https://imgur.com/vXr4IN6.png" height="80%" width="80%" alt="Load Balancer Steps"/>
<br />
<br />
Look at LoadBalancer Insights:  <br/>
<img src="https://imgur.com/UHaJyAc.png" height="80%" width="80%" alt="Load Balancer Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
