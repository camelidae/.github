# .github

<p align="center">
  <img src="https://raw.githubusercontent.com/camelidae/.github/main/images/splash.png" alt="Camelidae splash: a camel caravan crossing desert dunes under a deep blue sky" width="720" style="border-radius: 60px;" />
</p>

## Projects

| Project | Description | Language | Latest release | License |
| --- | --- | --- | --- | --- |
| [**oci-lib**](https://github.com/camelidae/oci-lib) | Daemonless OCI image building and container execution. Pure in-process Rust libraries and CLIs — no `dockerd`, `containerd`, or `podman` on `$PATH`. | Rust | [v0.1.15](https://github.com/camelidae/oci-lib/releases/latest) | Apache-2.0 |
| [**diorama**](https://github.com/camelidae/diorama) | Single-node Kubernetes distribution. Supervises upstream Kubernetes, Kine, and containerd across process and protocol boundaries. | Rust | [v0.1.4](https://github.com/camelidae/diorama/releases/latest) | ISC |
| [**diorama-vm**](https://github.com/camelidae/diorama-vm) | u-root initramfs running gVisor `runsc` as the OCI runtime, booted on macOS via Virtualization.framework. | Swift · Shell · Go | [v0.1.1](https://github.com/camelidae/diorama-vm/releases/latest) | — |

<sub>**Status.** `oci-lib` is published on crates.io as `oci-builder`, `oci-runner`, and `oci-cri`. `diorama` is early — configuration and `dioramactl` work, but node startup is not implemented. `diorama-vm` is a working proof of concept with no license file yet.</sub>
