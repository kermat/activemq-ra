This resource agent will start/stop/monitor an ActiveMQ resource in a Pacemaker cluster.

Clone down the repository, and place the `activemq` resource agent inside of the, 
`$OCF_ROOT/resource.d/heartbeat`, directory. Then use, `# pcs resource describe activemq`,
or, `# crm ra info ocf:heartbeat:activemq`, for more information.
