node{
    
    stage('Clone repo'){
        
    }
    stage('Maven Build'){
        def mavenHome = tool name: "maven3.9.2", type: "maven"
        def mavenCMD = "${mavenHome}/bin/mvn"
        sh "${mavenCMD} clean package"
    }
}
