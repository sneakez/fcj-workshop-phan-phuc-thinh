---
title: "Sharing and Feedback"
date: 2026-11-25
weight: 7
chapter: false
pre: " <b> 7. </b> "
---

This section summarizes my personal experience and suggestions after participating in **First Cloud AI Journey** at the AWS office.

### Learning experience

The program's greatest value was an environment that encouraged participants to research independently and take responsibility for results. I had to go beyond following instructions: read documentation, inspect actual state, explain why a configuration worked or failed, and complete my own project.

NexusOMS made the relationship between code and infrastructure concrete. A small change to a Docker image, IAM policy, connection string, or CloudFront behavior could affect the entire workflow. Deploying, observing, troubleshooting, rolling back, and cleaning up made ECS Fargate, ECR, S3, CloudFront, SQS, CloudWatch, CloudTrail, Secrets Manager, and GitHub OIDC much more tangible than theory alone.

### Support and community

Administrators and community members provided useful perspectives when I faced difficult problems. The most effective support was a diagnostic direction or a critical question that allowed me to identify the cause and record the lesson myself. The two events I attended expanded my understanding of product thinking, Cloud and AI trends, data readiness, and the operational requirements of real systems.

### What I valued most

- The freedom to choose NexusOMS and refine it through several cycles from business logic to infrastructure.
- Experience with a realistic workflow: testing, containers, CI/CD, deployment, observation, troubleshooting, and cleanup.
- Evidence that distinguishes what was implemented, what remains a target design, and what still requires study.
- The opportunity to turn personal experience into a bilingual workshop, a learning pack, and reusable articles.

### Challenges identified

- Some labs, repositories, and screenshots no longer matched current service interfaces or behavior.
- Many deployment failures occurred at service boundaries and were difficult to diagnose without explicit checkpoints.
- Cloud cost, secrets, IAM permissions, and cleanup order can be overlooked when learners focus only on making the system run.
- Review milestones were not always fixed, which sometimes pushed preparation and revision toward the end of the program.

### Suggestions for improvement

- Version each lab with its verification date, repository/tag/commit, and tested Region.
- Add observable checkpoints to each stage: validation command, expected state, relevant logs, and rollback path.
- Introduce mandatory secret-handling, budget/cost-alert, and cleanup checklists at the beginning of the program.
- Schedule short recurring reviews where participants present progress, limitations, and risks before the final submission.
- Encourage participants to restate lessons in their own words and disclose what has not yet been verified.

### Next steps

I will continue strengthening .NET, PostgreSQL, automated testing, and AWS Security; rebuild a smaller NexusOMS version with explicit production criteria; and keep writing and participating in the community as a way to test and deepen my own understanding.

### Conclusion

First Cloud AI Journey moved me from a “finish the lab” mindset to a “prove that the system works within a stated scope” mindset. Initiative, evidence-based investigation, and clear disclosure of limitations are the values I intend to carry forward.
