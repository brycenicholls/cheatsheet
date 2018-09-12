## Keystone Environment Var vs CLI

``` bash
OS_USERNAME     ->      --os-username
OS_PASSWORD     ->      --os-password
OS_PROJECT_NAME ->      --os-project-name
OS_AUTH_URL     ->      --os-auth-url
```
---

## Token reneew

``` openstack token issue ```

## Token revoke

``` openstack token revoke ```

---

## Change server settings
```
openstack server set <--option> <server name>
```


## HEAT stack commands

List stack and its status

``` openstack stack list ```

See resources in the stack

``` openstack stack resource list <stack name> ```

Check the stack events

``` openstack stack event list <stack name> ```


