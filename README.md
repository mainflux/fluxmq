> This repository is obsolete. A modern, maintained and improved version of the broker can be found at https://github.com/absmach/fluxmq. 

# FluxMQ
FluxMQ is simple, fast and lean MQTT broker made for the purposes of [Mainflux IoT Platform](https://github.com/mainflux/mainflux).

FluxMQ is built to be HA and FT, network partition tolerable and scales horizontaly via RAFT protocol and gPRC comm.

Still in early prototype mode, being built on existing [mProxy](https://github.com/mainflux/mproxy) base.

## Usage
```bash
go get github.com/mainflux/fluxmq
cd $(GOPATH)/github.com/mainflux/fluxmq
make
./fluxmq
```

## Deployment
TBD

## License
[Apache-2.0](LICENSE)
