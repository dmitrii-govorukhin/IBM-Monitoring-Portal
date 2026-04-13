# IBM Monitoring Portal

**Project:** 					  Deployment IBM Tivoli Monitoring System, Help Desk Integration.

**Consumer:**					  RF Pension Fund

**Program languages:**  Bash, PHP, SQL, JavaScript

**Description:**        The project involved the nationwide deployment of an IBM monitoring system across 87 regional monitoring sites. Following the phased deployment, technical support was provided, and the monitoring system was integrated with the help desk system. The repository contains individual files with my code and brief descriptions:

 - event_history_new.js - JavaScript for processing saved monitoring events and displaying them on the web portal (using AJAX and DataTable)
 - maintenance_screenshot.jpg - screenshot of the web portal for scheduled maintenance in technical facilities, integrated with the monitoring system to temporarily disable incident creation
 - Recursive_query_to_search_the_tree_of_parent_items.sql - recursive SQL query against an IBM DB2 database to search the tree of child configuration elements
 - runDeploy.sh - interactive Bash script for deploying regional monitoring servers on virtual machines running RHEL Linux 6.5
 - SCCD_trigger.php - PHP code for integrating monitoring system data with the technical support system

** Results / Key Findings ** The fully functional IBM Tivoli monitoring system has been remotely, operated via scripts, deployed across 87 regional monitoring centers. The total number of technical complexes being monitored exceeds 500, each of which includes its own server and network infrastructure. The monitoring system is integrated with the technical support system to enable immediate response to alarms and incidents, as well as to carry out scheduled maintenance.

**Illustration:**       Maintenance schedule as a part of the Monitoring Portal


![alt text](https://github.com/dmitrii-govorukhin/IBM-Monitoring-Portal/blob/main/maintenance_screenshot.jpg?raw=true)
