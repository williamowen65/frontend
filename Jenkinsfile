node {
   stage('test') {
     nodejs(nodeJSInstallationName: 'nodejs') {
       sh 'npm install'
       sh 'npm test'
     }
   }
   stage('build & Resolve PR') {
    println('resolve Pr on github')
   }
}