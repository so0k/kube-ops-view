# kube-ops-view compose

Simple compose file to run kube-ops-view locally with 
Docker For Mac / Docker For Windows.

## How

Mounts your `~/.kube/config` into a kubectl container and joins the kube-ops-view
container to the same network.

## Notes

Could this be used to run the kube dashboard with a kubectl proxy, thus
ensuring RBAC of the user is respected.

at the time of writing, the kube dashboard uses service account permissions and
can not execute in the name of the logged in user.

