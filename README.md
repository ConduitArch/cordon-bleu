P13n OpsWorks Cookbooks
=======================
java: Installs either OpenJDK or Sun/Oracle Java - taken from
https://github.com/opscode-cookbooks/java and adapted for OpsWorks. If you want
to use Oracle Java, make sure to have the following in your custom JSON:
```
{ "java": { "oracle": { "accept_oracle_download_terms": true  }  }  }
```