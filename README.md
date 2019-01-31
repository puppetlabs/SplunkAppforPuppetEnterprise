# Splunk App for Puppet Enterprise

## Requirements to run this app

- Splunk Enterprise 7.0+
- Puppet Enterprise 2018.1.1+
- Splunk Add-on for Puppet Enterprise (Obtain from [Splunkbase](https://splunkbase.splunk.com/app/3610/) or [Github](https://github.com/puppetlabs/SplunkTAforPuppetEnterprise/)) — _This component collects data from Puppet Enterprise and stores it in Splunk._

### Installation steps

[FIXME:]

## Version history

### Version 2.0

- Support for Multiple Versions of Puppet Enterprise
- Rewrite of the Factor Pull, Customer Merge Dict Feature to Only Pull certain facts. 
- Added PE Metrics for MQ
- Added Compiliation Timing
- Filter for Multiple Version of Puppet Enterprise
- Integration of VictorOps for Notification and Alerting

### Version 1.0

- Includes Support for Self Signed (8081) + HTTP (8080) for PuppetDB Calls
- Rewrite of all Extraction Fields + Cleanup of Resources, Classes, and CertName
- Fixed API Key Storage
- Fixed Title to Match Pulls
- Fixed Help Text to Match Fields
- Fixed Issue with Memoryleak on Timeout API Calls

## Support

Are you a Splunk + Puppet customer who enjoys sharing knowledge and want to put some great features into an open-source project? We encourage you to [submit issues](https://github.com/puppetlabs/SplunkTAforPuppetEnterprise/issues/new) and pull requests so that we can make this app better and help the community as a whole get better insight to their Puppet Enterprise deployments.

Feel free to leave comments or questions. We are here to make this community project more adaptive to all types of use cases.
