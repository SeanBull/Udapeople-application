# Deployment Pipeline of simple application
## pipeline steps include 

      - build frontend application
      - build backend application
      - test frontend application 
      - test backend application
      - scan frontend packages for vulnerabilities 
      - scan-backend packages for vulnerabilities 
      - send notification to slacked
      - deploy infrastructure via Cloudformation 
      - configure infrastructure via ansible
      - run migrations for database
      - deploy frontend on configured infrastructure
      - deploy backend on configured infrastructure
      - run smoke tests on front and back end
      - complete rolling update on cloudfront (delete old deployment and update cloudfront)

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)
