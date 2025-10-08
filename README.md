Secrets Reader for AWS Secrets Manager

A Python utility to securely list and retrieve secrets from AWS Secrets Manager.
Features:

Loads AWS credentials from a local file (creds.txt).

Supports direct access and AWS role assumption via STS for secure operations.

Lists all secrets in the specified AWS region.

Retrieves and displays individual secret values—supports both string and binary secrets.

Handles and displays detailed AWS error messages and permission issues for troubleshooting.

Usage:

Place your AWS credentials in a creds.txt file with required keys.

Run the script to list all secrets and fetch details by name or index.

Script prints detailed errors if permissions or decryption fail.

Ideal for cloud security, automation, and DevOps use cases.
