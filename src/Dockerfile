FROM fmartinou/teleinfo2mqtt:9.0.3

COPY --chmod=775 /rootfs/docker-entrypoint.sh /

ENTRYPOINT [ "/docker-entrypoint.sh" ]
CMD ["node", "index"]
