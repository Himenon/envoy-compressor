FROM envoyproxy/envoy:v1.19.1
COPY ./envoy.yaml /etc/envoy.yaml
CMD ["/usr/local/bin/envoy", "-c", "/etc/envoy.yaml", "-l", "info", "--service-cluster", "proxy"]
