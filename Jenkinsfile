node {
  git url: 'https://github.com/jglick/simple-maven-project-with-tests.git'
  def mvnHome = tool 'M3'
  env.PATH = "${mvnHome}/bin:${env.PATH}"
  sh 'mvn -B verify'
}

// pipeline{
//     agent any
//     environment{
//         dockerHome = tool 'myDocker'
        
//   PATH = "${dockerHome}/bin:${PATH}"


//     }
//     stages{
//         stage("A"){
//             steps{
//                 echo "========executing A========"
//                 //   sh 'docker version'
// //                sh "${dockerHome}"
//                sh "i got here"

//             }
//             post{
//                 always{
//                     echo "========always========"
//                 }
//                 success{
//                     echo "========A executed successfully========"
//                 }
//                 failure{
//                     echo "========A execution failed========"
//                 }
//             }
//         }
//     }
//     post{
//         always{
//             echo "========always========"
//         }
//         success{
//             echo "========pipeline executed successfully ========"
//         }
//         failure{
//             echo "========pipeline execution failed========"
//         }
//     }
// }
