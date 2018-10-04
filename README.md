# uDiffspec

Test case automation for CS 343

This is intended as an improvement on the work done by diffspec, to make it a bleeding
edge technology just like ucpp (lol).

Check out [here](https://github.com/ian952/diffspec/blob/master/diffspec) for the original diffspec

### Usage
```
./udiffspec -o <program> -O <sample> [options]
```

`-v` - Enable verbose mode

`-f` - Enable input file mode

`-i <test-file/dir>` - Test file/directory

`-a <args>` - Custom args

- If no testname is specified, all tests under specs/ will be ran.

---

Creds to [Ian Hu](https://github.com/ian952), [Denton Liu](https://github.com/Denton-L), 
and CS 247 TA for providing the code for diffspec

Feel free to contribute if you need more features!
