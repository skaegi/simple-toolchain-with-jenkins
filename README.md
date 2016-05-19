#Simple toolchain

This Hello World application uses Node.js and includes a DevOps toolchain that is preconfigured for continuous delivery using Jenkins, source control, issue tracking, and online editing.

##Steps:
* Create Jenkins for OTC toolchain that will deploy customized Jenkins in a Docker container

[![Deploy To Bluemix](https://bluemix.net/deploy/button.png)](https://daily-console.stage1.ng.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/szbra/toolchain-jenkins-otc)

* Navigate to Jenkins, and update variables listed below in the Build Job
<pre>
	CF_ACCESS_TOKEN="bearer ..."
	CF_REFRESH_TOKEN="..."
	CF_ORG_NAME="..."
	CF_SPACE_NAME="..."
</pre>
to use the right cf tokens, and org and space where your app should be deployed.


* Create the app toolchain that will deploy this Hello World app

[![Deploy To Bluemix](https://bluemix.net/deploy/button.png)](https://daily-console.stage1.ng.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/szbra/simple-toolchain-with-jenkins)

<!--
For more information about using the sample, including instructions to add tools to the toolchain and make code changes, see <a href="x">Simple toolchain tutorial</a>
-->
