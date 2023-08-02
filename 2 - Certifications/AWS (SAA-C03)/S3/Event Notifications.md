
Can allow to watch certain events, for example S3:ObjectCreated, S3:ObjectRemoved, etc.

You can filter the events to allow for example only watch all .jpg files (*.jpg).

Use case example: Generate a thumbnail for each uploaded image.

Notification can be delivered within seconds but sometimes can take a minute or more.

The notifications require the Access Policy that allows them to send messages, invoke a function or publish on the needed service.

Amazon EventBridge allows you to setup rules for over 18 services as destinations.
It also gives:
- Advanced control and filtering options when rules are declared as JSON.
- Multiple destinations
- Archive, Replays and Reliable delivery for events

