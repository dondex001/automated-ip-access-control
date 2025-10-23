# 🧩 Update File Through Python Algorithm

## 📘 Overview
This project automates the process of updating an allow list of IP addresses used to control access to restricted content.  
The Python algorithm reads a file containing approved IP addresses (`allow_list.txt`), removes IPs found in a specified remove list, and updates the allow list file automatically.

This script eliminates the need for manual edits and helps ensure that only valid IPs retain access.

---

## ⚙️ How It Works

1. **Read the allow list file** – Opens `allow_list.txt` in read mode and loads its contents.
2. **Convert the data into a list** – Uses the `.split()` method to transform the string of IPs into a list.
3. **Remove IPs in the remove list** – Iterates through each IP in the `remove_list` and removes matches from the allow list.
4. **Write back the updated list** – Joins the updated IPs into a string and writes them back to `allow_list.txt`.

---

## Supporting File

This project includes one supporting file that provides the core logic behind its functionality:

- [`update_allowlist_algorithm.py`](https://github.com/dondex001/automated-ip-access-control/blob/main/update_allow_list_algorithm.py.md) — Implements the main algorithm responsible for updating the allowlist.

You can explore this file to understand how the system operates and how its components interact within the project.

