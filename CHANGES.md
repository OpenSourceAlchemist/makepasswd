1.10.9-- A distilled list of changes since the last lilo release (done by the Debian maintainers):
 * Generate MD5 passwords with the --crypt-md5 option
 * UTF-8 clean
 * --crypt-md5 can now be used with --repeatpass.
 * Increase default password length range from 6-8 characters to 8-10
 * Use OpenSSL's random number generator, seeded with 256 bits of entropy from /dev/urandom (CVE-2010-2247)
 * Send --help output to stdout, not stderr.

1.10--  Added the --clearfrom option, so you can input a clear text
        password from a file.

1.07--  Inserted the omitted parsing for the --string option.  Cleaned up a
        bit of documentation.  Thanks to netgod of debian.org for hounding
        me until I fixed this. :)

1.06--  Initial release.
