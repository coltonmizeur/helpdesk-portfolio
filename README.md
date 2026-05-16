# Help Desk Portfolio
Colton Mizeur

---

## About
I built this lab to get hands-on experience with the tools and tasks I'd be doing in a help desk role. Everything here was done by me in a real environment, not simulated.

---

## Lab Setup
- Windows Server 2025 on AWS EC2
- Active Directory domain: helpdesk.local
- Ticketing: Zendesk

---

## Active Directory
I set up a domain controller from scratch and worked through the most common AD tasks a help desk tech handles daily.

What I did:
- Created user accounts for John Smith and Jane Doe
- Created a security group called HelpDesk-Users
- Added both users to the group
- Reset John Smith's password
- Disabled Jane Doe's account

<img width="1512" height="895" alt="Screenshot 2026-05-16 at 2 51 46 PM" src="https://github.com/user-attachments/assets/d8f6b581-94c7-47b6-8492-57f4ee40c0b1" />


---

## Ticket Workflow
I created and resolved three tickets in Zendesk tied to real AD work I did in the lab.

- Jane Doe locked out — found disabled account in AD, re-enabled it, reset password
- John Smith password expired — reset in AD, required change on next login
- New employee request — created AD account, added to security group

<img width="1512" height="808" alt="Screenshot 2026-05-16 at 3 31 42 PM" src="https://github.com/user-attachments/assets/65dac998-d44a-4650-9828-b66edecb7f66" />


---

## Tools Used
Windows Server 2025, Active Directory, PowerShell, Zendesk, AWS EC2
