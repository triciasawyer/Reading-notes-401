# Reading notes class 8

## 5 steps to RBAC

**What is Role Based Access Control (RBAC) and why do we care?**
Role-Based Access Control (RBAC) is a method of access control that provides a structured approach to managing and controlling user access to resources within a system or organization. It revolves around the concept of roles, which are defined based on job functions, responsibilities, or organizational positions.

**Describe a Role/Permission heirarchy that you might implement using RBAC.**
Role: Guest
Permissions: Limited access to public information and resources. No ability to modify or create content.
Role: Member
Permissions: Access to member-only resources, ability to view and update personal profile information, and participate in discussions.
Role: Moderator
Permissions: All permissions of a Member role, plus additional capabilities to manage discussions, moderate content, approve or reject user-generated content, and enforce community guidelines.

**What approach might you take to implement RBAC?**
I’d start by identifying the roles that exist within the organization or system. Then, analyze the different levels of access needed for each role.
Next, I’d determine the specific permissions or access rights required for each role, considering what actions, operations, or resources each role needs to perform its designated tasks.
I’d also assign permissions to roles, associating the defined permissions with their respective roles. As well as considering which permissions are appropriate for each role based on their responsibilities

## wiki - RBAC

**If Authentication is “you are who you say you are,” what is Authorization?**
Authorization determines what resources a user can access.

**Name three primary rules defined for RBAC.**

1. Role-User Assignment: This rule defines the relationship between roles and users.

2. Role-Permission Assignment: This rule determines the permissions associated with each role. It specifies what actions, operations, or access rights are allowed for each role

3. User-Role Activation: This rule defines how access rights are activated based on the user's assigned roles. Once a user authenticates and their identity is verified, the system activates the access rights associated with their assigned roles.

**Describe RBAC to a non-technical friend.**
Image that there is a clubhouse with different rooms and activities. RBAC is like having different membership roles for people in the clubhouse. Each role has its own set of permissions and responsibilities. Say there are three roles: "Member," "Moderator," and "Administrator." As a member, you can access the common areas, join activities, and use certain facilities. The moderator has a bit more authority and can organize activities, manage reservations, and make sure everyone follows the rules. The administrator has the highest level of control and can manage memberships, allocate resources, and make important decisions about the clubhouse.
RBAC helps ensure that people have the right level of access based on their roles and responsibilities. It prevents unauthorized access and keeps things organized and secure.

## RBAC tutorial

**What Are access rights Associated with? The User? or The Role? Explain.**
Access rights define what actions or operations a user is permitted to perform on a particular resource or system. These rights determine the level of access a user has within an organization's network, applications, files, or other resources.

**Access Rights, or Authorization, is activated after a user successfully does what?**
Access rights, or authorization, are activated after a user successfully authenticates themselves.

**Explain how RBAC might benefit a business.**
One benefit being that RBAC helps enhance security by ensuring that users only have access to the resources and functions necessary for their roles. This minimizes the risk of unauthorized access and reduces the attack surface for potential security breaches. RBAC also simplifies the management of access rights, making it easier to enforce security policies.

## Reflection

**What are your learning goals after reading and reviewing the class README?**
I’m excited to learn about access controls and more about how RBAC works.

## Things I want to know more about
