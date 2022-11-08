# Ansible playbooks for oci observability and management

This repository will contain all the ansible related automation for oci observability & management services.

# How to run

Clone this repository and run the playbooks as shown below:

```
$ cd <sample-directory> 

ex: $ cd mgmt_agent_install

$ ansible-playbook -i hosts mgmt_agent_install.yaml
```

**Note: Do set all the variables inside the hosts file before proceeding. All the examples have their own README, Please refer them before proceeding.

## Contributing

This project welcomes contributions from the community. Before submitting a pull
request, see [CONTRIBUTING](./CONTRIBUTING.md) for details.

## License

Copyright (c) 2021, 2022 Oracle and/or its affiliates.
Released under the Universal Permissive License (UPL), Version 1.0.
See [LICENSE](./LICENSE) for more details.

[oci]: https://cloud.oracle.com/en_US/cloud-infrastructure
[oci ansible]: https://github.com/oracle/oci-ansible-collection

