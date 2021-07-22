### SRE/DevOps

### What is a Site Reliability Engineer?
“Fundamentally, it’s what happens when you ask a software engineer to design an operations function…So SRE is fundamentally doing work that has historically been done by an operations team, but using engineers with software expertise, and banking on the fact that these engineers are inherently both predisposed to, and have the ability to, substitute automation for human labor.”
* [What is a Site Reliability Engineer?](https://hackernoon.com/so-you-want-to-be-an-sre-34e832357a8c)
* [Site Reliability Engineering by Google](https://landing.google.com/sre/book.html)
* [Being an On-Call Engineer](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44813.pdf)
* [Go for SREs Using Python](https://www.usenix.org/sites/default/files/conference/protected-files/srecon16_slides_hamilton.pdf)
* [DevOps Bookmarks](https://www.devopsbookmarks.org/)
* [School of SRE](https://linkedin.github.io/school-of-sre/)

------

#### Configuration Management

* [Ansible](https://www.ansible.com/)
* [Chef](https://www.chef.io/)
* [Foreman](https://theforeman.org/)
* [Loom](https://github.com/bfirsh/loom)
* [Puppet](https://puppet.com/)
* [SaltStack](https://saltstack.com/community/)

#### Continuous Integration & Delivery

* [GitLab CI](https://gitlab.com/gitlab-ci)
* [Jenkins](https://jenkins.io/)
* [Travis-CI](https://travis-ci.org/)

#### Error Tracking

* [OverOps](https://www.overops.com/)
* [Rollbar](https://rollbar.com/)
* [Sentry](https://sentry.io/welcome/)

#### High Availability

* [HAProxy](http://www.haproxy.org/)
* [Keepalived](http://www.keepalived.org/)

#### Logging & Monitoring

* [check_mk](https://mathias-kettner.de/check_mk.html)
* [collectd](http://collectd.org/)
* [Consul](https://www.consul.io/)
* [Grafana](https://grafana.com/)
* [Graphite](http://graphite.readthedocs.io/en/latest/)
* [jmxtrans](https://github.com/jmxtrans/jmxtrans)
* [Kibana](https://www.elastic.co/products/kibana)
* [Logstash](https://www.elastic.co/products/logstash)
* [Netdata](https://my-netdata.io/)
* [Nagios](https://www.nagios.org/)
* [OneOps](http://oneops.com/)
* [Packetbeat](https://www.elastic.co/products/beats/packetbeat)
* [Prometheus](https://prometheus.io/)
* [Sensu](https://sensuapp.org/)
* [Splunk](https://www.splunk.com/)
* [Zabbix](https://www.zabbix.com/)

#### Memory Caching

* [Memcached](http://memcached.org/)
* [Redis](https://redis.io/)

#### Message and Data Streaming

* [ActiveMQ](http://activemq.apache.org/)
* [Kafka](https://kafka.apache.org/)
* [RabbitMQ](https://www.rabbitmq.com/)
* [ZeroMQ](http://zeromq.org/)

#### Virtualization and Containers

* [Docker](https://docs.docker.com/)
* [Kubernetes](https://github.com/kubernetes/kubernetes)
* [Vagrant](https://www.vagrantup.com/)

#### Filesystems

* **[mhddfs](https://romanrm.net/mhddfs)**: join several filesystems together to
  form a single larger one.
* **[sshfs](https://github.com/libfuse/sshfs)**: allows you to mount a remote
  filesystem using SFTP. Most SSH servers support and enable this SFTP access
  by default, so SSHFS is very simple to use - there's nothing to do on the
  server-side.
* **[squashfs](http://squashfs.sourceforge.net/)**: Create and mount compressed
  filesystem images.
* **[xdiskusage](http://xdiskusage.sourceforge.net/)**: Visually represent
  disk usage in and below a directory.
* **[rsync](https://rsync.samba.org/)**: Provides fast, reliable, configurable
  incremental file transfer on local disk or over the network. Archive,
  mirror, etc.

#### Linting

* **[httpolice](https://github.com/vfaronov/httpolice)**: a validator for HTTP
  requests and responses. It can spot bad header syntax, inappropriate status
  codes, and other interoperability problems in your HTTP server or client.
* **[shellcheck](http://www.shellcheck.net/)**: a tool that gives warnings and
  suggestions for bash/sh shell scripts.

#### Networking

* **[mtr](https://www.bitwizard.nl/mtr/)**: My TraceRoute. combines the
  functionality of the 'traceroute' and 'ping' programs in a single network
  diagnostic tool.
* **[lft](https://linux.die.net/man/8/lft)**: display the route packets take
  to a network host/socket using one of several layer-4 protocols and
  methods. Basically traceroute for TCP, UDP and ICMP.
* **[netcat](https://en.wikipedia.org/wiki/Netcat)**: a computer networking
  utility for reading from and writing to network connections using TCP or
  UDP. Replacement for telnet. Can also act as a server.
* **[sshuttle](https://github.com/apenwarr/sshuttle)**: Sshutle is VPN over
  SSH without requiring a remote VPN server or admin rights. Instead, it
  builds up an ssh session and than locally forwards traffic over it by
  creating local PREROUTING firewall rules.
* **[stunnel](https://www.stunnel.org/)**: a proxy designed to add TLS
  encryption functionality to existing clients and servers without any changes
  in the programs' code.
* **[tcptraceroute](https://linux.die.net/man/1/tcptraceroute)**: A traceroute
  implementation using TCP packets
* **[wavemon](https://github.com/uoaerg/wavemon)**: an ncurses-based
  monitoring application for wireless network devices.
* **[rinetd](https://www.boutell.com/rinetd/)**: Redirects TCP connections
  from one IP address and port to another.
* **[dig](https://mediatemple.net/community/products/dv/204644130/understanding-the-dig-command)**:
  The multitool for DNS enquiries.
* **[ipcalc](http://jodies.de/ipcalc)**: IP network calculator. Available as
  online tool as well as a downloadable package. (Ubuntu users: `apt install
  ipcalc`).
* **[netalyzr](http://netalyzr.icsi.berkeley.edu/)**: Commandline tool that
  runs various network related tests and generates a report for potential
  problems. (careful: sends the results to Berkeley for research purposes).
* **[mitmproxy](https://mitmproxy.org/)**: An interactive console program that
  allows HTTP traffic flows to be intercepted, inspected, modified and
  replayed.
* **[iftop](http://www.ex-parrot.com/pdw/iftop/)**: iftop does for network
  usage what top(1) does for CPU usage. It listens to network traffic on a
  named interface and displays a table of current bandwidth usage by pairs of
  hosts. Handy for answering the question "why is our ADSL link so slow?".
* **[iptraf](http://iptraf.seul.org/)**: IPTraf is a console-based network
  statistics utility for Linux. It gathers a variety of figures such as TCP
  connection packet and byte counts, interface statistics and activity
  indicators, TCP/UDP traffic breakdowns, and LAN station packet and byte
  counts.

#### Security

* **[fail2ban](https://www.fail2ban.org/wiki/index.php/Main_Page)**: Fail2ban
  scans log files and bans IPs that show malicious signs. Easily protects your
  SSH ports against attacks.
* **[ferm](http://ferm.foo-projects.org/)**:  a tool to maintain complex
  firewalls, without having the trouble to rewrite the complex rules over and
  over again.
* **[testssl](https://testssl.sh/)**: checks a server's service on any port
  for the support of TLS/SSL ciphers, protocols as well as recent
  cryptographic flaws and more.
* **[pwgen](https://github.com/jbernard/pwgen)**: Generate pronouncable and
  easy to type passwords.
* **[keystore explorer](http://keystore-explorer.org/)**: Java GUI for
  managing Java Key stores (SSL certificate databases). Also lets you convert
  all kinds of certificate formats.
* **[qualys ssl server test](https://www.ssllabs.com/ssltest/)**: Online tool
  for deep analysis of the configuration of any SSL web server on the public
  Internet.
* **[mozilla ssl configuration
  generator](https://mozilla.github.io/server-side-tls/ssl-config-generator/)**:
  Generate secure SSL configurations for the most common browsers.
* **[mozilla observatory](https://observatory.mozilla.org/)**: Scan hosts for
  HTTPS, TLS and SSH to see if they are configured safely and securely. Warns
  about missing and improperly configured Content Security Policies for
  websites.
