## Udagram Infrastructure

![aws](https://github.com/canthuy/udacity-project-4/assets/67618651/4b9961d6-881b-44be-8ec5-0d41ce60f27d)

### AWS
#### RDS Postgres

The application server uses AWS RDS Postgres as database for storing and retrieving information.

Database Host: `udacityproject.cs7gv4jnughy.us-east-1.rds.amazonaws.com`
Database Port: `5432`
Database Name: `udacity_project`

#### Elastic Beanstalk
The application server is deployed on AWS Elastic Beanstalk service. The application is build, archived and uploaded
to and S3 bucket from where Elastic Beanstalk extracts and runs the application on an endpoint.

EB URL: `[http://udagram-env-2.eba-ajwnc32q.us-east-1.elasticbeanstalk.com/](http://udagram-api-env.eba-a2habsqp.us-east-1.elasticbeanstalk.com/)`

#### S3 Bucket
The frontend application is deployed using AWS S3 Bucket. The bundled assets are uploaded to an S3 bucket and that
bucket is made publicly readable.

Bucket URL: `http://udagram-thuyct.s3-website-us-east-1.amazonaws.com/`

End users can access the application from the Bucket URL.
