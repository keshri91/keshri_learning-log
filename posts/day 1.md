Here is your **Day 1** entry formatted and ready for your automated diary pipeline.

You can save the text below as `day1.txt` inside your `C:\Users\Mohit Keshri\OneDrive\Desktop\diary_folder` directory. When your script executes, Gemini API will polish it into Markdown, publish it to your GitHub repository, and generate a Medium draft in your local folder.

---

### Day 1: Laying the Foundations of Computer Networking

**Date:** October 5, 2026

**Focus:** Introduction to Computer Networking, OSI Model, & Basic CLI

---

#### 1. Overview & Objectives

Today marks the official beginning of my journey into Network Engineering. My goal for Day 1 was to get past high-level abstractions and build a clear, foundational mental model of how data travels across interconnected systems.

---

#### 2. Key Concepts Mastered

* **The OSI 7-Layer Model:** Deconstructed how data flows from application to physical transmission.
* **Layer 7 (Application):** HTTP, HTTPS, SSH, DNS.
* **Layer 4 (Transport):** TCP vs. UDP (Reliability vs. Speed).
* **Layer 3 (Network):** IP Routing, Logical Addressing, ICMP.
* **Layer 2 (Data Link):** MAC Addresses, Switching, Framing.
* **Layer 1 (Physical):** Bitstream transmission over physical media.


* **IP Addressing & Subnetting Basics:**
* IPv4 structure (32-bit dotted-decimal).
* Distinction between Public vs. Private IP ranges (RFC 1918).
* Understanding Default Gateways and Local Loopback (`127.0.0.1`).



---

#### 3. Hands-On CLI Exercises

Ran basic diagnostic commands on Linux/Windows CLI to analyze network state:

```bash
# Verify local IP interface configuration
ip a   # Linux
ipconfig /all   # Windows

# Test end-to-end connectivity
ping 8.8.8.8

# Trace path hops to destination
traceroute google.com

```

---

#### 4. Key Takeaways & Reflection

* Understanding how Layer 2 (MAC) and Layer 3 (IP) work together via ARP is essential before diving into routing protocols.
* Consistency in logging daily labs will make troubleshooting second nature.

**Next Goal (Day 2):** Deep dive into TCP/IP model, ARP protocol, and packet analysis using Wireshark.