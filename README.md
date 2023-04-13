# Paneling datas with Ignition SCADA
- Used in the Project <br>
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) - MySQL<br>
<img src="https://drive.google.com/uc?export=view&id=1wqdLdBeE-UIcXwulcmg566j3Hwh9dJb9"> - Ignition SCADA

# Download Required Files

[Click to download](https://drive.google.com/file/d/1a8iJdmicHrn-rpxTV-oO7NkLOKPzUOgl/view?usp=share_link)

# Installation

<h3>Ignition SCADA</h3>
<ul>
  <li>Login to Ignition SCADA localhost administration panel</li>
  <li>Click on the <strong>"Config"</strong> tab from the left side menu</li>
  <li>On the screen that comes up, click the <strong>"Connections"</strong> tab under the <strong>"Databases"</strong> section</li>
  <li>Add a new database by clicking on the link <strong>"Create new Database Connection..."</strong></li>
  <li>Select <strong>MySQL</strong> (The official MySQL JDBC Driver, Connector/J must be installed on the computer)</li>
  <li>Enter the information with the database name <strong>ScadaControl</strong> and click the <strong>"Create New Database Connection"</strong> button to create the database</li>
  <li>After the database is created, import the contents of the database you downloaded from above to the database you just created</li>
</ul>

# Usage
<ol>
  <li>Make sure <strong>Ignition Localhost</strong> is running</li>
  <li>Open <strong>Designer Launcher</strong>. </li>
  <li>Select the Designer <strong>running</strong> on Localhost and then click <strong>"Open Designer"</strong> button from bottom right</li>
  <li>Import the project you downloaded from here by clicking the <strong>"Import Project"</strong> button in the upper right part of the window that comes up.</li>
  <li>Run the project via <strong>Vision</strong> by following the <strong>"Tools/Launch Project/Launch"</strong> path from the top menu</li>
</ol>
