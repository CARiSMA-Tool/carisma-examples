# Secure links example

Assuming the default adversary (profile `null`), the provided check fails, because the communication path between the two nodes, specified as being `<<Internet>>`, does not fulfill the requirement `<<secrecy>>` of the dependency between the two artifacts. If you change `<<Internet>>` to `<<LAN>>`, the requirement is fulfilled and the check passes.

