# Artenvie-Project

1. git init                         // to initialize the repository
2. git status                       // to check the status of files in the repository
3. git add .                        // to add all the files (changed/unchanged) to the git
4. git commit -m "Init commit"      // to commit all the changes in the files to the git


5. ls -a -l ~/.ssh                                                  // checking the rsa keypairs
6. ssh-keygen -t rsa -b 4096 -c "omerashraf7222@gmail.com"         // generating the rsa key pair if not available  
7. eval "$(ssh-agent -s)"                                          // In order to view agent pid
8. ssh-add ~/.ssh/id_rsa                                           // Add the identity of the rsa key pair


9. git remote add origin https://github.com/umarashraf71/Artenvie-Project.git      // Add a new remote
10. git branch -m master                                                           // branch 
11. git push origin master --force                                                 // force push the changes to the github
            OR
12. git push -u origin master                                                   // push the changes normally             


13. cat ~/.ssh/id_rsa.pub                                // In order to get ssh key for putting in your github as ssh key
14. ssh -T git@github.com                                // For authenticating the ssh key on github


15. heroku keys:add                                       //In order to add the ssh public ket to the heroku
16. heroku create artenvie                                // create name of your application on heroku
17. git push heroku master                                // Push the files to the heroku development