# LU_Week9Project_Honeypot

# Project 8 - Honeypot

Time spent: **7** hours spent in total

> Objective: Create a repository on Github with a README.md that includes a brief write-up about your experiment.

## Steps

1. Create a VM for honeypot via cloud provider and ssh into it.
2. Install the honeypot application and deploy in the MHN console.
    - NOTE: MHN has to be cloned and is capable of detecting other honeypots through a sensor management system as well as attacks to the mhn.
3. Attack the honeypot using nmap.
    - TCP SYN/Connect()/ACK/Window/Maimon scans
    - Probe open ports to determine service/version info
    - OS detection

## Specifics
    - Dispatch the Ubuntu-specific dionaea honeypot
    - Information obtained:
      - 75 attacks from dionaea honeypot
      - Type of attacks (some not all):
        1. pcap
        2. smbd
        3. epmapper
        4. mssqld
        5. ftpd

## License

  Copyright [2017] [Kelly Lu]

  Licensed under the Apache License, Version 2.0 (the "License");
  you may not use this file except in compliance with the License.
  You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License.
