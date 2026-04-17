# db-gitops-apps

Important! ArgoCD Applications have auto-sync option enabled!

development flow: 
 -> create feature branch 
   -> make pull requests 
     -> run release candidate pipeline 
       -> deploy to 1/sub-set of pre-prod clusters 
         -> deploy to all pre-prod clusters 
           -> run production release pipeline
             -> deploy to 1/sub-set of prod clusters
               -> deploy to all prod clusters 