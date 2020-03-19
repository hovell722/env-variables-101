# Environment Variables in bash

This class is on Environment variables.

### What is variable

Variables are like boxes, you can extract and put things inside and give it a name.

For us an Environment is, system where code runs for different purposes.

Usually, at least there 3 environments exist:
- development
- testing
- production

**Environment Variables** are variables that exist on said environments and are interpolated from the environments AND NOT from the code.

**Environment variables exist in the machine NOT the code.**

This is great for things:
- things that you don't want to have in your code
- like **access keys**
- like AWS_SECRET keys
- similar to SSH keys, THEY NEVER GO IN THE CODE! or even close

Allows us to keep them secret and they don't end up on github where some wanna be hacker is going to find them and mine bitcoin.
