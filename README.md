# RandomGeneration
These are a random generation dataset of automation services and system policies, which are used in Rule Verification 
Framework (RVF) for the sake of assessing its stability and scalability.

For the sake of assessing our Rule Verification Framework (RVF) stability and scalability, we develop a small virtual building
automation to generate a number of automation services and policies, called Random Generation test cases.

Our virtual building simulates a study of large-scale users’ automation services and system constraints that represents 
the nature of any building automation system where the number of users, authored automation services and policies are 
exponential grow and represent a large-scale repository with complex and heterogeneity preferences.

The virtual building setting includes fifteen different locations (5 Halls, 5 Labs and 5 Offices) and for each of these 
locations a forty different devices (20 Integer device e.g., Temperature sensor and 20 Boolean device e.g., Door) are
assumed to be integrated to it.

A simple test cases was generated using the virtual building according to the rules:
(1) all attached devices are supposed working fine, 
(2) the number of rules in each service is between 6 to 8 rule, 
(3) the number of constraints in each policy is between 2 to 5 constraint, and
(4) the number of conditions and actions in each rule are between 0 to 4 and between 1 to 4, respectively.
