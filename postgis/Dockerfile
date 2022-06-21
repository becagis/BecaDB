ARG POSTGRES_VERSION
FROM kartoza/postgis:${POSTGRES_VERSION}

LABEL maintainer="Truong Thanh Tung <ttungbmt@gmail.com>"

###########################################################################
# Set Timezone
###########################################################################

ARG TIMEZONE=Asia/Ho_Chi_Minh
ENV TIMEZONE ${TIMEZONE}

###########################################################################
# Set Extensions
###########################################################################
ARG POSTGRES_MULTIPLE_EXTENSIONS='postgis,hstore,postgis_topology,postgis_raster,pgrouting,unaccent'
ENV POSTGRES_MULTIPLE_EXTENSIONS ${POSTGRES_MULTIPLE_EXTENSIONS}
