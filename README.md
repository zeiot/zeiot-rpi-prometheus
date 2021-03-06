# RPI Prometheus

* Master: [![pipeline status](https://gitlab.com/zeiot/rpi-prometheus/badges/master/pipeline.svg)](https://gitlab.com/zeiot/rpi-prometheus/commits/master)

Docker image of [Prometheus][] to use on a [Raspberry PI][].

Configure binfmt-support on the Docker host (works locally or remotely, i.e: using boot2docker):

    $ docker run --rm --privileged multiarch/qemu-user-static:register --reset

Then you can run an armhf image from your x86_64 Docker host :

    $ make run version=x.x

Or build :

    $ make build version=x.x


# Supported tags

* 1.5.x: [![](https://images.microbadger.com/badges/version/zeiot/rpi-prometheus:1.5.0.svg)](https://microbadger.com/images/zeiot/rpi-prometheus:1.5.0 "Get your own version badge on microbadger.com")
* 1.4.x: [![](https://images.microbadger.com/badges/version/zeiot/rpi-prometheus:1.4.1.svg)](https://microbadger.com/images/zeiot/rpi-prometheus:1.4.1 "Get your own version badge on microbadger.com")
* 1.3.x: [![](https://images.microbadger.com/badges/version/zeiot/rpi-prometheus:1.3.1.svg)](https://microbadger.com/images/zeiot/rpi-prometheus:1.3.1 "Get your own version badge on microbadger.com")
* 1.2.x: [![](https://images.microbadger.com/badges/version/zeiot/rpi-prometheus:1.2.3.svg)](https://microbadger.com/images/zeiot/rpi-prometheus:1.2.3 "Get your own version badge on microbadger.com")
* 1.1.x: [![](https://images.microbadger.com/badges/version/zeiot/rpi-prometheus:1.1.3.svg)](https://microbadger.com/images/zeiot/rpi-prometheus:1.1.3 "Get your own version badge on microbadger.com")


## License

See [LICENSE](LICENSE) for the complete license.


## Changelog

A [ChangeLog.md](ChangeLog.md) is available.


## Contact

Nicolas Lamirault <nicolas.lamirault@gmail.com>


[Raspberry PI]: https://www.raspberrypi.org/
[Prometheus]: https://prometheus.io/
