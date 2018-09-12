## HEAT stack commands

List stack and its status

``` openstack stack list ```

See resources in the stack

``` openstack stack resource list <stack name> ```

Check details of an instance built by the stack

``` openstack stack resource show <stack name> <resource name> ```

Check the stack events

``` openstack stack event list <stack name> ```

List the parameters of the stack
``` openstack stack output list <stack name> ```

View the value of a parameter
``` openstack stack output show <stack name> <resource name> ```

