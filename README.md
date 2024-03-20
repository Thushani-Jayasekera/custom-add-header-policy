# add-header-custom-policy

1. Fork the [Custom Add Header Policy Repo](https://github.com/Thushani-Jayasekera/add-header-custom-policy)
2. Open the project locally and run the following commands to push the policy to your organization.

```
export BALLERINA_CENTRAL_ACCESS_TOKEN=<access-token> 
export BALLERINA_DEV_CENTRAL=true
bal pack
bal push
```
Note: Replace `<access-token>` with your access token. The access token can be generated via https://dev-central.ballerina.io/
