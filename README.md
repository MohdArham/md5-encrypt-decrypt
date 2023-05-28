# md5-encrypt-decrypt
================================

Compute md5 value of file or string.

Try the following:

$ gcc main_md5.c md5.c -Wall -o md5_test

$ ./md5_test

// you may get following:

	[file - md5.c] md5 value :
	
	2a2caf52cb298f177a57a3211213e141
	
	[string - mohdarham94@gmail.com] md5 value:
	
	86dfa9320dc847761e5d429164b3b272  

// and you can check by md5sum

$ md5sum md5.c

2a2caf52cb298f177a57a3211213e141  md5.c

// Last: 16-digit md5 is the middle of 32-digit md5
