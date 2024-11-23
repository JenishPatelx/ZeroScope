ZeroScope is a cutting-edge implementation of Zero Trust Architecture (ZTA), designed to enhance network security by enforcing strict access controls and ensuring that no user, device, or service is trusted by default—whether they are inside or outside the network. Every access request is thoroughly verified before granting permissions to resources, eliminating the need for implicit trust and reducing vulnerabilities.

Project Components
The ZeroScope implementation is built around the following key components:

1. Trust Engine
The Trust Engine calculates trust scores for entities (users, devices) attempting to access resources. It evaluates factors like user behavior, device health, and context to determine trust levels, ensuring that only verified and compliant entities can interact with your resources.

2. Policy Engine
The Policy Engine enforces dynamic access control policies based on trust scores, resource requirements, and user roles. It ensures that entities can only access resources they are authorized to, based on the rules defined within the system.

3. Access Proxy
The Access Proxy acts as an intermediary layer between users/devices and network resources. It authenticates users, applies policies, and logs access attempts, creating a secure communication channel for resource access.

->Features
Trust Score Calculation: Assess and assign trust scores based on user/device behavior, network context, and health.
Dynamic Access Control: Enforce policies that control access based on trust levels, user roles, and resource requirements.
Real-time Monitoring: Continuously monitor and log access requests to ensure transparency and traceability of all network interactions.
Policy Enforcement: Ensure that only trusted and authorized users or devices can access sensitive resources on the network.


->Technologies Used

The project will utilize various technologies, including:

- Trust Engine: Python, Machine Learning Algorithms, Markov chains
- Policy Engine: Python
- Access Proxy: Nginx, OAuth, Flask framework

## Getting Started


1. Clone the repository: `git clone https://github.com/JenishPatelx/ZeroScope.git`
2. Install dependencies and set up the required environment.

