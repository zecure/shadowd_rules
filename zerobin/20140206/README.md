ZeroBin is an interesting example, because it contains the arch enemy of the whitelist: unpredictable variable names.

    http://zerobin/?7e4ce26c01e95afa#27TexLfvgtBocoW8Y/rYqr9iNtlAbHjKQO4js8rE7XM=

This would be easy to match with a regular expression, but not with a simple wildcard system. This forces us to allow more GET parameters than we would like to.
This is not a problem though, because the unsecurest GET filter (gcd) in ZeroBin is hexadecimal with a length of 40 characters. In a nutshell, very secure.
