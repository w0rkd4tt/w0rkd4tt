# 🧑‍💻 W0rkkd4tt – Offensive Security Engineer

📧 Email: datnguyenlequoc2001.com  
🔗 GitHub: [github.com/w0rkd4tt](https://github.com/w0rkd4tt)  
🛡️ Pentester | Recon Automation | Burp Suite Certified Practitioner  

---

## 💡 Summary

Offensive security engineer với nền tảng mạnh về pentesting, code audit, và tự động hóa bảo mật. Có kinh nghiệm phát triển công cụ tích hợp sâu với Burp Suite để tự động hoá quy trình tìm bug và generate báo cáo bảo mật. Tập trung vào **SQLi**, **XSS**, **logic bugs**, **auth bypass**, và **RCE qua code review**.

---

## ⚙️ Kỹ năng chính

- ✅ Web Application Pentesting (OWASP Top 10, logic flaws, chained exploits)
- ✅ Code Review & Exploit Development (PHP, JS, Python)
- ✅ Recon & Automation (Burp Extension, CLI tools, OSINT)
- ✅ Report Writing & Vulnerability Disclosure
- ✅ Burp Suite Extension, Burp Scanner Integration
- ✅ Scripting: Python, Bash, Go (cơ bản), SQLi payloads

---

## 🛠️ Dự án cá nhân nổi bật

### 🔍 Burp Extension – Auto Scan + Report Generator
> Tự động crawl targets từ HackerOne, Bugcrowd, Chaos Dataset.  
> Gán tag, lọc trùng, phân loại asset theo scope & tech stack.
> Tích hợp sâu với Burp Scanner để tự động scan và generate report dạng md và json.

### 📓 oscp-note
> Tổng hợp lệnh và cheat sheet phục vụ thi OSCP và pentest thực chiến.

### 📡 Project-machinelearning-in-Modsec_NGINX
> Ứng dụng Machine Learning để tối ưu rule detection trong ModSecurity + NGINX.

### 🧿 Sharingan (Private)
> Bộ tool hỗ trợ đọc và phân tích tự động các kết quả scan/vuln. *(Private repo)*

### 🌐 Django-To-Do-list-with-user-authentication
> Ứng dụng web mẫu dùng để luyện auth bypass, CSRF, và logic flaws.

### 🔧 CVE / Pwn / R0OtM3
> Các repo phục vụ nghiên cứu lỗ hổng, khai thác local privilege escalation & reverse engineering.


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Project Timeline Flowchart</title>
  <style>
    body {
      background-color: #0d1117;
      font-family: 'Segoe UI', sans-serif;
      color: #c9d1d9;
      margin: 0;
      padding: 2rem;
    }
    h1 {
      text-align: center;
      color: #58a6ff;
    }
    .timeline {
      position: relative;
      max-width: 1000px;
      margin: 0 auto;
    }
    .timeline::after {
      content: '';
      position: absolute;
      width: 4px;
      background-color: #58a6ff;
      top: 0;
      bottom: 0;
      left: 50%;
      margin-left: -2px;
    }
    .container {
      padding: 10px 40px;
      position: relative;
      background-color: inherit;
      width: 50%;
    }
    .container.left {
      left: 0;
    }
    .container.right {
      left: 50%;
    }
    .content {
      padding: 20px;
      background-color: #161b22;
      position: relative;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0, 255, 255, 0.2);
    }
    .date {
      font-size: 0.9rem;
      color: #8b949e;
      margin-bottom: 5px;
    }
    .container::before {
      content: " ";
      position: absolute;
      width: 20px;
      height: 20px;
      right: -10px;
      background-color: #58a6ff;
      border: 4px solid #0d1117;
      top: 15px;
      border-radius: 50%;
      z-index: 1;
    }
    .container.right::before {
      left: -10px;
    }
    @media screen and (max-width: 768px) {
      .container {
        width: 100%;
        left: 0;
      }
      .container.right {
        left: 0;
      }
      .timeline::after {
        left: 20px;
      }
      .container::before,
      .container.right::before {
        left: 10px;
      }
    }
  </style>
</head>
<body>
  <h1>🚀 w0rkd4tt’s Project Timeline</h1>
  <div class="timeline">
    <div class="container left">
      <div class="content">
        <div class="date">📍 2021–2022</div>
        <h3>CVE / Pwn / R0OtM3</h3>
        <p>Nghiên cứu khai thác, privilege escalation, reverse engineering.</p>
      </div>
    </div>
    <div class="container right">
      <div class="content">
        <div class="date">📍 2022</div>
        <h3>vuln-nodejs-app / CraftCMS</h3>
        <p>Thực hành pentest web, phân tích custom CMS vulnerabilities.</p>
      </div>
    </div>
    <div class="container left">
      <div class="content">
        <div class="date">📍 2023</div>
        <h3>oscp-note / Burp Extension</h3>
        <p>Hỗ trợ học OSCP, tự động hóa báo cáo trong Burp Suite.</p>
      </div>
    </div>
    <div class="container right">
      <div class="content">
        <div class="date">📍 2024</div>
        <h3>Recon CLI Tool</h3>
        <p>Tự động hoá tìm target bug bounty, tagging, asset mapping.</p>
      </div>
    </div>
    <div class="container left">
      <div class="content">
        <div class="date">📍 2025</div>
        <h3>ModSec ML / Sharingan</h3>
        <p>Ứng dụng Machine Learning trong rule detection, auto vuln parsing.</p>
      </div>
    </div>
  </div>
</body>
</html>


---

## 🔧 Công cụ & Tech Stack

| Mảng     | Công cụ                                     |
|----------|---------------------------------------------|
| Recon    | amass, httpx, gau, hakrawler, nuclei        |
| Exploit  | Burp Suite Pro, custom scripts, Postman     |
| Dev      | Python, Flask, Go (basic), Git              |
| Platform | Linux, VPS, tmux, Docker                    |

---

## 📜 Chứng chỉ & Học tập

- 🎯 **Burp Suite Certified Practitioner**  
- 📖 Tự học từ HackTheBox, PortSwigger labs

---

## 📞 Liên hệ

> Rất sẵn sàng chia sẻ kiến thức, hợp tác dự án.

**w0rkkd4tt**  
📬 Telegram: [@w0rkkd4tt](https://t.me/w0rkkd4tt)
