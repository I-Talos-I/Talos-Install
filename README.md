# 🚀 Talos – Installation Guide

> *Because developers should spend time building software, not fighting installers.* ☕

Talos is an **open-source CLI tool** designed to simplify the installation and management of tools, libraries, and packages across environments.

This guide describes the **primary and recommended installation method** for Linux (x64).

---

## 📦 Recommended Installation (Global)

This method installs Talos globally, allowing you to run it from **any directory**.

### 1️⃣ Extract the archive

```bash
tar -xzf talos-linux-x64.tar.gz
```

### 2️⃣ Enter the package directory

```bash
cd Talos-Instal
```

### 3️⃣ Grant execution permissions

```bash
chmod +x talos
```

### 4️⃣ Install globally (recommended)

```bash
sudo cp talos /usr/local/bin/
```

> 🧠 *Why `/usr/local/bin`?*
> Because it’s already in your `PATH`. Talos likes things simple — much like a good espresso.

---

## ✅ Verify Installation

Once installed, Talos should be available system-wide:

```bash
talos --help
talos hello --name "Installed"
```

If you see output, congratulations 🎉
Talos is now active and ready for duty.

---

## 🛠 Notes

* This is the **official and preferred installation method**.
* No environment variables required.
* No dependency conflicts.
* Minimal ceremony. Maximum productivity.

---

## ☕ Final Words

> *Good tools disappear. Great tools just work.*
> — J.A.R.V.I.S.

Happy hacking, and remember:

**"If you can't do great things, do small things in a spectacular way."** — Jarvis, assistant of Faragon
