saucelabs-test-automation
=========================

By the power of sauce!

**Tutorial**:
https://saucelabs.com/java

**Install dependencies for Ubuntu 13.10:**
sudo apt-get install maven

**Generate Maven project:**
mvn archetype:generate -DarchetypeRepository=http://repository-saucelabs.forge.cloudbees.com/release -DarchetypeGroupId=com.saucelabs -DarchetypeArtifactId=quickstart-webdriver-junit -DarchetypeVersion=2.0.5 -DsauceUserName=<username> -DsauceAccessKey=<access_key>

**Run test:**
cd ./sauce-labs
mvn test
