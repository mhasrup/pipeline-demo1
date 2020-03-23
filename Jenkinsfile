//@Library('lib-demo@master')
pipeline {
    agent any
//library 'lib-demo'
//library identifier: 'lib-demo', retriever: modernSCM([$class: 'GitSCMSource', credentialsId: '', id: 'd51eae8e-c7d2-4164-bc18-6bc0ee197b43', remote: 'https://github.com/mhasrup/pipeline-lib-demo1.git', traits: [[$class: 'jenkins.plugins.git.traits.BranchDiscoveryTrait']]])   
libraries {
	lib('lib-demo@master')
}
stages{
      stage('Demo')
	{
          steps{
            echo 'Hello World'
            //hello 'Laxman'
          }
        }
 }
}
