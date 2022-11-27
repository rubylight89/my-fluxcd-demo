# my-fluxcd-demo
Flux repository


flux create secret git podinfo-auth \
    --url=ssh://git@github.com/stefanprodan/podinfo \
    --private-key-file=./private.key


