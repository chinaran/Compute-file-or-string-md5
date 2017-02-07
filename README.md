Compute-file-or-string-md5 - C
================================

Compute md5 value of file or string.

Try the following:

$ gcc main_md5.c md5.c -Wall -o md5_test

$ ./md5_test

// you may get following:

	[file - md5.c] md5 value:
	
	2a2caf52cb298f177a57a3211213e141
	
	[string - gchinaran@gmail.com] md5 value:
	
	84701974fb98315895e3ed9053a0b389

// and you can check by md5sum

$ md5sum md5.c

2a2caf52cb298f177a57a3211213e141  md5.c

// Last: 16-digit md5 is the middle of 32-digit md5

