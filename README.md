# S3 Bucket Encryption with IAM Access Control

## 📌 Project Overview

This project demonstrates how to secure an Amazon S3 bucket using **AWS IAM**, **bucket policies**, and **server-side encryption**. The goal is to ensure that data stored in S3 is encrypted at rest and that access is strictly controlled based on user permissions.

The project simulates a real-world cloud security scenario where one IAM user manages the infrastructure, while another user has limited access due to enforced security policies.

---

## 🎯 Objectives

* Create and manage IAM users with different permission levels
* Configure an S3 bucket with default server-side encryption
* Enforce encryption using S3 bucket policies
* Restrict unauthorized access to S3 objects
* Validate access control using multiple IAM users

---

## 🛠️ AWS Services Used

* **Amazon S3** – Secure object storage
* **AWS IAM** – Identity and access management
* **S3 Bucket Policies** – Resource-based access control
* **Server-Side Encryption (SSE-S3)** – Data encryption at rest

---

## 🏗️ Architecture Summary

* **IAM User A (Admin):**

  * Creates and manages the S3 bucket
  * Configures encryption and bucket policies

* **IAM User B (Limited Access):**

  * Can view the bucket
  * Cannot access or upload objects due to policy restrictions

* **S3 Bucket:**

  * Default encryption enabled
  * Bucket policy enforces encryption and access control

---

## 🔐 Security Implementation

* Enabled **default server-side encryption (SSE-S3)** for the S3 bucket
* Applied a **bucket policy** to deny object uploads without encryption
* Blocked unauthorized access at the bucket and object level
* Tested access behavior using multiple IAM users

---

## ✅ Validation & Testing

* Verified that all uploaded objects are encrypted automatically
* Confirmed full access for the admin IAM user
* Observed access denied errors for the restricted IAM user
* Ensured encryption compliance through policy enforcement

---

## 📚 Key Learnings

* Practical use of IAM users and permission boundaries
* Difference between IAM policies and S3 bucket policies
* Importance of enforcing encryption at the bucket level
* Hands-on experience with AWS security best practices

---

## 🚀 Conclusion

This project highlights my ability to design and implement secure cloud storage solutions using AWS. It demonstrates real-world skills in **cloud security**, **IAM access control**, and **data protection**, which are essential for cloud support and cloud engineer roles.

---

## 🏷️ Keywords

AWS, Amazon S3, IAM, Cloud Security, Server-Side Encryption, Bucket Policy, Access Control

