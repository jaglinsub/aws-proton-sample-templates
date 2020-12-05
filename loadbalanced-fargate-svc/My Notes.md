Folder: /Users/a005222/AP/Project/Tryouts/aws-proton-sample-templates/loadbalanced-fargate-svc
tar -zcvf svc-template.tar.gz service/
tar -tvf svc-template.tar.gz


jaglinsub/zuorapoc
servicetemplate/svc-template.tar.gz

Secrets:
  - Name: jasypt.encryptor.password
    ValueFrom: zuorajasyptpwd
