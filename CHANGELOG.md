v1.0.0
======

* Added support of using custom S3 endpoint URL #4 [@oyarushe]
* Add support for MinIO #3 [@huiser]
* Made column_list as optional parameter #6 [@oyarushe]
* Fix for current postgres 12.* and s3 #11 [@phileon]
* Added support for aws_s3.query_export_to_s3 #12 [@darthbear]
* Fix uploaded records to ignore header #23(https://github.com/chimpler/postgres-aws-s3/pull/23) [@tzachshabtay]
* Minor Readme fixes + enhancements #21(https://github.com/chimpler/postgres-aws-s3/pull/21) [@GRBurst]
* import support multi-file and directorys #1(https://github.com/radondb/postgres-aws-s3/pull/1) [@yanboer] [@lianzhuangzhang]
* export not override file, if file exists will add _part{n} suffix #1(https://github.com/radondb/postgres-aws-s3/pull/1) [@yanboer] [@lianzhuangzhang]
* import and export add read_timeout param #1(https://github.com/radondb/postgres-aws-s3/pull/1) [@yanboer] [@lianzhuangzhang]
* export_s3 add override param #1(https://github.com/radondb/postgres-aws-s3/pull/1) [@yanboer] [@lianzhuangzhang]
* export/import add tempfile_dir param #1(https://github.com/radondb/postgres-aws-s3/pull/1) [@yanboer] [@lianzhuangzhang]
