properties([pipelineTriggers([githubPush()])])

node ('COMPONENT_ECS') {
    stage ('Checkout'){
        git url: 'https://github.com/Miranlfk/wso2-maven-test-repo.git'
    }
    stage ('Build'){
        echo build
    }
    stage ('Test'){
        // steps
    }
}    
