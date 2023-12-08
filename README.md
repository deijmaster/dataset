# dataset
test dataset on javascript librairies - focusing on XSS vulnerabilities.

### **Explanation of entries**

- **Identifier**: "060"
- **Snippet**: A JavaScript string that demonstrates an unsafe way of constructing an SQL query using user input, which can lead to SQL Injection.
- **Label**: "Vulnerable" - This code snippet is vulnerable to SQL Injection, which is a serious security vulnerability.
- **Vulnerability Type**: "SQL Injection" - Specifies the type of vulnerability.
- **Severity**: "High" - Indicates the severity level of the vulnerability.
- **Function Name**: "executeQuery" - The hypothetical name of the function where this snippet might be used.
- **Source**: "Database Interaction Guide" - An assumed source of the code snippet.
- **Timestamp**: "2020-09-10" - The date when this entry was supposedly created or last reviewed.
- **Reviewer Notes**: Provides context, explaining why the snippet is vulnerable.
- **Confidence Score**: "0.4" - A low score indicating lower confidence in the safety of the code, aligning with the vulnerable nature of the snippet.
