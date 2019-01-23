def workspace;
node{
    stage('Checkout'){
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'bf9dabad-4245-4149-95f9-2546ce8f31e7', url: 'https://github.com/BelindaA/SampleProject.git']]])
        workspace=pwd()    
    }
    stage('Static Code Analysis'){
        echo "Static Code Analysis"
    }
    stage('Build'){
        echo "Build the code"
    }
    stage('Unit Testing'){
        echo "Unit Testing"
    }
    stage('Delivery'){
        echo "Delivery the code"
    }
    
}
