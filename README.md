# AWS S3 Versioning & Web Hosting Lab

A hands-on AWS cloud storage project demonstrating Amazon S3 bucket configuration, object versioning, server-side encryption, and HTML object management.

## Project Overview

This project explores how Amazon S3 stores and manages objects with versioning enabled. An HTML file was uploaded, updated, and uploaded again to verify that S3 retains previous object versions.

## Objectives

- Create and configure an Amazon S3 bucket.
- Enable S3 Bucket Versioning.
- Verify server-side encryption.
- Upload and update an HTML object.
- Inspect and verify object version history.
- Document the implementation with screenshots.

## Technologies & Services

| Technology | Purpose |
|---|---|
| Amazon S3 | Cloud object storage |
| S3 Versioning | Retain multiple object versions |
| Server-Side Encryption | Protect stored objects |
| HTML | Sample webpage file |
| GitHub | Project documentation and evidence |

## Implementation

1. Created an S3 general-purpose bucket.
2. Enabled S3 Bucket Versioning.
3. Kept Block Public Access enabled.
4. Verified server-side encryption configuration.
5. Uploaded an HTML file.
6. Updated the HTML content and uploaded it again.
7. Used the object version history to verify two stored versions.

## Results

- S3 bucket was created successfully.
- Versioning and server-side encryption were enabled.
- The HTML object was uploaded and updated.
- Two object versions were visible in the S3 version history.
- The previous version remained available.

## Project Evidence

Screenshots included in this repository:

- `01-S3-Bucket-Created.png`
- `02-Versioning-Enabled.png`
- `03-Encryption-Enabled.png`
- `04-Files-Uploaded.png`
- `06-Object-Versions.png`
- `07-Two-Object-Versions.png`

## Security Considerations

- Block Public Access remained enabled.
- No AWS access keys or secret credentials are included.
- Public static website hosting was not enabled in this lab.

## Key Learning Outcomes

- Understanding Amazon S3 bucket configuration.
- Understanding object versioning and version history.
- Learning the role of server-side encryption.
- Practicing cloud storage documentation and evidence collection.

## Disclaimer

This project was performed in a personal AWS account for educational and learning purposes.
