# Automatiseerimine2 - AWX on K3s

This project sets up AWX on a lightweight Kubernetes cluster using `kurokobo/awx-on-k3s`.  
It was completed as part of the **Automatiseerimine 2** course assignment.

## 📦 What's Included

- Customized `awx-on-k3s` files (`base/`, `operator/`, etc.)
- Docker or Vagrant setup (if used)
- Optional rulebooks, backups, and restore setup

## 🚀 How to Run

1. Clone the repo:
git clone https://github.com/kristakutsar/automatiseerimine2.git
cd automatiseerimine2


2. Start the VM (if Vagrant was used):
vagrant up
3. Deploy AWX:
kubectl apply -k base/

4. Access AWX:
- URL: https://awx.172.20.10.5.nip.io (or your external IP)
- Default login: `admin`
- Password: `Passw0rd` (or whatever you set)

## 👩‍💻 Author

Krista Kutsar

