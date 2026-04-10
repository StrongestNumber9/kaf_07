FROM ghcr.io/strongestnumber9/cfp_01/systemd/el9:0.0.11

# Install dependencies
COPY rpm/kaf_07.rpm /kaf_07.rpm
RUN dnf -y install /kaf_07.rpm

# Bootstrap
COPY cfp_01.entrypoint.sh /cfp_01.entrypoint.sh
