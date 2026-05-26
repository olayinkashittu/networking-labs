This repository contains my personal IT portfolio website built using HTML, CSS, and JavaScript.

# networking-labs
│Cisco networking labs and troubleshooting practice
portfolio-website
│
├── README.md
├── index.html
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
├── script.js
└── images/
# VLAN Configuration Lab
