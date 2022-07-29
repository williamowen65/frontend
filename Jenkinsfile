node {
   stage('test') {
     nodejs(nodeJSInstallationName: 'nodejs') {
       sh 'npm run installDev'      //  sh 'npm run installLegacy'
       sh 'npm run install'      //  sh 'npm run installLegacy'
       sh 'npm run installLegacy'      //  sh 'npm run installLegacy'
       sh 'npm test'
     }
   }
   stage('build & Resolve PR') {
    println('resolve Pr on github')
    sh 'npm run start'
   }
}