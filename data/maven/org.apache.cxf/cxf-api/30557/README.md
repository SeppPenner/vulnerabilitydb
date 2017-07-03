## Overview
[`org.apache.cxf:cxf-api`](http://search.maven.org/#search%7Cga%7C1%7Ca%3A%22cxf-api%22)
Apache CXF before 2.6.14 and 2.7.x before 2.7.11 allows remote attackers to cause a denial of service (memory consumption) via a large request with the Content-Type set to text/html to a SOAP endpoint, which triggers an error.

## References
- [NVD](https://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2014-0109)