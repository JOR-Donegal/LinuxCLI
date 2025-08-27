# Wildcards

When searching for files (or copying or removing) it can be very handy to use wildcards.

The (\*) symbol (pronounced splat) is probably the most common.&#x20;

For example&#x20;

```
ls *.txt
```

would return all text files&#x20;

Because of extensions, wildcards behave a bit differently between DOS and Unix.&#x20;

The command&#x20;

```
ls *.txt
```

shows all files ending in **.txt** and is case sensitive

The command&#x20;

```
ls R*.txt
```

&#x20;shows all files beginning with capital R and with an extension .txt

If you use the symbol **\*** on its own, it means all files in the working directory.

The character **?** will match exactly one character. So “?ouse” will match files like house and mouse, but not grouse. Try typing

```
ls ?list
```

## Exercise

Delete all files in the **CLI/Backup** directory, then copy all files from **CLI** directory to **CLI/Backup** directory.
