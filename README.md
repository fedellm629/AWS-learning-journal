# AWS-learning-journal
# My AWS + DevOps Journey. Phone only: learning → AWS Cloud Practitioner → Remote Internship. Goal: Master AWS + Docker + Terraform. Started: Aug 2026



## Day 1: Aug 29, 2026
**What I learnt today:** Created GitHub repo. Starting AWS Cloud Practitioner journey using only phone.
**Goal this week:** Understand IAM and S3
**Mood:** Determined 💪

## Day 2: August 30, 2026
### Topic: IAM - Identity and Access Management

#### What I learnt today:
IAM is the "Security Man + HR" of AWS. 
it can decide WHO can do WHAT inside my AWS account.

#### The 4 Key Parts:
1. **USER** = Person with username + password. Example: fedellm629

2. **GROUP** = Team of users. Example: Developers-Group

3. **ROLE** = Temporary ID card for AWS services. Example: Let EC2 access S3

4. **POLICY** = The actual rule written in JSON. Example: Allow read-only access

#### Golden Rule:
**Least Privilege** = Give people ONLY the access they need. Nothing more.

#### What is JSON?
JSON = JavaScript Object Notation. 
is a organized format to store data. AWS use it to write IAM Policies.
Example:
```json
{
  "Effect": "Allow",
  "Action": "s3:GetObject",
  "Resource": "my-bucket/*"
}
*Biggest lesson* If IAM is weak, your whole AWS account is at risk.