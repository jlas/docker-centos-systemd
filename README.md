Run ``systemd`` in your CentOS docker container

Based on http://jperrin.github.io/centos/2014/09/25/centos-docker-and-systemd/

Need to run the iamge like so

    docker run –privileged -ti -v /sys/fs/cgroup:/sys/fs/cgroup:ro jlas/docker-centos-systemd