# js-trojan-cleanup
This handy script was written to find and remove malicious javascript codes injected into js files. The infection starts and ends with a comment, the comment text is a random generated 32 lower case character. The script searches recursively in *.js files for this pattern, and removes any character surrounded with these 2 comment block. It takes no difference whether the code is minimised or not.

**Usage:**
- detect [directory] : detect malicious code in the given directory
- cleanup [directory] : remove malicious code in the given directory
- help : this help :)"


