<h1>Kubernetes Pod Security with SecurityContext</h1>


<h2>Description</h2>
This project demonstrates how to secure Kubernetes workloads using securityContext. It enforces non-root users, disables privilege escalation, sets read-only filesystems, and drops unsafe Linux capabilities.
<br />


<h2>Tools and Technologies</h2>

- Kubernetes
- YAML
- securityContext
- Pod and Container Spec Configuration
- Linux Capabilities
- kubectl CLI

<h2>Project Walk-through</h2>

<p align="center">
Explore securityContext in a basic Pod without extra hardening <br />
<img src="https://i.postimg.cc/fyq0rvnz/1.jpg"/>
<br />
<br />
Harden the Pod by enforcing non-root user and disabling privilege escalation <br/>
<img src="https://i.postimg.cc/52dtNr3c/2.jpg" />
<br />
<br />
Deploy another Pod with only required Linux capabilities<br/>
<img src="https://i.postimg.cc/rwfFCpTT/3.jpg"/>
<br />
<br />


</p>

