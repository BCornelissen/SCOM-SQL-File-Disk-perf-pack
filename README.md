# SCOM-SQL-File-Disk-perf-pack
This management pack brings together I/O statistics for SQL data files and log files directly from the SQL virtual file stats view into SCOM where you can report on these for any period of time. It can collect data from SQL 2005, 2008 and 2012.

Moved the project from TechNet Galleries to github repo.

Purpose

This management pack brings together I/O statistics for SQL data files and log files directly from the SQL virtual file stats view into SCOM where you can report on these for any period of time. It can collect data from SQL 2005, 2008 and 2012.


Introduction

Starting SQL 2005 SQL DBA’s have the possibility to use Dynamic Management Views and Functions to monitor the health of a server instance, diagnose problems, and tune performance. This management pack is specifically geared towards the sys.dm_io_virtual_file_stats view, which returns I/O statistics for data and log files. The view is used by DBA’s to view current counter values for each database file (data or log). It is a current point in time and these values are cumulative values since the last restart of the server. This management pack collects these values for use in viewing and reporting. There are no health state changes or alerts connected to these values. There are short time performance views and two reports with double Y axis to display longer term data. The long term data is translated from cumulative data into IOPS for each point in time.

Files

You can find all management pack files, optional override management packs and the management pack guide explaining it all in the zip file attached in the TechNet Gallery page. The current version of this management pack is 1.0.2.48 and released on
the second of June 2013.


General

This Management Pack is provided free of charge by the authors to the System Center and SQL community.

Written by Bob Cornelissen, David Scheltens, and Pavel Dzemyantsau
