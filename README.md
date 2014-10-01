<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>Overview</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>Overview</h1>
    <p>
            <img src="images_community/download/attachments/88245112/icon.png" alt="images_community/download/attachments/88245112/icon.png" class="confluence-embedded-image" />
            </p>
    <p>
The SSH Client Action Plugin executes any arbitrary command or script on any SSH accessible remote machine.  It can be used as an Incident Action plugin to perform some action on a remote machine as a result of an incident triggering.    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">SSH Action Plugin</strong>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Plug-In Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1.0.2    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Compatible with    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
dynaTrace 4.x    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Joe Hoffman (joseph.hoffman@compuware.com)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels">Community Supported</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Downloads    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_88440991_1_com.dynatrace.sshClient_1.0.2.jar">com.dynatrace.sshClient_1.0.2.jar</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Key benefits    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Ensures encrypted communication with remote machine<br/>Executes any command or script<br/>Open source: Adaptable as necessary<br/>OS Independent<br/>Uses the jsch (java Secure Channel) encryption package which is an implementation of SSH2    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Additional Notes    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
It accepts SSH connections from whatever responds on port 22 on the specified machine.  This means that it could be vulnerable to a Man in the Middle attack.    Therefore we suggest running it on and across only trusted networks.<br/>This plugin requires an SSH service be running on the specified remote machine.  FreeSSHd is a good option for any OS that does not have SSH natively.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Configuration    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/88245112/sshactionplugin.png" alt="images_community/download/attachments/88245112/sshactionplugin.png" class="" />
            </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
        </tr>
</tbody>        </table>
            </div>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Debugging    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Output from the executed command is written to the plugin log which can be found in the log directory of the Collector where the plugin is being executed.    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    <p>
<strong class=" ">Additional suggested Improvements</strong>    </p>
<ul class=" "><li class=" ">    <p>
Provide a switch to be able to disable logging for verbose commands    </p>
</li><li class=" ">    <p>
Regex Match for output match    </p>
</li><li class=" ">    <p>
Configurable as a task    </p>
</li><li class=" ">    <p>
Success criteria    </p>
</li><li class=" ">    <p>
Make the SSH port configurable    </p>
</li><li class=" ">    <p>
Most of these features would be attainable by adding this SSH functionality to the Generic Execution Plugin and making the SSH feature optional.    </p>
</li></ul>    <p>
    </p>
    <div class="tablewrap">
        <table>
<thead class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
&nbsp;    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="SSH_Action_Plugin.html">File</a>    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="SSH_Action_Plugin.html">Modified</a>    </p>
            </td>
        </tr>
</thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
        <p>
Java Source                    <a href="https://community/download/attachments/88245112/com.dynatrace.sshClient_1.0.2.jar?api=v2">com.dynatrace.sshClient_1.0.2.jar</a>    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Jul 13, 2012by<a href="    /community/display/~joseph.hoffman@compuware.com ">Joe Hoffman</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="2">
        <p>
    </p>
    <p>
Labels    </p>
<ul class="label-list has-pen "><li class="no-labels-message ">    <p>
No labels    </p>
</li><li class="labels-edit-container ">    <p>
<a href="SSH_Action_Plugin.html">Edit Labels</a>    </p>
</li></ul>    <p>
    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
<ul class=" "><li class="drop-zone-text hidden ">    <p>
Drag and drop to upload or browse for files    </p>
            <img src="images_community/images/icons/wait.gif" alt="images_community/images/icons/wait.gif" class="plugin_attachments_dropzone_uploadwaiticon" />
        </li></ul>    <p>
Upload fileFile description    </p>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
