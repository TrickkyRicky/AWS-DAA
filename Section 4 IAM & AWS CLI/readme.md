### IAM: Users and Groups

- IAM: Identity and Access Management, Global service
  - Can contain groups of users or just users without a group, This is ment to permit certains permissions and access to certain services
  - These roles can be assigned in JSON documents. In AWS we apply the **least privilege principle:** which means don't give more permissions than a user would need

### IAM: Policies

- group policies: which users can inherit the policies from a group
- inline policies: which are policies for users that dont belong to a group
- the JSON consist of version number, Id(optional), and the statement which holds an array of objects
- Statement
  - sID: this is an identifier for the statement
  - Effect: whether the statement allows or denies access
  - Principal: account/user/role to which the policy is applied to
  - Action: actions that the policy allows or denies
  - Resource: the resources to which the actions are applied
  - Condition: conditions for when the policy is in effect
- These policies can be written by Json or the Visual editor
