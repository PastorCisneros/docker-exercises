FROM nginx
HEALTHCHECK --interval=45s --timeout=5s --retries=2 --start-period=15s  \
  CMD curl -f http://localhost/ || exit 1
EXPOSE 8084