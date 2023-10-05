# Oracle Maximum Availability Architecture (MAA)

**High availability** provides redundant components to go ahead and ensure your service is uninterrupted in case of a type of hardware failure. So if one server goes down, the other servers will be up. Ideally, you'll have a cluster to go ahead and provide that level of redundancy.

**Disaster recovery** protects us from a complete site outage. So if the site goes down entirely, we want to have a redundant site to be able to failover to. 

## Chaos Engineering

Chaos engineers take all this into consideration and build out the use cases to go ahead and test the system:

- network, server, and storage failures
- human errors 
- data corruption
- power failures or site failure
- application, database, server sofware updates
- data reorganization or changes
- application changes and optimizations

## MMA

The key goal of MAA is to achieve optimal high availability, data protection, and disaster recovery for Oracle customers at the lowest cost and complexity. 

MAA consists of reference architectures for various buckets of HA service level agreements, configuration practices, and HA lifecycle operational best practices. 

MMA reference architectures are applicable for non-engineered systems, engineered systems, non-cloud and cloud deployments.

![Oracle Maximum Availability Architecture (MAA)](../images/mma.png)