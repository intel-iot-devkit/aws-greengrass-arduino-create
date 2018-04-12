# Equipment Activity Monitor Device Service

The Equipment Activity Monitor device service is an integration component provided as part of the Intel How to Code Samples for AWS Greengrass. It is designed to act as a proxy between AWS IoT services and the actual hardware. It presents to AWS IoT with the security identity of the device it is managing and keeps the device shadow for the device in AWS IoT Device registry in sync pushing sensor values and performing hardware updates as needed.
