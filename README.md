🚀 MongoDB + Mongo Express on Kubernetes

This setup deploys MongoDB and Mongo Express on a Kubernetes cluster (Minikube) to visualize and manage MongoDB data through a web UI.

🧠 What’s Included

MongoDB Deployment and Service configured within Kubernetes.

Mongo Express Deployment linked to MongoDB using environment variables (ME_CONFIG_MONGODB_SERVER, etc.).

NodePort Service exposing Mongo Express to the browser at 127.0.0.1:<nodeport>.

Verified successful connectivity and access to the default databases:

admin

config

local

Checked server metrics including uptime, MongoDB version, Node version, and active connections.

⚙️ Tech Stack

Kubernetes (Minikube)

MongoDB 8.0.15

Mongo Express (Node.js 18.20.3)

Docker for container images

YAML Manifests for Kubernetes configuration


<img width="1728" height="1117" alt="Screenshot 2025-10-14 at 2 15 46 PM" src="https://github.com/user-attachments/assets/17a2112f-ac84-4c08-882d-4710c1639b78" />
