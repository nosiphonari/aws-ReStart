# AWS S3 Static Website Hosting Project

## Overview
This project demonstrates how to host a static website using Amazon S3. The website is a simple HTML page with associated assets, fully hosted on S3, showcasing how to leverage AWS for static content delivery.

![architecture](Downloads/s3-architecture.png) 
## Features
- **Static Website Hosting**: Accessible via a public URL provided by S3.
- **Access Management**: Implemented AWS S3 Bucket Policies and ACLs to control public access.

## Setup and Deployment

### Step 1: Create an S3 Bucket
1. Log in to the [AWS Management Console](https://aws.amazon.com/).
2. Navigate to the `S3 service`.
3. Create a new bucket:
   * Give it a unique name (e.g., my-awesome-website-bucket).
   * Choose a region closest to your target audience (e.g., Oregon `us-west-2`).
4. Enable ACLs:
   * During bucket creation, under "Object Ownership," select ACLs enabled.
   * This allows fine-grained control over the permissions of individual objects in the bucket.

![Creating an S3 bucket](Downloads/S3DLBUCKET.jpg)
