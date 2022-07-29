node {
   stage('test') {
     nodejs(nodeJSInstallationName: 'nodejs') {
       sh 'npm run install'
       sh 'npm test'
     }
   }
   stage('build & Resolve PR') {
    println('resolve Pr on github')
   }
}