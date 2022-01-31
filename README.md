# merge_feature_branch
Merge source branch into feature branch and push. Create PR if conflicts

inputs: 

&nbsp;&nbsp;**token**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: 'the GitHub PAT used to create PRs and perform commits'  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
&nbsp;&nbsp;**emailAddress**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: 'the email address used to login to GitHub and send email notifications'  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
&nbsp;&nbsp;**emailPassword**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: 'the password used to login to your mail server'  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
&nbsp;&nbsp;**featureBranch**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: 'featureBranch: The name of the branch to update'  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
&nbsp;&nbsp;**gitHubUsername**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: 'the username to display on the PR and commits'  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
&nbsp;&nbsp;&nbsp;&nbsp;default: 'Auto Merge Triage'  
&nbsp;&nbsp;**sourceBranch**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: 'sourceBranch: The name of the branch ahead of featureBranch'  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
&nbsp;&nbsp;&nbsp;&nbsp;default: 'develop'  
&nbsp;&nbsp;**toEmailAddress**:  
&nbsp;&nbsp;&nbsp;&nbsp;description: 'the email address to send notifications to'  
&nbsp;&nbsp;&nbsp;&nbsp;type: string  
&nbsp;&nbsp;&nbsp;&nbsp;required: true  
