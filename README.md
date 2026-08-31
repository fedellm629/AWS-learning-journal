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

```
```

**Biggest lesson**: If IAM is weak, your whole AWS account is at risk

---
#100DaysOfCloud #AWS #PhoneOnly #LearningInPublic


> **Biggest lesson**: If IAM is weak, your whole AWS account is at risk
---
#100DaysOfCloud #AWS #PhoneOnly #LearningInPublic

## Day 3: August 31, 2026
## Topic: AWS S3 Basics

"If IAM is weak, your whole AWS account is at risk"

In today's #100DaysOfCloud, I learned:
- How to create S3 buckets with Boto3
- Upload files to S3 
- Apply bucket policies with JSON
- Difference between IAM Policy and Bucket Policy

## How to Run
1. `pip install boto3`
2. `aws configure`
3. `python day3_s3.py`

## Key Takeaway
S3 is object storage. Buckets hold objects. Permissions matter.
Master IAM and S3 policies early.

---
Day 3 ✅ | 97 Days to go