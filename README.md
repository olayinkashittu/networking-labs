# IT Support & Networking Portfolio

![Status](https://img.shields.io/badge/status-active-success)
![License](https://img.shields.io/badge/license-MIT-blue)
![Built With](https://img.shields.io/badge/built%20with-HTML%20%7C%20CSS%20%7C%20JavaScript-orange)

---

## About Me

Hi, I'm **Olayinka Shittu**.

I am an IT Support Administrator with hands-on experience in:

- IT support and troubleshooting
- Windows & Linux administration
- TCP/IP networking
- DNS & DHCP troubleshooting
- Active Directory user management
- Cisco networking fundamentals
- PowerShell scripting

I enjoy solving technical problems, supporting users, and building reliable IT systems.

---

## Portfolio Website

This repository contains my professional IT Support & Networking portfolio website built using:

- HTML
- CSS
- JavaScript

The website showcases:
- Technical skills
- Networking labs
- Troubleshooting projects
- PowerShell scripts
- IT support experience

---

## Featured Projects

### DNS Troubleshooting Lab

Diagnosed and resolved DNS-related connectivity issues preventing users from accessing websites using domain names.

#### Tools Used
- ipconfig
- ping
- nslookup
- Command Prompt

#### Skills Demonstrated
- DNS troubleshooting
- Network diagnostics
- Connectivity testing
- Windows troubleshooting

---

### VLAN Configuration Lab

Configured VLANs on Cisco switches and assigned switch ports to VLANs.

#### Sample Configuration

```bash
enable
configure terminal

vlan 10
name SALES

interface fa0/1
switchport mode access
switchport access vlan 10
no shutdown

write memory
```

#### Skills Demonstrated
- VLAN configuration
- Cisco switch management
- Network segmentation
- CLI administration

---

### PowerShell PC Information Script

Created a PowerShell script to display:
- System information
- Disk usage
- IP configuration
- Computer details

#### Skills Demonstrated
- PowerShell scripting
- Windows administration
- Automation

---

## Technical Skills

### Operating Systems
- Windows
- Linux

### Networking
- TCP/IP
- VLANs
- DNS
- DHCP
- LAN/WAN

### Tools & Technologies
- Active Directory
- PowerShell
- Command Prompt
- Cisco CLI
- Git & GitHub

---

## Folder Structure

```text
portfolio-website/
│
├── index.html
├── style.css
├── script.js
├── README.md
└── images/
```

---

## Future Improvements

- Add dark mode
- Add downloadable CV
- Add certification section
- Add contact form
- Add more networking labs
- Add Linux administration projects

---

## Connect With Me

- GitHub: https://github.com/olayinkashittu
- Email: talk2_olayinka@yahoo.com 
---

## License

This project is licensed under the MIT License.

This repository contains my personal IT portfolio website built using HTML, CSS, and JavaScript.

# networking-labs
│Cisco networking labs and troubleshooting practice
portfolio-website
│
├── README.md
├── index.html
<button id="darkToggle">Toggle Dark Mode</button>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IT Support & Networking Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="container">
            <h1>Olayinka Shittu</h1>
            <p>IT Support Administrator | Networking | System Administration</p>

            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#labs">Networking Labs</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <h2>Building Reliable IT & Network Solutions</h2>
            <p>
                Passionate IT Support Administrator with hands-on experience
                in troubleshooting systems, managing networks, and supporting users.
            </p>

            <a href="#projects" class="btn">View My Projects</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2>About Me</h2>

            <p>
                I am an IT Support Administrator with practical experience in:
            </p>

            <ul>
                <li>Windows & Linux Administration</li>
                <li>TCP/IP Networking</li>
                <li>Active Directory User Management</li>
                <li>Hardware & Software Troubleshooting</li>
                <li>DNS & Connectivity Troubleshooting</li>
                <li>PowerShell Automation</li>
            </ul>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <div class="container">
            <h2>Technical Skills</h2>

            <div class="skills-grid">
                <div class="card">Windows Administration</div>
                <div class="card">Linux</div>
                <div class="card">Cisco Networking</div>
                <div class="card">DNS & DHCP</div>
                <div class="card">PowerShell</div>
                <div class="card">TCP/IP</div>
                <div class="card">Active Directory</div>
                <div class="card">Troubleshooting</div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <div class="container">
            <h2>Projects</h2>

            <div class="project-card">
                <h3>DNS Troubleshooting Lab</h3>

                <p>
                    Diagnosed and resolved DNS issues preventing users from accessing websites.
                </p>

                <h4>Tools Used:</h4>

                <ul>
                    <li>ipconfig</li>
                    <li>ping</li>
                    <li>nslookup</li>
                    <li>Command Prompt</li>
                </ul>
            </div>

            <div class="project-card">
                <h3>PC Information PowerShell Script</h3>

                <p>
                    Created a PowerShell script to display system information,
                    disk usage, and network configuration.
                </p>
            </div>
        </div>
    </section>

    <!-- Networking Labs Section -->
    <section id="labs">
        <div class="container">
            <h2>Networking Labs</h2>

            <div class="lab-card">
                <h3>VLAN Configuration Lab</h3>

<pre>
enable
configure terminal

vlan 10
name SALES

interface fa0/1
switchport mode access
switchport access vlan 10
no shutdown

write memory
</pre>

            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact</h2>

            <p>Email: yourname@email.com</p>

            <p>
                GitHub:
                <a href="https://github.com/yourusername" target="_blank">
                    github.com/yourusername
                </a>
            </p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 Olayinka Shittu | IT Support Portfolio</p>
    </footer>

    <script src="script.js"></script>

</body>
</html>
├── style.css
/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f7fa;
    color: #333;
}

/* Container */
.container {
    width: 90%;
    max-width: 1100px;
    margin: auto;
}

/* Header */
header {
    background-color: #0d1b2a;
    color: white;
    padding: 20px 0;
}

header h1 {
    text-align: center;
    margin-bottom: 10px;
}

header p {
    text-align: center;
    margin-bottom: 15px;
    color: #cbd5e1;
}

/* Navigation */
nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    flex-wrap: wrap;
}

nav ul li {
    margin: 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #38bdf8;
}

/* Hero Section */
.hero {
    background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
    url('images/network.jpg') center/cover no-repeat;

    color: white;
    text-align: center;
    padding: 100px 20px;
}

.hero h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

.hero p {
    max-width: 700px;
    margin: auto;
    margin-bottom: 30px;
}

.btn {
    display: inline-block;
    background-color: #38bdf8;
    color: white;
    padding: 12px 25px;
    text-decoration: none;
    border-radius: 5px;
    transition: 0.3s;
}

.btn:hover {
    background-color: #0284c7;
}

/* Sections */
section {
    padding: 60px 0;
}

section h2 {
    text-align: center;
    margin-bottom: 30px;
    color: #0d1b2a;
}

/* About */
#about ul {
    margin-top: 20px;
    padding-left: 20px;
}

#about li {
    margin-bottom: 10px;
}

/* Skills */
.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
}

.card {
    background: white;
    padding: 20px;
    text-align: center;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    font-weight: bold;
}

/* Projects */
.project-card,
.lab-card {
    background: white;
    padding: 25px;
    margin-bottom: 25px;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.project-card h3,
.lab-card h3 {
    margin-bottom: 15px;
    color: #0d1b2a;
}

.project-card ul {
    margin-top: 10px;
    padding-left: 20px;
}

/* Code Block */
pre {
    background-color: #1e293b;
    color: #f8fafc;
    padding: 20px;
    border-radius: 8px;
    overflow-x: auto;
    margin-top: 15px;
}

/* Contact */
#contact p {
    text-align: center;
    margin-bottom: 15px;
}

#contact a {
    color: #0284c7;
    text-decoration: none;
}

#contact a:hover {
    text-decoration: underline;
}

/* Footer */
footer {
    background-color: #0d1b2a;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 40px;
}

/* Responsive */
@media (max-width: 768px) {

    .hero h2 {
        font-size: 2rem;
    }

    nav ul {
        flex-direction: column;
        align-items: center;
    }
}
├── script.js
// Smooth scrolling for navigation links
document.querySelectorAll('nav a').forEach(link => {
    link.addEventListener('click', function (e) {
        e.preventDefault();

        const targetId = this.getAttribute('href');
        const targetSection = document.querySelector(targetId);

        targetSection.scrollIntoView({
            behavior: 'smooth'
        });
    });
});

// Display current year automatically in footer
const footer = document.querySelector('footer p');
const currentYear = new Date().getFullYear();

footer.innerHTML = `© ${currentYear} Olayinka Shittu | IT Support Portfolio`;

// Simple fade-in animation on scroll
const sections = document.querySelectorAll('section');

window.addEventListener('scroll', () => {
    sections.forEach(section => {
        const sectionTop = section.getBoundingClientRect().top;
        const screenPosition = window.innerHeight / 1.2;

        if (sectionTop < screenPosition) {
            section.classList.add('show');
        }
    });
});

// Add initial hidden class
sections.forEach(section => {
    section.classList.add('hidden');
});
└── images/
# VLAN Configuration Lab
