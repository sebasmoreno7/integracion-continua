# Continuous integration coursework

Historical coursework repository for the Integración Continua subject at Politécnico Grancolombiano. It collects Dockerfile examples for PHP/Apache, PostgreSQL, MySQL on Oracle Linux and Jenkins, alongside small supporting files.

These files are examples rather than a documented, running CI pipeline. Some Dockerfiles refer to files or paths that are not present in this repository, so a successful image build is not implied.

## Contents

- `Dockerfile`: PHP 7.4/Apache example; its `COPY src/` path is absent here.
- `Dockerfile-datos`: PostgreSQL base-image example.
- `Dockerfile.oracle`: generated MySQL/Oracle Linux Dockerfile example.
- `Dockerfile.txt`: Jenkins Dockerfile example that references support files absent here.

The Dockerfiles use historical versions and should be reviewed before any new use.
