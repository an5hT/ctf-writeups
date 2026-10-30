🛡️ Cybersecurity Portfolio & Write-UpsA curated repository documenting hands-on offensive security labs, Capture The Flag (CTF) challenges, and custom automation tool development.🎯 Repository ObjectiveThe goal of this repository is not just to showcase completed badges or points, but to demonstrate proof of methodology, problem-solving, and practical engineering skills. Every tool and write-up here reflects active experimentation within authorized sandbox environments.📁 Repository Structurecybersec-portfolio-and-writeups/
├── README.md                          <-- Table of contents linking to your best tools & reports
├── tools/                             <-- Custom Python scripts built to automate lab/CTF solutions
│   ├── blind_sqli_extractor.py        <-- Automates PortSwigger Blind SQLi labs
│   ├── jwt_auditor.py                 <-- Decodes JWTs, tests 'alg: none' & weak HMAC secrets
│   └── cryptohack_encoding_solver.py  <-- Uses pwntools to solve 100 encoding levels in seconds
└── writeups/
    ├── web-and-api/
    │   ├── htb-oopsie-idor-fileupload.md
    │   ├── thm-sqhell-blind-sqli.md
    │   └── portswigger-graphql-jwt-chaining.md
    ├── network-forensics/
    │   ├── thm-carnage-pcap-investigation.md
    │   └── picogym-tftp-and-dns-exfiltration.md
    └── osint/
        └── thm-sakura-osint-investigation.md
