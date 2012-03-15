plus7
=====

plus7 is a command line interface to the arte plus7 media library.
It is implemented in Python and uses the same API calls as the iPad
client.


Usage
-----

- List available content:
  ```./plus7```
  The listing is cached in '.plus7.json' in your home directory.

- Details on content items:
  ```./plus7 info <id>```

- Download items:
  ```./plus7 download <id>```
  Resuming on is supported on the file block level: Files are downloaded
  in blocks of about 1M.
