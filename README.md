# QueryVS belgeler

Bu repository alanım ile ilgili aldığım notlar ve çalışma notlarımı içeren repo'dur. 

**Bulabileceğiniz başlıca konular şunlardır ;**
 - [Distributed Systems](distributed_systems/)
   - [**Infrastructure Engineering**](distributed_systems/infrastructure_engineering)
     - [Orchestration](distributed_systems/infrastructure_engineering/orchestration.md)
       - Virtual Machine
         - Virtlib
         - VMWare
         - VirtualBox
       - Container
         - Kubernetes
         - Mesos
         - Docker Swarm
     - [Container](distributed_systems/infrastructure_engineering/container.md)
       - Docker
       - containerd
       - podman
     - [Virtualization](distributed_systems/infrastructure_engineering/virtualization.md)
       - System VMs
       - Process VMs
       - Virtual Machine Language
     - [Proxy](distributed_systems/infrastructure_engineering/proxy.md)
       - nginx
     - [GitOPS](distributed_systems/infrastructure_engineering/gitops.md)
       - IaC
         - Terraform
         - Ansible
         - Chef
         - Puppet
     - [software engineering for infrastructure](distributed_systems/infrastructure_engineering/software_engineeringforinfra.md)
       - system tools
       - controller
       - Deployment Scripts
       - Monitoring service
       - Popular Language
         - Python
         - Golang
         - C/C++
     - [System Desing](distributed_systems/infrastructure_engineering/system_design.md)
       - Software Architectural Patterns
     - [Benchmark](distributed_systems/infrastructure_engineering/benchmark.md)
       - Devops Engineer
       - System Engineer
     - [Standards](distributed_systems/infrastructure_engineering/standards.md)
       - Security
         - ISO 27001 and ISO 27002
         - OWASP Top 10
     - [Management of infrastructure](distributed_systems/infrastructure_engineering/management.md)
       - Users permission
         - Developer level
           - Database permissions
           - Monitoring permissions
           - Deployment Permissions
           - Document Permissions
         - System Manager level 
           - Orchestration Management
           - Physical Server Management
           - Database Management
           - Users Management
           - VMs Management
           - Document Permissions
       - System checklists
         - troubleshooting
         - new change monitoring
       - Documentation
         - System design
         - Permissions lists
         - Services list
         - Evolution of Infrastructure
     - [**Cloud**](distributed_systems/infrastructure_engineering/cloud.md)
       - Public cloud
         - AWS
         - HuaweiCloud
         - Azure
       - Private Cloud
         - OpenStack
           - Compute
             - compute
             - containers
           - Hardware Lifecycle
             - ironic
             - cyborg
           - Storage
             - swift
             - cinder
             - manila
           - Networking
             - neutron
             - octavia
             - designate
           - Shared
             - keystone
             - placement
             - glance
             - barbican
           - Orchestration
             - heat
             - senlin
             - mistral
             - zaqar
             - blazar
             - aodh
           - Workload Provisioning
             - magnum
             - sahara
             - trove
           - Application Lifecycle
             - masakari
             - murano
             - solum
             - freezer
           - API proxies
             - EC2API
           - Web Frontend
             - horizon
             - skyline
   - [**Linux System Engineering**](distributed_systems/linux_system_engineering)
     - Init Systems
       - OpenRC
       - Systemd
       - SysVinit
     - Kernel Space
       - Syscalls
       - CPU Architecture
       - Driver
       - Firmware
       - Module
     - User Space
       - Command Language
         - Bash
         - ash
         - sh
         - csh
         - zsh
       - netwoking
         - Wireless
         - Wired
         - Virtual Network
         - Route
       - tools
         - Developing
         - System
           - File
           - Storage
           - network
       - troubleshooting
         - Monitoring
         - Log analysis
   - **Linux System Management**
     - linux distributions
       - Debian
         - Ubuntu
         - Devuan
       - Redhat
         - Fedora
         - CentOS
       - Gentoo
       - Arch
         - Artix
     - Package Management
       - rpm
       - yum
       - dnf
       - apt
       - apt-get
       - aptitude
       - pacman
       - portage
     - Networking
       - wireless
       - wired
       - virtual network
       - VPN
       - Proxy
       - Router
       - DNS
   - [**Devops Engineering**](distributed_systems/devops_engineering)
     - [GitOps](distributed_systems/devops_engineering/gitops.md)
       - Merge Requests
       - CI/CD
     - [CI/CD Services](distributed_systems/devops_engineering/cicd_services.md)
       - Jenkins
       - Tekton CI
     - [Repository Services](distributed_systems/devops_engineering/repository_services.md)
       - Nexus
       - Jfrog Artifactory
     - [Git Repository Services](distributed_systems/devops_engineering/git_repository_services.md)
       - Gitlab
     - [Project Management Services](distributed_systems/devops_engineering/project_management_services.md)
       - JIRA
       - TaskCafe
       - Trello
     - [Messaging Services](distributed_systems/devops_engineering/messaging_services.md)
       - Slack
       - Zulip
     - [Monitoring Services](distributed_systems/devops_engineering/monitoring_services.md)
       - Web Applications
         - Kibana
         - Grafana
       - zabbix
       - ELKStack
         - kibana
         - elasticsearch
         - beats
         - logstash
 - [**Software Engineering**](software_engineering)
   - Fundamentals
     - Algorithm
       - Basic concepts
         - UML
         - Pseudo code
         - flow chart
         - O(büyük o) notation
     - Coding
       - OOP
       - clean code
       - Design Patterns
   - Programing Languages
     - interpreted
       - Python
       - PHP
       - Perl
       - Ruby
     - compiled
       - Go
       - Rust
       - C
       - C++
       - Java
   - Building and Running Code
     - Languages
       - Compilable Languages
       - Interpretable Languages
     - Building Code
       - cmake
       - make
       - ninja
       - GNU autotools
 - **Database**
   - Relational Database
     - PostgreSQL
     - Mysql
     - MariaDB
   - Non-Relational Database
     - MongoDB
     - Elasticsearch
 - **Message Broker**
   - Apache Kafka
   - RabbitMQ
 - **Security**
   - Offensive (Red Team)
   - Defensive (Blue Team)
 - [**Test Engineering**](test_engineering)
   - [Static tests](test_engineering/static_tests.md)
   - [Dynamic tests](test_engineering/dynamic_tests.md)
     - Functional Testing
       - Unit Testing
       - Integration testing
       - System Testing
       - Acceptance Testing
     - Non-Functonal testing
       - Performance Testing
       - Security Testing
       - Compliance Testing

## QueryVS Belgeler Giriş

Bu döküman infrastructure engineering ile ilgili kapsamlı bir döküman olması amacı ile hazırlanıyor. Ayrıca kendi bilgimin üzerinden geçmem ve bunu açıklamam bana yararlı olabileceğinden hazırlamaya başladım. Bu dökümana herkes destek verebilir. Eğer bilgisayar bilimi altında burada olmayan bir kategoriyi eklemek ve katkı sunmak istiyorsanız, yapabilirsiniz. Sadece değişiklik yaptıktan sonra pull request atın.

Bu dökümanda yazan bölümlerin tamamı açık olarak dağıtılmasına ve okunmasına izin verilmektedir. Yazıların kopyalanması kullanılması serbesttir sadece açık bir şekilde kaynak belirtilmelidir. 

**Katkı sağlayanlar:**

 - Ahmet Numan Coşkun
 - ChatGPT

