# Threat-Detection

<p><img src="https://redcanary.com/wp-content/uploads/Atomic-Red-Team-Logo.png" width="150px" /></p>

 
 This  is a library of SIGMA rules to detect attack techniques based on [MITRE ATT&CK®](https://attack.mitre.org/) framework. 
Security teams can use this to quickly create detection rules in their SIEM environments. The TTPs are executed in the system using [Atomic Red Team](https://github.com/redcanaryco/atomic-red-team/tree/master))

## Get started

You can use these SIGMA rules directly from the command line.
See the [Getting started]([https://github.com/redcanaryco/atomic-red-team/wiki/Getting-Started](https://github.com/SigmaHQ/sigma-cli))
page to install Sigma command line interface.



## Example
Download the SIGMA rule file from the repository

#For Splunk:
sigma convert -t splunk -p splunk_windows bloodhound-detection.yml

#For Elastic:
sigma convert -t lucene -p ecs_windows bloodhound-detection.yml





