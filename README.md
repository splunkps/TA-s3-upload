# TA-s3-upload

v2.1.0

Added new functionality to have more than one account and account can be chosen in in alert action settings.

index=_internal | stats c by sourcetype | sendalert s3_upload param.bucket_name="<<bucket>>" param.file_name="fun" param.file_format="json" param.account_name="<<account_name>>"

For how to configure:

https://www.youtube.com/watch?v=qYI__Pxa3bI
