Folder: /Users/a005222/AP/Project/Tryouts/aws-proton-sample-templates/loadbalanced-fargate-svc
tar -zcvf svc-template.tar.gz service/
tar -tvf svc-template.tar.gz

IMPORTANT*******************************************
ADD CORRECT ROLES FOR: AWSProton-my-env-20-cloudform-ECSTaskExecutionRole-2YUQ2PIUZEEM
FOR NOW I HAVE ADDED ADMINISTRATOR ACCESS

jaglinsub/zuorapoc
jaglinsub/zuoraproduct
servicetemplate/svc-template.tar.gz

Secrets:
  - Name: jasypt.encryptor.password
    ValueFrom: zuorajasyptpwd
