# Integration of DAC and RBAC policies

Introduction:
------------
This project focuses on the integration of Discretionary Access Control (DAC) and Role-Based Access Control (RBAC) policies to enhance the security of a system.

•	DAC: Allows data owners to determine access permissions for resources.

•	RBAC: Assigns permissions based on user roles within an organization.



Methodology:
-----------
**Step 1**: Creating Users 

    Users are created using the `adduser` command and protected with passwords. 

**Step 2**: Creating Groups 

    Groups are created using the `addgroup` command. 
        
**Step 3**: Assigning Users to Groups 

    Users are assigned to their respective groups using the `usermod` command.  

**Step 4**: Verifying User Group Memberships 

    Group memberships are verified using the `id` command. 

**Step 5**: Setting User and Group Permissions 

    The `chown` and `chmod` commands are used to set permissions. 

**Step 6**: Creating the Required File 

    A `Documents` directory is created in April's account. 

**Step 7**: Reviewing the Required File by Developers 
 
    Developers are granted access to review `Reqs.pdf`. 

**Step 8**: Implementing RBAC Policies on Users 
   
    RBAC policies are applied to manage user access based on roles. 

**Step 9**: Deleting a User 

    The user 'Steven' is deleted from the Developer group by the administrator. 

**Step 10**: Checking Account and Access in Developers 

    Verifications are performed to ensure that access permissions are correctly updated. 

**Step 11**: New User Access Verification 

    New users added to the Developer group are verified to ensure they can review the `Reqs.pdf` 



Conclusion:
----------

This project demonstrates the integration of DAC and RBAC policies to create a secure and efficient access control system. By defining clear roles and permissions, the system ensures that only authorized users can access and manipulate critical resources, enhancing overall security and compliance.



