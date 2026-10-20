# 🛡️ Firewall Configuration

## 🔐 1. Allow SSH

```bash
sudo ufw allow ssh
```

This allows SSH connections so administrators can access and manage the server remotely.

## 🚫 2. Set the Default Firewall Rules

```bash
sudo ufw default deny incoming
sudo ufw default allow outgoing
```

The first command blocks incoming connections unless they are allowed by a firewall rule, while the second allows outgoing connections by default.

## ⚙️ 3. Enable the Firewall

```bash
sudo ufw enable
```

This turns on the firewall and applies the configured rules.

## 🌐 4. Allow Port 8080

```bash
sudo ufw allow 8080/tcp
```

This allows incoming TCP connections on port 8080 so users can access the Nginx web application.

## 🔎 5. Check the Firewall Rules

```bash
sudo ufw status verbose
sudo ufw status numbered
```

These commands show the firewall status, default policies, and numbered rules so I can check whether the settings are correct.

## ⚠️ 6. Why SSH Must Be Allowed First

If I enable UFW before allowing SSH, remote SSH access may be blocked, which could prevent me from managing the server remotely.
