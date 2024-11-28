To build

`podman build --build-arg GIT_HASH="$(git rev-parse HEAD)" --build-arg POSIX_TIMESTAMP_CREATION="$(date +%s)" -t platformio:latest .`

To run

`podman run --hostname contdev -ti --rm localhost/platformio:latest`
