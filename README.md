# AWS S3 Bucket Listing Script

This script allows you to list AWS S3 buckets along with their respective sizes.

## Prerequisites

Before running the script, make sure you have the following prerequisites:

- [AWS CLI](https://aws.amazon.com/cli/) installed and configured on your system.
- Appropriate AWS credentials with sufficient permissions to list S3 buckets.

## Usage

1. Clone the repository or copy the script file to your local machine.

2. Make the script executable:

    ```shell
    chmod +x bucket.sh
    ```

3. Run the script:

    ```shell
    ./bucket.sh
    ```

4. The script will prompt you for the AWS profile to use. Enter the name of the AWS profile configured in the AWS CLI. If you have set a default profile, press Enter without entering any profile name.

5. The script will then retrieve a list of S3 buckets and display them along with their sizes.

## Example Output

```text
aws-stage
bucket1
Total Size: 1.5 GB
```

Note: The size displayed represents the total size of the objects within each bucket.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This script is licensed under the [GNU GENERAL PUBLIC LICENSE](LICENSE).
