
# Alfred-Workflows

[Alfred 3](https://www.alfredapp.com/) workflows.


## Install

Download and open file using [Alfred 3](https://www.alfredapp.com/).

You need to [buy the Powerpack](https://buy.alfredapp.com/) to use these workflows.

## vpn
Allows the user to connect to VPN via Cisco AnyConnect

You should have an entry in your KeyChain for the VPN-server.

The following will create a keychain-entry:

```security add-internet-password -s <SERVER_NAME> -p /Cert-Auth -a <USERNAME> -w```

Be aware that your username be prefixed by the Domain (domain\username)

Add the ```SERVER_NAME``` to the Workflow Environment Variables

## switchRole
Workflow for managing all accounts in an AWS Organization

Add the ```organization_profile``` to the Workflow Environment Variables. This should be a profile, capable for creating a list for all your accounts.

Currently, is is only able to switch to ```OSCAdmin`` account.
