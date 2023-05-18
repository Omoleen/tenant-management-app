<!DOCTYPE html>
<html>
<head>
  <title>Tenant Management Application</title>
</head>
<body>
  <h1>Tenant Management Application</h1>
  <p>Welcome to the Tenant Management Application! This application is built using the Frappe framework and helps you manage tenants and their related information.</p>
  
  <h2>Prerequisites</h2>
  <p>Before you can set up the Tenant Management Application, ensure that you have the following dependencies installed on your computer:</p>
  <ul>
    <li>Python 3.7 or higher</li>
    <li>Node.js (version specified in <code>package.json</code>)</li>
    <li>Redis</li>
    <li>MariaDB or MySQL</li>
  </ul>
  
  <h2>Installation</h2>
  <p>Follow the steps below to set up the application on your local machine:</p>
  
  <ol start="1">
    <li>Install the application:</li>
  </ol>
  <pre><code>cd frappe-bench<br>bench get-app tenant_management https://github.com/Omoleen/tenant-management-app.git<br>bench --site your-site-name install-app tenant_management</code></pre>
  
  <p>Replace <code>your-site-name</code> with the desired site name for your application.</p>
  
  <ol start="2">
    <li>Start the development server:</li>
  </ol>
  <pre><code>bench start</code></pre>
  
  <p>The Tenant Management Application should now be accessible at <a href="http://localhost:8000">http://localhost:8000</a>. You can log in using the administrator credentials you specified during the installation.</p>
  
  <h2>License</h2>
  <p><a href="LICENSE">MIT License</a></p>
</body>
</html>
