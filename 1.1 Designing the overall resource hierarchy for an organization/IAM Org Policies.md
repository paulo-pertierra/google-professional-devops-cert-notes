### Who can do what?

Who = principal, might be an email.
Do = role, a collection of permissions.

Permissions like Create, Delete, start VMs, which is theoretically VM Manager.



Policies are inherited **downward.** You can add deny rules for roles.

**DENY** more important, than **ALLOW**. 

### Roles

Different roels

- Basic IAM Role
- Predefined IAM Role
- Custom IAM Role
	- You need to manage permissions that define the custom role you created
	- Custom roles can be applied only to project level or org level, NOT folder level.