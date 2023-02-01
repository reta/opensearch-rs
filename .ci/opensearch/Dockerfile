ARG STACK_VERSION
FROM "opensearchproject/opensearch:$STACK_VERSION"

COPY root-ca.pem /usr/share/opensearch/config/root-ca.pem
COPY esnode.pem /usr/share/opensearch/config/esnode.pem
COPY esnode-key.pem /usr/share/opensearch/config/esnode-key.pem