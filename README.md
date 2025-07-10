
    
    
</head>
<body>
    <h1>How to Create a SQL Database </h1>
    <p>
        Follow these steps to add Static Web App :
    </p>
    <ol>
        <li>
            <strong>Create a Documentation File:</strong>
            <ul>
                <li>Add a new file named <code>STATIC_WEB_APP.md</code> or <code>docs/static-web-app.md</code> in your repository.</li>
            </ul>
        </li>
        <li>
            <strong>Include Key Sections:</strong>
            <ul>
                <li><strong>Overview:</strong>  A SQL Database is a type of relational database that uses Structured Query Language (SQL) for storing, managing and retrieving information. its commonly used in web application, enterprise systems, and data analysis task due to its ability to handle large volume of structured data efficiently 
              Purpose my your project- Its purpose in my project is to move a retail company online store to Azure to handle traffic spike during sales event and to ensure high availability and secure customers transactions.</li>
            <li><strong>Prerequisites:</strong> List requirements such as an Azure account, .</li>
                <li><strong>Prerequisites:</strong> List requirements such as a GitHub account, Azure account, and Azure CLI.</li>
                <li><strong>Deployment Steps:</strong> Provide step-by-step instructions to deploy your static web app. For example:
                    <pre>
az login
az staticwebapp create \
  --name &lt;your-app-name&gt; \
  --resource-group &lt;your-resource-group&gt; \
  --source &lt;repository-url&gt; \
  --location &lt;region&gt;
                    </pre>
                </li>
                <li><strong>Configuration:</strong> Explain how to set environment variables, custom domains, and authentication options.</li>
                <li><strong>Troubleshooting:</strong> Add common issues and solutions.</li>
                <li><strong>References:</strong> Link to official Azure Static Web Apps documentation.</li>
            </ul>
        </li>
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
