# fail

shell command that will always fail (return exit code 1)

## Example

```sh
$ fail
```

will immediatly terminate with exit code 1

## Best in class command for failing

The program closely follows the Unix philosophie of "doing one thing, and doing one thing well".
This program fails. Reliably.

While a lot of my programs fail regular, this fails the best. Fails 10 out of 10 times.

## Comparision

this command is unambiguos to `sh -c "exit 1"`

## TODO
benchmark efficient failing
