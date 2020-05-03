# Pull Jira

# How to Run:
```
go run ./main.go <username> <password> <apiurl>
ex: go run /main.go user password https://your-domain.atlassian.net/rest/api/2/issue/createmeta
```

# Caution:
Proper Error handling not deployed yet. YMMV

## what it does
This program uses Basic Authentication to run an API Jira Search Query and print it to the command line.

It gives options for fields (not all) within a Jira API query.


Basic Auth Jira Documentation here:
https://developer.atlassian.com/cloud/jira/platform/basic-auth-for-rest-apis/

