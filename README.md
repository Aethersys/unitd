# unitd
NGINX Unit statically compiled to create compact and high performant docker containers. Nginx Unit currently uses Glibc, where as Alpine uses Musl libc. To ensure Nginx Unit works well under Alpine, we can statically compile it which bundles the necessary Glibc components so that we can then have Alpine running under the hood powering python and php etc under musl via Alpine's repos.
