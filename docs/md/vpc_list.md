---
date: 2018-02-28T23:59:59Z
title: "vpc list"
slug: vpc_list
url: /command/vpc_list
---
## vpc list

list counts of each VPC type

### Synopsis


list counts of each VPC type

```
vpc list [flags]
```

### Options

```
  -h, --help              help for list
  -c, --obj-counts        list the number of objects per type
  -t, --obj-type string   List objects of a given type. Valid types: ethlink, mgmt, vmnic, vpc-link, vpcnat, vpcp, vpcrtr, vpcsw (default "all")
  -s, --sort-by string    Change the sort order within a given type: id, name (default "id")
```

### Options inherited from parent commands

```
  -F, --log-format string   Specify the log format ("auto", "zerolog", or "human") (default "auto")
  -l, --log-level string    Change the log level being sent to stdout (default "INFO")
      --use-color           Use ASCII colors
  -P, --use-pager           Use a pager to read the output (defaults to $PAGER, less(1), or more(1))
  -Z, --utc                 Display times in UTC
```

### SEE ALSO
* [vpc](/command/vpc)	 - vpc configures and manages VPCs

