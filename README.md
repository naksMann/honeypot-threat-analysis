Honeypot Deployment and Threat Analysis
=

A honeypot built to attract attackers, capture what they do, and turn that activity into readable threat intelligence. Set up during my cybersecurity Work Intergrated Learning program at the 4IR Lab.

What a honeypot is for
=

A honeypot is a system that looks like a real target but exists only to be attacked. It has no legitimate users, so any traffic that reaches it is suspicious by definition. That makes it a clean way to study attacker behaviour: every connection, login attempt, and command is something worth looking at, with none of the noise you get from normal users.

What this project captures
=

The honeypot was deployed in a controlled lab and left exposed to incoming connections. From the activity it recorded, the project documents:

- Connection attempts and where they came from.

- Login attempts, including the usernames and passwords attackers tried.

- Commands run once a session was established.

- Patterns in attacker behaviour, mapped to common tactics and techniques.

Why it matters
=

Watching attackers in a safe environment teaches you what real intrusion attempts look like before you have to defend a production system against them. The credentials attackers try, the tools they reach for, and the order they do things in all feed back into better detection rules and stronger defences elsewhere.

Repository contents
=
```
honeypot-threat-analysis/
├── README.md
├── docs/
    └── Honeypot_Documentation.pdf

```
Findings
=
The full analysis, including captured activity and the breakdown of attacker behaviour, is in `docs/Honeypot_Documentation.pdf`.

Tools used
=
Honeypot framework, log analysis, traffic capture, Docker

Demo
=
Video walkthrough: https://youtu.be/Z07DxozD9tM

Author
=

Nakedi Tumelo Peta (naksMann)

Cybersecurity Intern, 4IR Lab

Computer Systems Engineering, Tshwane University of Technology
