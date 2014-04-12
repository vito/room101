# room101

Room 101 is an experimental CI system with the following immediate goals:

1. Able to run the same build as your Room 101 deployment locally on your
   machine.
1. Large-scale deployments with heterogenous workers (Linux, Windows).
1. Every build should be isolated, with only explicit shared state between
   builds.
1. Triggered by GitHub hooks, also running pull requests.
1. Composable with existing CI systems (Go CD, Jenkins).
1. A complex Room 101 deployment should be trivially recreatable.
1. Every build can be public without security risks (no leaking credentials,
   no pull requests hosing the deployment).
