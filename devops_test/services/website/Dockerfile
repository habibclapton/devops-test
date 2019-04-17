# Start from a small base
FROM scratch

# Our application requires no privileges
# so run it with a non-root user
ADD users /etc/passwd
USER nobody

# Our application runs on port 3000
# so allow hosts to bind to that port
EXPOSE 3000

# Add our application binary
ADD app /app

# Run our application!
ENTRYPOINT [ "/app" ]
