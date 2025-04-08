# Cloudkit execution environment

Tools and configuration to run playbooks that interact with both OpenStack/ESI and OpenShift.

## Building the execution environment

1. Download the `openshift-clients` package from [the customer portal] and place it in
    `openshift-clients.rpm`

2. Run:

    ```
    ansible-builder build --tag cloudkit-aap-ee
    ```
