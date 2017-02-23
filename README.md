# systemd-timed-reboot
Simple systemd example to reboot after 24 hours

You Probably Don't Want To Do This
==================================

Under most circumstances this would be bad practice.

This was used in an embedded system where one of the components had a memory leak, 
and there is no way for the user to login + no keyboard.
