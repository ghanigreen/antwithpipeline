node {
    
    stage ("code"){
    
    git 'https://github.com/ghanigreen/ant-demo.git'  
    }
     stage ("build"){
  bat 'ant war'  
     }
     stage ("deploy")
 sh 'cp -R "C:\\Program Files (x86)\\Jenkins\\workspace\\antpipeline\\dist\\AntExample.war"  "C:\\Program Files\\Apache Software Foundation\\Tomcat 9.0\\webapps"'
    
    
}
