# Leapp Upgrade Metadata for RHEL

https://access.redhat.com/articles/3664871

## Instructions

Note: Please ensure that you are always using the latest builds of leapp and the 
leapp-repository packages.

For a successful in-place upgrade of RHEL versions supported by the Leapp utility, 
the data files must be extracted into the /etc/leapp/files/ directory on the target system.

The data files include RPM package changes (pes-events.json), RPM repository mapping 
(repomap.json; original repomap.csv have become obsoleted as it is not used anymore), 
and information about removed or unsupported kernel drivers (device_driver_deprecation_data.json; 
original unsupported_driver_names.json and unsupported_pci_ids.json files have become 
obsoleted as they are not used anymore).

https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html-single/upgrading_from_rhel_7_to_rhel_8/

https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/9/html-single/upgrading_from_rhel_8_to_rhel_9/

https://leapp.readthedocs.io/en/latest/
