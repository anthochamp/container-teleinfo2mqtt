FROM fmartinou/teleinfo2mqtt:9.0.6@sha256:2f28caae9c9c8f52217d535ac3e96a2ea506061ca95aa38aa3e014b034516f77

COPY --chmod=775 /rootfs/docker-entrypoint.sh /

ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD ["node", "index"]
