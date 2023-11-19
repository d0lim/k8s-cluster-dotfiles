# k8s-cluster-dotfiles

## What is this repository for?

- Manage the dotfiles used for the configuration of the K8S Cluster that I maintain as a hobby

## Environment Variables

- All environment variables are declared at the `env.sh``.
- Modify the contents of the `env.sh` and run it.

### How to apply with Environment Varibles?

```sh
cat {FILE_PATH_YOU_WANT_TO_APPLY} | envsubst | kubectl apply -f -
```
