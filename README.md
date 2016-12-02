######Vagrant config for research project under M. Gerla and J. Joy

Query:

Node A: localhost:19902, Node B: localhost:19903

`curl --user foo:bar --data-binary '{"jsonrpc": "1.0", "id":"curltest", "method": "getinfo", "params": [] }' -H 'content-type: text/plain;' localhost:19902`

See other methods here: https://github.com/peerchemist/peercoin_rpc/blob/master/peercoin_rpc/peercoin_rpc.py
