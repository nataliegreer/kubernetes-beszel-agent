<p align="center">
<img width="100" height="100" alt="image" src="https://github.com/user-attachments/assets/98b2edad-6dd6-419f-89ad-beb22d1637cd" /> <br />
<h1 align="center"> Kubernetes Beszel-agent </h1>
</p>

A [DaemonSet](https://kubernetes.io/docs/concepts/workloads/controllers/daemonset/) that deploys beszel-agent with automatic system naming. Just apply this daemonset and your nodes with automatically add themselves as systems to your Beszel hub.

You can access your Beszel hubs universal token by going to the Beszel hub Settings -> Tokens -> Fingerprints.

<img width="400" height="400" alt="Screenshot 2026-01-28 at 3 33 46 PM" src="https://github.com/user-attachments/assets/af14850d-7cc5-4c57-afa3-bea5c0e3fb92" /><img width="400" height="400" alt="Screenshot 2026-01-28 at 3 31 58 PM" src="https://github.com/user-attachments/assets/15baba1a-18e3-4e23-a05b-4a0c29b64f4d" />



## Enviornment Variables
- `KEY`: The SSH key of your node
- `HUB_URL`: The https URL of your Beszel hub
