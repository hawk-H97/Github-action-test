# GitHub Action

***

## Step - 1:
In the repository create a github workflow folder and create yaml file for action in the workflow folder.

***
## Step - 2:
* In yaml we want to write a code for action in the format of events, jobs, runners and action.
* Run the sample test by printing 'Hello World'.

# Self-Hosted runners:
In the action normally we use runners as ubuntu in github action. If you give as default(ubuntu) runner then it will runs on github server for processing the action.
* Background it will send all file in repo to github server for execution as copy. Once the process is finished data will still remain in the github server.
* We don't know whether they delete the job after the process completion. So we want to work on zero-trust method.
* In this repository mainly focused on Self-Hosted runner that is actions will run on our machine.
* While building self-hosted setup we can also use ephemeral runner it will clean after the action job completed. 
* We can setup on instaling the self hosted config we want to add the line ephemeral eg: (  ./config.sh --url https://github.com/your repo --token your token  --ephemeral.

## Advantages:
* 

## Dependency:
 * libicu (International Components for Unicode)
 libicu (International Components for Unicode) is a widely used library that provides:
 Unicode and locale support
 Date, time, and currency formatting
 String manipulation and collation> 

## rsync
* nstall rsync on a system where sudo requires interactive password input, which isn't possible in a non-interactive environment like GitHub Actions.

apt-get update && 
apt-get install -y rsync


