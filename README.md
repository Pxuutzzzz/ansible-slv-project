\# Ansible Server Load Balancing (SLV) Project



\## 📌 Deskripsi

Project ini merupakan implementasi \*\*Server Load Balancing (SLV)\*\* menggunakan \*\*Ansible\*\* sebagai automation tool.

Sistem dirancang untuk mendistribusikan trafik HTTP secara merata ke beberapa web server menggunakan \*\*HAProxy\*\* sebagai load balancer,

dengan \*\*Apache2\*\* dan \*\*Nginx\*\* sebagai backend web server.



Project ini dibuat untuk memenuhi kebutuhan \*\*praktikum / tugas mata kuliah Cloud-Based Learning (CBL)\*\*.



---



\## 🧰 Teknologi yang Digunakan

\- Ansible

\- HAProxy

\- Apache2

\- Nginx

\- Ubuntu Server

\- Virtual Machine (VM)

\- Git \& GitHub



---



\## 🏗️ Arsitektur Sistem



| Role | IP Address | Keterangan |

|----|----|----|

| HAProxy | 192.168.33.237 | Load Balancer |

| Apache Web 1 | 192.168.33.238 | Backend Web Server |

| Apache Web 2 | 192.168.33.239 | Backend Web Server |

| Nginx Web | 192.168.33.240 | Backend Web Server |



HAProxy menggunakan metode \*\*round-robin\*\* untuk mendistribusikan request ke backend server.



---



\## 📂 Struktur Direktori





