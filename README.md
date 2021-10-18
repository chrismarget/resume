# chris marget  

chris@marget.com  
[@chrismarget](https://twitter.com/chrismarget)  
https://github.com/chrismarget  
https://fragmentationneeded.net

Experienced UNIX/Linux sysadmin, network engineer, sometimes developer, expert
troubleshooter. Automation zealot, application security evangelist, distributed
systems enthusiast, protocol aficionado. Interested in infrastructure
automation, secure application development, PKI and infosec in general. Head in
the cloud, but wary of devops.

### Professional Experience

**Mutualink, Inc. Feb 2020 - Present**  
*Infrastructure Architect*

Mutualink was the biggest account among my consulting gigs. It's been a ~9 year
relationship despite the 2 year timeline indicated above.

- Full spectrum of Linux and Network admin responsibilities for data center,
campus and remote offices.
- All aspects of this role performed to the standards befitting a critical
life-safety and emergency communications system.
- Designed, implemented and managed a 5x hub, ~1000 branch WAN with unusual
challenges related to IP multicast traffic engineering, QoS, and offline system
challenges. Maintaining a system where easily 1/3 of it (emergency response
stuff) is disconnected or powered off is... Interesting.
- Wrote internal tooling in Ansible/Bash/Go/Terraform/Perl/Python to automate
manufacturing, deployment and management of physical, virtual, and cloud system
resources.
- Designed and implemented components of shipping products in Bash/Perl/Python/Go.


**Independent Consultant Apr 2013 - Feb 2020**  
*Just me*

- Performed a variety of Linux and Networking projects directly contracted by
customers and as a subcontractor to other consulting firms.
- Customer verticals included financial services, pharmaceutical, manufacturing,
public safety, SME.
- Projects included design review, network upgrades and greenfield deployment,
cloud migrations, software development.


**BT Jan 2009 - Oct 2012**  
*Senior Consultant*

It was during my Network consulting tenure at BT that I completed my pivot to
network engineering. The constant stream of different projects, new customer
environments, and vendor product releases, combined with being expected to be
the expert in customer meetings was exhilarating and gave valuable perspective
on effective network design and ops practices.

- Pre-sales, post-sales and network project work at BT INS (a Cisco Gold VAR)
- Designed and implemented data center projects up to ~20k user access ports and
~200 DC cabinets.
- Projects unrelated to hardware sales include technical design reviews,
business process reviews, site migrations and cloud migrations.
- Customer verticals include financial services, biotech, pharmaceutical
manufacturing, chemical manufacturing, state and local government.
- Collected a bunch of obscure Cisco certifications required for Cisco partner
status because management knew they could count on me to absorb new information
quickly.


**Fidelity Investments Jul 2006 - Dec 2008**  
*Director, Network Engineering*

Fidelity was a Reuters customer I'd worked closely with since 2001. They poached
me from Reuters and moved me cross-country to lead a networking group dedicated
to supporting market data and trading applications.

- This role taught me a ton about mature IT ops processes in large
organizations. It turns out that when ITIL is done right, and every misstep is
used as input to a process improvement feedback loop, even huge organizations
can continuously improve. It's rarely seen, but is a thing of beauty.
- Planned and implemented an in-place network upgrade from hybrid-mode CatOS/IOS
to native IOS.
- Designed and implemented a new network topology built from carefully selected
hardware to better support the peculiar QoS and Multicast requirements of
pricing and trading applications.
- Reverse-engineered application and wire protocols, wrote custom analysis tools
to expedite troubleshooting.


**Reuters Apr 2001 - July 2006**  
*Senior Consultant*

This role was primarily Solaris/Linux admin work combined with high-touch
customer support/consulting around integrating Reuters' market pricing backend
engine into financial services customer environments. The network operators at
these customers were rarely prepared to support the multicast and QoS
requirements of this product family. Bridging that gap marked a hard pivot in my
career from *nix admin focus into network engineering.

- Planed and implemented integrations with WAN/Data Center/Campus/Server/Desktop
components ranging from 2 servers and a switch to 60 servers geographically
distributed with hundreds of consuming applications.
- Short and long-term migration and support projects for these systems.
- Frequently recognized as the #1 troubleshooting SME for this global company,
with regular international engagements for emergency break-fix and
troubleshooting. [I've got stories.](https://www.fragmentationneeded.net/2012/01/dispatches-from-trading-floor-moldudp.html)


**New York Times Company Digital ([boston.com](https://boston.com)) Jun 2000 - Apr 2001**  
*Manager Internet Systems Engineering*

This was the first role where I got to play architect and own responsibility for
my own system design decisions. Disregard the title, this was mostly an
individual contributor role and I did most of it alone.
- Responsibilities included the full spectrum of *nix administration and
services (DNS, DHCP, email, file servers, etc...) and rearchitecture,
installation, operation, maintenance of the production web services farm, simple
network administration tasks including L2 switching and load balancers.
- Executed a no-budget migration of services from one facility to another. I
managed every facet of this project from interviewing colo providers, physically
moving the gear, keeping the environments in sync, traffic engineering during
the migration, etc...
- The new architecture was extremely scalable and resilient with multiple layers
of cacheing hardware SSL offload, two stages of workload-based traffic steering
and cheap cattle-style servers doing the heavy lifting. After my departure, on
9/11 this environment saw traffic levels at 15 times the previous high-water
mark (previously set during the Boston marathon) and remained responsive while
many other news sites were unusable.


**US Air Force / USStratcom Oct 1994 - Oct 1998**  
*Enlisted software developer / UNIX administrator*

I'd used UNIX systems and done software development in college and as an intern
at a high-energy physics lab, but the Air Force *made* me a sysadmin. There was
a ~6 month delay waiting for my security clearance; I spent half of it in on a
Sun Microsystems campus, absorbing every class they had to offer, and the other
half in an unclassified lab environment. I was very fortunate.
- Began as a junior member of a sysadmin team responsible for a network with
~1500 users, ~500 workstations and a variety of servers ranging from Sun Sparc 1
through e6500.
- Became the SME for troubleshooting performance issues on the larger systems.
Can't tell these stories, but they usually revolved around Solaris' workload
reputation-based scheduler, resource limits, CPU fencing and the like.
- Implemented an [Orange Book](https://en.wikipedia.org/wiki/Rainbow_Series)
B2 system (Trusted Solaris) to pass messages between Top Secret and Secret
environments.
- Govt. #2 (this project was led by vendor/contractors) for a hybrid disk/tape
filesystem for user data: Infrequently accessed files spooled off to tape on a
*huge* multi-silo tape library. This thing was awesome.
  
### Example Projects / Research
- **eIDC32Proxy**: With a colleague, we reverse-engineered from wire protocol
analysis, c# disassembly and binary inspection the behavior of an enterprisey
IoT door lock, implemented a client, server, and proxy, [demonstrated by friends
at DEFCON 28](https://www.youtube.com/watch?v=ghiHXK4GEzE&t=5595s)
- **cisco-l2t**: Reverse engineered from binary inspection and wire protocol
behavior the little-known Cisco L2Trace service, implemented an aggressive
client which leaks configuration and topology info from Cisco Catalysts. This
project resulted in a [Cisco PSIRT advisory](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-20190925-l2-traceroute)
and my library is [now part of](https://www.rumble.run/docs/release-notes/#v256)
the Rumble network scanner.
- **oldDog**: A general-purpose software watchdog able to run arbitrary tasks as
arbitrary users. Applications "pet the dog" by touching a file which details
expire-time actions. It uses the [inotify](https://man7.org/linux/man-pages/man7/inotify.7.html)
API to keep track of touchfile create/remove/update/touch events. It's part of
the lifecycle management of containers which handle interactive user sessions in
a customer's product.
- **epsw2hosts**: Developed with a colleague, an [NSS](https://www.gnu.org/software/libc/manual/html_node/Name-Service-Switch.html)
plugin which provides records to the `hosts` system database using
application-specific knowledge about the state and availability of a fleet of
IoT-like appliances. This project is in two parts:
  - A userspace filesystem module which renders `/etc/hosts`-like file from
  in-memory state of the IoT universe each time the file is accessed. Written in
  Go.
  - NSS plugin (mention it under `hosts` in `/etc/nsswitch.conf` which consumes
    the file above.) Written in C.

### Buzzwords

###### Distinctions (most of these have expired)
* Cisco CCNA/CCNP (plus a pile of oddball partner certs)
* ISC^2 CISSP
* ISACA CISA
* Sun Certified Solaris Administrator
* Frequent Gestalt IT [Tech Field Day](https://techfieldday.com/about/) Delegate
* TS/SCI Security Clearance

###### Networking vendors/products/OSes
Cisco IOS/IOS-XE/NX-OS/LocalDirector/CSS/ACE, Catalyst and Nexus switches, ISR
and ASR routers, ASA, HPE/Comware, HPE/Aruba provision Cumulus, FASTPATH, VyOS,
Arista EOS, Juniper JunOS/ScreenOS, F5 BigIP LTM and GTM, Alteon and ArrowPoint
L7 switches.

###### Networking technologies
BGP, OSPF, EIGRP, STP, MLAG, OTV, SPB, MPLS L3 VPN LNIA (lab; never in anger)
IPSec, Wireguard, Zerotier, MP-BGP EVPN VXLAN (LNIA)

###### Development and Automation tools
Go, Python, Git, Perl, Bash, Ansible, Terraform, Packer, CloudFormation

###### Systems, Services
ISC DNS/DHCP, HTTP (apache, nginx), email (sendmail, postfix), Docker, AWS (EC2,
VPC, SSM, SecretsManager, IAM, IOTCore, Route53, Lambda, ImageBuilder, S3),
iptables/ebtables, Wireshark, OpenSSL
