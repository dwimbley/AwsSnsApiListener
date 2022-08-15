# AWS SNS API Listener
AWS SNS API Listener. Responds to published messages to an SNS topic. Handles auto confirming the initial request that comes in when endpoint is subscribed to an SNS topic.

Has failover capabilities where if handling of the processing of the SNS published message fails, it will save message to SQS for later fail over processing.
