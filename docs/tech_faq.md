# Technical FAQs

### Why won't X install on Mac Catalina?

Some students reported warnings about "malicious" software when trying to install VSCode or Atom code editors on Mac Catalina.

This [StackOverflow post](https://stackoverflow.com/questions/58457958/visual-studio-code-cant-be-opened-because-apple-cannot-check-it-for-malicious) has a temporary work-around. Probably worth trying the simpler solution first (`System Preferences > Security & Privacy`).

### Why are basic shell commands missing on Mac Catalina?

Mac users who have upgraded to Catalina reported that they don't have basic shell utilities such as `ls`, `cp`, etc. in the Terminal.

Running `xcode-select --install` appears to fix the problem.

> Note: This is one of the steps you need to run in our [technical setup](tech_setup.md), so please make sure to only run it once.

### Which Ubuntu should I use? 

Typically, you'll want the latest "LTS" release from the [Ubuntu download page](https://ubuntu.com/download/desktop).