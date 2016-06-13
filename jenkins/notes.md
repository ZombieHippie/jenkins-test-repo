
## Jenkins
[GitHub Plugin](https://wiki.jenkins-ci.org/display/JENKINS/GitHub+plugin)
[Material Theme](http://jenkins-contrib-themes.github.io/jenkins-material-theme/)
[Material Theme blue](https://jenkins-contrib-themes.github.io/jenkins-material-theme/dist/material-blue.css)

## Ubuntu
 * [Install zsh](https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH)
 * [Install oh-my-zsh]()
 * [Install build-essential](https://help.ubuntu.com/community/InstallingCompilers)
 * [Logging into SSH VirtualBox](http://stackoverflow.com/a/10532299)
   - `ssh -p 9022 cole@127.0.0.1`
 * [Install OpenJDK 8](http://openjdk.java.net/install/)
   - 'sudo apt-get install openjdk-8-jre openjdk-8-jdk'
 * [Install Jenkins](https://wiki.jenkins-ci.org/display/JENKINS/Installing+Jenkins+on+Ubuntu)

Install nginx
Initial Admin Password
vi /var/lib/jenkins/secrets/initialAdminPassword
9a36bf542e2c49429d3a248e1f173f6a

Jenkins user:
cole/-92sWinish

## Jenkins setup
* Maven
  - `sudo apt-get install maven`
[Blue Ocean](https://github.com/jenkinsci/blueocean-plugin)


from [jenkins-notes.md](https://gist.github.com/misterbrownlee/3708738)

## Configure Jenkins

 * Make sure the Manage Jenkins > Configure System has the right path to git
 * Set the global git user.name and user.email to match your global config options
 * Configure GitHub Web Hook to Manually manage hook urls
 * Click the (?) icon next to the manual option and copy the hook URL you see there
 * Optionally set the service account email as the Jenkins sender email address
