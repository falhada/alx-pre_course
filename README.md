root@42d2b478f3e8:/alx-pre_course# git add.                                                                                             
git: 'add.' is not a git command. See 'git --help'.                                                                                     
                                                                                                                                        
The most similar command is                                                                                                             
        add                                                                                                                             
root@42d2b478f3e8:/alx-pre_course# git add .                                                                                            
root@42d2b478f3e8:/alx-pre_course# git status                                                                                           
On branch master                                                                                                                        
                                                                                                                                        
No commits yet                                                                                                                          
                                                                                                                                        
Changes to be committed:                                                                                                                
  (use "git rm --cached <file>..." to unstage)                                                                                          
        new file:   README.md                                                                                                           
                                                                                                                                        
root@42d2b478f3e8:/alx-pre_course# git commit -m 'my first commit'                                                                      
[master (root-commit) 996b87e] my first commit                                                                                          
 1 file changed, 1 insertion(+)                                                                                                         
 create mode 100644 README.md                                                                                                           
root@42d2b478f3e8:/alx-pre_course# git status                                                                                           
On branch master                                                                                                                        
Your branch is based on 'origin/master', but the upstream is gone.                                                                      
  (use "git branch --unset-upstream" to fixup)                                                                                          
                                                                                                                                        
nothing to commit, working tree clean                                                                                                   
root@42d2b478f3e8:/alx-pre_course# git push                                                                                             
Password for 'https://ghp_hMv1kl0EWRAO2vsmRhwoaQCFYxtLn927j88u@github.com':                                                             
remote: Invalid username or password.                                                                                                   
fatal: Authentication failed for 'https://github.com/falhada/alx-pre_course.git/'                                                       
root@42d2b478f3e8:/alx-pre_course# git push                                                                                             
Password for 'https://ghp_hMv1kl0EWRAO2vsmRhwoaQCFYxtLn927j88u@github.com':                                                             
remote: Support for password authentication was removed on August 13, 2021.                                                             
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for
 information on currently recommended modes of authentication.                                                                          
fatal: Authentication failed for 'https://github.com/falhada/alx-pre_course.git/'                                                       
