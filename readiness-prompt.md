Verify that my machine is ready to run the Electric Wealth application. Do not install, modify, or start anything.

Check and report:
1. Git is installed.
2. Node.js is installed and major version is 24 or higher.
3. npm is installed.
4. Java is installed and major version is 21 or higher.
5. The TD artifact repositories are reachable:
   - Maven: https://rp.td.com/repository/tdu-maven-group/
   - npm: https://rp.td.com/repository/npm-all/
   - Report the HTTP status code for each URL. HTTP 200 is PASS; any other response or connection failure is FAIL.
6. Maven Wrapper prerequisites are available:
   - Java is on PATH.
7. Ports 4200 and 5173 are available, or identify the process using either port.

Treat the required version or any higher version as PASS. Treat lower versions, missing tools, unavailable TD Maven or npm repository access, or occupied required ports as FAIL.

Provide a clear PASS/FAIL table with detected versions, HTTP status codes, failures, and exact remediation commands. Do not start the application unless I explicitly ask.
