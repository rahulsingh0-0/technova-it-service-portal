# Access Control Lists (ACL)

## Objective

Configure and test Access Control Lists (ACLs) to control who can access and modify ServiceNow records.

## Access Control Model

The project demonstrates the relationship:

User → Group → Role → ACL → Permission

ACLs are used to determine whether a user can perform specific operations on a record or field.

## ACL Operations

The following access operations were considered:

- Read
- Write
- Create
- Delete

## Testing Approach

Access was tested using users with different roles and group memberships.

The tests verify that:

- Authorized users can perform the permitted operation.
- Unauthorized users are denied access.
- Role and group assignments affect the resulting access.

## Example Test Users

### Deepak

Used to test access for an authorized user with the required permissions.

### Shiraj

Used to test access when the required permissions are not available.

## Skills Demonstrated

- ACL configuration
- Role-based access control
- User and group permissions
- Access testing
- ServiceNow security fundamentals
