# AWS-Youtube-Analytics-Pipeline
AWS Project

## Project Overview
This repository contains the resources and documentation for setting up an end-to-end data processing and analytics pipeline on AWS. The pipeline integrates various AWS services to ingest, process, catalog, and visualize data. 

### Architecture
The project utilizes a series of AWS services to handle data through its lifecycle:

1. **Data Lake Storage**: Utilizing Amazon S3 buckets for landing, cleansing, and analyzing data.
2. **Data Preprocessing**: Employing AWS Glue for ETL processes and AWS Lambda for serverless data transformations.
3. **Data Cataloging**: Using AWS Data Catalog to maintain metadata and facilitate data discovery.
4. **Analysis and Visualization**: Analyzing data with Amazon Athena and visualizing insights through Amazon QuickSight.
5. **Monitoring and Management**: Implementing AWS Identity and Access Management (IAM) for secure access control and AWS CloudWatch for monitoring the pipeline.

## Repository Contents

- `presentation/` - A folder containing the project presentation slides.
- `demo/` - A folder with the demo video showcasing the pipeline in action.
- `src/` - Source code files for any custom scripts or Lambda functions used in the pipeline.


## Getting Started

To get started with deploying this analytics pipeline:

1. **Setup AWS Services**: Follow the instructions in the `/presentation` to configure the necessary AWS services.
2. **Data Ingestion**: Place your raw data in the S3 landing bucket to kick off the pipeline.
3. **Monitor the Pipeline**: Use CloudWatch to monitor the ETL jobs and Lambda functions.
4. **Data Exploration**: Use Athena to run queries against your processed data.
5. **Visualization**: Connect QuickSight to Athena to create dashboards and gain insights from your data.

## Demo

Watch the `demo/.mp4` to see a walkthrough of the data analytics pipeline in action.

## Contributors

This project exists thanks to all the people who contribute. 

- Swathi
- Bharath
- Monica

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repository and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Contact

For any further questions or feedback, please open an issue in the repository or contact the maintainers directly.

---
**Note**: This repository does not include AWS service charges related to the operation of the pipeline.
