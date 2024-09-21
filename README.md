To model mutual authentication between four entities (User, Things, Registration Gateway, and Server) using the AVISPA (Automated Validation of Internet Security Protocols and Applications) tool, you can write a protocol in the HLPSL (High-Level Protocol Specification Language). Here’s an outline of how to structure the authentication process and the corresponding code for these four entities:

### Mutual Authentication Entities:
1. User to Things: The User authenticates to a "Thing" (an IoT device).
2. Things to Registration Gateway: The Thing authenticates to the Registration Gateway (RG).
3. Registration Gateway to Server: The Registration Gateway authenticates to the Server (central authority).
4. User and Server: The User and Server mutually authenticate to each other.

### AVISPA HLPSL Structure:
- Define each entity's role: `User`, `Things`, `Registration Gateway`, and `Server`.
- Specify message exchange and key usage.
- Define session, environment, and goals.

Use the code in the docx file for creating HLPSL

### Running in AVISPA:
- This code can be run in the AVISPA tool by saving it as a `.hlpsl` file and using the AVISPA backend tools like OFMC, CL-AtSe, or SATMC for validation.

### Next Steps:
- You can customize this model according to your system's specific requirements, such as adding additional checks or incorporating cryptographic algorithms other than symmetric key encryption.
