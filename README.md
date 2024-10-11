# PC Gadget

This repository is a playground for testing a variety of gadget snaps I use
day-to-day for both personal use and testing.

Gadget snaps are generally verboten from the Global Store, which means these
will not be published anywhere very visible.

These are primarily intended for my own personal use, so YMMV.

You can find more of my other work relating to gadget snaps [here](https://github.com/canonical/iot-field-gadget-snap)


## Repository structure

Each branch contains precisely one gadget. There won't be full coverage of
every release or permutation, but rather only what I need when it's made. Thus,
maintenance is not guaranteed; things will almost certainly fall through the
cracks.

This branch mainly exists just to host workflows in a singular location.


## Contributing

Feel free to open an issue if you experience a problem or have a question.

PRs are generally welcome.

Commits should follow the below style:

* The entire message should read as:
```
    <path/to/file>: <imperative present tense short description of change>
    <longer explanation of change if required>
    Signed-off-by: <author name> <author email>
```

* Keep first line summaries to under 60 characters, body summaries under 80

* Include a signoff for each commit using `git commit -s`
    * To amend prior commits with a signoff, do `git rebase --signoff HEAD~<number of commits>`

* Signing commits with `git commit -S` (GPG or SSH) is preferred but not required

* If you are modifying the `README.md`, `LICENSE`, `.gitignore`, `.github`,
    etc., please use `README`, `LICENSE`, `github`, `gitignore`, etc as the filename in the message

* Commits should be atomic

* PRs should contain logically related commits

* Try to follow prior art and style wherever possible
