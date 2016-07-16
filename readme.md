# Deployment Plans

This will be the plan set forth by the original developer (Kyle Wilson) as a list
of rules and/or order of operations in how to upload and change the live master
branch of the github and website.

1. Complete full testing of new feature on a new branch

2. Once new version is complete, merge the new branch with the master branch

... switch to the master branch. ..
... make sure you pull the master branch for the newest version. ..
... Resolve any conflicts if you have duplicated code with anyone. ..
... One you have resolved all conflicts, commit that version to the repo. ..
... Now merge the new branch into the master.  ..
... Then pull master branch again and resolve any conflicts. ..

3. Test on the staging server

... Resolve any conflicts on the staging server before submitting it to the the production.

4. Commit to the production master

... git push LiveServer master

5. Communicate with the class on slack that the newest version is live

6. Test again