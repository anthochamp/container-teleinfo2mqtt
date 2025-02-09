FROM fmartinou/teleinfo2mqtt:9.0.4@sha256:2b3bdb9b00b2065ae4d73ffb04c4053de22545eeaaba46bc5b0c8b09fcdcb1dd

COPY --chmod=775 /rootfs/docker-entrypoint.sh /

ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD ["node", "index"]
