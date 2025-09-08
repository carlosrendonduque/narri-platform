# AWS DevOps Professional Certification Learning Notes

## Project: Narri.co - Story-Driven AI Website Builder

### GitHub Actions → AWS Service Mappings

| GitHub Actions Component | AWS Equivalent | Purpose | Certification Topic |
|--------------------------|----------------|---------|-------------------|
| `on: push` | CodePipeline Source Stage | Trigger automation | Pipeline Orchestration |
| `runs-on: ubuntu-latest` | CodeBuild Environment | Compute for builds | Build Environments |
| `actions/checkout` | CodeCommit Source Action | Code retrieval | Source Control |
| `npm ci && npm run build` | CodeBuild Build Phase | Application compilation | Build Automation |
| `npm test` | CodeBuild Test Reports | Automated testing | Quality Gates |
| `upload-artifact` | S3 Artifact Store | Build output storage | Artifact Management |

### Future AWS Implementation Plan

#### Phase 1: Basic Deployment
- [ ] **S3 + CloudFront**: Static website hosting
- [ ] **Route 53**: DNS management  
- [ ] **Certificate Manager**: SSL/TLS certificates

#### Phase 2: Advanced CI/CD
- [ ] **CodePipeline**: Replace GitHub Actions
- [ ] **CodeBuild**: Build automation
- [ ] **CodeDeploy**: Deployment automation
- [ ] **CloudFormation**: Infrastructure as Code

#### Phase 3: Production Features
- [ ] **CloudWatch**: Monitoring and logging
- [ ] **AWS Config**: Compliance monitoring
- [ ] **Systems Manager**: Configuration management
- [ ] **Secrets Manager**: Secure credential storage

### Key Learning Objectives
- [x] Set up basic CI/CD pipeline
- [ ] Deploy static site to S3
- [ ] Configure CloudFront distribution
- [ ] Implement Infrastructure as Code
- [ ] Set up monitoring and alerting
- [ ] Practice blue/green deployments

### Certification Exam Topics Covered
- Domain 1: SDLC Automation 
- Domain 2: Configuration Management 
- Domain 3: Monitoring and Logging
- Domain 4: Policies and Standards Compliance
- Domain 5: Incident and Event Response
- Domain 6: High Availability and Elasticity