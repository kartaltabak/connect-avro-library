FROM gradle as builder

WORKDIR /app

COPY build.gradle .

RUN gradle downloadDependencies --no-daemon

FROM scratch

COPY --from=builder /app/build/downloaded/* /lib/