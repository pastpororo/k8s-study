

```
## brew install kind
==> Auto-updating Homebrew...
Adjust how often this is run with HOMEBREW_AUTO_UPDATE_SECS or disable with
HOMEBREW_NO_AUTO_UPDATE. Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
Installing from the API is now the default behaviour!
You can save space and time by running:
  brew untap homebrew/core
  brew untap homebrew/cask
==> Auto-updated Homebrew!
Updated 2 taps (homebrew/core and homebrew/cask).
==> New Formulae
air                   chawan                go-rice               lolcrab               mlc                   plutovg               sherif                tiledb
arp-scan-rs           eask-cli              jq-lsp                lunasvg               moodle-dl             pytr                  sqlite-rsync          yaml2json
assimp@5              ffmate                kbt                   mermaid-cli           onigmo                rnp                   swift-section         yek
backgroundremover     gemini-cli            kingfisher            minify                ovsx                  rsql                  teslamate
==> New Casks
accordance@13                       flowdown                            font-tenderness                     music-presence                      swama
aigcpanel                           font-google-sans-code               futubull@legacy                     opal-app                            tng-digital-mini-program-studio
alienator88-sentinel                font-libertinus-sans                insta360-link-controller            pcsx2                               vibemeter
aloha-browser                       font-libertinus-serif               kameleo                             raiderio                            vibetunnel
bcut                                font-mozilla-headline               linqpad                             riverside-studio                    xppen-pentablet
canon-mg2500-driver                 font-mozilla-text                   longbridge-pro                      smoothcsv                           yuanbao
eid-viewer                          font-nacelle                        macsyzones                          spacesaver
filefillet                          font-nata-sans                      msgfiler                            stillcolor

You have 9 outdated formulae installed.

==> Downloading https://ghcr.io/v2/homebrew/core/kind/manifests/0.29.0
########################################################################################################################################################################### 100.0%
==> Fetching kind
==> Downloading https://ghcr.io/v2/homebrew/core/kind/blobs/sha256:9dd60f52284f2aa41b0583a8fecb1374e5783522e85e5798198d913c2df6be6d
########################################################################################################################################################################### 100.0%
==> Pouring kind--0.29.0.arm64_sequoia.bottle.tar.gz
🍺  /opt/homebrew/Cellar/kind/0.29.0: 9 files, 9.4MB
==> Running `brew cleanup kind`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
==> Caveats
zsh completions have been installed to:
  /opt/homebrew/share/zsh/site-functions


## kind version
kind v0.29.0 go1.24.3 darwin/arm64


## brew install kubernetes-cli
==> Auto-updating Homebrew...
Adjust how often this is run with HOMEBREW_AUTO_UPDATE_SECS or disable with
HOMEBREW_NO_AUTO_UPDATE. Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
Installing from the API is now the default behaviour!
You can save space and time by running:
  brew untap homebrew/core
  brew untap homebrew/cask
==> Auto-updated Homebrew!
Updated 2 taps (homebrew/core and homebrew/cask).
==> New Formulae
backlog-md: Markdown‑native Task Manager & Kanban visualizer for any Git repository
damask-grid: Grid solver of DAMASK - Multi-physics crystal plasticity simulation package
decker: HyperCard-like multimedia sketchpad
lunarml: Standard ML compiler that produces Lua/JavaScript
lutgen: Blazingly fast interpolated LUT generator and applicator for color palettes
min-lang: Small but practical concatenative programming language and shell
plakar: Create backups with compression, encryption and deduplication
==> New Casks
allen-and-heath-midi-control: Midi control software for Allen & Heath audio consoles
context: MCP client and inspector
devonsphere-express: Find items related to the frontmost document locally or online
es-de: Frontend for browsing and launching games from your multi-platform collection
freelens@nightly: Kubernetes IDE
jordanbaird-ice@beta: Menu bar manager
loop-messenger: Team messenger for business communication
nifty-file-lists: Extract file metadata into exportable tables
skint: Check status of key security settings and features
teleport-suite@17: Modern SSH server for teams managing distributed infrastructure

You have 9 outdated formulae installed.

==> Downloading https://ghcr.io/v2/homebrew/core/kubernetes-cli/manifests/1.33.2
########################################################################################################################################################################### 100.0%
==> Fetching kubernetes-cli
==> Downloading https://ghcr.io/v2/homebrew/core/kubernetes-cli/blobs/sha256:b1e2e5650487db8b2a2441e03804151fc26e2a342bbc1597e2a1f29c47140165
########################################################################################################################################################################### 100.0%
==> Pouring kubernetes-cli--1.33.2.arm64_sequoia.bottle.tar.gz
🍺  /opt/homebrew/Cellar/kubernetes-cli/1.33.2: 255 files, 62.2MB
==> Running `brew cleanup kubernetes-cli`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
==> Caveats
zsh completions have been installed to:
  /opt/homebrew/share/zsh/site-functions

## kubectl version --client=true
Client Version: v1.32.2

Kustomize Version: v5.5.0

## brew install helm
==> Downloading https://formulae.brew.sh/api/formula.jws.json
==> Downloading https://formulae.brew.sh/api/cask.jws.json
helm 3.18.2 is already installed but outdated (so it will be upgraded).
==> Downloading https://ghcr.io/v2/homebrew/core/helm/manifests/3.18.4
########################################################################################################################################################################### 100.0%
==> Fetching helm
==> Downloading https://ghcr.io/v2/homebrew/core/helm/blobs/sha256:20c68f43e2df4ab531ed61975cde488340471d6446ef928c30398c0db8ac91fb
########################################################################################################################################################################### 100.0%
==> Upgrading helm
  3.18.2 -> 3.18.4 
==> Pouring helm--3.18.4.arm64_sequoia.bottle.tar.gz
🍺  /opt/homebrew/Cellar/helm/3.18.4: 66 files, 56.5MB
==> Running `brew cleanup helm`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
Removing: /opt/homebrew/Cellar/helm/3.18.2... (66 files, 56.5MB)
Removing: /Users/ejjoe/Library/Caches/Homebrew/helm_bottle_manifest--3.18.2... (8.3KB)
Removing: /Users/ejjoe/Library/Caches/Homebrew/helm--3.18.2... (16MB)
==> Caveats
zsh completions have been installed to:
  /opt/homebrew/share/zsh/site-functions

## helm version
version.BuildInfo{Version:"v3.18.4", GitCommit:"d80839cf37d860c8aa9a0503fe463278f26cd5e2", GitTreeState:"clean", GoVersion:"go1.24.5"}

brew install krew
==> Downloading https://formulae.brew.sh/api/formula.jws.json
==> Downloading https://formulae.brew.sh/api/cask.jws.json
==> Downloading https://ghcr.io/v2/homebrew/core/krew/manifests/0.4.5
########################################################################################################################################################################### 100.0%
==> Fetching krew
==> Downloading https://ghcr.io/v2/homebrew/core/krew/blobs/sha256:2612180540b05504e2f9c3aae82cb6335ffa55e88ac9e27f2bdad18390c22dc0
########################################################################################################################################################################### 100.0%
==> Pouring krew--0.4.5.arm64_sequoia.bottle.tar.gz
🍺  /opt/homebrew/Cellar/krew/0.4.5: 6 files, 12.8MB
==> Running `brew cleanup krew`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
brew install kube-ps1
==> Downloading https://ghcr.io/v2/homebrew/core/kube-ps1/manifests/0.9.0
########################################################################################################################################################################### 100.0%
==> Fetching kube-ps1
==> Downloading https://ghcr.io/v2/homebrew/core/kube-ps1/blobs/sha256:8b7dbe43c977fc6410a1c076cdd9d488a42201b62be6389e0f09b63030bf5e1b
########################################################################################################################################################################### 100.0%
==> Pouring kube-ps1--0.9.0.all.bottle.tar.gz
==> Caveats
Make sure kube-ps1 is loaded from your ~/.zshrc and/or ~/.bashrc:
  source "/opt/homebrew/opt/kube-ps1/share/kube-ps1.sh"
  PS1='$(kube_ps1)'$PS1
==> Summary
🍺  /opt/homebrew/Cellar/kube-ps1/0.9.0: 7 files, 39.7KB
==> Running `brew cleanup kube-ps1`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
brew install kubectx
==> Downloading https://ghcr.io/v2/homebrew/core/kubectx/manifests/0.9.5-2
########################################################################################################################################################################### 100.0%
==> Fetching kubectx
==> Downloading https://ghcr.io/v2/homebrew/core/kubectx/blobs/sha256:6552e91e68ff8abda73be837c80539b47e3aadc73e5f8bab57cbb3bf0356c682
########################################################################################################################################################################### 100.0%
==> Pouring kubectx--0.9.5.all.bottle.2.tar.gz
🍺  /opt/homebrew/Cellar/kubectx/0.9.5: 15 files, 41.1KB
==> Running `brew cleanup kubectx`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
==> Caveats
zsh completions have been installed to:
  /opt/homebrew/share/zsh/site-functions
brew install kubecolor
==> Downloading https://ghcr.io/v2/homebrew/core/kubecolor/manifests/0.5.1
########################################################################################################################################################################### 100.0%
==> Fetching kubecolor
==> Downloading https://ghcr.io/v2/homebrew/core/kubecolor/blobs/sha256:795369e861c4fd5cad6c14bcb2aefff51654cce635abf17daf52cbc60c0c7110
########################################################################################################################################################################### 100.0%
==> Pouring kubecolor--0.5.1.arm64_sequoia.bottle.tar.gz
🍺  /opt/homebrew/Cellar/kubecolor/0.5.1: 6 files, 5.3MB
==> Running `brew cleanup kubecolor`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
echo "alias kubectl=kubecolor" >> ~/.zshrc
echo "compdef kubecolor=kubectl" >> ~/.zshrc
docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
kind create cluster
Creating cluster "kind" ...
⠊⠁ Ensuring node image (kindest/node:v1.33.1) 🖼 
 ✓ Ensuring node image (kindest/node:v1.33.1) 🖼 
⢄⡱ Preparing nodes 📦  
⢄⡱ Preparing nodes 📦  
⢆⡱ Preparing nodes 📦  
⢎⡰ Preparing nodes 📦  
⢎⡀ Preparing nodes 📦  
⠎⠁ Preparing nodes 📦  
⠈⠁ Preparing nodes 📦  
 ✓ Preparing nodes 📦  

 ✓ Writing configuration 📜 
 ✓ Starting control-plane 🕹️ 
 ✓ Installing CNI 🔌 
 ✓ Installing StorageClass 💾 
Set kubectl context to "kind-kind"
You can now use your cluster with:

kubectl cluster-info --context kind-kind

Not sure what to do next? 😅  Check out https://kind.sigs.k8s.io/docs/user/quick-start/
                                                                                                                                                                                  






^[i
kind create cluster
ERROR: failed to create cluster: node(s) already exist for a cluster with the name "kind"
kind get clusters
kind
~
kind get nodes  
kind get nodes
kind-control-plane
The command shows that your kind cluster has one node:

•  kind-control-plane (the control plane node)

This is the single-node cluster that was created when you ran kind create cluster. The control plane node handles both the Kubernetes control plane components and can also run workloads since it's a single-node setup.

If you want to see more detailed information about the nodes, you can also use:
bash
kubectl cluster-info
Kubernetes control plane is running at https://127.0.0.1:53919
CoreDNS is running at https://127.0.0.1:53919/api/v1/namespaces/kube-system/services/kube-dns:dns/proxy

To further debug and diagnose cluster problems, use 'kubectl cluster-info dump'.
kubectl get node -o wide
NAME                 STATUS   ROLES           AGE    VERSION   INTERNAL-IP   EXTERNAL-IP   OS-IMAGE                         KERNEL-VERSION     CONTAINER-RUNTIME
kind-control-plane   Ready    control-plane   106s   v1.33.1   172.18.0.2    <none>        Debian GNU/Linux 12 (bookworm)   6.10.14-linuxkit   containerd://2.1.1
kubectl get pod -A
NAMESPACE            NAME                                         READY   STATUS    RESTARTS   AGE
kube-system          coredns-674b8bbfcf-c54fq                     1/1     Running   0          114s
kube-system          coredns-674b8bbfcf-psbj9                     1/1     Running   0          114s
kube-system          etcd-kind-control-plane                      1/1     Running   0          2m1s
kube-system          kindnet-97mg4                                1/1     Running   0          114s
kube-system          kube-apiserver-kind-control-plane            1/1     Running   0          2m
kube-system          kube-controller-manager-kind-control-plane   1/1     Running   0          2m
kube-system          kube-proxy-pglj4                             1/1     Running   0          114s
kube-system          kube-scheduler-kind-control-plane            1/1     Running   0          2m
local-path-storage   local-path-provisioner-7dc846544d-5ccck      1/1     Running   0          114s
kubectl get componentstatuses
Warning: v1 ComponentStatus is deprecated in v1.19+
NAME                 STATUS    MESSAGE   ERROR
controller-manager   Healthy   ok        
scheduler            Healthy   ok        
etcd-0               Healthy   ok        
docker ps
CONTAINER ID   IMAGE                  COMMAND                  CREATED         STATUS         PORTS                       NAMES
8fd39bd7deae   kindest/node:v1.33.1   "/usr/local/bin/entr…"   2 minutes ago   Up 2 minutes   127.0.0.1:53919->6443/tcp   kind-control-plane
docker images
REPOSITORY                                          TAG                                                                           IMAGE ID       CREATED         SIZE
apache/polaris                                      latest                                                                        94c9f269141b   3 weeks ago     595MB
apache/polaris                                      postgres-latest4                                                              94c9f269141b   3 weeks ago     595MB
apache/polaris-admin-tool                           latest                                                                        68c25e4b4dd7   3 weeks ago     492MB
apache/polaris-admin-tool                           postgres-latest4                                                              68c25e4b4dd7   3 weeks ago     492MB
apache/polaris                                      postgres-latest3                                                              7871d8854cf5   3 weeks ago     602MB
apache/polaris-admin-tool                           postgres-latest3                                                              52028cc22fc6   3 weeks ago     499MB
apache/polaris                                      postgres-latest2                                                              58ff7200dcd6   3 weeks ago     602MB
apache/polaris-admin-tool                           postgres-latest2                                                              72e5ccb326fc   3 weeks ago     499MB
kindest/node                                        <none>                                                                        071dd73121e8   7 weeks ago     1.09GB
docker/desktop-kubernetes                           kubernetes-v1.32.2-cni-v1.6.0-critools-v1.31.1-cri-dockerd-v0.3.16-1-debian   ca2d12959459   4 months ago    400MB
registry.k8s.io/kube-apiserver                      v1.32.2                                                                       6417e1437b6d   4 months ago    93.9MB
registry.k8s.io/kube-scheduler                      v1.32.2                                                                       82dfa03f692f   4 months ago    67.9MB
registry.k8s.io/kube-controller-manager             v1.32.2                                                                       3c9285acfd2f   4 months ago    87.2MB
registry.k8s.io/kube-proxy                          v1.32.2                                                                       e5aac5df76d9   4 months ago    97.1MB
debezium/debezium-with-oracle-jdbc                  3.0.6.Final                                                                   3e7d8f395498   6 months ago    1.41GB
oracle/instantclient                                19                                                                            fa586f63e3da   7 months ago    499MB
registry.k8s.io/etcd                                3.5.16-0                                                                      7fc9d4aa817a   10 months ago   142MB
registry.k8s.io/coredns/coredns                     v1.11.3                                                                       2f6c962e7b83   11 months ago   60.2MB
registry.k8s.io/pause                               3.10                                                                          afb61768ce38   13 months ago   514kB
container-registry.oracle.com/database/enterprise   19.3.0.0                                                                      291fd8c7958b   22 months ago   8.32GB
docker/desktop-vpnkit-controller                    dc331cb22850be0cdd97c84a9cfecaf44a1afb6e                                      3750dfec169f   2 years ago     35MB
hivemetastore                                       v2.0.0                                                                        8dc2bc75ca4e   3 years ago     735MB
docker/desktop-storage-provisioner                  v2.0                                                                          c027a58fa0bb   4 years ago     39.8MB
cat ~/.kube/config
apiVersion: v1
clusters:
- cluster:
    certificate-authority-data: LS0tLS1CRUdJTiBDRVJUSUZJQ0FURS0tLS0tCk1JSURCVENDQWUyZ0F3SUJBZ0lJVk1hQ0ZaMlBHMk13RFFZSktvWklodmNOQVFFTEJRQXdGVEVUTUJFR0ExVUUKQXhNS2EzVmlaWEp1WlhSbGN6QWVGdzB5TlRBME1Ua3hNalE1TkRGYUZ3MHpOVEEwTVRjeE1qUTVOREZhTUJVeApFekFSQmdOVkJBTVRDbXQxWW1WeWJtVjBaWE13Z2dFaU1BMEdDU3FHU0liM0RRRUJBUVVBQTRJQkR3QXdnZ0VLCkFvSUJBUUR5QU1UZVBNVldoZkl0NW04YU91dG1WY2k5b1BmK2ZTSjYzTE1WZzZKQ3YzeUVobGhZdHdORWRlWWcKMTlEV1l6Y1ZRQmVvWXM0YmVPK21mV0JHMENtL09QRzJzL3EyVlMwSkNLWEVPeHVqUVBWT1VxamNGcWdUTjdlWApXclIyc2p5MTdYWVVhU01sbHBBbDRBT0FYL2FTL0R2dm9DeEgvWkpIVmhvMGZaUWRCZHlIVmYweFhZOStaZ2RqCk1nQmd4eWpOUnBRY2kzMjZnTUFsRUdERjFKMk5nRWdNT3ZmS1VEU3cwc0VnVWY2Z1lyemZIejRIekNJWVJTZXgKTEYyMmUzZDBhVnpEOThEU3JxZExPS3drdldwTURIaDhlSi92eC9obnhhNmJrSGszWWlPVGY2VC8vQm14ZHJ6dgpSWmJwYWFaV01ITWV4akprYlg3OWFuam1mSjhqQWdNQkFBR2pXVEJYTUE0R0ExVWREd0VCL3dRRUF3SUNwREFQCkJnTlZIUk1CQWY4RUJUQURBUUgvTUIwR0ExVWREZ1FXQkJUeW5aMENDNGVsMzdaNlBzbXJIQnRpZGluSmZqQVYKQmdOVkhSRUVEakFNZ2dwcmRXSmxjbTVsZEdWek1BMEdDU3FHU0liM0RRRUJDd1VBQTRJQkFRQm54MjNTS29MawoySWlhTzRiREF0cytmZVBFcStUN1k3ZmZ0YklQdUI3RlhEeUhnQkNTRjBublE1aytYbEVUeFZEMk0zbmNXTTF5CjZHYm9hQk1nSkVuUXRIb3hwcWlFWDBHdUZYbkp5SXpzamlockladmN2aFNsS1BjUjVIMG5BTlRWM3RNNm51dkEKZ3ExeHdOQTl6SElQM05qMXRFWWhkQVJiRnBPRDR3N0xmeUJ5SSt3ekkwNVg5alZtZEtTcndHaGszb2t0eG1FZQpXdnp0RnF5SHFsMUNhVmk3WmhUQ3ZPU21aanMwc2ZCWDM3RHd2M0hvUHJBSVZINGN0bFFLbXBSRGtYVXRNajh1CktWZUw4eUY4TzJwK25hMVgwVTZGVWtWdnROdE5rN0hYbkNtY2pJaTZsdTVzaU8xU09jd3lMR09rU3RrUGhyMUYKQWxIblFLdGl3SmRICi0tLS0tRU5EIENFUlRJRklDQVRFLS0tLS0K
    server: https://kubernetes.docker.internal:6443
  name: docker-desktop
- cluster:
    certificate-authority-data: LS0tLS1CRUdJTiBDRVJUSUZJQ0FURS0tLS0tCk1JSURCVENDQWUyZ0F3SUJBZ0lJYzVxTzV3TnNjd1V3RFFZSktvWklodmNOQVFFTEJRQXdGVEVUTUJFR0ExVUUKQXhNS2EzVmlaWEp1WlhSbGN6QWVGdzB5TlRBM01URXdOREExTWpWYUZ3MHpOVEEzTURrd05ERXdNalZhTUJVeApFekFSQmdOVkJBTVRDbXQxWW1WeWJtVjBaWE13Z2dFaU1BMEdDU3FHU0liM0RRRUJBUVVBQTRJQkR3QXdnZ0VLCkFvSUJBUURSTFk0WHNyOVdmVnUyU0pYd2dOOEcwVGFoQXN5MlFPenhrSVZCS3YvWTJlZjJOMTJDais2TjR6Nk4KdDFzaUJlb0xXVlZLdUxXK1JGQUphcEszcFE0dWRZdTduSXhvRjBkZzlNVkxWMHMwTGlvcmZhSUgyR3luSGx5OQpLZW1jMlNNWFdCcS9ZR0owZ1M4TWpYU1FJeFpRakZFWjdnZ3FqLzZnaDlPd3c2dDZkTTlDRVI3cUVkY3B1dk8xCmdoQWhwTk5uQ09GT3YzZGExem14T0svUy9iK0MzWmFzdUh6K3dLMmx0ZWhLSXlFN0p2c1VTYVV5QjR4cjA5Y04KV0JyU2pkcHJCaVQ3SVNhNURQZUJ3NnU4eXFCSlk1cDhEV3J6SVJBYTFPbVBBMkNwRlJIakhjMUMvZ3NHVEMwQwp6NHlIU2pWMWIwOW9WMjN1MFVhcEF0cmFtYURaQWdNQkFBR2pXVEJYTUE0R0ExVWREd0VCL3dRRUF3SUNwREFQCkJnTlZIUk1CQWY4RUJUQURBUUgvTUIwR0ExVWREZ1FXQkJUa0tJTWJFNXl0RXdkK0MyWmtDNlFTcGpIN3ZqQVYKQmdOVkhSRUVEakFNZ2dwcmRXSmxjbTVsZEdWek1BMEdDU3FHU0liM0RRRUJDd1VBQTRJQkFRQ0gzMWFQYmNhUwpjVVJhWmtIZ1RlMHRzYVphS0pxVmJxaDE4bXYyWWpLWFV0Y1ZQTEJCcTZnMGtTOGdYSlIxWFFiZ0JvejJQQnpvCnREdFJUWUo2aE5hbDdnRjVGc2Y3ZUd3YWY3L0JMdElWZ2ZRUm5qY2g5VHZCZmhvMGdyWmlFODNVaFBTdjNtMmoKekdPSDVlKzR0ZXJwdWY1NHFpQlBIWWVBYVVVTTJRQjF5ZnRSa0U0SWZjQnR3S3lWNTlOZE93Y1VmMHBLVi9ZVQpvR0VPUE5ZUVlKL25jYzdEVWFkSVhEYVdEeHdaVG9nVE8wM0QrY1BxRkNUWHY1KzdSMC9ybDJDZlVRbVR4T3BiClNCaURkcmNMNEdzSnFXQVdBT0R3ZlJtekRPcG5TYUp1RFNxN21LUnFmZXVmajdOQy81M1Zvelo5cCtZclo3RjQKbS91VWNZMFplUVljCi0tLS0tRU5EIENFUlRJRklDQVRFLS0tLS0K
    server: https://127.0.0.1:53919
  name: kind-kind
contexts:
- context:
    cluster: docker-desktop
    user: docker-desktop
  name: docker-desktop
- context:
    cluster: kind-kind
    user: kind-kind
  name: kind-kind
current-context: kind-kind
kind: Config
preferences: {}
users:
- name: docker-desktop
  user:
    client-certificate-data: LS0tLS1CRUdJTiBDRVJUSUZJQ0FURS0tLS0tCk1JSURRakNDQWlxZ0F3SUJBZ0lJZGlXaTg1bE1LMTB3RFFZSktvWklodmNOQVFFTEJRQXdGVEVUTUJFR0ExVUUKQXhNS2EzVmlaWEp1WlhSbGN6QWVGdzB5TlRBME1Ua3hNalE1TkRGYUZ3MHlOakEwTVRreE1qUTVOREZhTURZeApGekFWQmdOVkJBb1REbk41YzNSbGJUcHRZWE4wWlhKek1Sc3dHUVlEVlFRREV4SmtiMk5yWlhJdFptOXlMV1JsCmMydDBiM0F3Z2dFaU1BMEdDU3FHU0liM0RRRUJBUVVBQTRJQkR3QXdnZ0VLQW9JQkFRRGNUU09mazFHV0Rrd3QKK0VBK2FJQVRVZk5WNWdWMHV2K0JhOGR6TGF4Zkp3N3Z6L1QxbEFtSG5rcXVzeG40dGQxa0pPRVVxTXVUbkY5UApvTUdKcmo3VFFCOUtwcUhqV3BRSEp3ZVpZd2hYMDhUKzQxam9jRnJBUUxUVGl0aVd1MzdDSW4xRE9vbDFUOW8xCmFscGNmbzkzRHc2ZXBrb3A2NmRuMGt2Q3dnVGdMeFZYa3BxaFhXUlJESk1qQXJRNGo3ZFhBZUFCWjdsSWJUSmQKUVl0Ujk3aFBwWmJNeFJEU0xEUjBIN3Bldngyb3ZDOWUwWVFpdVpIVUNaamJBaWRTaHNkU1E0bmg4SzJXMDh1RwpLUEVEWUZubStPWXRZWG4zZlZPRGFBaTVGeGVkTDBIVnZrbEQxV1YwMWpwTHltWmxwR21JS2g1OU5DTGN2UEJZCllnNVVMMEZ2QWdNQkFBR2pkVEJ6TUE0R0ExVWREd0VCL3dRRUF3SUZvREFUQmdOVkhTVUVEREFLQmdnckJnRUYKQlFjREFqQU1CZ05WSFJNQkFmOEVBakFBTUI4R0ExVWRJd1FZTUJhQUZQS2RuUUlMaDZYZnRubyt5YXNjRzJKMgpLY2wrTUIwR0ExVWRFUVFXTUJTQ0VtUnZZMnRsY2kxbWIzSXRaR1Z6YTNSdmNEQU5CZ2txaGtpRzl3MEJBUXNGCkFBT0NBUUVBekxCcGV1Wkk3bW84ZnNKRkp3Mlg0WWU2Yk0vUHhEOFNTOFhJaWRrNUVBdytVZ3E1S29uMmZMWnMKUktoeHQ0dXQ1cW9URVlBTEJuMlNLM1NZcTd3WTVoSTQyRXRHT3pyNUVpRGQvYmlYNDRCMEtVTDlrOExJRkkvagpYbHk5TE5FSkd2TzU0YjViNFc5UHpHWU9QRHBLbGtraTMrUnFOdXJIN256YXkvdHdDbVpaZVhCL0szckZLKzNMCmpEWUFORHdhUEJ4SUJBK1dtSm1XVGZaczVyV0FTRFpGYkgwNzk4a2NrL1FxeFVZKzhuV01ZdU4yajA2TVdTOUcKUDcwamtTYmpEWlB1Y3VSL09MVzdkaEFoelFOa0k2bCtkdlR3amJFaXhCL2NPdndRMHoxS2E5N1JqMDhjaFlLaApEM2JlYWpRUkU1bkE1U01CTmo5SHhDTVlyTkxZL3c9PQotLS0tLUVORCBDRVJUSUZJQ0FURS0tLS0tCg==
    client-key-data: LS0tLS1CRUdJTiBSU0EgUFJJVkFURSBLRVktLS0tLQpNSUlFcFFJQkFBS0NBUUVBM0Uwam41TlJsZzVNTGZoQVBtaUFFMUh6VmVZRmRMci9nV3ZIY3kyc1h5Y083OC8wCjlaUUpoNTVLcnJNWitMWGRaQ1RoRktqTGs1eGZUNkRCaWE0KzAwQWZTcWFoNDFxVUJ5Y0htV01JVjlQRS91TlkKNkhCYXdFQzAwNHJZbHJ0K3dpSjlRenFKZFUvYU5XcGFYSDZQZHc4T25xWktLZXVuWjlKTHdzSUU0QzhWVjVLYQpvVjFrVVF5VEl3SzBPSSszVndIZ0FXZTVTRzB5WFVHTFVmZTRUNldXek1VUTBpdzBkQis2WHI4ZHFMd3ZYdEdFCklybVIxQW1ZMndJblVvYkhVa09KNGZDdGx0UExoaWp4QTJCWjV2am1MV0Y1OTMxVGcyZ0l1UmNYblM5QjFiNUoKUTlWbGROWTZTOHBtWmFScGlDb2VmVFFpM0x6d1dHSU9WQzlCYndJREFRQUJBb0lCQUFkdmd4aEx2S0UzOGxKSwo0c0E0ZnJvb05mSmNSU3JmZE9oRlh3SUFOS1V4aUV1SDFWakVtbDI5ZGYvWGc3VGxUb2VteHdJUGdHK0hBNkNJCmFIL2hKYld6b0ZyQXJRNGpiSU9oU1p4ZnYxUlhqWHFjNmM5T200R0pyWkRHU3ZFcmV1ZktpamZPcmYwTHFPM00KblNncURXV1RXSWI2VGQ2RVdhNGpadk0zNFRvL3pJazdBajNuZEY1dnRzb29FQVdZbFNxOXc2Sk1MeEpjRStpSgpOWlRGVTNIeVF4b2JGTUpDTWZCNFNzWldoQlZXZ3NNS1FMOGczaElmY2w4ejdUU0w4NW9oT0pIbG9qZmNQc24vCi9vMmhDSkJheFJYM1FTcWhwVmh2MlB5YS9OV1prblZUQVJSMnBKdlFpejY2Y0J4K094WWtycVhTYU5Wdks2QTMKLytMVzZxRUNnWUVBOTEzNnpLY2Jyclk0UE5ZOS8zTFVGdWh1MU0wWmRhRzRCNHl6S3pLNDdCWkFFT2x0Ti9ZUAo4cG5nVzF5Z0k5aExnSkxWNldveEtVRDZKL25VQmJiLzNQNS9TWEhxbVBoODQvYjZmMU9RTVdQVmM3MlphbUNPCnVyckxWMXlxcTh0dTExanRJZ2VXU00wTkVyNGV1Z1gzalJaU3Vlem1JMDduM2kvTHBUSnY5RlVDZ1lFQTQvMVoKWHNUU3ptSlhxc3lyZExJNFRFSExQd3VXeVNTNUVqVlliajVqV0J6MTFlNnA2c0pPc1pLeXVsMHJNZGg1QVFUTwpReEU2ZjEvMllxOWhlQjdkZDBlaW03eWRjZlVWeWF3R0d1NWJQd2tBajRRY2Foc0JIZDNFell3YnRHNW4vVjByCkpYSDZlV3Q0dHE3T2h3QUthK2pYVFNDZHh4Zy9iQW1kVjZ6RHdyTUNnWUVBekl1NXgyQ25VMkQ2UDlRb2tBS3oKdmYyVktBSXcrMFF1bUkrUDJEaXBFUStWQ21iN0dUc3ZGTHlJK1FNdXFIVkNlWjd4bzRGY0JYRGxhZ2o3ZVg1SgpOTVI5SEk1R0h4ZmFyZWFjWEkwTXZzcCt4cVlSSmhXUjhIWmxqbWZoK1F6UEt1TXRzdVh6TDEvZlg1QTJlRHhXCjV5TitaSit2N2FKaHVTaHNqTDJZTmNFQ2dZRUE0M2ZEY2YwNFFuZjE5ZEJNaEpySDlyVnlQazJtdkxycDk1UEgKemY1ckNkK2pHellLeTlIZngrV1Fjc1pBTVhSRWpsS29KRndOSEVhM1FaQ3YwN1FmekVGcHFLNVAvQUhHSWplQwp3OTNxcGdLcVQ0WkUvMHhBR2ZkSXdyZTJjSmZ6SXVPUkI4UW5YbnR1cmYzTXl2NnNaeXVobkM4ZG5DWENLVjJTCllZWmFybWNDZ1lFQTVBS25BRU9NYXpreS9vV3AvdlJqbEwwS0ZpbFBkL2dOM2ZHMEplYzR5TC9GdzNjYmJVcGQKY2JkaGk1MktXTHhyNTJ1MWUrNzIrN2xyd1N3YXc3K2Rua1RsT3E5RXJkbWRPSlBpS01SbnhnNjlTSXNmdzRmWAp0MzJuRWl3SCtUNVRpclVHUm00b1lSaXNjTXUxV2ttdGJ5aEFUckZuTmVmNnRIN1R2QmdDNXZRPQotLS0tLUVORCBSU0EgUFJJVkFURSBLRVktLS0tLQo=
- name: kind-kind
  user:
    client-certificate-data: LS0tLS1CRUdJTiBDRVJUSUZJQ0FURS0tLS0tCk1JSURLVENDQWhHZ0F3SUJBZ0lJSmRybU52c3hBRW93RFFZSktvWklodmNOQVFFTEJRQXdGVEVUTUJFR0ExVUUKQXhNS2EzVmlaWEp1WlhSbGN6QWVGdzB5TlRBM01URXdOREExTWpWYUZ3MHlOakEzTVRFd05ERXdNalZhTUR3eApIekFkQmdOVkJBb1RGbXQxWW1WaFpHMDZZMngxYzNSbGNpMWhaRzFwYm5NeEdUQVhCZ05WQkFNVEVHdDFZbVZ5CmJtVjBaWE10WVdSdGFXNHdnZ0VpTUEwR0NTcUdTSWIzRFFFQkFRVUFBNElCRHdBd2dnRUtBb0lCQVFES2k4K3oKcERjVFZpSVp5aDZBRDBheXJMb2dBelI4ZGpqVkR4K0xReFN5OTZ0NEM3VC9lU3VxNnc1YWZNVHlxYWZLL002cAplYUJWWHM2R1FsNlRCaUVNbzdUT2tDRWhKOUVOalhSL2xqZGpZdGdCbjlQZy9xV2ZHMHFwK0xlWGl0SGtnaFpwCjhSckkvWlVJWnY1KzA0dElndDBML3ZBYXlSVk9lVElYckRCYVpKRVJZL1MxNWlsOUc3S1lmZ1B5R3p3UEFqNHMKOW9uSC9UdVpGbnhNMXgzdWlKVzhubXdlZW9VS1I5Wk9naVNkdDZHSTFPOHljZGxXbUpOR1cyWm9QMzhkNVQ0eAp6SWpIQlUrMWFldExUUnk4UWlsMEJVYm5NSmhLdzFlRklxSHlkSm1CRTYzclZJTmV2aG1wUk5xejJhS3NKdE12CkMwUGE3TTBWc0U3bmpqem5BZ01CQUFHalZqQlVNQTRHQTFVZER3RUIvd1FFQXdJRm9EQVRCZ05WSFNVRUREQUsKQmdnckJnRUZCUWNEQWpBTUJnTlZIUk1CQWY4RUFqQUFNQjhHQTFVZEl3UVlNQmFBRk9Rb2d4c1RuSzBUQjM0TApabVFMcEJLbU1mdStNQTBHQ1NxR1NJYjNEUUVCQ3dVQUE0SUJBUUNiUk9temUvM0I5WGtPVDg5NlA3MzNSWWR0CjlkdlBUY1cwZ1pRbFBPb0dEVWJEclE3WndxN1VGZmx2QnpDMG1UV0xRWnRwNHdnNjB1VWtienFHZzVFMEZyeGoKK0d4WGJWZzVwSTlwY3A4aW1oV0lKdE1TaFRxQ1JPdFN2Z29UK2pQcDBmTElmV0tGQzlsVk5zQ2orNUI2Wkp3MApCWVBFT2h3ZlEwNjRxVjdPRnJKdzh1bFd2bTVOdkhLT0lYdldXMmcyTVNLcG1ndFdBTjVmaEdweTVva0xTSzBPCk91cmVsd0JrVlpCQjRMdm5UWlZSOWpPV0J2OCtWYml3aGdCREp3Ui90SXIzd0o5TUMyQWp2VW1VK0lpRHNMcGgKblpBdXRNY3lMVmVRclg4VmZHSlZBbUpBWXorV20xWDExcnBnSzFoSXVYQk5LMmpMdXUzaU10YVVVQnRvCi0tLS0tRU5EIENFUlRJRklDQVRFLS0tLS0K
    client-key-data: LS0tLS1CRUdJTiBSU0EgUFJJVkFURSBLRVktLS0tLQpNSUlFb3dJQkFBS0NBUUVBeW92UHM2UTNFMVlpR2NvZWdBOUdzcXk2SUFNMGZIWTQxUThmaTBNVXN2ZXJlQXUwCi8za3JxdXNPV256RThxbW55dnpPcVhtZ1ZWN09oa0pla3dZaERLTzB6cEFoSVNmUkRZMTBmNVkzWTJMWUFaL1QKNFA2bG54dEtxZmkzbDRyUjVJSVdhZkVheVAyVkNHYitmdE9MU0lMZEMvN3dHc2tWVG5reUY2d3dXbVNSRVdQMAp0ZVlwZlJ1eW1INEQ4aHM4RHdJK0xQYUp4LzA3bVJaOFROY2Q3b2lWdko1c0hucUZDa2ZXVG9Ja25iZWhpTlR2Ck1uSFpWcGlUUmx0bWFEOS9IZVUrTWN5SXh3VlB0V25yUzAwY3ZFSXBkQVZHNXpDWVNzTlhoU0toOG5TWmdST3QKNjFTRFhyNFpxVVRhczltaXJDYlRMd3REMnV6TkZiQk81NDQ4NXdJREFRQUJBb0lCQUdTNzJCYk42eDVRempEcApWdlgxb3dHbDZnT1YxSHE2Q1ZYZGFhREhRZm9vTnoxREJVZXhxY2dkazB2cGxjSGlJck5QdkRDSmJ2Wkdhb3hYCllkWFpUSUtPd0pPakZ2YjRhSDVIQmRPV2tBRjczVlloZVMwRE9MZkN5UVZ6ejBzdEhXcDZVRTlzUEJnT0ZoclIKcm16QkpScHhDeUsyTGhBRVJmWjdUREI5MEthRFRmM3AwK1hJbFlDTElRQ0Z4Q1dHcmw5VzVybFVPTHVnVTAwQQpyckFLUjZWS2lBZjNrTHg3UXFVbitjWWZwQjcvdkx0NzJYZE5LWlZHVXZQYzBhMzFsdXc4d0ozZENtY0dlQUNmCkwyeEc5eWFJbW5ERnZvTXo0a2xHVGduSmc5UGE0VmFNY2RFb3l4MWhRZTE3WTZxT0xkRFNQOGc0eDdxcExleTQKWUlKMzdlRUNnWUVBL0J3L21uTS8xaVRSeUtldGk3ZFhtU1Jqa0U5Wll3Z0cxYkxJZXhHM24wSXJRM2dKRkdmUgpBK3I4ZThXaThaQ1lIR3FNTDVUWUd5WFlaYnNkci85MklsMlI3SEZBa2RwSGUyeHM2YVczQWRJU05MOVRBbkRYCjZMaXR1bG9YaHZaVVJrNVJobjF3MFF1aURsR0hyUEwvOGd2ZmIwTXB1cDZwdktDcndwOFdmd2tDZ1lFQXphdk4KQStvTTdEM2d2K1JaL2RYTXUzdjV1WUQ1VSsydWJqYnpxd3lHTnUrMGdpU3F3Mno5WE4wc09sendwa2g4Z0F6MApCb3U0TGN1VzJPZlFBakpBc1RONGZwUkFiN2pSZ1BtT3A0d3V5NTlteVVydUgwSGdrVTZndTZoT1J4RlB0VGtuClNDc3Z6VHRXL05xUVlwREFuY3l2b0drcXVOSVE0eE9IYTdxRjZHOENnWUVBMk1ubHU0ZHRGbFRVL0VtTHh6L2kKR0xNYzFvUVZKajVKdWtzaGNBcWRMbHAwMzNDQnhrVTdpN1h1WlBSZkdJQXcvUVoyQTVobmVIakRxejhLMlVQQQpMdTd0UXpkandjZkVmaEtQV1I4QnpwUDR5ZGpYcFpxcFh0b25zYjQweXY1Wkc1ZlBMT29ETUE5anpCSTVxL1BOCk9UTVNjQmQ5ODVicCtHVGxMZGNsUGhrQ2dZQkJEeFowSllaZStKZnV1NUpIL0dpZDZmS3Qzb0dBTGhCZVp0MmYKZnYrNXd3dXJtMk8xRy9YdGVUMHpYUkQyMkxraFhIZVkxbnUxYU5CWDNzUnEzWENmWFRQQmZxMy9hVXhFYXl6WQpEVDBFUm5FaVBhU2ptSmdyL3Q1VFhrTWNzZm92emx1QnRiK1NRVEljSEJ0T1FwSGJtTkw1Z0NyMmVlVERuL3JYCmRoSkQyd0tCZ0hoSXZGZzNYUVJsTUV0dVdrYkpxVnlZbVVaVFQ0NjA1R25FT3F0RGwwWXJWcU0wQS94cEJ2WlkKTmJqbWVwcnY2NzBtZmt1Zkw4dXJDNm1jbHdoSFhqek5tOTdnWnNoUm9GRE9VMXhyWHpSai9OUUhyR1A5NDY2Zwo2cXhISE1yWFV6K2ZXVDhRWTZNeGkzRk9Udlp1S2NuMUF5VlNzNVFMdFRpNUlQZlRvQjdHCi0tLS0tRU5EIFJTQSBQUklWQVRFIEtFWS0tLS0tCg==
kubectl run nginx --image=nginx:alpine
pod/nginx created
kubectl get pod -owide
NAME    READY   STATUS    RESTARTS   AGE   IP           NODE                 NOMINATED NODE   READINESS GATES
nginx   1/1     Running   0          11s   10.244.0.5   kind-control-plane   <none>           <none>
kubectl describe node | grep Taints
Taints:             <none>
ubectl describe node | grep Taints
zsh: command not found: ubectl
kubectl describe node | grep Taints
Taints:             <none>
kind delete cluster
Deleting cluster "kind" ...
Deleted nodes: ["kind-control-plane"]
The kind cluster has been successfully deleted. The output shows:

•  Cluster "kind" deleted
•  Node "kind-control-plane" removed

The cluster and all its resources have been cleaned up. If you need to create a new cluster later, you can simply run kind create cluster again.
cat ~/.kube/config

docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
kind create cluster --name myk8s --image kindest/node:v1.32.5 --config - <<EOF
kind: Cluster
apiVersion: kind.x-k8s.io/v1alpha4
nodes:
- role: control-plane
  extraPortMappings:
  - containerPort: 30000
    hostPort: 30000
  - containerPort: 30001
    hostPort: 30001
  - containerPort: 30002
    hostPort: 30002
  - containerPort: 30003
    hostPort: 30003
- role: worker
- role: worker
- role: worker
EOF
Creating cluster "myk8s" ...
 ✓ Ensuring node image (kindest/node:v1.32.5) 🖼 
 ✓ Preparing nodes 📦 📦 📦 📦  
 ✓ Writing configuration 📜 
 ✓ Starting control-plane 🕹️ 
 ✓ Installing CNI 🔌 
 ✓ Installing StorageClass 💾 
 ✓ Joining worker nodes 🚜 
Set kubectl context to "kind-myk8s"
You can now use your cluster with:

kubectl cluster-info --context kind-myk8s

Have a question, bug, or feature request? Let us know! https://kind.sigs.k8s.io/#community 🙂
kind get nodes --name myk8s
myk8s-worker3
myk8s-worker2
myk8s-control-plane
myk8s-worker
kubens default
Context "kind-myk8s" modified.
Active namespace is "default".
docker network ls
NETWORK ID     NAME      DRIVER    SCOPE
0a15f2739408   bridge    bridge    local
a9f686e29102   host      host      local
e1d4a20bbe59   kind      bridge    local
a435fd951441   none      null      local
docker inspect kind | jq
[
  {
    "Name": "kind",
    "Id": "e1d4a20bbe590710d7e154a369855cfa05a407d3151029c8ce09ea15b0c2a255",
    "Created": "2025-07-11T04:10:23.461544096Z",
    "Scope": "local",
    "Driver": "bridge",
    "EnableIPv4": true,
    "EnableIPv6": true,
    "IPAM": {
      "Driver": "default",
      "Options": {},
      "Config": [
        {
          "Subnet": "fc00:f853:ccd:e793::/64"
        },
        {
          "Subnet": "172.18.0.0/16",
          "Gateway": "172.18.0.1"
        }
      ]
    },
    "Internal": false,
    "Attachable": false,
    "Ingress": false,
    "ConfigFrom": {
      "Network": ""
    },
    "ConfigOnly": false,
    "Containers": {
      "2700a57de2daaf24801d541f861f54d8e130cad64a72eb3e902d2c73726cbeb3": {
        "Name": "myk8s-worker2",
        "EndpointID": "da0fa6fe10e94559fba310011397422f80882f751fada64be7a89ee85a97ea1c",
        "MacAddress": "7e:8c:75:f9:dc:0b",
        "IPv4Address": "172.18.0.3/16",
        "IPv6Address": "fc00:f853:ccd:e793::3/64"
      },
      "3e78d0e58b6d679b9f156799854e0b106cb5ae81fed3b951c4111286a94b587d": {
        "Name": "myk8s-worker",
        "EndpointID": "78ae0bf5927b31dd13ba5b859c7ab3121a216c78e91b95116b1ae70e7a9f368f",
        "MacAddress": "fa:fb:f0:9a:b9:59",
        "IPv4Address": "172.18.0.2/16",
        "IPv6Address": "fc00:f853:ccd:e793::2/64"
      },
      "47f68fc1bf2154541bf6b51fde4569968ace232d59be9f42eb166fd2eaf7bd02": {
        "Name": "myk8s-worker3",
        "EndpointID": "3fe889932a9db165ca32ebb1084e1adbeb737e0a3c389a3324455910e4ef0ae0",
        "MacAddress": "3e:ad:ff:68:1c:75",
        "IPv4Address": "172.18.0.4/16",
        "IPv6Address": "fc00:f853:ccd:e793::4/64"
      },
      "6aeddd3f53bddcf4c5ceee2bfa172a15ed3bb3d1e843e064336fa5c5ee4e7463": {
        "Name": "myk8s-control-plane",
        "EndpointID": "6b40a7643cf543eb106960f62e55fbe19fb086a91c9e4fc640945e1b8839b5c6",
        "MacAddress": "2e:27:68:53:16:c1",
        "IPv4Address": "172.18.0.5/16",
        "IPv6Address": "fc00:f853:ccd:e793::5/64"
      }
    },
    "Options": {
      "com.docker.network.bridge.enable_ip_masquerade": "true",
      "com.docker.network.driver.mtu": "65535",
      "com.docker.network.enable_ipv4": "true"
    },
    "Labels": {}
  }
]
kubectl cluster-info
Kubernetes control plane is running at https://127.0.0.1:53978
CoreDNS is running at https://127.0.0.1:53978/api/v1/namespaces/kube-system/services/kube-dns:dns/proxy

To further debug and diagnose cluster problems, use 'kubectl cluster-info dump'.
kubectl get node -o wide
NAME                  STATUS   ROLES           AGE     VERSION   INTERNAL-IP   EXTERNAL-IP   OS-IMAGE                         KERNEL-VERSION     CONTAINER-RUNTIME
myk8s-control-plane   Ready    control-plane   3m36s   v1.32.5   172.18.0.5    <none>        Debian GNU/Linux 12 (bookworm)   6.10.14-linuxkit   containerd://2.1.1
myk8s-worker          Ready    <none>          3m26s   v1.32.5   172.18.0.2    <none>        Debian GNU/Linux 12 (bookworm)   6.10.14-linuxkit   containerd://2.1.1
myk8s-worker2         Ready    <none>          3m26s   v1.32.5   172.18.0.3    <none>        Debian GNU/Linux 12 (bookworm)   6.10.14-linuxkit   containerd://2.1.1
myk8s-worker3         Ready    <none>          3m26s   v1.32.5   172.18.0.4    <none>        Debian GNU/Linux 12 (bookworm)   6.10.14-linuxkit   containerd://2.1.1
kubectl get pod -A -o wide
NAMESPACE            NAME                                          READY   STATUS    RESTARTS   AGE     IP           NODE                  NOMINATED NODE   READINESS GATES
kube-system          coredns-668d6bf9bc-k59gw                      1/1     Running   0          3m41s   10.244.0.2   myk8s-control-plane   <none>           <none>
kube-system          coredns-668d6bf9bc-n7pnt                      1/1     Running   0          3m41s   10.244.0.4   myk8s-control-plane   <none>           <none>
kube-system          etcd-myk8s-control-plane                      1/1     Running   0          3m48s   172.18.0.5   myk8s-control-plane   <none>           <none>
kube-system          kindnet-5vsxw                                 1/1     Running   0          3m41s   172.18.0.5   myk8s-control-plane   <none>           <none>
kube-system          kindnet-kkl49                                 1/1     Running   0          3m40s   172.18.0.3   myk8s-worker2         <none>           <none>
kube-system          kindnet-mjvtw                                 1/1     Running   0          3m40s   172.18.0.2   myk8s-worker          <none>           <none>
kube-system          kindnet-p4ks5                                 1/1     Running   0          3m40s   172.18.0.4   myk8s-worker3         <none>           <none>
kube-system          kube-apiserver-myk8s-control-plane            1/1     Running   0          3m48s   172.18.0.5   myk8s-control-plane   <none>           <none>
kube-system          kube-controller-manager-myk8s-control-plane   1/1     Running   0          3m48s   172.18.0.5   myk8s-control-plane   <none>           <none>
kube-system          kube-proxy-4jjqf                              1/1     Running   0          3m41s   172.18.0.5   myk8s-control-plane   <none>           <none>
kube-system          kube-proxy-69sbx                              1/1     Running   0          3m40s   172.18.0.3   myk8s-worker2         <none>           <none>
kube-system          kube-proxy-6v6kr                              1/1     Running   0          3m40s   172.18.0.4   myk8s-worker3         <none>           <none>
kube-system          kube-proxy-gsqrx                              1/1     Running   0          3m40s   172.18.0.2   myk8s-worker          <none>           <none>
kube-system          kube-scheduler-myk8s-control-plane            1/1     Running   0          3m48s   172.18.0.5   myk8s-control-plane   <none>           <none>
local-path-storage   local-path-provisioner-7dc846544d-lkz6t       1/1     Running   0          3m41s   10.244.0.3   myk8s-control-plane   <none>           <none>
kubectl get namespaces
NAME                 STATUS   AGE
default              Active   4m35s
kube-node-lease      Active   4m35s
kube-public          Active   4m35s
kube-system          Active   4m35s
local-path-storage   Active   4m31s
docker ps
CONTAINER ID   IMAGE                  COMMAND                  CREATED         STATUS         PORTS                                                             NAMES
47f68fc1bf21   kindest/node:v1.32.5   "/usr/local/bin/entr…"   4 minutes ago   Up 4 minutes                                                                     myk8s-worker3
2700a57de2da   kindest/node:v1.32.5   "/usr/local/bin/entr…"   4 minutes ago   Up 4 minutes                                                                     myk8s-worker2
6aeddd3f53bd   kindest/node:v1.32.5   "/usr/local/bin/entr…"   4 minutes ago   Up 4 minutes   0.0.0.0:30000-30003->30000-30003/tcp, 127.0.0.1:53978->6443/tcp   myk8s-control-plane
3e78d0e58b6d   kindest/node:v1.32.5   "/usr/local/bin/entr…"   4 minutes ago   Up 4 minutes                                                                     myk8s-worker
docker images
REPOSITORY                                          TAG                                                                           IMAGE ID       CREATED         SIZE
apache/polaris                                      latest                                                                        94c9f269141b   3 weeks ago     595MB
apache/polaris                                      postgres-latest4                                                              94c9f269141b   3 weeks ago     595MB
apache/polaris-admin-tool                           latest                                                                        68c25e4b4dd7   3 weeks ago     492MB
apache/polaris-admin-tool                           postgres-latest4                                                              68c25e4b4dd7   3 weeks ago     492MB
apache/polaris                                      postgres-latest3                                                              7871d8854cf5   3 weeks ago     602MB
apache/polaris-admin-tool                           postgres-latest3                                                              52028cc22fc6   3 weeks ago     499MB
apache/polaris                                      postgres-latest2                                                              58ff7200dcd6   3 weeks ago     602MB
apache/polaris-admin-tool                           postgres-latest2                                                              72e5ccb326fc   3 weeks ago     499MB
kindest/node                                        v1.32.5                                                                       6ce80de0598f   7 weeks ago     1.06GB
kindest/node                                        <none>                                                                        071dd73121e8   7 weeks ago     1.09GB
docker/desktop-kubernetes                           kubernetes-v1.32.2-cni-v1.6.0-critools-v1.31.1-cri-dockerd-v0.3.16-1-debian   ca2d12959459   4 months ago    400MB
registry.k8s.io/kube-apiserver                      v1.32.2                                                                       6417e1437b6d   4 months ago    93.9MB
registry.k8s.io/kube-controller-manager             v1.32.2                                                                       3c9285acfd2f   4 months ago    87.2MB
registry.k8s.io/kube-scheduler                      v1.32.2                                                                       82dfa03f692f   4 months ago    67.9MB
registry.k8s.io/kube-proxy                          v1.32.2                                                                       e5aac5df76d9   4 months ago    97.1MB
debezium/debezium-with-oracle-jdbc                  3.0.6.Final                                                                   3e7d8f395498   6 months ago    1.41GB
oracle/instantclient                                19                                                                            fa586f63e3da   7 months ago    499MB
registry.k8s.io/etcd                                3.5.16-0                                                                      7fc9d4aa817a   10 months ago   142MB
registry.k8s.io/coredns/coredns                     v1.11.3                                                                       2f6c962e7b83   11 months ago   60.2MB
registry.k8s.io/pause                               3.10                                                                          afb61768ce38   13 months ago   514kB
container-registry.oracle.com/database/enterprise   19.3.0.0                                                                      291fd8c7958b   22 months ago   8.32GB
docker/desktop-vpnkit-controller                    dc331cb22850be0cdd97c84a9cfecaf44a1afb6e                                      3750dfec169f   2 years ago     35MB
hivemetastore                                       v2.0.0                                                                        8dc2bc75ca4e   3 years ago     735MB
docker/desktop-storage-provisioner                  v2.0                                                                          c027a58fa0bb   4 years ago     39.8MB

docker exec -it myk8s-control-plane ss -tnlp
State           Recv-Q           Send-Q                     Local Address:Port                      Peer Address:Port          Process                                            
LISTEN          0                4096                          172.18.0.5:2379                           0.0.0.0:*              users:(("etcd",pid=635,fd=9))                     
LISTEN          0                4096                          172.18.0.5:2380                           0.0.0.0:*              users:(("etcd",pid=635,fd=7))                     
LISTEN          0                4096                          127.0.0.11:40697                          0.0.0.0:*                                                                
LISTEN          0                4096                           127.0.0.1:2381                           0.0.0.0:*              users:(("etcd",pid=635,fd=13))                    
LISTEN          0                4096                           127.0.0.1:2379                           0.0.0.0:*              users:(("etcd",pid=635,fd=8))                     
LISTEN          0                4096                           127.0.0.1:10257                          0.0.0.0:*              users:(("kube-controller",pid=528,fd=3))          
LISTEN          0                4096                           127.0.0.1:10259                          0.0.0.0:*              users:(("kube-scheduler",pid=521,fd=3))           
LISTEN          0                4096                           127.0.0.1:10248                          0.0.0.0:*              users:(("kubelet",pid=698,fd=16))                 
LISTEN          0                4096                           127.0.0.1:10249                          0.0.0.0:*              users:(("kube-proxy",pid=887,fd=11))              
LISTEN          0                4096                           127.0.0.1:38261                          0.0.0.0:*              users:(("containerd",pid=104,fd=11))              
LISTEN          0                4096                                   *:10256                                *:*              users:(("kube-proxy",pid=887,fd=24))              
LISTEN          0                4096                                   *:10250                                *:*              users:(("kubelet",pid=698,fd=19))                 
LISTEN          0                4096                                   *:6443                                 *:*              users:(("kube-apiserver",pid=577,fd=3))

kubectl create deployment timeserver --image=docker.io/gasida/timeserver:1
deployment.apps/timeserver created
kubectl expose deployment timeserver --type=NodePort --port 80 --target-port=80
service/timeserver exposed
kubectl get deploy,rs,pod,svc,ep -owide
NAME                         READY   UP-TO-DATE   AVAILABLE   AGE   CONTAINERS   IMAGES                          SELECTOR
deployment.apps/timeserver   0/1     1            0           23s   timeserver   docker.io/gasida/timeserver:1   app=timeserver

NAME                                    DESIRED   CURRENT   READY   AGE   CONTAINERS   IMAGES                          SELECTOR
replicaset.apps/timeserver-86f7b895c7   1         1         0       23s   timeserver   docker.io/gasida/timeserver:1   app=timeserver,pod-template-hash=86f7b895c7

NAME                              READY   STATUS             RESTARTS   AGE   IP           NODE           NOMINATED NODE   READINESS GATES
pod/timeserver-86f7b895c7-925hw   0/1     ImagePullBackOff   0          23s   10.244.1.2   myk8s-worker   <none>           <none>

NAME                 TYPE        CLUSTER-IP    EXTERNAL-IP   PORT(S)        AGE   SELECTOR
service/kubernetes   ClusterIP   10.96.0.1     <none>        443/TCP        9h    <none>
service/timeserver   NodePort    10.96.76.26   <none>        80:30971/TCP   7s    app=timeserver

NAME                   ENDPOINTS         AGE
endpoints/kubernetes   172.18.0.5:6443   9h
endpoints/timeserver                     7s

kubectl get deploy,rs,pod,svc,ep -owide
NAME                         READY   UP-TO-DATE   AVAILABLE   AGE   CONTAINERS   IMAGES                          SELECTOR
deployment.apps/timeserver   0/1     1            0           82s   timeserver   docker.io/gasida/timeserver:1   app=timeserver

NAME                                    DESIRED   CURRENT   READY   AGE   CONTAINERS   IMAGES                          SELECTOR
replicaset.apps/timeserver-86f7b895c7   1         1         0       82s   timeserver   docker.io/gasida/timeserver:1   app=timeserver,pod-template-hash=86f7b895c7

NAME                              READY   STATUS             RESTARTS   AGE   IP           NODE           NOMINATED NODE   READINESS GATES
pod/timeserver-86f7b895c7-925hw   0/1     ImagePullBackOff   0          82s   10.244.1.2   myk8s-worker   <none>           <none>

NAME                 TYPE        CLUSTER-IP    EXTERNAL-IP   PORT(S)        AGE   SELECTOR
service/kubernetes   ClusterIP   10.96.0.1     <none>        443/TCP        9h    <none>
service/timeserver   NodePort    10.96.76.26   <none>        80:30971/TCP   66s   app=timeserver

NAME                   ENDPOINTS         AGE
endpoints/kubernetes   172.18.0.5:6443   9h
endpoints/timeserver                     66s
k logs pod/timeserver-86f7b895c7-925hw
zsh: command not found: k
kubectl logs pod/timeserver-86f7b895c7-925hw
Error from server (BadRequest): container "timeserver" in pod "timeserver-86f7b895c7-925hw" is waiting to start: trying and failing to pull image
kubectl run curl-pod --image=curlimages/curl:latest --command -- sh -c "while true; do sleep 3600; done"
pod/curl-pod created
kubectl exec -it curl-pod -- curl timeserver
curl: (7) Failed to connect to timeserver port 80 after 2 ms: Could not connect to server
command terminated with exit code 7
kubectl scale deployment timeserver --replicas 2 && kubectl get pod -w
deployment.apps/timeserver scaled
NAME                          READY   STATUS              RESTARTS   AGE
curl-pod                      1/1     Running             0          30s
timeserver-86f7b895c7-925hw   0/1     ImagePullBackOff    0          3m7s
timeserver-86f7b895c7-xf72x   0/1     ContainerCreating   0          1s
timeserver-86f7b895c7-xf72x   0/1     ErrImagePull        0          4s
timeserver-86f7b895c7-925hw   0/1     ErrImagePull        0          3m12s
timeserver-86f7b895c7-925hw   0/1     ImagePullBackOff    0          3m23s
timeserver-86f7b895c7-xf72x   0/1     ImagePullBackOff    0          18s

^C%                                                                                                                                                                               
kubectl set image deployment timeserver timeserver=gasida/timeserver:2 && kubectl get pod -w
deployment.apps/timeserver image updated
NAME                          READY   STATUS              RESTARTS   AGE
curl-pod                      1/1     Running             0          65s
timeserver-86f7b895c7-925hw   0/1     ImagePullBackOff    0          3m42s
timeserver-86f7b895c7-xf72x   0/1     ErrImagePull        0          36s
timeserver-c744b9c65-tc7mc    0/1     ContainerCreating   0          0s
timeserver-c744b9c65-tc7mc    0/1     ErrImagePull        0          3s
timeserver-86f7b895c7-xf72x   0/1     ImagePullBackOff    0          47s
timeserver-c744b9c65-tc7mc    0/1     ImagePullBackOff    0          17s
^C%                                                                                                                                                                               
kubectl delete deploy,svc timeserver 
deployment.apps "timeserver" deleted
service "timeserver" deleted
```