# EBS-SnapShooter

EBS-SnapShooter is a python script based on [boto2], that creates daily, weekly on monthly snapshots for all your aws ebs volumes.

### Requirements:

* [boto2] - Python package that provides interfaces to Amazon Web Services

To install requirements :
```
(env)$ pip install -r requirements.txt
```

And of course EBS-Snapshooter itself is open source on GitHub.

### How to run
* Edit ebs-snpshooter.py file with your aws api creadentials 

* And just run the script ebs-snpshooter.py

```
export AWS_ACCESS_KEY=<aws-access-key> -e AWS_SECRET_KEY=<aws-secret-key> & python ebs-snapshooter.py
```

You can also run it within docker container. Go to --> https://quay.io/repository/smile/ebs-snapshooter

## License

EBS-SnapShooter is BSD-licensed.