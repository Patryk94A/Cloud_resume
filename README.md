# My own azure resume, following ACG.

## First steps

- Adjusted frontend, HTML contains my CV and details
- main.js contains visitor counter code.
- Strugled with properly git push some data into github. Need to be carefull what folder i am pushing. Fortunately i could 
git revert <commit_hash>

- Strugled with deploying function app to azure: First i found out i needed to create a Storage Account. Later found after some reaserch that I was missed a lot of things not being attached to my subscription.
such as
--namespace Microsoft.Web, Microsoft.Storage, Microsoft.Insights, Microsoft.Network, Microsoft.ManagedIdentity

-After VSCode showed me a lot of (around 19 errors like """The type or namespace name 'Newtonsoft' could not be found (are you missing a using directive or an assembly referenc""" - and i wanted to fix them all i started to fix it one by one, installing all "dotnet add package Newtonsoft.Json" and other staff. And found out after that, i made it even worse and i actually could just ignored them as it was working and all the errors come probably from the Ubuntu I am working on.
So i didn't know how to fix them, they i though i have pushed a good version into github. So what i did was:
```git fetch origin 
git reset --hard origin/main```


and everything works back perfectly fine  


______________________________________________
(Just for me [I can put a link in here.]())


