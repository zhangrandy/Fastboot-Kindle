## added below line to avoid error buidling on macOS Sequoia

```c
/* ...undeclared function 'fb_queue_check',ISO C99 and later do not support 
implicit function declarations -Wimplicit-function-declaration... */
void fb_queue_check(const char *ptn);
```

This is a version of Android's "fastboot" for the Kindle 4, Kindle Touch and Kindle PaperWhite. It will NOT work with Android phones.

To build the project on OS X, simply run

    make
