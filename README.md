# besu-duplicate-peers
setup to reproduce duplicate peers in besu

If I start besu1 and then besu2, besu2 gets 2 peers 100% of the time.

besu --config-file=besu1.conf
besu --config-file=besu2.conf

extract from log files in besu1.log and besu2.log
result of admin_peers in besu1-admin-peers and besu2-admin-peers
