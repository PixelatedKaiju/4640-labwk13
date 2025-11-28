- When is the state file created? <br>
The state file is created as soon as you complete `terraform apply`

- When is the lock file present? <br>
The lock file is created during the `terraform apply process`

- Is the lock file always in the bucket after it is created? <br>
No, the lock file only shows up during the process of applying

![AWS showing state file](/state-file.jpg "State File")

![AWS showing lock file](/lock-file.jpg "Lock File")

![AWs showing both lock and state file](/2files.jpg "Both Files")


