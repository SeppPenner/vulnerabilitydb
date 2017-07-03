## Overview
[`org.apache.activemq:activemq-jaas`](http://search.maven.org/#search%7Cga%7C1%7Ca%3A%22activemq-jaas%22)
The LDAPLoginModule implementation in the Java Authentication and Authorization Service (JAAS) in Apache ActiveMQ 5.x before 5.10.1 allows remote attackers to bypass authentication by logging in with an empty password and valid username, which triggers an unauthenticated bind. NOTE: this identifier has been SPLIT per ADT2 due to different vulnerability types. See CVE-2015-6524 for the use of wildcard operators in usernames.

## References
- [NVD](https://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2014-3612)