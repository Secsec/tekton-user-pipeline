FROM registry.access.redhat.com/ubi8/ubi:latest
RUN dnf install -y ansible
RUN ansible-galaxy collection install kubernetes.core
RUN pip3.9 install kubernetes
