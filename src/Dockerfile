FROM fmartinou/teleinfo2mqtt:9.1.1@sha256:e8087b26aad966512eaaac760eb01d9d42bd5a1629960cedcd76bd2a076035f8

COPY --chmod=775 /rootfs/docker-entrypoint.sh /

ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD ["node", "index"]
