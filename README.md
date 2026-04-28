# Agentic AI Security Architecture (AWS Bedrock + MCP Integration)

This project demonstrates the design and implementation of a secure, cloud-native Agentic AI system using Amazon Bedrock AgentCore and Strands Agents.

It focuses on enforcing identity-driven access control, secure agent-to-tool communication (via MCP), and end-to-end observability for AI-driven workflows.

## 🖥️ Lab Environment & Requirements
Executed on a secure AWS EC2 instance (us-west-2) with least-privilege IAM roles.

**Requirements**
- Amazon Bedrock access
- Cognito User Pool for authentication
- Docker, AWS CLI, Python 3.11+

## 🧩 Project Architecture & Workflow
![Deployment Architecture](images/06-deployment-architecture.png)

## 🔐 Security Architecture Highlights
- Implemented Zero Trust access control using AWS Cognito (JWT-based authentication)  
- Secured agent-to-tool communication using Model Context Protocol (MCP)  
- Enforced least-privilege IAM roles across all system components  
- Eliminated hard-coded secrets using managed identity and credential services  
- Protected API access through AgentCore Gateway with controlled request validation

## ⚙️ System Capabilities
- Secure agent-to-tool interaction with structured and controlled execution  
- Real-time API integration through MCP-enabled tool invocation  
- End-to-end observability with CloudWatch for tracing and monitoring agent workflows  
- Scalable deployment using Docker, Amazon ECR, and AWS CodeBuild  
- Modular architecture supporting extensible AI agent workflows

## 🧠 Design Considerations
- Designed with a Zero Trust security model across distributed agent workflows  
- Prioritized identity-driven access control over static credential usage  
- Ensured modular architecture to support extensibility and integration  
- Focused on observability to enable auditability of AI-driven actions  

## 🛠️ Implementation Overview
- Developed Strands Agents integrated with Amazon Bedrock models and custom tools  
- Implemented secure identity and credential management using AgentCore Identity  
- Enforced JWT-based authentication via AWS Cognito for controlled gateway access  
- Enabled structured agent-tool communication using MCP with OpenAPI integration  
- Deployed system using Docker, Amazon ECR, and AWS CodeBuild  
- Configured CloudWatch for real-time observability and monitoring  

## ⚡ Key Features
- Secure JWT-based API gateway integration
- Zero-code MCP tool generation from OpenAPI
- Production-ready credential management
- Full session tracing and observability

## 📊 Outcomes & Results
- Successfully deployed secure Agentic AI workflows with external API integration  
- Achieved end-to-end authentication with zero hard-coded secrets  
- Validated real-time agent execution with monitored and traceable interactions  
- Demonstrated secure architecture patterns applicable to cloud and critical infrastructure environments  

## 🔧 Technologies & Tools
- Strands Agents • Amazon Bedrock • Bedrock AgentCore (Identity, Browser, Runtime, Gateway)
- Cognito • OpenAPI • MCP • Docker • ECR • CodeBuild • CloudWatch GenAI

## 📸 Implementation Evidence
### 1. First Working Strands Agent
![First Agent](images/00-first-agent-calculator.png)

### 2. Secure Credentials with AgentCore Identity
![Secure Credentials](images/01-secure-credentials-identity.png)

### 3. Cognito JWT Token Generation
![Cognito JWT](images/03-cognito-jwt-token.png)

### 4. AgentCore Gateway with OpenAPI MCP
![Gateway & MCP](images/04-openapi-mcp-gateway.png)

### 5. Gateway Testing with Strands Agent
![Gateway Testing](images/05-gateway-testing-with-strands.png)

### 6. CloudWatch Observability Dashboard
![Observability](images/08-cloudwatch-genai-dashboard.png)

## Related Component
This system includes secure agent-to-tool communication implemented using MCP.

See implementation:
https://github.com/CliffordEdewor/secure-mcp-agent-integration.git

## 📚 Use Case
This project demonstrates applied expertise in designing and securing production-grade Agentic AI systems in cloud-native environments, with capabilities directly applicable to protecting hybrid IT/OT infrastructures and critical national infrastructure.

## 📄 License
This project is provided for demonstration and portfolio purposes, showcasing applied implementation of secure Agentic AI systems.
