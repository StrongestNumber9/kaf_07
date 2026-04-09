FROM ghcr.io/strongestnumber9/cfp_01/plain/el9:0.0.5

# Install dependencies
COPY rpm/kaf_07.rpm /kaf_07.rpm
RUN dnf -y install /kaf_07.rpm

# Bootstrap
COPY tester.sh /tester.sh
RUN chmod +x /tester.sh

# Run
ENTRYPOINT ["/tester.sh"]
CMD [""]
