Level 1: Resource

Level 2: Project
Manage API, Billing, collaborators.
Can have different owners/users
Project ID: Global unique, immutable AFTER creation, assigned by GCP
Project Name: Your own name, no need to be unique, chosen by you, mutable
Project number: globally unique, assigned by gcp, immutable
Resource Manager Tool: Can CRUD and restore projects, through RPC or REST.

Level 3: Folder
Can contain **projects or folders**.
Can group per department basis, delegate admin rights too so they can work independently.
To use folders, you must have organization nodes.

Level 4: Organization Node

**Cloud Identity for no org** or **Google Workspace automatic with org**

![[Pasted image 20250616163756.png]]