<img width="918" height="1015" alt="image" src="https://github.com/user-attachments/assets/0ed0454d-223b-43f2-9b32-ff88a685fb96" />
In osTicket, roles are a way to group permissions and apply them consistently across multiple agents (staff users). Instead of assigning permissions one by one to every staff member, you configure a role, then assign it to staff through departments or teams. Here’s a short but clear guide you can use when explaining or setting this up:

🔑 1. What Roles Do

A Role defines what an agent can do in osTicket.

Examples of permissions include:

Creating tickets, editing tickets, or closing tickets

Managing user accounts

Assigning tickets to other agents

Deleting tickets or threads

By grouping these permissions into roles, you keep the system organized and secure.

⚙️ 2. How to Configure Roles

Log in as Admin → Go to Admin Panel → Agents → Roles.

Click “Add New Role”.

Give the role a name (e.g., Support Agent, Team Lead, Manager).

Under Permissions, check the boxes for the actions you want this role to be able to perform.

For example:

Support Agent → can create and reply to tickets, but not delete.

Manager → full ticket control, user management, reporting.

Save the role.

👥 3. Assigning Roles

Roles are assigned within Departments.

Example: In the “Customer Support” Department, you might assign:

Support Agent role to junior staff

Manager role to supervisors

This means permissions can vary depending on which department the agent is working under.

📌 4. Best Practices

Keep roles simple: Start with 2–3 standard roles (e.g., Agent, Lead, Manager).

Use least privilege principle: Only give the minimum permissions needed for the job.

Combine with Departments/Teams: Roles control what an agent can do; Departments control where they can do it; Teams allow temporary cross-department access.
