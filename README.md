# splitty

Splitty is a minimal speedrun timer for linux.

Before first launch, run `splitty init` to set up config directories.

To launch the timer without any splits, just use `splitty start`

To use splits, first create a new profile with `splitty make [name]`, and then you can edit the `splits` file, which is in a simple json format, to add splits. Then, you can use the splits with `splitty start [name]`

# Dependancies

Splitty depends on the following pip libraries:

```
pynput
rich
toml
```

Once these are installed, you should be able to run the program.
