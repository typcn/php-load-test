# php-load-test
CVE 2015-4024 , bug #69364 , multi process php load test

WARNING: USE THIS TOOL AT YOUR OWN RISK
注意：此工具造成的任何后果由使用者自行承担

Usage: python xxx.py -t "http://TARGET_URL" -x "THREAD" -r "REQUEST_LENGTH"

Example: python xxx.py -t "http://your.site.using.php/" -x "100" -r "350000"

Will crash a php cluster
