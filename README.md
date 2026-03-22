# 🔐 Linux Security Logging & Monitoring

## 📌 Overview

This project simulates a Security Operations Center (SOC) environment by implementing logging, auditing, and monitoring practices on Linux systems.

It focuses on detecting suspicious activity and ensuring traceability through system logs.

---

## 🎯 Objectives

- Enable system auditing
- Monitor authentication events
- Centralize logs
- Simulate SOC practices

---

## 🏗️ Architecture

- auditd for system auditing
- rsyslog for log management
- Ansible for automation
- Modular design for scalability

---

## ⚙️ Features

- Audit rules for sensitive files
- SSH login monitoring
- Privilege escalation tracking
- Log centralization simulation

---

## 🔍 Security Events Monitored

- User authentication (SSH)
- Privilege escalation (sudo)
- Critical file changes (/etc/passwd, /etc/shadow)

---

## 📂 Key Log Files

- /var/log/auth.log
- /var/log/secure
- /var/log/syslog

---

## 🚀 How It Works

The playbook configures auditd and rsyslog to capture and manage security events.

---

## 🧠 Skills Demonstrated

- Linux security
- SOC fundamentals
- Log analysis
- Automation with Ansible
- Incident visibility

---

## ⚠️ Notes

This project simulates SOC environments and should be adapted before production use.
