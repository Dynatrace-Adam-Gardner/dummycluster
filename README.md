# dummycluster

Create a k8s cluster (using k3s) with 3 namespaces:

- customer1
- customer2
- customer3

Each customer has their own application running on port 80.

- customer1.<VM-IP>.nip.io
- customer2.<VM-IP>.nip.io
- customer3.<VM-IP>.nip.io

`Customer 1` and `customer 2` have `v1` of the application running.
`Customer 3` is running `v2` of the application.