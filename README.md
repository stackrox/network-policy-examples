# Examples from the Network Policies guide

YAML files for all the network policy configurations described in the [Setting up Kubernetes Network Policies - A Detailed Guide](https://www.stackrox.com/post/2019/04/setting-up-kubernetes-network-policies-a-detailed-guide/) post on the StackRox blog.

## How to use

Assuming that you're connected to a Kubernetes cluster, most of these network policies can be created as is, by running `kubectl create -f <filename.yaml>`. For the policies that don't specify a namespace in the YAML, you may want to specify a namespace using `kubectl create -n <namespace_name> -f <filename.yaml>`.

Note that some of the YAMLs are not ready to create as-is; you will have to replace the labels in them with the actual labels from your pods.
