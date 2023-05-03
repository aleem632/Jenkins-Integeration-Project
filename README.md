### Jenkins-Integeration-Project


![Jenkins](https://github.com/aleem632/Jenkins-Integeration-Project/blob/f32d91067e84c08a006aebebf165b80365870a63/Diagram/Jenkins-Integeration.png)


### CURRENT SITUATION
- agile SDLC
- Developers make regular code changes
- These commits need to be Build & Test
- Usually build & Release Team will do this job 
- Or Develops responsiblity to merge and integerate code

### PROBLEM
- In an agile SDLC, there will be frequent code changes
- Not so frequently code will be tested 
- Which accumulates bugs and error in the code

### RESPONSIBLITIES & PROBLEMS
- Developers need to rework to fix these bugs and error
- Manual Build and release
- Inter Team Dependencies

### SOLUTION
- Build and Test every commit 
- Automated Process
- Notify for every build status 
- Instantly fix bugs or error if found

### BENEFITS
- Short MTTR
- Fault isolation
- Agile
- No human intervention

### OBJECTIVE
- Fault isolation
- short MTTR
- Fast turn around on feature changes
- less disruptive
### FLOW OF EXECUTION

![jENKINS](https://github.com/aleem632/Jenkins-Integeration-Project/blob/793e67489bd527faa724f04617102f43122c856a/Diagram/Jenkins-Execution.png)

### STEPS
- Login to aws account
- create Key pair
- Create Security group(jenkins,nexus,sonarqube)
- create ec2 instance with userdata
- post installation (jenkins setup & plugins and nexus repository setup)
- sonar login test
- create github repository and migrate code 
- build job with nexus integeration
- Github webhook
- sonarqube server integeration stage 
- Nexus Artifact upload stage 
- Slack notification

















