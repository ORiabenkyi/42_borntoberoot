# 42_borntoberoot
This is my project.
I will describe for myself which files I have to check. Maybe in the future I will increase the number of commands.

ssh username@127.0.0.1 -p 4242 (to connect)

  if some problem ~/.ssh/knows_hosts
  
lsblk (to see partition)

ufw status numbered (to see opened port)

  Password Policy
/etc/pam.d/common-password

  retry
  minlen
  ucredit    lower-case letters in the password
  lcredit    upper-case letter in the password
  dcredit    digital in the password
  ocredit    other characters in the password
  maxrepeat
  reject_username
  difok      define number of characters that must be different from the previous password
  enforce_for_root

/etc/login.defs

  PASS_MAX_DAYS
  PASS_MIN_DAYS
  PASS_WARN_AGE

group

