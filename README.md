# kubectl-real-all
Really get all k8s objects.  As opposed to kubectl get all, which lies to you.


## Installation

Copy to your PATH and make executable.

Copy to oc-all if you use OpenShift.

## Configuration

Optionally ```export $OC_ALL=/path/to/file```, which contains a list of regular expressions to filter against.  If an api-resource matches one of these RE's, it *WILL NOT* be included in the output.

## Usage

kubectl all [-n|--namespace NS]
-n|--namespace - List resources in this namespace.  If ommitted, resources in the entire cluster will be included.
