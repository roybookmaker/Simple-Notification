**Custom Angular Notification Module**

This Angular Notification Module is designed to streamline and enhance the notification process within Angular projects. Originally created for personal use, this module offers a simple yet adaptable framework for managing notifications. It provides a foundational structure that can be seamlessly integrated into various Angular applications.


**Features:**
Customizable Configuration: Tailor notifications to suit specific project needs by easily adjusting configurations.
Ease of Integration: Simple integration into Angular projects, ensuring a smooth implementation process.
Flexibility: Adaptable to diverse notification requirements, enabling developers to create tailored solutions.
Extensibility: Built with extensibility in mind, allowing for easy expansion and modification as per project demands.


**Usage Instructions:**

**Installation**: Easily integrate this component by importing this component into your project.

**Configuration**: This component is ready-use. But you can change how the component works or styles to your liking.
**Note: This module is provided as-is, and users are encouraged to configure it according to their individual project needs.**

**Usage**:
**To use this component, you can import the Service file into your component :**

_import { NotificationService } from "../shared-component/notification/notification.service";_

**Add the service to the constructor**

_public constructor(
  private notificationService: NotificationService
) {}_

**Call the service to show the notification on any function you like (pick one that suit the condition)**

* _this.notificationService.showNotification("Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.", "success");_
* _this.notificationService.showNotification("Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.", "warning");_
* _this.notificationService.showNotification("Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.", "info");_
* _this.notificationService.showNotification("Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.", "success");_
* _this.notificationService.showNotification("Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.", "error");_


**Getting Started**:
Explore the comprehensive documentation for detailed instructions on installation, configuration, and implementation.


**License**:
This project is licensed under MIT License, ensuring flexibility for usage and modification. Refer to the LICENSE file for more details.
