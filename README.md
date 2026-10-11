<h1>🏠 Multi-VM Departmental Homelab</h1>

<h3>Enterprise-Style Virtual Infrastructure & System Administration Lab</h3>

<p>
  <img src="https://img.shields.io/badge/Virtual%20Machines-18-6A1B9A" alt="18 Virtual Machines">
  <img src="https://img.shields.io/badge/Windows%20Server-2022-0078D4" alt="Windows Server 2022">
  <img src="https://img.shields.io/badge/Workstations-Windows%208.1-00A4EF" alt="Windows 8.1">
  <img src="https://img.shields.io/badge/Departments-5-FF6600" alt="Five Departments">
  <img src="https://img.shields.io/badge/Platform-Oracle%20VirtualBox-183A61" alt="Oracle VirtualBox">
  <img src="https://img.shields.io/badge/Networking-IPv4%20%2F24-008000" alt="IPv4 Networks">
</p>

<h3>📌 Project Overview</h3>

<p>
The Multi-VM Departmental Homelab was designed and built to simulate a small enterprise IT environment using Oracle VirtualBox.
</p>

<p>
The project consists of 18 virtual machines organised across five departmental environments: Finance, Audit, Information Technology, Procurement, and Guest.
</p>

<p>
The environment contains four Windows Server 2022 servers and fourteen Windows 8.1 workstations. Finance, Audit, Information Technology, and Procurement each contain one server and three workstations, while the Guest environment contains two standalone workstations.
</p>

<p>
Each department was configured with its own /24 network, static IPv4 addressing, hostname convention, and VirtualBox group structure. This created an organised enterprise-style virtual infrastructure with clear separation between departmental systems.
</p>

<p>
The build covered virtual-machine provisioning, operating-system installation, resource allocation, network configuration, departmental segmentation, connectivity testing, and baseline snapshot creation for system recovery.
</p>

<p>
The homelab provides a practical foundation for future Active Directory, DNS, Group Policy, Windows security, networking, vulnerability management, and cybersecurity exercises.
</p>

<h3>🏢 Departmental Structure</h3>

<table>
  <thead>
    <tr>
      <th>Department</th>
      <th>Server</th>
      <th>Workstations</th>
      <th>Environment Type</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Finance</td>
      <td>1</td>
      <td>3</td>
      <td>Departmental network</td>
    </tr>
    <tr>
      <td>Audit</td>
      <td>1</td>
      <td>3</td>
      <td>Departmental network</td>
    </tr>
    <tr>
      <td>Information Technology</td>
      <td>1</td>
      <td>3</td>
      <td>Departmental network</td>
    </tr>
    <tr>
      <td>Procurement</td>
      <td>1</td>
      <td>3</td>
      <td>Departmental network</td>
    </tr>
    <tr>
      <td>Guest</td>
      <td>0</td>
      <td>2</td>
      <td>Standalone network</td>
    </tr>
    <tr>
      <td><strong>Total</strong></td>
      <td><strong>4</strong></td>
      <td><strong>14</strong></td>
      <td><strong>18 virtual machines</strong></td>
    </tr>
  </tbody>
</table>

<h3>🌐 Network Architecture</h3>

<p>
For security and documentation purposes, the exact laboratory IP addresses have been anonymised.
</p>

<table>
  <thead>
    <tr>
      <th>Department</th>
      <th>IPv4 Network</th>
      <th>Subnet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Finance</td>
      <td>Private Departmental Network</td>
      <td>/24</td>
    </tr>
    <tr>
      <td>Audit</td>
      <td>Private Departmental Network</td>
      <td>/24</td>
    </tr>
    <tr>
      <td>Information Technology</td>
      <td>Private Departmental Network</td>
      <td>/24</td>
    </tr>
    <tr>
      <td>Procurement</td>
      <td>Private Departmental Network</td>
      <td>/24</td>
    </tr>
    <tr>
      <td>Guest</td>
      <td>Isolated Guest Network</td>
      <td>/24</td>
    </tr>
  </tbody>
</table>

<h3>⚙️ Project Implementation</h3>

<ol>
  <li>Installed and configured Oracle VirtualBox,</li>
  <li>Created departmental VirtualBox groups,</li>
  <li>Provisioned four Windows Server 2022 virtual machines,</li>
  <li>Provisioned fourteen Windows 8.1 workstations,</li>
  <li>Allocated processor, memory, and storage resources,</li>
  <li>Applied a consistent enterprise hostname convention,</li>
  <li>Created separate /24 networks for each department,</li>
  <li>Configured static IPv4 addresses,</li>
  <li>Tested communication between authorised systems,</li>
  <li>Verified departmental network separation and,</li>
  <li>Created baseline snapshots for recovery.</li>
</ol>

<h3>🔐 Security Value</h3>

<p>
Departmental network separation reduces unnecessary communication between systems and provides a foundation for applying access restrictions, firewall rules, vulnerability scanning, security monitoring, and least-privilege controls.
</p>

<p>
The Guest environment was separated from the internal departmental networks to represent how an organisation can prevent unmanaged guest devices from directly accessing internal business systems.
</p>

<h3>🧪 Validation Performed</h3>

<ol>
  <li>Confirmed that all 18 virtual machines started successfully,</li>
  <li>Verified the operating system installed on each virtual machine,</li>
  <li>Confirmed hostname assignments,</li>
  <li>Verified static IPv4 configurations,</li>
  <li>Tested network connectivity within each departmental environment,</li>
  <li>Confirmed departmental network separation and,</li>
  <li>Verified that baseline snapshots were successfully created.</li>
</ol>

<h3>🛠️ Skills Demonstrated</h3>

<ol>
  <li>Oracle VirtualBox administration and VM provisioning,</li>
  <li>Windows Server 2022 deployment,</li>
  <li>Windows 8.1 workstation deployment,</li>
  <li>Virtual hardware resource allocation,</li>
  <li>IPv4 addressing and subnet planning,</li>
  <li>Virtual networking and departmental segmentation,</li>
  <li>Static IPv4 configuration,</li>
  <li>Enterprise hostname and VM organisation,</li>
  <li>Network connectivity testing,</li>
  <li>Snapshot and recovery management and,</li>
  <li>Technical infrastructure documentation.</li>
</ol>

<h3>🚀 Future Development</h3>

<p>
This virtual infrastructure provides a foundation for additional enterprise IT and cybersecurity projects, including:
</p>

<ul>
  <li>Active Directory Domain Services,</li>
  <li>DNS configuration,</li>
  <li>Group Policy administration,</li>
  <li>Identity and access management,</li>
  <li>Windows security hardening,</li>
  <li>Firewall policy testing,</li>
  <li>Vulnerability scanning,</li>
  <li>Security monitoring and,</li>
  <li>Incident-response exercises.</li>
</ul>

<h3>⚠️ Disclaimer</h3>

<p>
This homelab was created for educational and professional portfolio purposes. All systems, network addresses, departments, and configurations shown in this repository are part of a controlled virtual lab environment.
</p>

<h3>👤 Author</h3>

<p>
<strong>Saheed Bakare</strong><br>
IT Support Engineer | Cybersecurity Analyst & IAM Practitioner
</p>
