<h1>Multi-VM Departmental Homelab</h1>
<h3>Enterprise-Style Virtual Infrastructure & System Administration Lab</h3>
<p>The Multi-VM Departmental Homelab was designed and built to simulate a small enterprise IT environment using Oracle VirtualBox. The project consists of 18 virtual machines organised across five departmental environments: Finance, Audit, Information Technology (IT), Procurement, and Guest.: </p>

<p>The environment includes four Windows Server 2022 servers and fourteen Windows 8.1 workstations. Finance, Audit, IT, and Procurement each contain one server and three workstations, while the Guest environment contains two standalone workstations.: </p>

<p>Each department was configured with its own /24 network, static IP addressing, hostname convention, and VirtualBox group structure, creating an organised enterprise-style environment. The build covers VM provisioning, operating system deployment, resource allocation, network configuration, connectivity testing, and baseline snapshots for recovery.

The homelab provides a practical foundation for future Active Directory, DNS, Group Policy, Windows security, networking, and cybersecurity exercises.: </p>


<h1>Skills Demonstrated</h1>

<ol>
  <li>Information Technology (IT),</li>
  <li>Finance, </li>
  <li>Audit, and </li>
  <li>Procurement.</li>
</ol>
<p>Four separate /24 networks were configured for the departmental segments, with each network providing 254 usable host addresses. The networks were 192.168.40.0/24 (IT), 192.168.10.0/24 (Finance), 192.168.20.0/24 (Audit), and 192.168.50.0/24 (Procurement). Network isolation was implemented using VirtualBox NAT Network functionality, with each department attached to its 
own isolated virtual network..</p>

<p>Sixteen virtual machines were deployed across the four departmental networks  three employee workstation VMs and one Windows Server VM per department for a total of 12 workstations and 
4 servers.. Each VM's network adapter was explicitly attached to its corresponding departmental NAT Network, ensuring that devices in one department cannot directly communicate with 
devices in another without passing through a controlled routing or firewall boundary. This project demonstrates core network security principles including the reduction of lateral movement risk, the containment of a potential breach to a single department, and the enforcement of the principle of least privilege at the network layer.</p>
