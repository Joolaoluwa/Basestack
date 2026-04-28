# Week 2 day 2

# IAM POLICIES

IAM policies are json documents in AWS that grant permission to what resources can be accessed and what actions can be taken against the resource mentioned. Policies can be managed policies which are either defined by AWS or the customer, there are also inline policies which are directly assigned to the resource such as a user, group or role. Policies follow a structure of effect, action and resource associated with that specific user, group or role. In today’s task, I worked with the IAM simulator to simulate different scenarios for different level of access to an S3 bucket, to check for the effect of GETOBJECT, and, DELETEOBJECT. Explicit deny rules in AWS have a precedence over allow rules when explicitly defined in the policies

https://lnkd.in/eiKYBu9q

Defined the policy from scratch in a GitHub gist, two statements were defined, resource-scoped permissions and an explicit deny, #IAM #AWSSECURITY #HANDSONLEARNING
