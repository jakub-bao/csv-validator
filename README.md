[*] Create pipeline: cd csv-validator && sam pipeline init --bootstrap
[*] Validate SAM template: cd csv-validator && sam validate
[*] Test Function in the Cloud: cd csv-validator && sam sync --stack-name {stack-name} --watch