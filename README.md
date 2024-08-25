# DomainScan Surrounding PoC -- Pilot

**DomainScan Surrounding**! is a very simple py script tool for search subdomains, checking if they’re alive, and seeing if they’re up and running. For getting the lowdown on a domain’s subdomains.

## What’s Inside?

- **Subdomain Enumeration:** Automatically pulls in subdomains from sources like Sublist3r and DNS Dumpster.
- **DNS Resolution Check:** Figures out which subdomains are live by resolving their DNS records.
- **HTTP Availability Check:** Pings the subdomains to see if they’re up, and tells you their status.
- **Visuals:** Generates cool bar charts so you can quickly see which subdomains are active.
- **DataFrames with Pandas:** All the results are stored in Pandas DataFrames, making it super easy to work with or export the data.

## How to Get Started

1. Clone the repo:
    ```bash
    git clone https://github.com/yourusername/domainscan-surrounding-poc.git
    ```
2. Install the dependencies (make sure you’re using a virtual environment):
    ```bash
    pip install -r requirements.txt
    ```
3. Run the main script with your target domain:
    ```bash
    python main.py
    ```

## Why You Should Care

Dive into the subdomains of any domain, see which ones are active, and check out their status—all while getting some nice data visualizations. 
Doing some recon for a security assessment sshould have you covered.
