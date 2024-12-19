# ddev-1password
Allow 1password SSH Agent to be used inside a DDEV container.

```
ddev add-on get sweetroll/ddev-1password
```

After adding your SSH keys to 1password and exporting the `SSH_AUTH_SOCK` environment variable as per [the 1password docs](https://developer.1password.com/docs/ssh/get-started/), this add-on will allow access to the SSH keys inside the DDEV container.
