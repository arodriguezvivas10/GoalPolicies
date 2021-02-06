## intent:service_policies

- Hey Nora, I want my network to have [at least](constraint) 80 Gb

- The resnet cap is currently 200 [gigabytes](threshold) per each 7 day period of combined [incoming](service) [and](junction) [outgoing traffic](service)

- When a total of 18 [gigabytes](threshold) of [data](service) is reached, the individual's [bandwidth](metric) rate [limit](constraint) is set to 2 [Mbps](threshold-unit)

- [limit](constraint) [torrent](service) traffic for guests to 100 [Mbps](threshold-unit)

- [limit](constraint) [torrent](service) traffic to 100 [Mbps](threshold-unit)

- [limit](constraint) to 100 [Mbps](threshold-unit) the [bandwidth](metric) [torrent](service) traffic can consume

- [Streaming](service) traffic should receive [highest](constraint) [priority](threshold-unit), [lowest](constraint) [delay](metric), [lowest](constraint) [jitter](metric), [and](junction) [highest](constraint) [bandwidth](metric)

- [Peer-to-peer](service) traffic should receive [lowest](constraint) [priority](threshold-unit), [highest](constraint) [delay](metric), [lowest](constraint) [jitter](metric), [and](junction) [highest](constraint) [bandwidth](metric)

- [FTP](service) traffic should receive [highest](constraint) [bandwidth](metric).

- [VoIP](service) traffic should receive [delay](metric) [lower than](constraint) 20 [ms](threshold-unit) [and](junction) [bandwidth](metric) [higher than](constraint) 128[kbps](threshold-unit).

- [SNMP](service) traffic should receive [priority](threshold-unit) [higher than](constraint) 500 [and](junction) [bandwidth](metric) [lower than](constraint) 16[kbps](threshold-unit).

- [ssh](service) traffic should receive [bandwidth](metric) [higher than](constraint) 1024 [kbps](threshold-unit), [delay](metric) [lower than](constraint) 50 [ms](threshold-unit), [and](junction) [lowest](constraint) [jitter](metric).

- [HTTP](service) traffic should receive [lowest](constraint) [priority](threshold-unit)

- [Streaming](service) traffic should receive [highest](constraint) [priority](threshold-unit) [or](junction) [lowest](constraint) [delay](metric), [and](junction) [bandwidth](metric) [higher than](constraint) 512[kbps](threshold-unit).

- [VoIP](service) traffic should receive [highest](constraint) [priority](threshold-unit), [delay](metric)[lower than](constraint) 200 [ms](threshold-unit), [lowest](constraint) [jitter](metric), [and](junction) [bandwidth](metric) [higher than](constraint) 128[kbps](threshold-unit).

- [HTTP](service) services should receive bandwidth [higher than](constraint) 100 [kbps](threshold-unit) [and](junction) [delay](metric)[lower than](constraint) 300[ms](threshold-unit)

- [Streaming](service) services should receive [bandwidth](metric) [higher than](constraint) 20 [Mbps](threMbpsshold-unit) [and](junction) [delay](metric) [lower than](constraint) 1 [ms](threshold-unit)

- [Conversational voice](service) will have a [QCI](metric) of 1 (100 [ms](threshold-unit) in [delay](metric), 2 of [priority](threshold-unit) leve [and](junction) 10^-2 in [packet loss rate](metric) metric

- [Video Streaming](service) communications will have a [QCI](metric) (QoS Class Identifier) of 6 ([delay](metric) [not superior to](constraint) 300[ms](threshold-unit), 6 of [priority](threshold-unit) level [and](junction) 10^-6 of packet loss rate

- [Video Streaming](service) communications will have a [QCI](metric) (QoS Class Identifier) of 6 ([delay](metric) not superior to 300[ms](threshold-unit), 6 of [priority](threshold-unit) level [and](junction) 10^-6 of packet loss rate
- Customers using our [Quickstream DSL](service) service can expect [latency](metric) of [less than](constraint) 50[ms](threshold-unit) on our network.

- Customers using our [Quickstream DSL](service) service can expect [latency](metric) of [less than](constraint) 50[ms](threshold-unit) on our network.

- [Availability](metric) of the [VoIP](service) service must be 99.999[%](threshold-unit)

- The total [packet delay](metric) budget of the [Streaming video transfer](service) without buffering must be [between](constraint) 50 to 300 [ms](threshold-unit)

- [internet](service) is [limited to](constraint) 3 [Mbps per host](threshold-unit)

- [P2P](service) application is separately [capped at](constraint) 30 [Mbps](threshold-unit) for the entire campus

- The [resnet](service) [cap](constraint) is currently 200 [gigabytes](threshold-unit) per each 7 day period of combined incoming [and](junction) outgoing traffic

## intent:endpoint_resource_policies

- The individual will have a 4 [Mbps](threshold-unit) [bandwidth](metric) rate [limit](constraint)

- If the [capacity](metric) of a [virtualized network](endpoint) function [exceeds](constraint) 80[%](threshold-unit) a new instance must be deployed

- The mean [CPU](endpoint) [load](metric) of [VM’s](endpoint) can [not exceed](constraint) 80[%](threshold-unit) [and](junction) can [not be under](constraint) 20[%](threshold-unit)

- No individual service or system running on the [wired/wireless network](endpoint) should use [more than](constraint) 10 [gigabytes](threshold-unit) per day](threshold) of [bandwidth](metric), regardless of whether it is in inbound or outbound over the commodity [network link](endpoint)

- [limit](constraint) [servers](endpoint) [bandwidth](metric) to 5[gbps](threshold) [between](constraint) 4pm [and](junction) 7pm

- [limit](constraint) the [bandwidth](metric) to 5 [Gb](threshold-unit) for [rack servers](endpoint) from 4 pm until 7 pm

- [limit](constraint) [rack servers](endpoint) to 5[gbps](threshold-unit) during 5pm to 7pm

## intent:endpoint_user_policies

- guests' network is [rate-limited to](constraint) 5 Mb/s per user

- [internet](service) is limited to 3 [Mbps per host](threshold-unit)

- [faculty members](endpoint) have 500 [GB per week](threshold) of [free](constraint) [network use](metric)

- [Quotas](constraint) for [students](endpoint) are 5000 Megabyte per hr download [and](junction) 2000 Megabyte per hour upload

- [Reduce](constraint) the [download rate](metric) for [faculty](endpoint) members to 20 [Mbps](threshold-unit)

- Lumi, [set to](constraint) 10 [kbps](threshold-unit) the [upload rate](metric) for [faculty](endpoint)

- [Set to](constraint) 1 Gbps [bandwidth](metric) [limit](constraint) for the traffic to [DMZ](endpoint)

- [students](endpoint) should [not use more than](constraint) five [gigabytes](threshold) of [bandwidth](metric) per week

- We provide a [quota](constraint) to all [students](endpoint) of 1 [GB per week](threshold) of usage

- Define a [quota of](constraint) 10 [GB per week](threshold-unit) for all [students](endpoint)

- [limit](constraint) [bandwidth](metric) usage to 50 [Mbps](threshold-unit) for [professors](endpoint).

- set a 10 [GB per week](threshold-unit) download  quota for [students in dorms](endpoint)

- The [individual](endpoint) will have a 4 [Mbps](threshold-unit) [bandwidth rate](metric) [limit](constraint)

- [guests' network](endpoint) is [rate-limited to](constraint) 5 [Mb/s per user](threshold-unit)

- [limit](constraint) [students](endpoint) in the [dorm](endpoint) to 10 [GB per week](threshold-unit)

- set quota to 10 [GB per week](threshold-unit) at [labs](endpoint)

- set quota to 10 [GB per week](threshold-unit) at [servers](endpoint)

- Set quota to 10 [GB per week](threshold-unit) at [guest](endpoint)

 -set quota to 10 [GB per week](threshold-unit) at [LAN](endpoint)

- Set quota to 10 [GB per week](threshold-unit) at [dorms](endpoint)

- [limit](constraint) traffic to 10 [GB per week](threshold-unit) at [dorms](endpoint)

- for endpoint dorms set quota download 10 [GB/wk](threshold-unit)

- [students](endpoint) shall download [no more than](constraint) 1000000 [megabytes per week](threshold-unit)

- please [limit](constraint) [bandwidth](metric) to 5 [Gigabits per second](threshold-unit) for the [server racks](endpoint) everyday from 4 PM to 7PM

- [limit](constraint) the [bandwidth](metric) in [server racks](endpoint) to 5gbps [between](constraint) 4pm [and](junction) 7pm

- set a [maximum](constraint) of 5 [gbps](threshold) to the [servers](endpoint) from 4pm to 7pm

- [students](endpoint) should download [no more than](constraint) 10 GB of [data](service) in a week

- set [torrent](service) traffic from [guest](endpoint) to 100 [Mbps](threshold-unit)

- [limit](constraint) the [bandwidth rate](metric) of the [server racks](endpoint) to 5 gbps from 4pm to 7pm

## intent:mixed_policies

- [P2P](service) application is separately capped at 30 [Mbps](threshold-unit) for the entire campus

- You may [not run](constraint) [FTP](service), telnet, peer-to-peer, [HTTP](service), IRC, DNS [and](junction) mail server(server) on your resnet or UIC wireless

- [students](endpoint) [data](service) [limit](constraint) is 100 [GB per week](threshold)

- [Deny](constraint) [ssh](service) access to [students](endpoint)

- Lumi, please [set to](constraint) [1 GB per day](threshold) the [download](service) [limit](constraint) for [guests](endpoint)

- [Grant](constraint) [ssh](service) access to [professors](endpoint)

- [limit](constraint) in 10 [Mbps](threshold-unit) the [download rate](metric) of [dorms](endpoint) from [internet](service)

- [students](endpoint) may use [up to](constraint) 10 GB of [data](service) weekly

- Please Lumi, [block](constraint) [Streaming](service) traffic for [students](endpoint) [and](junction) set a 10 [Mbps](threshold-unit) [bandwidth](metric) [limit](constraint)

- We provide a [data plan](service) [quota](constraint) for all [staff](endpoint) of 10 [GB per day](threshold-unit)

- [students](endpoint) can download  [up to](constraint) 10 [GB per week](threshold-unit) of [data](service)

- The [response time](metric) for [signaling procedures](service) of a [mobile network](endpoint) must be [less than](constraint) 1 [ms](threshold-unit)

- A [virtual machine](endpoint) to deploy the [access](service) [and](junction) [mobility](service) function must be [formed by](constraint) 2 [cores](threshold-unit), 1 [GB of RAM](threshold-unit) [and](junction) 10 [GB of hard disk](threshold-unit)

- A [slice](endpoint) for [tactile internet](service) must guarantee a [maximum](constraint)](constraint) [delay](metric)of 1 [ms](threshold-unit)

- I want the [torrent](service) traffic from [guest users](endpoint) to be [no more than](constraint) 100 [Mbps](threshold-unit)

 -[limit](constraint) [network usage](service) of all [students](endpoint) in the dorms to [no more than](constraint) 10 [GB per seven days](threshold-unit)

- the achievable [data rate](metric) across the coverage area must be 100 [Mbits per second](threshold-unit)  for [real-time](service) services in the [mobile network](endpoint)

- [latency](metric) for [client](endpoint) B must be [less than](constraint) 10 [ms](threshold-unit) [and](junction) 100 [Mbps](threshold-unit) of [bandwidth](metric), [and](junction) allow [HTTPS](service) only, everyday from 9:00 to 18:00

- Quotas for [students](endpoint) are 5000 [Megabyte per hr](threshold-unit) [download](service) [and](junction) 2000 [Megabyte per hour](threshold-unit) [upload](service)

- When a total of 18 [gigabytes](threshold-unit) of [data](service) is reached, the [individual's](endpoint) [bandwidth](metric) rate [limit](constraint)](constraint) is set to 2 [Mbps](threshold-unit)

- [torrent](service) traffic must be allowed for [guest](endpoint) but [limited to](constraint) 100 [Mbps](threshold-unit)

- for the [guest network](endpoint), [limit](constraint) the [traffic of torrent](service) protocol to 100 [Mbps](threshold-unit)

- [students](endpoint) shall [download](service) [no more than](constraint) 1000000 [MB per week](threshold-unit)

- put a [download](service) quota for [students](endpoint) of 10 [GB per week](threshold-unit)

## intent: other_policies

- You may not run any services (e.g., [FTP](service) services, listservers, [P2P](service) [file sharing](service) [servers](endpoint), publishing files via generic file services, etc.) via NYU's resnet or NYURoam wireless networks

- [students](endpoint) have a quota of 5 GB per day The quota is reset at 6am

- [students](endpoint) have 200 GB of [Free](constraint) monthly usage

- No individual service or system running on the wired/wireless network should use [more than](constraint) 10 [gigabytes](threshold) of [bandwidth](metric) per day, regardless of whether it is in inbound or outbound over the commodity network link

- [students](endpoint) 10 GB a day download quotas are on 10 AM to Midnight
- There is a 6 GB per 24-hour period upload or download [data](service) transfer [limit](constraint), starting at midnight of each day, on all your combined traffic on resnet [and](junction) UIC wireless

- [Increase](constraint) the [bandwidth](metric) consumption [limit](constraint) for [professors](endpoint) to 100 [Mbps](threshold-unit)

- [Prioritize](constraint) [VoIP](service) traffic on the meeting room 23 from 13:00 to 14:00

- Grant [SFTP](service) access to all [students](endpoint) from 08:00 to 17:00

- [Prioritize](constraint) [Netflix](service) traffic from 18:00 to midnight

- Set users [bandwidth](metric) to 500 [kbps](threshold-unit) when the 100 [Gb per month](threshold) quota is reached

- [between](constraint) [internet](service) [and](junction) [servers](endpoint) [limit](constraint) traffic to 5Gbps start 16:00 finish 19:00

- System periodically monitors (e.g., 20 minutes) the connections on its network in the aggregate to determine the condition of the network. 

- The available [instances](endpoint) for the [control](service) function is 5.

- For the special weekend event, the [capacity](metric) of the network should be increased to twice the usual

- The system will trigger an overuse notification if the average for either inbound or outbound usage [exceeds](constraint) 10 [GB per week](threshold-unit)

- please lumi, block f2movies traffic from [internet](service) to [students](endpoint) [labs](endpoint)

- [Dismiss](constraint) [rate limiting](servic)  for [faculty](endpoint) members
