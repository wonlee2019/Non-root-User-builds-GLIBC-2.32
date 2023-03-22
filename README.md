# Non-root-User-builds-GLIBC-2.32
"bison --yacc --name-prefix=__gettext --output plural.c plural.y" loads to "bison: m4 subprocess failed: permission denied."

This problem occurs in "/glibc-2.32/intl".

still fail in trying root permission, same result.
still fail in trying "set m4=/path/to/bin && bison=/path/to/bin", same result in vain. 
