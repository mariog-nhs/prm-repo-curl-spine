# prm-repo-curl-spine

Basic setup to invoke SPINE via curl.

Ensure you have the certificates on your file system, the script will default to the folder `certs`. You can use whatever folder you prefer, it's recommended to use a folder at the root of this repo starting with `certs` so it will be ignored via .gitignore.

Invoke the script running `./curl-spine` and it will output the response to `response-yyyyMMddhhmmss`.
