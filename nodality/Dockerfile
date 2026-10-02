# Copyright (c) 2026 808 Technology Limited. All rights reserved.
# SPDX-License-Identifier: LicenseRef-Nodality-Proprietary
# TODO: choose the base image deliberately and pin it by digest; record it in THIRD-PARTY-NOTICES.
FROM alpine:3.20
ARG VERSION=0.0.1
ARG REVISION=unknown
LABEL org.opencontainers.image.title="Nodality (test placeholder)" \
      org.opencontainers.image.description="Placeholder image for testing distribution" \
      org.opencontainers.image.vendor="808 Technology Limited" \
      org.opencontainers.image.source="https://github.com/nodality-casa/nodality-apps" \
      org.opencontainers.image.licenses="LicenseRef-Nodality-Proprietary" \
      org.opencontainers.image.version="${VERSION}" \
      org.opencontainers.image.revision="${REVISION}"
COPY LICENSE /licenses/LICENSE
COPY THIRD-PARTY-NOTICES.md /licenses/THIRD-PARTY-NOTICES.md
COPY run.sh /run.sh
RUN chmod +x /run.sh
CMD ["/run.sh"]
