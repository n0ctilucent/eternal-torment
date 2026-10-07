# container — Podman/Docker Configurations

Two base container configurations are available:

| Directory | Purpose | Build command |
|-----------|---------|---------------|
| [kali/](kali/) | Kali Linux dev/CTF base | `podman build -t eternal-torment-kali .` |
| [puzzle1/](puzzle1/) | Puzzle1 CTF challenge container | `podman build -t ski-mask-ciso .` |

## Networking (shared)

Both containers may use custom bridge or macvlan networks:

```sh
# Bridge network (default subnet)
podman network create --subnet 10.89.0.0/24 franklin_custom_network

# Macvlan for physical interface
sudo podman network create --driver macvlan --opt parent="enp9s0" research
```

## Troubleshooting

```sh
# IPv6 forwarding (required for some network configs)
sudo sysctl -w net.ipv6.conf.all.forwarding=1

# Container registry login
export CR_PAT=$(pass show ghcr)
echo "$CR_PAT" | docker login ghcr.io -u devsecfranklin --password-stdin
```

See [../docs/README.md](../docs/README.md) for related documentation.

---

⛧ Draft by **n0ctilucent** | [bitsmasher.net/research](https://www.bitsmasher.net/research/)
