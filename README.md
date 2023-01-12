Created a multicast messaging android app that can send each message entered by the user to every AVD in the group.
1. Key-value pairs representing the messages were stored in a file-based content provider.
2. Implementation of the ISIS algorithm maintained real-time total and FIFO ordering.
3. The algorithm's decentralized structure was used to deal with an app instance failure mid-execution.
4. AWS EC2 was used to host the website.