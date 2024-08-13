ARG BUILD_FROM
FROM $BUILD_FROM

ARG BUILD_ARCH
COPY "bin/PantherLinkHA${BUILD_ARCH}" /PantherLinkHA
RUN chmod +x /PantherLinkHA

CMD ["/PantherLinkHA"]