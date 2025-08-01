<h1>ACME System 1 Work Item Extraction Automation</h1>

<h2>Overview:</h2>
<p>This repository contains <strong>UiPath automation projects</strong> designed specifically for practicing Robotic Process Automation (RPA) skills using the <strong>ACME System 1</strong> website. Each project replicates common real-world automation scenarios, helping RPA developers enhance their development and problem-solving abilities.</p>

<h2>Project Description: Basic Work Item Extraction</h2>
<p>This basic-level automation project automates the extraction of specific work items (<strong>Type WI5 and Status Open/Completed</strong>) from the ACME System 1 website and stores the filtered data into a structured Excel file.</p>

<h3>Steps Performed:</h3>
<ul>
    <li>Login to ACME System 1 website.</li>
    <li>Navigate to the "Work Items" page.</li>
    <li>Extract and filter work items (Type = WI5, Status = Open/Completed)li>
    <li>Export filtered results to Excel (Work Item ID, Type, Status, Date)</li>
</ul>

<h3>Input:</h3>
<ul>
    <li>ACME System 1 login credentials (<code>username</code> and <code>password</code>).</li>
</ul>

<h3>Output:</h3>
<ul>
    <li>An Excel file containing filtered work items.</li>
</ul>

<h3>RPA Concepts Utilized:</h3>
<ul>
    <li><strong>Web Automation:</strong> Using UiPath activities for browser interactions.</li>
    <li><strong>Data Scraping:</strong> Extracting structured data from webpages.</li>
    <li><strong>DataTable Manipulation:</strong> Filtering and organizing extracted data.</li>
    <li><strong>Excel Automation:</strong> Exporting and managing data within Excel.</li>
</ul>

<h3>Tools & Technologies:</h3>
<ul>
    <li>UiPath Studio</li>
    <li>Excel</li>
    <li>ACME System 1 Website</li>
</ul>

<h3>How to Use this Project:</h3>
<ol>
    <li>Clone or download the repository.</li>
    <li>Open the project in UiPath Studio.</li>
    <li>Provide your ACME System 1 website credentials.</li>
    <li>Run the workflow and verify the output in the generated Excel file.</li>
</ol>
