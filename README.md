
    
    
</head>
<body>
    <h1>How to Create a SQL Database </h1>
   
<li><strong>Requirement:</strong> GitHub account, Azure account, and Azure CLI.</li>
                             <li><strong>Overview:</strong>  A SQL Database is a type of relational database that uses Structured Query Language (SQL) for storing, managing and retrieving information. its commonly used in web application, enterprise systems, and data analysis task due to its ability to handle large volume of structured data efficiently.
             </li>
            <li><strong>Purpose In Project:</strong> Its purpose in my project is to move a retail company online store to Azure to handle traffic spike during sales event and to ensure high availability and secure customers transactions .</li>
                   <li><strong>Deployment Steps:</strong> step-by-step instructions to deploy a SQL Database
                    <pre>
                        login to your AZURE PORTAL
                        Go to Azure SQL
                        Accept the free tier database
                        Click on your resouse group (create on if you dont have)
                        Database name
                        Create a server
                        Select US2 or any authorized location
                        Authentication- Use Microsoft entra only
                        Set Admin
                        Go to Networking
                        Connectivity Method- Public endpoint.

                        
                        
                                    
  --resource-group &lt;your-resource-group&gt; \
  --source &lt;repository-url&gt; \
  --location &lt;region&gt;
                    </pre>
  
                    <ing src="screenshot.jpeg" alt="This is my image">
                </li>
                <li><strong>Configuration:</strong> Explain how to set environment variables, custom domains, and authentication options.</li>
                <li><strong>Troubleshooting:</strong> Add common issues and solutions.</li>
                <li><strong>References:</strong> Link to official Azure Static Web Apps documentation.</li>
            </ul>
        </li>
      <ing src="Screenshot 2025-05-22 173849.png" alt="This is my image">
        <li>
            <strong>Commit and Push:</strong>
            <ul>
                <li>Commit your documentation file and push it to your GitHub repository.</li>
            </ul>
        </li>
        <li>
            <strong>Keep Documentation Updated:</strong>
            <ul>
                <li>Update the documentation as your deployment process or app configuration changes.</li>
            </ul>
        </li>
    </ol>
    <p>
        For more details, see the <a href="https://learn.microsoft.com/en-us/azure/static-web-apps/">Azure Static Web Apps Documentation</a>.
    </p>
</body>
</html>
