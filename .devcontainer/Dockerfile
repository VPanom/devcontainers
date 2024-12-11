FROM parrotsec/security:latest
WORKDIR /workspace
RUN apt update && apt upgrade -y && \
    apt install -y \
    git nmap openvpn \
    && apt clean
CMD ["bash"]

