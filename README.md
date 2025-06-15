# Netpractice_basics
Discover the basics of networking

# NetPractice

## 🧠 Objective

**NetPractice** is an introductory project designed to help you understand the fundamentals of computer networking. Through a series of practical exercises, you will work with simulated networks to fix configuration issues related to IP addressing, subnetting, gateways, and routing.

---

## 📚 Key Concepts

Throughout this project, you will learn to:

- Understand and apply **IPv4 addressing**
- Use **subnet masks** and CIDR notation effectively
- Identify and fix common networking configuration errors
- Configure basic **routing** between networks
- Diagnose connectivity issues in simulated environments
- Analyze and interpret **network diagrams**

---

## 🛠️ Requirements

To complete this project successfully, you should have a basic understanding of:

- **IP addressing and subnetting**
- **Network and broadcast addresses**
- **Gateways and default routes**
- **How routers forward packets**

---

## 🧪 How It Works

1. Download the archive provided in the project page.
2. Extract the files to a folder of your choice.
3. Open `index.html` in a web browser to launch the NetPractice interface.
4. Complete all **10 levels** by fixing each broken network.
5. For each level:
   - Review the goal and the network diagram.
   - Adjust the unshaded fields to restore connectivity.
   - Click **[Check again]** to validate your solution.
   - Export your configuration using **[Get my config]** and save it to your repository.

---

## 📁 Submission

- You must submit **10 configuration files** (1 per level).
- Place all files at the **root** of your Git repository.
- Make sure to enter your **42 login** in the interface before exporting each config.
- Only the content of your repository will be evaluated.

---

## 🧑‍💻 Defense

- During the defense, you’ll be asked to solve **3 random levels** in a limited time.
- **External tools are not allowed**, except for basic calculators like `bc`.

---

## ✅ Tips

- Practice subnetting and routing using online tools such as:
  - https://subnettingpractice.com
  - https://jodies.de/ipcalc
- Study the basics of IPv4, CIDR, and routing before starting.
- Save and back up your configuration files after each level.

---

## 🧪 How to Test Each Level

You can test and validate each level of the project locally using Python’s HTTP server.

### 📦 Launching the NetPractice interface

From the folder where your project is located (the one containing `index.html`), run:

```bash
python3 -m http.server 8000

## 📌 Version

**NetPractice v3.3**
```

---

