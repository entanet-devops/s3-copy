s3 copy
=========

Simple role to copy a list of objects from an AWS s3 bucket to a local directory

Requirements
------------

This module has a dependency on boto3 and botocore.

Role Variables
--------------

Local directory to copy files to:
s3_local_dir: /tmp

Name of source s3 bucket
s3_bucket: s3-bucket

List of object to fetch from the bucket
s3_objects:
  - my_object
  - my/other/object.txt

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - entanet_devops.s3-copy

License
-------

BSD