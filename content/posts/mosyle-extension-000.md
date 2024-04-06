---
layout: default
title: Mosyle Extension
nav_order: 010
has_children: true
description: "An extension is a microservice working on its own in a container independently from the ClearPass operating system, which is used by ClearPass to communicate with external systems."
categories: [Class-1]
---
# Mosyle Extension
By itself, ClearPass is already a very powerful tool. ClearPass becomes even more powerful with the use of extensions. An extension is a microservice working on its own in a container independently from the ClearPass operating system, which is used by ClearPass to communicate with external systems. Because they are developed as microservices, they can be integrated into ClearPass without any major changes to the OS. It is very flexible and it's easy to add and remove extensions. You can think of it as applications on a phone. We can install, update, remove applications without having to update the phone OS.

Extensions allow ClearPass to interact with external systems. They can be leveraged to perform advanced authentication, two-factor authentication, apply policies or firewall rules, onboard guests onto the Wi-Fi networks or manage BYOD devices. The list of use cases is endless. Extensions are easy to install from the ClearPass Extensions Store. In a cluster, extensions can be installed on a subscriber independently of the publisher.

To view and work with the list of extensions and to install and configure new extensions, go to Guest > Administration > Extensions. The **Manage Extensions** list view opens. All extensions that have been installed are included in the list. Information shown for each extension includes its name, version, state (running or stopped), hostname, and IP address.

*Figure 1: The Manage Extensions List View*

![image-20220720163122598](C:\Users\guptabi\AppData\Roaming\Typora\typora-user-images\image-20220720163122598.png)



| **Name**              | The name of the extension.                                   |
| --------------------- | ------------------------------------------------------------ |
| **Version**           | The version number of the extension.                         |
| **State**             | The extension’s current state, either **Running** or **Not Running**. |
| **Hostname**          | The hostname for the extension.                              |
| **IP Address**        | The IPv4 address used for the extension. This address will be within the network range 172.17.0.1/16. |
| **Filter**            | Lets you filter for an extension by name, version, state, hostname, or IP address. |
| **Show Details**      | Displays details for the extension such as its state, instance ID, store ID, and any content items. |
| **Reinstall**         | Opens the **Extension Reinstall** form, which lets you delete and then reinstall the extension. You may also modify the IP address. When it is reinstalled, it retains its previous configuration and includes any current Extension Store updates for the extension. After it is reinstalled, the extension’s details show the time it was installed. |
| **Delete**            | Deletes the extension. You will be asked to confirm the deletion. |
| **Stop**              | Stops a running extension.                                   |
| **Restart**           | Restarts a stopped extension.                                |
| **Show Logs**         | Displays log messages for extensions actions and various extension-related actions. |
| **Configuration**     | The form expands to include the **Extension Configuration** form with the extension’s current configuration, if any. If you modify the default configuration, you must then select the **Restart extension after updating configuration** check box in order to have the changes take effect, and then click **Save Changes**. A progress bar is displayed while the extension is being restarted. |
| **Install extension** | To install an extension, click this link in the list or in the upper right corner. The initial setup page of the **Install Extension** form opens. See the next section, [Installing Extensions](https://www.arubanetworks.com/techdocs/ClearPass/6.9/Guest/Content/AdministrationTasks1/ExtensionInstall.htm). |
| **Refresh**           | Clears any filter selections and refreshes the full list of installed extensions. |
