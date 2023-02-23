# ExMoveApp

Repo for users to laucnh ExMove App locally through a GitHub repository.
This is just a test page for now as the main project repo is still private

To launch the app run the following code:

```{r}
library(shiny)
runGitHub("ExMoveApp", username = "LukeOzsanlav",
          ref = "master", subdir = "app")
```
