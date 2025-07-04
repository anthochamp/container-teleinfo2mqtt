FROM fmartinou/teleinfo2mqtt:9.0.5@sha256:18c3224bb57e239ae46b065194b5a0aca1054e7929bb18803c6bc9da8213bccb

COPY --chmod=775 /rootfs/docker-entrypoint.sh /

ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD ["node", "index"]
