#Simple toolchain

This Hello World application uses Node.js and includes a DevOps toolchain that is preconfigured for continuous delivery using Jenkins, source control, issue tracking, and online editing.

##Prerequisites:
1. Deploy Jenkins for OTC first

[![Deploy To Bluemix](https://bluemix.net/deploy/button.png)](https://daily-console.stage1.ng.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/szbra/toolchain-jenkins-otc)

2. Navigate to Jenkins, and update variable in the Build Job
<code>CF_ACCESS_TOKEN="bearer ..."
CF_REFRESH_TOKEN="..."
CF_ORG_NAME="..."
CF_SPACE_NAME="..."</code>
to use the right cf tokens, and org and space where your app should be deployed.


To get started, click **Deploy to Bluemix**.

[![Deploy To Bluemix](https://bluemix.net/deploy/button.png)](https://daily-console.stage1.ng.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/szbra/simple-toolchain-with-jenkins)

<!--
For more information about using the sample, including instructions to add tools to the toolchain and make code changes, see <a href="x">Simple toolchain tutorial</a>
-->
