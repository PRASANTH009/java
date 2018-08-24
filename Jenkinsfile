node {
    
    stage ('SCM Checkout'){
        git 'https://github.com/PRASANTH009/java.git'
        
    }
    stage('Compile-Package'){
        def MVNHome = tool name: 'maven_3', type: 'maven'
        sh "${MVNHome}/bin/mvn clean package"
    }
}
