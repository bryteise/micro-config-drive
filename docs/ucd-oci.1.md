ucd-oci(1) -- Fetch ssh public key from OCI service
========================================================

## SYNOPSIS

`/usr/bin/ucd-oci`

## DESCRIPTION

`ucd-oci` a helper program that fetches the SSH pubkey provided to the
cloud instance. After fetching the data, ucd-aws creates a
`#cloud-config` text block and passes the output to `ucd`(1) for
processing/execution.

## OPTIONS

`ucd-oci` has no configurable options.

## EXIT STATUS

On success, 0 is returned, a non-zero failure code otherwise. The exit
code returned may be the exit code of the subsequent `ucd` program
execution.

## COPYRIGHT

 * Copyright (C) 2017 Intel Corporation, License: CC-BY-SA-3.0

## SEE ALSO

`ucd`(1)

## NOTES

Creative Commons Attribution-ShareAlike 3.0 Unported

 * http://creativecommons.org/licenses/by-sa/3.0/
