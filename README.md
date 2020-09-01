# virtual-hub

There are two main options that we have come up with to be able to get the necessary information out of the virtulized FTC Robot Controller (Android Phone) and into the Virtualized field (Unity instance).
	1: Modify the FTC Robot Controller libraries https://github.com/ftctechnh/ftc_app to send messages (JMS to kafka for streaming capibilities?) with intended physical movements to the field reciever
	2: Create a USB Interface to intercept the FTC Robot Controller commands and send them to the field reciever

Here are some useful links:

	https://www.revrobotics.com/software/#REVHubInterfaceSoftware
	https://kafka.apache.org/25/documentation/streams/core-concepts
	https://github.com/REVrobotics/kernel-controlhub-android
	https://github.com/REVrobotics/uboot-controlhub-android
