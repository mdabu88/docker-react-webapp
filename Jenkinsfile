@library('shared-library@master') _

withCredentials([usernamePassword(credentialsId: 'Jenkins', passwordVariable: 'test-password', usernameVariable: 'test-username')]) {
    reactbaseBuild {
   	appName = "docker-react-webapp"
        buildType = "react"
        deployType = "helm-service"
    }
}
