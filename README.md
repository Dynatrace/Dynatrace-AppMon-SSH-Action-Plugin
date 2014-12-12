## Overview

![images_community/download/attachments/88245112/icon.png](images_community/download/attachments/88245112/icon.png)

The SSH Client Action Plugin executes any arbitrary command or script on any SSH accessible remote machine. It can be used as an Incident Action plugin to perform some action on a remote machine as a
result of an incident triggering.

## Plugin Details
| Name | Action Plugin
| :--- | :---
| Version | 1.0.2
| Author | Joe Hoffman (joseph.hoffman@compuware.com)
| Supported dynaTrace Versions | >= 5.5
| License | [dynaTrace BSD](dynaTraceBSD.txt)
| Support | [Community Supported](https://community.compuwareapm.com/community/display/DL/Support+Levels)
| Downloads | [com.dynatrace.sshClient_1.0.2.jar](com.dynatrace.sshClient_1.0.2.jar)

## Key benefits

Ensures encrypted communication with remote machine  
Executes any command or script  
Open source: Adaptable as necessary  
OS Independent  
Uses the jsch (java Secure Channel) encryption package which is an implementation of SSH2

## Additional Notes

It accepts SSH connections from whatever responds on port 22 on the specified machine. This means that it could be vulnerable to a Man in the Middle attack. Therefore we suggest running it on and
across only trusted networks.  
This plugin requires an SSH service be running on the specified remote machine. FreeSSHd is a good option for any OS that does not have SSH natively.

## Configuration

![images_community/download/attachments/88245112/sshactionplugin.png](images_community/download/attachments/88245112/sshactionplugin.png)

## Debugging

Output from the executed command is written to the plugin log which can be found in the log directory of the Collector where the plugin is being executed.

**Additional suggested Improvements**

  * Provide a switch to be able to disable logging for verbose commands 

  * Regex Match for output match 

  * Configurable as a task 

  * Success criteria 

  * Make the SSH port configurable 

  * Most of these features would be attainable by adding this SSH functionality to the Generic Execution Plugin and making the SSH feature optional. 

