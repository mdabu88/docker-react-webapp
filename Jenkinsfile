@library('library@master') _

withCredentials([usernamePassword(credentialsId: 'Jenkins', passwordVariable: 'test-password', usernameVariable: 'test-username')]) {
       buildPipeline {
            appName = "docker-react-webapp"
            buildType = "dockerfile"
            deployType = "helm-service"
         }
}
