# CVE Repo

This repo is a collection of exploits that I have discovered and currently have CVEs on. 


## Confirmed CVEs 

### CVE-2024-7303

[Full Writeup](https://github.com/cl4irv0yance/CVEs/blob/main/CVE-2024-7303/CVE-2024-7303.md)

[NVD Listing](https://nvd.nist.gov/vuln/detail/CVE-2024-7303)

### Overview

In Version 1.0 of the Online Blood Bank Management application, Stored Cross-Site Scripting can be performed from the /request.php page via unknown functionality of the request.php component. An attacker can supply malicious commands to be stored and executed when a user navigates to the 'viewrequest.php' page or when an admin navigates to the /admin/request.php page.

### CVE-2024-7320

[Full Writeup](https://github.com/cl4irv0yance/CVEs/blob/main/CVE-2024-7320/CVE-2024-7320.md)

[NVD Listing](https://nvd.nist.gov/vuln/detail/CVE-2024-7320)

### Overview 

In Version 1.0 of the Online Blood Bank Management System application, a SQL injection vulnerability was found in the '/admin/index.php' file and the '/index.php file' of the 'Online Blood Bank Management System' project. The reason for this issue is that attackers inject malicious code from the parameter "user" and use it directly in SQL queries without the need for appropriate cleaning or validation. This allows attackers to forge input values, thereby manipulating SQL queries and performing unauthorized operations, allowing access to both the user console page as well as the admin user page.

No login or authorization is required to exploit this vulnerability

### CVE-2024-7321

[Full Writeup](https://github.com/cl4irv0yance/CVEs/blob/main/CVE-2024-7321/CVE-2024-7321.md)

[NVD Listing](https://nvd.nist.gov/vuln/detail/CVE-2024-7321)

### Overview 

In Version 1.0 of the Online Blood Bank Management application, A Stored Cross Site Scripting vulnerability was identified in the User Registration (signup.php) of the 'Online Blood Bank Management System' project, that affects both the 'register.php' and /admin/user.php application components. Malicious code can be injected within both the 'user' parameter due to improper sanitization, filtering, sanitization and implementation of other XSS prevention mechanisms.

