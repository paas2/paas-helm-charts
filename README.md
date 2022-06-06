Add submodule
  git submodule add https://github.com/paas2/argo-apps-base charts/argo-apps-base --name charts/argo-apps-base
To update the submodules  
  git submodule -q foreach git pull -q origin main   