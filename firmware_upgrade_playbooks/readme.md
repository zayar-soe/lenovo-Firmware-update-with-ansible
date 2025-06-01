# 🚀 Lenovo Firmware Update Automation with Ansible

This project provides two Ansible playbooks to automate **firmware management on Lenovo infrastructure** using **Lenovo XClarity Administrator (LXCA)** API.

---

## 📂 Project Structure

```bash
.
├── check_firmware_updates.yml   # Step 1: Check for available firmware updates from LXCA
├── apply_firmware_updates.yml   # Step 2: Apply approved firmware updates 
├── vars/
│   └── lxca.yml                 # LXCA login credentials and playbook variables
