# PiracyShield Routing Table

Aggregated elaboration of PiracyShield to ensure efficient Routing Performance!

## File Structure

In order to improve Routing Performance and allow Routing on low-end Routers, we provide aggregations of the blocked IPs. 
If a /24 subnet contains more than N IPs (where N is known in N.txt), the whole /24 is used instead of the IPs. If two adjacent /24 are used, they are merged into /23 and so on.

We only provide an elaboration of actual data, real data is not provided here.

## How to use this data

`full.txt` contains the raw list of IPs we randomly generated for this test.  
`254.txt` contains the aggregated prefixes that are adjacent and fully used.  
`10.txt` contains the aggregation of all the prefixes, plus the aggregation of all the /24 that contained more than 10 IPs. 

#### Why summarizing to /24?

Because this is not meant for blocking. This is not a censorship tool.
This is freedom, we don't care if your network runs on a Mikrotik hEx Lite, you must be able to bypass censorship and damages to your freedom. 
Having less rows in your RoutingTable can help your old router not to collapse under the mass of randomly blocked IPs.

    This won't help much as the data is randomly generated and not real data :)
