## Overview
[`org.apache.solr:solr-velocity`](http://search.maven.org/#search%7Cga%7C1%7Ca%3A%22solr-velocity%22)
Directory traversal vulnerability in SolrResourceLoader in Apache Solr before 4.6 allows remote attackers to read arbitrary files via a .. (dot dot) or full pathname in the tr parameter to solr/select/, when the response writer (wt parameter) is set to XSLT.  NOTE: this can be leveraged using a separate XXE (XML eXternal Entity) vulnerability to allow access to files across restricted network boundaries.

## References

- [Redhat Bugzilla](https://bugzilla.redhat.com/CVE-2013-6397)
- [Nicolas Grégoire Blog](http://www.agarri.fr/kom/archives/2013/11/27/compromising_an_unreachable_solr_server_with_cve-2013-6397/index.html)
