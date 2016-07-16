# Deployment Plans

This will be the plan set forth by the original developer (Kyle Wilson) as a list
of rules and/or order of operations in how to upload and change the live master
branch of the github and website. Because I am the only developer working on this
project I will use the staging server to do the testing and developing rather than use branches. If
this was a project with several developers, I would use branches off of the live server to make sure
the production server is only affected in the correct way.

1. Complete full testing of new feature on StagingServer

2. Once new version is complete, merge the newest version on StagingServer with the master branch of LiveServer

... switch to the master branch. 
... make sure you pull the master branch for the newest version.
... Resolve any conflicts if you have duplicated code with anyone.
... Once you have resolved all conflicts, commit that version to the repo.
... Then pull master branch again and resolve any conflicts.

3. Test on the staging server once more

... Resolve any conflicts on the staging server before submitting it to the the production.

4. Merge updated files to the LiveServer

5. Commit to the production master

... git push LiveServer master

6. Communicate with the class on slack that the newest version is live

7. Test again