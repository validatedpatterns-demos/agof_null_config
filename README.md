# Ansible GitOps Framework Null Configuration

## What is this?

This is a configuration that does not configure any objects in AAP. It is useful for using AGOF to bootstrap and
entitle an AAP instance, but does not add any additional configuration.

The intention is to provide a placeholder, to be able to test the provisioning and entitlement capabilities, in the
absence of adding additional configuration.

## How do I get started?

1. Check this repository out
1. Check out the AGOF [repository](https://github.com/validatedpatterns/agof), which will serve as the provisioner for the pattern
1. Configure an `~/agof_vault.yml` file with your AWS credentials and configuration. Still needed for entitling the
instance.
