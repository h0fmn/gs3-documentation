# `network timeout <timeout>`

### Description
Configures the SSH timeout duration. The timeout must set to at least `60` seconds, with a range from `60` to `86,400` seconds. The default value is `3,600` seconds.

### Example 
```
[admin@ssh-to-serial]>network timeout 60
Reverse SSH Timeout is set to 60 seconds.
```