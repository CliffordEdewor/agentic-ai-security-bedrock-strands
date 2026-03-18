# Agentic AI Security with Strands Agents & Bedrock AgentCore

**Hands-on labs from BeSA Week 3** - Building, securing, and deploying production-grade Agentic AI agents using Amazon Bedrock AgentCore, Strands framework, MCP Gateway, and Cognito authentication.
## 🎯 Objectives
- Build functional Strands Agents with Bedrock models and tools
- Implement secure credential management and JWT authentication
- Create and test AgentCore Gateway with OpenAPI-to-MCP conversion
- Deploy agents to Bedrock AgentCore Runtime with full observability

## 🖥️ Lab Environment & Requirements
Executed on a secure AWS EC2 instance (us-west-2) with least-privilege IAM roles.

**Requirements**
- Amazon Bedrock access
- Cognito User Pool for authentication
- Docker, AWS CLI, Python 3.11+

## 🧩 Project Architecture & Workflow
![Deployment Architecture](screenshots/06-deployment-architecture.png)

## ⚙️ Key Implementation Steps
- Created Strands Agents with custom tools and Bedrock models
- Secured credentials using Bedrock AgentCore Identity
- Implemented Cognito JWT authentication for gateway access
- Built MCP tools automatically from OpenAPI specifications
- Deployed to Bedrock AgentCore Runtime with Docker + ECR + CodeBuild
- Enabled CloudWatch GenAI observability

## ⚡ Key Features
- Secure JWT-based API gateway integration
- Zero-code MCP tool generation from OpenAPI
- Production-ready credential management
- Full session tracing and observability

## 📊 Outcomes & Results
- Successfully deployed and tested agents with external API integration
- Achieved secure authentication with zero hard-coded secrets
- Demonstrated real-time gateway testing and observability
- Skills now directly applied to cloud security and AI agent protection in critical infrastructure

## 🔧 Technologies & Tools
- Strands Agents • Amazon Bedrock • Bedrock AgentCore (Identity, Browser, Runtime, Gateway)
- Cognito • OpenAPI • MCP • Docker • ECR • CodeBuild • CloudWatch GenAI

## 📸 Implementation Evidence
### 1. First Working Strands Agent
![First Agent](screenshots/00-first-agent-calculator.png)

### 2. Secure Credentials with AgentCore Identity
![Secure Credentials](screenshots/01-secure-credentials-identity.png)

### 3. Cognito JWT Token Generation
![Cognito JWT](screenshots/03-cognito-jwt-token.png)

### 4. AgentCore Gateway with OpenAPI MCP
![Gateway & MCP](screenshots/04-openapi-mcp-gateway.png)

### 5. Gateway Testing with Strands Agent
![Gateway Testing](screenshots/05-gateway-testing-with-strands.png)

### 6. CloudWatch Observability Dashboard
![Observability](screenshots/08-cloudwatch-genai-dashboard.png)

## 📚 Use Case
This project demonstrates applied expertise in securing and deploying Agentic AI systems within cloud-native environments. It highlights capabilities in secure architecture design, identity and access management, API protection, and observability—key areas for protecting modern hybrid infrastructures and AI-driven applications.

## 📄 License
Educational and portfolio use only.
