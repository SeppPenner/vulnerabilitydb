## Overview
[`org.apache.camel:camel-snakeyaml`](http://search.maven.org/#search%7Cga%7C1%7Ca%3A%22camel-snakeyaml%22)
Apache Camel's `camel-snakeyaml` is vulnerable to arbitrary code execution. User input is sent to object de-serialization, allowing attackers to craft malicious calls containing java code that will run on the server. 

## References
- [Apache Camel Security Advisory](http://camel.apache.org/security-advisories.data/CVE-2017-3159.txt.asc?version=1&modificationDate=1486565167000&api=v2)
- [CVE](https://www.cvedetails.com/cve/CVE-2017-3159/)
- [Jira Issue](https://issues.apache.org/jira/browse/CAMEL-10575)
