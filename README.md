# Enterprise-Cloud-Migration-Sales-Pipeline-Manager
A comprehensive Salesforce Sales Cloud solution designed for AWS CloudOps specialty sales teams. This project demonstrates advanced B2B sales process management, partner ecosystem integration, and technical solution selling capabilities.
Repository Structure 
enterprise-cloud-migration-sales/
├── README.md
├── sfdx-project.json
├── .github/
│   └── workflows/
│       ├── deploy-to-dev.yml
│       └── deploy-to-staging.yml
├── force-app/
│   └── main/
│       └── default/
│           ├── applications/
│           │   └── CloudOps_Sales_Console.app-meta.xml
│           ├── classes/
│           │   ├── CloudReadinessAssessmentController.cls
│           │   ├── PartnerEngagementService.cls
│           │   ├── TechnicalSolutionCalculator.cls
│           │   └── CustomerFeedbackProcessor.cls
│           ├── flows/
│           │   ├── Cloud_Migration_Sales_Play.flow-meta.xml
│           │   ├── Partner_Notification_Process.flow-meta.xml
│           │   └── Post_Sale_Handoff.flow-meta.xml
│           ├── objects/
│           │   ├── Cloud_Readiness_Assessment__c/
│           │   ├── Partner_Relationship__c/
│           │   ├── Technical_Solution__c/
│           │   ├── Partner_Engagement__c/
│           │   └── Customer_Feedback__c/
│           ├── tabs/
│           ├── permissionsets/
│           ├── profiles/
│           ├── reports/
│           ├── dashboards/
│           ├── email/
│           │   └── templates/
│           ├── workflows/
│           └── triggers/
├── data/
│   ├── sample-accounts.json
│   ├── sample-partners.json
│   └── sample-opportunities.json
├── scripts/
│   ├── deploy.sh
│   ├── create-scratch-org.sh
│   └── data-import.sh
├── docs/
│   ├── DEPLOYMENT_GUIDE.md
│   ├── USER_GUIDE.md
│   ├── TECHNICAL_SPECS.md
│   └── DEMO_SCENARIOS.md
├── config/
│   ├── project-scratch-def.json
│   └── user-scratch-def.json
└── tests/
    ├── apex/
    └── data/
