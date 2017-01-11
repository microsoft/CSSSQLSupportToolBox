# CSS Support Tools

This repro contains links to various tools developed and used by Microsoft SQL Server support.

## Pssdiag & Sqldiag manager
  This is data collection tool for performance issues.  It collects DMV, perfmon, profiler trace or extended events (xevents) data for support analysis.  [Pssdiag & Sqldiag Manager repo](https://github.com/Microsoft/DiagManager). 

## SQL Nexus 
   This is data analysis tool. It analyzes data collected by pssdiag or Sqldiag. [SQL Nexus codeplex project](http://sqlnexus.codeplex.com/) (to be migrated to GitHub repro)

## RML Utilities
  RML Utilities process, aggregate and replay profiler trace files.  SQL Nexus depends on RML Utilities to process profiler traces.

License
see license.md