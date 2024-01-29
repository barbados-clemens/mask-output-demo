# Mask Nx Cloud Terminal Output


use `maskProperties` within [`nx.json`](./nx.json) with the env var value that should be removed from the terminalOutput

Output shown locally

![local output with env var not hidden](./img/local-output.png)

Output seen via Nx Cloud
![nx cloud output showing env var redacted](./img/nx-cloud-output.png)

